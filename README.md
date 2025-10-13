# 📌 Segmentasi Pasar dengan K-Means Clustering  

## 🧠 Deskripsi Proyek  
Proyek ini bertujuan untuk melakukan **segmentasi pelanggan** berdasarkan perilaku belanja pada dataset *E-commerce Customer Behavior*.  
Analisis dilakukan melalui beberapa tahapan, mulai dari **EDA (Exploratory Data Analysis)**, **preprocessing**, penentuan jumlah cluster optimal menggunakan **Elbow Method** & **Silhouette Score**, hingga **interpretasi hasil clustering (K=3)**.

---

## 📂 Dataset  
Dataset yang digunakan diambil dari Kaggle:  
🔗 [E-commerce Customer Behavior Dataset – Kaggle](https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset)  

Dataset ini berisi **350 baris data** dan **11 kolom**, yang merepresentasikan atribut profil serta perilaku pelanggan terhadap transaksi e-commerce.

---

## 🔑 Fitur Utama Analisis  

1. **Eksplorasi Data (EDA)**  
   - Visualisasi awal menggunakan boxplot, seperti hubungan antara *Membership* dan *Total Spend*.  

2. **Pra-pemrosesan Data**  
   - Melakukan *label encoding* untuk data kategorikal.  
   - Melakukan *standardisasi* untuk menyeimbangkan skala antar fitur.  

3. **Penentuan Jumlah Cluster Optimal**  
   - Menggunakan **Elbow Method** dan **Silhouette Score** untuk menentukan nilai *K* terbaik.  

4. **Penerapan K-Means Clustering**  
   - Segmentasi pelanggan menjadi tiga kelompok:  
     - **High Value Customers (Gold-like)**  
     - **Mid Value Customers (Silver-like)**  
     - **Low Value Customers (Bronze-like)**  

5. **Visualisasi & Evaluasi Hasil**  
   - Menampilkan hasil clustering dalam bentuk **boxplot**, **scatterplot**, dan **grafik evaluasi** untuk interpretasi lebih lanjut.  

---

## 📊 Hasil Utama  
Analisis menghasilkan **3 segmen pelanggan utama** dengan karakteristik yang berbeda:

| Segmen | Rata-rata Total Spend | Items Purchased | Days Since Last Purchase | Karakteristik |
|:-------|:----------------------:|:----------------:|:-------------------------:|:--------------|
| 0 | 473 | 8 | 31 | Usia lebih tua, belanja rendah, jarang transaksi |
| 1 | 1311 | 18 | 18 | Usia muda, belanja tinggi, aktif bertransaksi |
| 2 | 748 | 12 | 30 | Usia menengah, belanja sedang, aktivitas moderat |

Insight ini dapat dimanfaatkan untuk strategi pemasaran seperti:  
- Retensi pelanggan bernilai tinggi.  
- Program *upselling* dan *cross-selling*.  
- Aktivasi pelanggan pasif.  

---

## 🧰 Tools & Teknologi  
- **Python**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
- **Jupyter Notebook / Google Colab**  

---

## ✍️ Author  
**ricki309**  
📚 Proyek ini merupakan bagian dari portofolio pembelajaran data analytics.
