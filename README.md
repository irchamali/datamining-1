# Aplikasi Web Data Mining

Project ini adalah aplikasi web interaktif untuk membandingkan akurasi klasifikasi 3 algoritma populer: KNN, SVM, dan Random Forest, dengan dataset bawaan scikit-learn.

## Fitur
- Pilih dataset:
  - Bunga IRIS
  - Kanker Payudara
  - Digit Angka
- Pilih algoritma:
  - KNN
  - SVM
  - Random Forest
- Atur parameter algoritma di sidebar
- Tampilkan akurasi klasifikasi
- Visualisasi data (PCA 2D scatter)

## Instalasi
1. Siapkan virtual environment (opsional):
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # macOS/Linux
   .\.venv\Scripts\activate  # Windows
   ```
2. Install dependency:
   ```bash
   pip install -r requirements.txt
   ```

## Menjalankan aplikasi
```bash
streamlit run main.py
```

Setelah jalan, buka browser ke `http://localhost:8501`.

## Preview Deploy
- URL produksi: `https://ircham2.streamlit.app/`
- Pastikan repo ini sudah terhubung ke Streamlit Cloud dan `main.py` adalah entry point.

## Struktur
- `main.py`: kode aplikasi Streamlit
- `requirements.txt`: daftar dependensi
- `README.md`: dokumen ini

## Info Tambahan
- Untuk meningkatkan akurasi, bisa tambahkan feature scaling (StandardScaler), grid search (GridSearchCV), atau model lain.
- Gunakan `streamlit` versi `>=1.20`.
