
# 🚗 Honda Civic Fiyat Tahmin Modeli

Bu proje, **Honda Civic** marka araçlar için ikinci el fiyat tahminlemesi yapmayı amaçlayan bir yapay zeka modelini içermektedir. Proje, Python diliyle Jupyter Notebook ortamında geliştirilmiştir ve veri analizi ile makine öğrenimi algoritmalarını birleştirerek tahminlerde bulunur.

## 🔍 Projenin Amacı

İkinci el Honda Civic araçlarının bazı özelliklerine (model yılı, kilometre, yakıt tipi vb.) bakılarak, satış fiyatını otomatik olarak tahmin eden bir sistem geliştirmek.

## 🛠️ Kullanılan Teknolojiler

- Python 🐍
- Pandas, NumPy 📊
- Scikit-learn 🔧
- Matplotlib, Seaborn 📈
- Jupyter Notebook 📓

## 📁 Dosyalar

- `Yapay_Zeka_Civic_Araba.ipynb`: Projeyi içeren Jupyter notebook dosyası. Veri yükleme, görselleştirme, model oluşturma ve değerlendirme adımlarını içerir.

## 📊 Model Özeti

- **Veri Temizleme:** Eksik veriler giderildi ve kategorik değişkenler sayısal verilere dönüştürüldü.
- **Model:** Linear Regression (Doğrusal Regresyon) ve/veya diğer regresyon modelleri kullanılarak fiyat tahminlemesi yapıldı.
- **Başarı Ölçütü:** R² skoru, MAE, MSE gibi metrikler ile model performansı değerlendirildi.

## 📌 Notlar

- Model yalnızca Honda Civic araçları için eğitilmiştir.
- Gerçek piyasa fiyatlarından sapmalar olabilir; model sadece referans içindir.

