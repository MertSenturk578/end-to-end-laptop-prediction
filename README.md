# 💻 End-to-End Laptop Price Prediction & Smart Advisor

Bu proje; ham dizüstü bilgisayar verilerini temizleyerek, makine öğrenmesi (regresyon) modelleriyle piyasa fiyatını tahmin eden ve kullanıcıya akıllı donanım önerileri sunan web tabanlı interaktif bir uçtan uca veri bilimi uygulamasıdır.

## 🚀 Proje Aşamaları ve Akışı
1. **Problem Tanımı:** Donanım özelliklerine göre bilgisayar fiyatını tahmin etme (Regresyon).
2. **Veri Toplama ve Hazırlama:** ~1.300 satırlık veri setinin temizlenmesi, eksik değerlerin giderilmesi ve sayısal dönüşümler.
3. **Keşifçi Veri Analizi (EDA) ve Görselleştirme:** Fiyat trendlerinin ve özellik ilişkilerinin incelenmesi.
4. **Model Kurma ve Eğitme:** Scikit-Learn ile regresyon modellerinin eğitilmesi ve başarım ölçümü ($R^2$ skoru).
5. **Tahmin ve Değerlendirme:** Test verileri üzerinden modelin dürüstçe test edilmesi.
6. **Akıllı Tahmin ve Öneri Aracı (Arayüz):** Kullanıcı dostu arayüz ile anlık fiyat tahmini ve alternatif konfigürasyon önerileri.
7. **Dokümantasyon:** Kod, sunum ve rapor üçlüsüyle eksiksiz teslim.

## 🛠️ Teknik Altyapı ve Kullanılan Araçlar
* **Dil:** Python
* **Veri İşleme:** Pandas, NumPy
* **Görselleştirme:** Matplotlib, Seaborn
* **Makine Öğrenmesi:** Scikit-Learn
* **Arayüz / Dağıtım:** Gradio / Ipywidgets (Colab)

## 📂 Veri Seti (Dataset)
Bu projede kullanılan dizüstü bilgisayar fiyatları veri seti **Kaggle** platformundan temin edilmiştir. 
* **Kaynak:** [Kaggle - Laptop Price Dataset](https://www.kaggle.com/datasets/sohaibdevv/modern-laptops-hardware-and-pricing-dataset-2026)
* **İçerik:** Çeşitli markalara ait dizüstü bilgisayarların donanım özellikleri (RAM, CPU, GPU, Ekran Boyutu vb.) ve fiyat(€ cinsinden) bilgilerini içermektedir.
