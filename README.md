# Titanic ve Tips Veri Setleri Üzerine Görevler

Bu proje, Titanic ve Tips veri setleri üzerinde çeşitli veri manipülasyonu ve analiz işlemlerini gerçekleştirmektedir. Çalışma boyunca Seaborn, Pandas ve Numpy gibi Python kütüphaneleri kullanılmıştır.

## Proje İçeriği

### Titanic Veri Seti Görevleri

1. **Veri Setini Tanımlama:**
   Titanic veri seti Seaborn kütüphanesi ile yüklenmiştir ve temel yapı incelenmiştir.

2. **Kadın ve Erkek Yolcuların Sayısı:**
   Cinsiyete göre yolcuların dağılımı `value_counts()` yöntemiyle hesaplanmıştır.

3. **Sütunlardaki Unique Değerlerin Sayısı:**
   Tüm sütunların benzersiz değer sayıları incelenmiştir.

4. **pclass Değişkeninin Unique Değerleri:**
   `unique()` yöntemi kullanılarak pclass değişkeninin benzersiz değerleri listelenmiştir.

5. **pclass ve parch Değişkenleri:**
   İki değişkenin benzersiz değerlerinin sayısı birlikte analiz edilmiştir.

6. **embarked Değişkeni Tip Dönüşümü:**
   `embarked` değişkeni `category` tipine dönüştürülmüştür.

7. **embarked Değeri C Olanların Bilgileri:**
   embarked değeri "C" olan yolcuların bilgileri filtrelenmiştir.

8. **embarked Değeri S Olmayanlar:**
   embarked değeri "S" olmayan yolcuların bilgileri seçilmiştir.

9. **30 Yaşından Küçük ve Kadın Olanlar:**
   Yaşı 30'dan küçük ve kadın olan yolcuların bilgileri filtrelenmiştir.

10. **Fare'i 500’den Büyük veya Yaşı 70’den Büyük Olanlar:**
    Belirtilen kriterlere uyan yolcuların bilgileri incelenmiştir.

11. **Boş Değerlerin Toplamı:**
    Tüm sütunlardaki eksik değerlerin sayıları bulunmuştur.

12. **who Değişkenini Silme:**
    `drop()` yöntemiyle `who` değişkeni veri setinden kaldırılmıştır.

13. **deck Değişkenindeki Eksik Değerleri Doldurma:**
    Eksik değerler, `deck` değişkeninin moda değeri ile doldurulmuştur.

14. **age Değişkenindeki Eksik Değerleri Doldurma:**
    Eksik değerler, `age` değişkeninin medyanı ile doldurulmuştur.

15. **Hedef Değişken Analizi:**
    `survived` değişkeninin `pclass` ve `sex` kırılımındaki toplam, ortalama ve sayıları hesaplanmıştır.

16. **age_flag Değişkeni Oluşturma:**
    Yaşa bağlı olarak 30 yaşın altında olanlara `1`, diğerlerine `0` atanmıştır.

---

### Tips Veri Seti Görevleri

17. **Veri Setini Tanımlama:**
    Seaborn üzerinden `tips` veri seti yüklenmiştir.

18. **time Değişkeni Kategorileri:**
    `Dinner` ve `Lunch` zamanlarına göre toplam, minimum, maksimum ve ortalama `total_bill` değerleri hesaplanmıştır.

19. **Gün ve time Kategorileri:**
    Gün ve zaman kırılımında `total_bill` değişkeninin toplam, minimum, maksimum ve ortalaması hesaplanmıştır.

20. **Lunch ve Kadın Müşterilere Ait Analiz:**
    Kadın müşterilerin `Lunch` zamanı `total_bill` ve `tip` değerlerinin analizleri yapılmıştır.

21. **Özel Filtreleme ve Ortalama Hesabı:**
    `size` değeri 3’ten küçük ve `total_bill` değeri 10’dan büyük olan siparişlerin ortalaması hesaplanmıştır.

22. **total_bill_tip_sum Değişkeni:**
    Her müşterinin ödediği toplam tutar ve bahşiş toplamı hesaplanarak yeni bir değişken eklenmiştir.

23. **Büyükten Küçüğe Sıralama:**
    `total_bill_tip_sum` değişkenine göre sıralama yapılmış ve ilk 30 kişi yeni bir dataframe'e atanmıştır.

---

## Kullanılan Kütüphaneler

- **Numpy:** Matematiksel işlemler ve veri manipülasyonu.
- **Pandas:** Veri analizi ve manipülasyonu.
- **Seaborn:** Veri görselleştirme.

---

## Sonuçlar

Bu proje, Titanic ve Tips veri setleri üzerinde veri manipülasyonlarını anlamak ve analiz becerilerini geliştirmek için hazırlanmıştır. Görevler boyunca veri temizleme, dönüştürme, filtreleme ve gruplama işlemleri gerçekleştirilmiştir. Ayrıca, Python’da veri analizi süreçlerinin otomasyonu üzerine çalışmalar yapılmıştır.

 
