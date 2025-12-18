# 📘 Judul Proyek
*Prediksi Popularitas Berita Online (Online News Popularity Prediction)*

## 👤 Informasi
- **Nama:** FAUZAN FATHIN ZAKY  
- **Repo:** [...]  
- **Video:** [...]  

---

# 1. 🎯 Ringkasan Proyek
- Melakukan pembersihan dan eksplorasi data (EDA) untuk memahami pola viralitas  
- Melakukan transformasi data (Log Transform & Scaling) untuk menangani distribusi skewed. 
- Membangun dan membandingkan 3 model: Linear Regression (Baseline), Random Forest (Advanced), dan Multilayer Perceptron (Deep Learning).  
- Mengevaluasi model menggunakan metrik RMSE, MAE, dan R² Score  

---

# 2. 📄 Problem & Goals
**Problem Statements:**  
- Bagaimana cara memprediksi jumlah share artikel berita berdasarkan karakteristik konten (judul, topik, sentimen)?  
- Fitur apa yang paling berpengaruh terhadap viralitas sebuah artikel?
- Model mana yang memberikan prediksi paling akurat antara pendekatan statistik, machine learning, dan deep learning?

**Goals:**  
- Membangun model regresi dengan error (RMSE) seminimal mungkin.
- Mengidentifikasi fitur dominan (seperti keyword populer atau kategori topik) yang mempengaruhi popularitas.
- Menyediakan pipeline end-to-end yang dapat direproduksi ulang.

---
## 📁 Struktur Folder
```
project/
│
├── data/                   # Dataset (tidak di-commit, download manual)
│
├── notebooks/              # Jupyter notebooks
│   └── 234311014_UAS_FAUZANF.Z.ipynb
│
├── src/                    # Source code
│   
├── models/                 # Saved models
│   ├── scaler.pkl
│   ├── model_linear_regression.pkl
│   ├── model_random_forest.pkl
│   └── model_deep_learning.h5
│
├── images/                 # Visualizations
│   ├── distribusi_shares.png
│   ├── heatmap_korelasi.png
│   ├── rf_feature_importance.png
│   ├── dl_training_history.png
│   └── model_comparison.png
│
├── requirements.txt        # Dependencies
├── .gitignore
└── README.md
```
---

# 3. 📊 Dataset
- **Sumber:** https://archive.ics.uci.edu/dataset/332/online+news+popularity  
- **Jumlah Data:** 39,644 baris, 61 kolom.  
- **Tipe:** Tabular (Numerik & Kontinu).

### Fitur Utama
| Fitur | Deskripsi |
|------|-----------|
| n_tokens_content | Jumlah kata dalam artikel. |
| num_imgs | Jumlah gambar dalam artikel. |
| data_channel_is_*| Kategori berita (Tech, Entertainment, World, dll). |
|kw_avg_avg|Rata-rata performa kata kunci (keyword) historis.|
|global_sentiment_polarity|Sentimen keseluruhan teks (Positif/Negatif).|
|shares|(Target) Jumlah share di media sosial.|

---

# 4. 🔧 Data Preparation
- Cleaning (missing/duplicate/outliers)  
- Transformasi (encoding/scaling)  
- Splitting (train/val/test)  

---

# 5. 🤖 Modeling
- **Model 1 – Baseline:** [...]  
- **Model 2 – Advanced ML:** [...]  
- **Model 3 – Deep Learning:** [...]  

---

# 6. 🧪 Evaluation
**Metrik:** Accuracy / F1 / MAE / MSE (pilih sesuai tugas)

### Hasil Singkat
| Model | Score | Catatan |
|-------|--------|---------|
| Baseline | [...] | |
| Advanced | [...] | |
| Deep Learning | [...] | |

---

# 7. 🏁 Kesimpulan
- Model terbaik: [...]  
- Alasan: [...]  
- Insight penting: [...]  

---

# 8. 🔮 Future Work
- [ ] Tambah data  
- [ ] Tuning model  
- [ ] Coba arsitektur DL lain  
- [ ] Deployment  

---

# 9. 🔁 Reproducibility
Gunakan environment:
