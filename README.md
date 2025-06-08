# Hamming Kodlayıcı (SEC) - Web Arayüzü

Bu proje, Hamming Kodu (Single Error Correction - SEC) algoritmasını kullanarak 8, 16 veya 32 bitlik ikili verilerin hataya karşı nasıl korunduğunu interaktif bir arayüzle göstermektedir. Kullanıcılar veriyi girebilir, kodlayabilir, rastgele bir hata ekleyebilir ve hatayı tespit edip düzeltebilir.

## 🚀 Özellikler

- 8, 16 veya 32 bitlik ikili veri girişi
- Hamming kodlama (hata düzeltme biti ekleme)
- Rastgele hata ekleme (tek bitlik hata)
- Hata tespiti ve düzeltme
- Hata pozisyonunun ikili olarak gösterimi
- Hatalı ve düzeltilmiş verinin renkli görselleştirilmesi

## 🧪 Kullanım

1. Sayfayı bir tarayıcıda açın (örneğin `index.html` dosyasını çift tıklayarak).
2. Veri kutusuna 8, 16 veya 32 bitlik ikili bir sayı girin.  
   Örnek: `10110011` veya `1101001010110101`
3. `Kodla` butonuna tıklayın → Kodlanmış veri ekranda görünür.
4. `Hata Ekle` butonuna tıklayın → Rastgele bir bit hatalı hale getirilir.
5. `Çöz ve Düzelt` butonuna tıklayın → Hata tespit edilir ve düzeltilir.

## 💡 Teknik Detaylar

- Kodlama işlemi, gerekli Hamming parite bitlerini hesaplar ve yerleştirir.
- Hata ekleme, kodlanmış verinin rastgele bir bitini tersine çevirir.
- Çözümleme, hata sendromu hesaplayarak hatayı bulur ve düzeltir.
- Tüm işlemler sadece tek bitlik hata düzeltmeye uygundur (SEC).

## 📁 Dosya Yapısı

- `index.html` – Tüm HTML, CSS ve JavaScript kodlarını içerir.

## 📷 Ekran Görüntüsü

![image](https://github.com/user-attachments/assets/a4bb8cd8-cfeb-473a-80fb-a881ad6988ec)


## 📌 Gereksinimler

- Sadece bir modern web tarayıcısı yeterlidir.
- Ekstra kütüphane ya da sunucu gerekmez.

