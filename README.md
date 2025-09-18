# 🏡 House Price Prediction with Linear Regression  

## 📌 Deskripsi Proyek  
Proyek ini bertujuan untuk menganalisis faktor-faktor yang memengaruhi harga rumah serta membangun model prediksi menggunakan **Linear Regression**. Dataset yang digunakan mencakup beberapa fitur penting seperti:  

- **square_feet** → luas bangunan  
- **num_rooms** → jumlah ruangan  
- **age** → usia rumah  
- **distance_to_city(km)** → jarak ke pusat kota  
- **price** → harga rumah (variabel target)  

Notebook ini menyajikan alur lengkap mulai dari **pembersihan data**, **eksplorasi data (EDA)**, hingga **pembangunan model prediktif**.  

---

## 🔍 Langkah-Langkah Analisis  

1. **Data Loading & Cleaning**  
   - Memuat dataset dari file CSV.  
   - Menangani missing values dan konversi tipe data.  
   - Menghapus data yang tidak lengkap agar analisis lebih bersih.  

2. **Exploratory Data Analysis (EDA)**  
   - Membuat **histogram** distribusi tiap fitur.  
   - Menampilkan **pairplot** untuk melihat hubungan antar variabel.  
   - Membuat **correlation heatmap** untuk mengidentifikasi variabel yang paling berpengaruh.  
   - Membuat **countplot** untuk distribusi kategori jumlah kamar.  

3. **Predictive Modeling**  
   - Membagi dataset menjadi **train set** dan **test set**.  
   - Melatih model **Linear Regression** untuk memprediksi harga rumah.  
   - Evaluasi menggunakan metrik:  
     - **R² Score** → mengukur seberapa baik fitur menjelaskan variasi harga.  
     - **Mean Squared Error (MSE)** → mengukur rata-rata kesalahan prediksi.  

---

## 📊 Hasil Analisis  
- **Luas rumah** dan **jumlah ruangan** memiliki korelasi positif dengan harga.  
- **Usia rumah** cenderung menurunkan harga.  
- Model Linear Regression memberikan baseline yang cukup baik untuk prediksi harga rumah.  

---

## 🚀 Potensi Pengembangan  
- Menambahkan **feature engineering** (interaksi antar fitur, polinomial).  
- Menggunakan algoritma lain seperti **Random Forest** atau **Gradient Boosting**.  
- Mengatasi **outlier** yang memengaruhi performa model.  
- Membuat **dashboard interaktif** untuk visualisasi hasil prediksi.  

---

## 🛠️ Tools & Libraries  
- **Python**  
- **Pandas, NumPy** → Data wrangling  
- **Matplotlib, Seaborn** → Visualisasi data  
- **Scikit-learn** → Machine learning & evaluasi model  

---
