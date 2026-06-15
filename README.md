# 🛒 Maliyet-Duyarlı Müşteri Kaybı & Promosyon ROI Motoru

YBS 4. Sınıf | Python ile Veri Bilimi | Dönem Sonu Projesi | Haziran 2026

## 📌 Proje Özeti
Bu projede bir e-ticaret şirketinin müşteri kaybı (churn) riski XGBoost ile tahmin edilmiş; yanlış tahminlerin finansal maliyeti hesaplanmış ve en kârlı promosyon stratejisi simüle edilmiştir.

**Sonuçlar:**
- 🎯 ROC-AUC: 1.00
- 💰 Net Kâr Potansiyeli: 3.631.426 ₺
- 👥 Hedef Müşteri: 600 kişi
- 📊 Optimal Karar Eşiği: 0.28 (standart 0.50 yerine)

## 📁 Dosyalar
| Dosya | Açıklama |
|---|---|
| `proje_churn_roi.ipynb` | Tam analiz ve model kodu |
| `Yonetici_Ozeti_FINAL.pdf` | Yönetici Özeti Raporu (5 sayfa) |

## 🗂️ Veri Kaynakları
- **Kaynak 1:** [UCI Online Retail II – Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
- **Kaynak 2:** TCMB GBP/TRY Aylık Kur Verisi (notebook içinde tanımlıdır)

## 🔧 Kurulum
```bash
pip install pandas numpy scikit-learn xgboost shap matplotlib seaborn openpyxl jupyter
```

## 🚀 Kullanım
1. `online_retail_II.csv` dosyasını Kaggle'dan indirip proje klasörüne koy
2. `jupyter notebook` komutuyla notebook'u aç
3. `Kernel → Restart & Run All` ile çalıştır

## 📊 Kullanılan Teknolojiler
`Python` `XGBoost` `SHAP` `pandas` `scikit-learn` `matplotlib` `seaborn`
