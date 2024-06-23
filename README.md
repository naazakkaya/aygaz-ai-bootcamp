# Aygaz AI Bootcamp - Fashion MNIST Sınıflandırma Projesi

## Proje Açıklaması
Bu proje, Aygaz Yapay Zeka Bootcamp kapsamında Fashion MNIST veri setini kullanarak moda ürünlerini sınıflandırmayı amaçlamaktadır. Bu proje ile görüntü verilerini işleme, makine öğrenmesi modelleri oluşturma ve değerlendirme adımları gerçekleştirilmektedir.

## Veri Seti
- **Veri Seti:** Fashion MNIST
- **Eğitim Veri Seti Boyutu:** 60,000 görüntü
- **Test Veri Seti Boyutu:** 10,000 görüntü
- **Sınıf Sayısı:** 10 (Tişört, pantolon, kazak, elbise, ceket, sandalet, gömlek, spor ayakkabı, çanta, bot)

## Proje Adımları
1. **Veri Ön İşleme:**
   - Verilerin normalleştirilmesi
   - Verilerin eğitim ve test setlerine ayrılması

2. **Model Oluşturma ve Eğitim:**
   - K-Nearest Neighbors (KNN) algoritması kullanılarak model eğitimi
   - Model performans değerlendirme metrikleri: Accuracy, F1-Score

3. **Model Değerlendirme:**
   - Karışıklık matrisi oluşturma ve görselleştirme
   - Modelin sınıf bazında performans değerlendirmesi

## Proje Dosyaları
- **aygazaibootcamp.ipynb:** Proje kodları ve analizler.
  - Veri ön işleme, model eğitimi ve değerlendirme adımlarını içeren kodlar.
  - K-Nearest Neighbors (KNN) algoritması kullanılarak yapılan model eğitimi.
  - Model performans değerlendirme metrikleri ve karışıklık matrisi analizi.

- **SudeNazAkkayaAygazSunumu.pptx:** Proje sunumu dosyası.
  - Projenin amacı, veri seti genel bakışı, veri ön işleme adımları, model seçimi ve eğitimi, model değerlendirme sonuçları ve gelecek çalışmalar hakkında bilgiler.
  - Görsel materyaller ve değerlendirme sonuçları.

## Kurulum ve Çalıştırma
1. Proje dosyalarını klonlayın:
   ```bash
   git clone https://github.com/naazakkaya/aygaz-ai-bootcamp.git
   cd aygaz-ai-bootcamp
