Berikut README.md yang sudah aku susun berdasarkan isi notebook kamu (rapi, siap taruh di repo GitHub):

---

# 📸 Face Recognition untuk Pengenalan Identitas

Proyek ini merupakan implementasi **Machine Learning untuk face recognition** yang digunakan untuk mengenali identitas seseorang berdasarkan data citra wajah dan atribut tambahan seperti usia dan gender.

---


## 🧰 Library yang Digunakan

* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`
* `opencv (cv2)`
* `scikit-learn`

---

## 🔍 Exploratory Data Analysis (EDA)

Dilakukan untuk memahami distribusi data:

### 1. Distribusi Usia

* Menggunakan histogram + KDE
* Melihat sebaran umur dalam dataset

### 2. Distribusi Gender

* Countplot untuk melihat proporsi gender

---

## ⚙️ Data Preprocessing

### 1. Resize & Normalisasi Gambar

* Semua gambar diubah ke ukuran **100x100**
* Disimpan kembali setelah preprocessing

### 2. Histogram Equalization

* Digunakan untuk meningkatkan kontras gambar
* Membantu model mengenali fitur wajah lebih baik

### 3. Encoding Label

* `LabelEncoder` untuk mengubah ID menjadi numerik

---

## 🤖 Model yang Digunakan

Beberapa algoritma Machine Learning diuji:

### 1. Logistic Regression

* Model baseline
* Cepat dan sederhana

### 2. Random Forest

* Lebih robust terhadap noise
* Menggunakan ensemble learning

### 3. Support Vector Machine (SVM)

* Cocok untuk data berdimensi tinggi

### 4. K-Nearest Neighbors (KNN)

* Berdasarkan kedekatan data

---

## 🧪 Training & Evaluasi

Pipeline umum:

1. Preprocess gambar
2. Preprocess data CSV
3. Gabungkan fitur
4. Split data:

   * Train set
   * Test set
5. Training model
6. Evaluasi menggunakan:

   * Accuracy
   * Classification Report

---

## 📈 Visualisasi Hasil

* Perbandingan performa model
* Distribusi prediksi
* Insight dari hasil klasifikasi

---

## 🧠 Insight & Hasil

* Model dengan performa terbaik bergantung pada preprocessing
* Histogram Equalization membantu meningkatkan akurasi
* Kombinasi fitur gambar + atribut meningkatkan performa

---
