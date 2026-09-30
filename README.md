Markdown# 📊 Employee Workplace & Performance Analytics (EDA)

Proyek ini berfokus pada **Pembersihan Data (Data Cleaning)** dan **Analisis Data Eksploratif (Exploratory Data Analysis - EDA)** terhadap data karyawan untuk mengidentifikasi pola hubungan antara produktivitas, kepuasan kerja, peran jabatan, departemen, serta kompensasi gaji.

---

## 📌 Ringkasan Proyek

Analisis performa dan retensi karyawan sangat penting untuk pengambilan keputusan strategis di bidang SDM (*Human Resources*). Proyek ini mencakup alur kerja *data science* hulu ke hilir:
1. **Inspeksi Awal & Pembersihan Duplikasi:** Memeriksa struktur awal dataset serta menghapus data redundan/duplikat.
2. **Pendeteksian Outlier & Imputasi Missing Values:** Menggunakan visualisasi *Boxplot* untuk mendeteksi outlier sebelum menentukan metode imputasi (Mean/Median untuk numerik, Mode untuk kategorikal).
3. **Standarisasi Fitur Kategorikal:** Menyeragamkan inkonsistensi input pada variabel `Gender`, `Department`, dan `Position`.
4. **Feature Engineering / Kategorisasi Gaji:** Mengelompokkan nominal `Salary` ke dalam beberapa rentang kategori untuk mempermudah visualisasi dan interpretasi analitik.
5. **Visualisasi Data & Analisis Hubungan:** Mengevaluasi distribusi fitur numerik serta mengkaji korelasi antara produktivitas, jumlah proyek, gender, dan kompensasi.

---

## 📁 Struktur Direktori

```text
├── dataset/
│   └── dataset aol itds.csv       # File data mentah karyawan
├── notebook/
│   └── code aol itds.ipynb        # Jupyter Notebook analisis lengkap
├── assets/
│   └── poster aol itds.png        # Poster / infografis hasil analisis
├── README.md                      # Dokumentasi proyek
└── requirements.txt               # Daftar pustaka Python
```

---

## 🛠️ Tech Stack & Pustaka
Bahasa: Python 3.x
Manipulasi & Analisis Data: Pandas, NumPy
Visualisasi Data: Matplotlib, Seaborn

---

## 🚀 Cara Menjalankan Kode Secara Lokal

Clone repositori ini:
```
git clone [https://github.com/USERNAME-KAMU/employee-performance-eda.git](https://github.com/USERNAME-KAMU/employee-performance-eda.git)
cd employee-performance-eda
```
Pasang dependensi yang diperlukan:
```
install pandas numpy matplotlib seaborn jupyter
```
Jalankan Jupyter Notebook:
```
jupyter notebook
```
Buka file notebook code aol itds.ipynb dan jalankan sel kode secara berurutan.

---

## 👤 Author
Nama: Vanessa Santoso
Fokus: Data Science & Analytics
