# 🩺 Sağlıkta Yapay Zeka: Diyabet Tahmini (Diabetes Prediction)

Bu proje, **Burdur Mehmet Akif Ersoy Üniversitesi** bünyesindeki **Sağlıkta Yapay Zeka** dersi kapsamında geliştirilmiştir. Projenin amacı, hastaların tıbbi verilerini (glukoz seviyesi, BMI, yaş vb.) kullanarak makine öğrenmesi modelleriyle diyabet riskini tahmin etmektir.

## 📌 Proje Özeti
Proje kapsamında, **[Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/busranurok/diabetscsv)** kullanılarak veri analizi (EDA), veri ön işleme ve çeşitli sınıflandırma modellerinin karşılaştırılması yapılmıştır. Veri seti 768 hastaya ait 8 özellik ve 1 hedef değişken (Diyabet var/yok) içermektedir.

## 🛠️ Kullanılan Teknolojiler
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-Learn** (Makine Öğrenmesi Kütüphanesi)
- **Modeller:** - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Gradient Boosting & AdaBoost
  - Support Vector Machine (SVC)
  - Naive Bayes

## 🚀 Proje Adımları

1. **Veri Analizi (EDA):** Veri setinin istatistiksel özeti çıkarıldı, özelliklerin birbiriyle olan korelasyonu incelendi.
2. **Aykırı Değer Analizi (Outlier Detection):** Verinin doğruluğunu artırmak için aykırı değerler tespit edildi.
3. **Veri Ön İşleme:** Model performansını optimize etmek için veriler **StandardScaler** ile ölçeklendirildi.
4. **Model Eğitimi:** Birden fazla algoritma ile eğitim yapıldı ve çapraz doğrulama (Cross-Validation) ile başarı oranları test edildi.
5. **Hiperparametre Tünelleme:** GridSearchCV kullanılarak modellerin en iyi parametreleri belirlendi.
6. **Performans Ölçümü:** Modeller; Accuracy, Precision, Recall ve F1-Score metriklerine göre değerlendirildi.

## 📊 Sonuçlar
Proje sonunda modellerin performansları karşılaştırılmış ve sağlık verileri üzerinde en güvenilir sonucu veren algoritma seçilmiştir. Model, diyabeti olmayan (0 sınıfı) hastaları yüksek doğrulukla tespit ederken, diyabeti olan (1 sınıfı) hastaları tespit etme konusunda (Recall değeri üzerinden) titizlikle analiz edilmiştir.

## 📂 Dosya Yapısı
- `diyabet_tahmini_uyg1.ipynb`: Proje kodlarını ve analizleri içeren Jupyter Notebook dosyası.
- `diabetes.csv`: Kaggle üzerinden temin edilen Pima Indians Diabetes veri seti.
  
**⚠️ Önemli Uyarı:** Bu proje eğitim ve araştırma amaçlı bir akademik çalışmadır. Üretilen sonuçlar ve tahminler tıbbi tavsiye niteliği taşımaz. Gerçek bir teşhis veya tedavi süreci için mutlaka bir uzman hekime danışınız.


