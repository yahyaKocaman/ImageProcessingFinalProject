# UYG332 Image Processing Final Project

## Öğrenci Bilgileri
- **Ad Soyad:** Yahya Kocaman
- **Öğrenci No:** B2180.060025
- **Ders:** UYG332 - Image Processing
- **Eğitmen:** Batuhan Hangün

## Proje Açıklaması
Bu proje görüntü işleme dersinin final projesi için hazırlanmıştır. Proje kapsamında 6 farklı problem çözülmüş ve Python ile OpenCV kütüphanesi kullanılarak görüntü işleme teknikleri uygulanmıştır.

## Çözülen Problemler
1. **Problem 1 :** tf2_engineer.jpg - Görüntü merkezi bulma ve renkli patch ekleme
2. **Problem 2 :** einstein.tiff - Negatif görüntü oluşturma
3. **Problem 3 :** pout.tiff - Log ve ters log dönüşümleri
4. **Problem 4 :** moon.tiff - Uzamsal ve frekans alanında keskinleştirme (unsharp masking)
5. **Problem 5 :** pcb.tiff - Gürültü analizi ve giderme
6. **Problem 6 :** pollen.tiff - Görüntü iyileştirme teknikleri

## Kullanılan Kütüphaneler

### Temel Gereksinimler
```bash
pip install opencv-python
pip install numpy
pip install matplotlib
pip install scipy
```

### Kütüphane Listesi
- **OpenCV (cv2)**: Görüntü işleme operasyonları için
- **NumPy**: Sayısal hesaplamalar ve matris işlemleri için
- **Matplotlib**: Görüntü görselleştirme ve grafik çizimi için
- **SciPy**: İleri düzey bilimsel hesaplamalar için
- **Random**: Rastgele sayı üretimi için

## Kurulum ve Çalıştırma

### 1. Gerekli Kütüphanelerin Kurulumu
```bash
# Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt
```

### 2. Görüntü Dosyalarının Hazırlanması
- Proje klasöründe aşağıdaki görüntü dosyalarının bulunması gerekir:
  - `tf2_engineer.jpg`
  - `einstein.tiff`
  - `pout.tiff`
  - `moon.tiff`
  - `pcb.tiff`
  - `pollen.tiff`

### 3. Jupyter Notebook'u Çalıştırma
```bash
# Jupyter Notebook'u başlatın
jupyter notebook

# Ardından UYG332_Image_Processing_Final_Project.ipynb dosyasını açın
```

## Dosya Yapısı
```
UYG332_Final_Project/
│
├── UYG332_Image_Processing_Final_Project.ipynb  # Ana proje dosyası
├── README.md                                     # Bu dosya
├── requirements.txt                              # Gerekli kütüphaneler
├── B2180.060025_YahyaKocaman.txt                   # GitHub repo linki ve diğer bilgiler
│
├── images/                                       # Görüntü dosyaları klasörü
│   ├── tf2_engineer.jpg
│   ├── einstein.tiff
│   ├── pout.tiff
│   ├── moon.tiff
│   ├── pcb.tiff
│   └── pollen.tiff
│
└── outputs/                                      # Çıktı görüntüleri (opsiyonel)
    ├── problem1_results/
    ├── problem2_results/
    ├── problem3_results/
    ├── problem4_results/
    ├── problem5_results/
    └── problem6_results/
```

## Notebook Kullanım Talimatları

### Adım 1: Kütüphaneleri İçe Aktarma
Notebook başında gerekli tüm kütüphaneler import edilmiştir ilk olarak o hücreyi önce çalıştırın.

### Adım 2: Problemleri Sırayla Çalıştırma
- Her problem için ayrı bölümler oluşturulmuştur
- Her problemi sırayla çalıştırın
- Her hücrenin çıktısını kontrol edin

### Adım 3: Sonuçları İnceleme
- Her problemin sonunda görsel sonuçlar ve yorumlar bulunur
- Çıktı görüntülerini karşılaştırın
- Sayısal sonuçları analiz edin

## Önemli Notlar

### Görüntü Dosyaları
- Tüm görüntü dosyaları notebook ile aynı dizinde olmalıdır
- Dosya isimlerinin tam olarak eşleşmesi gerekir
- Desteklenen formatlar: .jpg, .tiff

### Hata Giderme
Eğer hata alırsanız:
1. Kütüphanelerin doğru yüklendiğini kontrol edin
2. Görüntü dosyalarının doğru konumda olduğunu kontrol edin
3. Python ve Jupyter versiyonlarınızı kontrol edin

## Proje Sonuçları

### Problem 1 - Görüntü Manipülasyonu
- Görüntü merkezi başarıyla bulundu
- Belirtilen renkte patch eklendi
- Pixel değerleri doğru şekilde hesaplandı

### Problem 2 - Negatif Görüntü
- Negatif transformasyon uygulandı
- Rastgele pixellerin değerleri karşılaştırıldı
- Matematiksel doğruluk kanıtlandı

### Problem 3 - Logaritmik Dönüşümler
- Log ve ters log dönüşümleri uygulandı
- Dönüşümlerin etkileri analiz edildi
- Veri kaybı durumu incelendi

### Problem 4 - Keskinleştirme
- Uzamsal ve frekans alanında keskinleştirme yapıldı
- Farklı k değerleri test edildi
- İki yöntem karşılaştırıldı

### Problem 5 - Gürültü Giderme
- Gürültü türü doğru tespit edildi
- Uygun filtreleme yöntemi seçildi
- Sonuçlar başarıyla elde edildi

### Problem 6 - Görüntü İyileştirme
- İki farklı iyileştirme yöntemi uygulandı
- Histogram analizi yapıldı
- Sayısal karşılaştırmalar gösterildi


