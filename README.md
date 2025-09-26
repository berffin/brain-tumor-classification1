# Brain Tumor MRI Classification - Akbank Deep Learning Bootcamp

## Giriş
Bu proje, Akbank Derin Öğrenme Bootcamp kapsamında geliştirilmiş bir beyin tümörü sınıflandırma modelidir. Brain Tumor MRI veri seti üzerinde Evrişimli Sinir Ağları (CNN) ve Transfer Learning yöntemleri kullanılarak MRI görüntülerinden beyin tümörü tespiti yapılmıştır.

## Proje Detayları
- **Veri Seti:** Kaggle Brain Tumor MRI Dataset (7,022 görüntü)
- **Sınıflar:** Glioma, Meningioma, Pituitary, No Tumor
- **Kullanılan Yöntemler:** CNN, VGG16 Transfer Learning, Data Augmentation
- **Geliştirme Ortamı:** Kaggle Notebook

## Metrikler
### Model Performans Sonuçları:
- **Özel CNN Modeli Test Doğruluğu:** 68.57%
- **VGG16 Transfer Learning Test Doğruluğu:** 82.46%

### Elde Edilen Bulgular:
- Transfer Learning yönteminin medical imaging'de daha yüksek performans gösterdiği gözlemlenmiştir
- Data augmentation teknikleri overfitting'i önlemede etkili olmuştur
- CNN modeli daha hızlı eğitilirken, VGG16 daha yüksek doğruluk sağlamıştır

## Teknik Uygulamalar
Proje kapsamında aşağıdaki teknikler uygulanmıştır:
- Veri ön işleme ve normalizasyon
- Görüntü augmentasyon teknikleri
- Özel CNN mimarisi tasarımı
- Transfer Learning ile VGG16 fine-tuning
- Hiperparametre optimizasyonu
- Model değerlendirme metrikleri

## Ekler
Proje Kaggle platformunda geliştirilmiş olup, tüm eğitim ve değerlendirme süreçleri notebook içerisinde detaylandırılmıştır. Model görselleştirmeleri ve confusion matrix analizleri ile sonuçlar desteklenmiştir.

## Sonuç ve Gelecek Çalışmalar
### Mevcut Çalışmanın Katkıları:
- Medical AI alanında pratik deneyim kazanıldı
- CNN ve Transfer Learning teknikleri derinlemesine uygulandı
- Model interpretability için Grad-CAM görselleştirmeleri planlandı

### Gelecek Çalışmalar:
- **Real-time Deployment:** Streamlit veya FastAPI ile web arayüzü
- **Model Geliştirme:** EfficientNet, ResNet gibi modern mimarilerin test edilmesi
- **Veri Çeşitliliği:** Farklı hastane verileri ile modelin genelleme yeteneğinin artırılması
- **Explainable AI:** Grad-CAM ile model kararlarının görselleştirilmesi
- **Multi-modal AI:** MRI yanında hasta demografik verilerinin entegrasyonu




## Gereksinimler
Proje için gerekli kütüphaneler `requirements.txt` dosyasında belirtilmiştir.


Proje Linkleri
- **Kaggle Notebook:** https://www.kaggle.com/code/berfintavan/deep-learning-project-brain-tumor-mri-data-set-cnn/edit
- **GitHub Repository:** https://github.com/berffin/brain-tumor-classification1

