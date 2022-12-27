# Sorunu Anlamak:

1. 1 butonuna basılmasından, güncellenen değerimizin render edilmesine kadar olan uygulama adımları nelerdir?
   Her adım için kodun hangi bölümünün geçerli olduğunu listeleyin.

- Kullanıcı 1 butonuna tıkadı.
- Tıklandığında state'i değiştirmeye yarayan dispatch fonksiyonuyla actions\index.js dosyasındaki addOne() fonksiyonunu çağırmış ve tetiklemiş olduk.
- actions\index.js dosyasındaki addOne() fonksiyonu return değeri olarak reducer fonksiyonunda kullanacağımız ADD_ONE değerini dönüyor. Bu type değerini bir değişkene bağlayıp export ediyoruz.
- Bu değer(ADD_ONE) reducers\index.js dosyasına import edili. Burada reducer fonksiyonundaki ilgili case'/koşul total değerini 1 arttırıyor.

- TotalDisplay total artı 1'i gösterdi.
