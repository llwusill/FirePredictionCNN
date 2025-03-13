# Fire Prediction using CNN & Machine Learning Models

Bu proje, **orman yangınlarını tespit etmek ve tahmin etmek** için **Convolutional Neural Networks (CNN)** ve geleneksel makine öğrenimi modellerini kullanmaktadır. Model, farklı algoritmalarla eğitilerek **en yüksek doğruluk oranına sahip olanın belirlenmesi** amaçlanmıştır.

## Özellikler
🔥 **Derin Öğrenme ile Görüntü Sınıflandırma** – CNN modeli kullanarak yangın tespiti.  
🔥 **Makine Öğrenmesi Modelleri** – SVM, Naive Bayes ve Random Forest algoritmalarının karşılaştırılması.  
🔥 **Veri Görselleştirme & Analiz** – Eğitim verileri görselleştirilerek analiz edilmiştir.  
🔥 **Google Colab Uyumluluğu** – Google Drive entegrasyonu ile kolay kullanım.  

## Modellerin Performans Karşılaştırması
| Model | Doğruluk (%) |
|--------|------------|
| **SVM (Support Vector Machine)** | **94.12** |
| **Random Forest** | 88.24 |
| **Gaussian Naive Bayes** | 82.35 |

SVM modeli en yüksek doğruluk oranına sahip olduğu için, **yangın tahmini için en iyi model** olarak belirlenmiştir.

## Gereksinimler
Aşağıdaki kütüphanelerin yüklenmesi gerekmektedir:

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn opencv-python
```

##Nasıl Çalıştırılır?
1️⃣ Google Colab veya Jupyter Notebook'ta açın
2️⃣ Veri setini yükleyin
3️⃣ Ön işleme adımlarını tamamlayın (görüntü temizleme, ölçekleme vb.)
4️⃣ CNN ve diğer modelleri eğitin
5️⃣ Sonuçları karşılaştırın ve en iyi modeli seçin
