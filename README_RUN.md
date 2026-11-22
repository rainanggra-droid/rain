# Prediksi Nilai Akhir Matematika Siswa — Streamlit App (Executive Dark Analytics)

## Isi Folder
- `app_gabungan.py` — Aplikasi Streamlit terpadu (Regresi, Clustering, Prediksi Massal, Evaluasi Model, & EDA interaktif Plotly).
- `requirements.txt` — Daftar dependensi Python (sudah menyertakan `plotly`).
- `student-mat.xlsx` — Dataset UCI Student Performance (Matematika, 395 baris × 33 kolom).
- `.streamlit/config.toml` — Konfigurasi tema gelap (*Executive Dark Analytics*).

## Cara Menjalankan di Lokal
1. Pastikan Python 3.10+ terpasang, lalu install dependensi:
   ```bash
   pip install -r requirements.txt
   ```
2. Jalankan aplikasi Streamlit dari folder yang berisi `app_gabungan.py`:
   ```bash
   streamlit run app_gabungan.py
   ```

## Cara Deploy ke Streamlit Community Cloud
1. Unggah seluruh isi folder ini (termasuk folder `.streamlit/config.toml`) ke repositori GitHub.
2. Pada Streamlit Community Cloud, pilih `app_gabungan.py` sebagai *Main file path*.
