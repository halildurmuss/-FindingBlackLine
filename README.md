# Finding Black Line

## Görüntü üzerindeki hangi piksellerin siyah çizgiler oluşturduğunu, siyah çizgilerin matrisi elemanlarının adreslerini ve satır sütun bilgilerini veren C programı yazılmıştır.

![matris](https://user-images.githubusercontent.com/66306220/86596870-9777b280-bfa3-11ea-86cc-16677ba4f469.png)

### **Yukarıda verilen matris bir görüntünün piksellerinin taşıdığı değerleri ifade etmektedir.**

Aşağıda verilen görüntüde en sol tarafta 0 değeri en koyu ve en sağ tarafta 15 değeri en açık renktir.  

![Piksel](https://user-images.githubusercontent.com/66306220/86597333-3c928b00-bfa4-11ea-9481-b253921c3c02.png)

0 değerini taşıyan pikseller siyah, aynı değeri taşıyıp birbirine komşu olan piksellerin çizgi oluşturduğu kabul edilmektedir.

Yukarıda verilen matriste
- hangi piksellerin siyah çizgiler oluşturduğunu tespit eden
- siyah çizgilerin parçası olan matris elemanlarının adreslerini ve satır/sütun bilgilerini yeni bir çok boyutlu diziye kaydeden
- adres bilgisi ve matris satır/sütun bilgilerini içeren diziyi ekrana 

yazdıran program yazılmıştır.

# Programın Hazırlamasına dair:
1. Program yukarıda verilen matrisi bir alt fonksiyondan almıştır. Alt fonksiyonda hazır olarak bulunuyor.

2. Sıfır değerlerinin kontrolü bir başka alt fonksiyonda yapılmıştır. Bu alt fonksiyon birisi “matris”, diğeri “aranacakDeger” olmak üzere iki adet parametre ile çalışıyor. Bu alt fonksiyonun işlevi “matris” içerisinde “aranacakDeger”i aramak, bulunan her değer için komşu hücreleri aynı değer için kontrol etmek ve komşu hücrelerden herhangi birinde aranacak değeri bir daha bulunacak olursa matrisin ilgili hücresindeki değerin adresini, hücrenin satır ve sütun değerleri ile birlikte daha sonra geri döndüreceği bir çok boyutlu diziye kaydetmektedir. Matrislerin komşuluğu ile ilgili temsili ifade aşağıda verildiği gibidir:

![Hücre_komşuları](https://user-images.githubusercontent.com/66306220/86597667-b591e280-bfa4-11ea-9518-e9722670359a.png)

3. Gerek dizi, gerekse matris elemanları üzerinde işlemler yapılırken döngü kullanılmıştır.

4. Belirtilen alt fonksiyon aranan değeri bulamazsa 10 değeri döndürerek programın sonlanmasını sağlanıyor.

5. Program başarılı çalışma durumunda 0 değeri döndürüyor.

# Çıktı

![Proje_cıktı](https://user-images.githubusercontent.com/66306220/86597877-00abf580-bfa5-11ea-8af4-72c42544a777.png)
