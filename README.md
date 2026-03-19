# Aplikasi Web Data Mining

Ini merupakan project aplikasi web interaktif berbasis Streamlit untuk membandingkan akurasi klasifikasi 3 algoritma populer: KNN, SVM, dan Random Forest, dengan dataset bawaan scikit-learn.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ircham2.streamlit.app/)

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
1. Siapkan virtual environment:
   ```bash
   python -m venv .venv
   ```
2. Aktivasi .venv dengan:
   ```bash
    .venv\Scripts\activate.bat # Windows command prompt
    .venv\Scripts\Activate.ps1 # Windows PowerShell
    source .venv/bin/activate # macOS and Linux
   ```
 
3. Install dependency:
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
