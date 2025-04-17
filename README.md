# System Rekomendasi Transformer Model (Sentiment Analysis Tokopedia)

Proyek ini merupakan sistem analisis sentimen dari review produk Tokopedia, yang digunakan sebagai bagian dari eksperimen berbagai model machine learning, termasuk LSTM dan beberapa model klasik seperti Naive Bayes, SVM, dan XGBoost.

## 📁 Struktur File

- `model-pelatihan.ipynb` - Notebook untuk melatih dan mengevaluasi model.
- `scraping.ipynb` - Notebook untuk scraping data review dari Tokopedia.
- `sentiment_lstm_model.h5` - Model LSTM hasil pelatihan.
- `sentiment_nb_model.pkl` - Model Naive Bayes hasil pelatihan.
- `sentiment_svm_model.pkl` - Model SVM hasil pelatihan.
- `sentiment_xgb_model.pkl` - Model XGBoost hasil pelatihan.
- `tokopedia_reviews_raw.csv` - Dataset hasil scraping (belum diproses).
- `tokopedia_reviews_processed.csv` - Dataset yang sudah diproses.
- `tokopedia_reviews_binary.csv` - Dataset dengan label biner (positif/negatif).
- `requirments.txt` - Daftar dependencies yang dibutuhkan (perlu diperbaiki namanya jadi `requirements.txt`).

## ⚙️ Cara Menjalankan

1. Clone repository ini:
   ```bash
   git clone https://github.com/Npppss/system-rekomendasi-transformer-model.git
   
