# 💻 End-to-End Laptop Price Prediction & Smart Advisor

Bu proje; ham dizüstü bilgisayar verilerini temizleyerek, makine öğrenmesi (**XGBoost**) modelleriyle piyasa fiyatını tahmin eden, **Gradio** ile interaktif web arayüzüne kavuşturulmuş uçtan uca bir veri bilimi uygulamasıdır.

## 🚀 Proje Aşamaları ve Akışı

1. **Problem Tanımı:** Donanım özelliklerine göre bilgisayar piyasa fiyatını tahmin etme (Regresyon).
2. **Veri Toplama ve Hazırlama:** Kaggle veri setinin temizlenmesi, eksik değerlerin giderilmesi ve sayısal dönüşümler.
3. **Veri Güvenliği & Sızıntı Önleme (Data Leakage Prevention):** Modelin ezber yapmasını önlemek ve gerçekçi sonuçlar üretmek amacıyla fiyatı doğrudan ele verebilecek sızıntı yaratabilecek sütunlar temizlenmiştir.
4. **Model Kurma ve Eğitme:** **XGBoost Regressor** kullanılarak modelin eğitilmesi ve **%87.3 $R^2$ skoru** ile başarılı başarım ölçümü.
5. **Akıllı Donanım Analizi ve Otomasyon:** Seçilen GPU ve donanımlara göre performans seviyesinin (`Performance_Level` - Tier) sistem tarafından otomatik olarak tespit edilmesi.
6. **Akıllı Tahmin ve Arayüz (Gradio):** Kullanıcı dostu Gradio web arayüzü ile anlık fiyat tahmini ve detaylı teknik raporlama.
7. **Dokümantasyon:** Kod, sunum ve rapor üçlüsüyle eksiksiz teslim.

## 🛠️ Teknik Altyapı ve Kullanılan Araçlar

* **Dil:** Python
* **Veri İşleme:** Pandas, NumPy
* **Makine Öğrenmesi & Algoritma:** Scikit-Learn, XGBoost Regressor
* **Arayüz / Dağıtım:** Gradio (Web Demosu)

## 📊 Model Mimarisi ve Doğrulama

Veri setinin boyutu göz önünde bulundurularak aşırı öğrenmeyi (overfitting) engellemek amacıyla dengeli (%80 Eğitim, %20 Test) kullanılmıştır; XGBoost algoritmasının doğal boosting mekanizmasıyla yüksek genelleme başarısına ulaşılmıştır.


## 📂 Veri Seti (Dataset)
Bu projede kullanılan dizüstü bilgisayar fiyatları veri seti **Kaggle** platformundan temin edilmiştir. 
* **Kaynak:** [Kaggle - Laptop Price Dataset](https://www.kaggle.com/datasets/sohaibdevv/modern-laptops-hardware-and-pricing-dataset-2026)
* **İçerik:** Çeşitli markalara ait dizüstü bilgisayarların donanım özellikleri (RAM, CPU, GPU, Ekran Boyutu vb.) ve fiyat bilgilerini içermektedir.
