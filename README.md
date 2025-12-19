# Heart Failure Prediction using Neural Network

## Deskripsi Project
Project ini bertujuan untuk memprediksi risiko kematian pasien gagal jantung
menggunakan metode **Neural Network** berdasarkan data klinis pasien.
Model ini diharapkan dapat berperan sebagai **Decision Support System**
dalam Sistem Informasi Kesehatan.

---

## Dataset
- **Nama Dataset:** Heart Failure Clinical Records Dataset  
- **Sumber:** UCI Machine Learning Repository  
- **Link Dataset:**
  https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records  
- **Jumlah Data:** 299 pasien  
- **Jumlah Atribut:** 13  
- **Target:** `DEATH_EVENT` (0 = Hidup, 1 = Meninggal)  
- **Missing Value:** Tidak ada  

Dataset berisi data klinis pasien seperti umur, tekanan darah, diabetes,
kadar kreatinin, kebiasaan merokok, dan atribut medis lainnya.

---

## Ruang Lingkup Pengerjaan
1. Data Understanding  
2. Data Preparation  
3. Desain Neural Network  
4. Training dan Testing Model (70:30)  
5. Evaluasi Model  
6. Interpretasi dari Perspektif Sistem Informasi  

---

## Arsitektur Neural Network
- **Input Layer:** 12 neuron  
- **Hidden Layer 1:** 16 neuron (ReLU)  
- **Hidden Layer 2:** 8 neuron (ReLU)  
- **Output Layer:** 1 neuron (Sigmoid)  

Model dilatih menggunakan:
- Optimizer: Adam  
- Loss Function: Binary Crossentropy  
- Epoch: 100  
- Batch Size: 16  

---

## Evaluasi Model
Evaluasi dilakukan menggunakan data testing (30%) dengan metode:
- Accuracy  
- Confusion Matrix  
- Classification Report  

Hasil evaluasi menunjukkan bahwa model Neural Network mampu memprediksi
risiko kematian pasien gagal jantung dengan performa yang cukup baik.

---

