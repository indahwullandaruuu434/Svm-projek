# Diabetes Prediction Model

Proyek ini mengembangkan model machine learning untuk memprediksi status merokok pasien berdasarkan data kesehatan. Model dibangun menggunakan algoritma Support Vector Machine (SVM) dan dilatih pada dataset dengan beberapa fitur medis.

## Dataset
Dataset `K02_diabetes.csv` berisi informasi kesehatan pasien, termasuk:
- `gender`: Jenis kelamin pasien
- `age`: Umur pasien
- `hypertension`: Status hipertensi (0 = tidak, 1 = ya)
- `heart_disease`: Riwayat penyakit jantung (0 = tidak, 1 = ya)
- `smoking_history`: Riwayat merokok pasien
- `bmi`: Indeks massa tubuh
- `HbA1c_level`: Tingkat HbA1c pasien
- `blood_glucose_level`: Tingkat glukosa darah
- `diabetes`: Status diabetes pasien

## Langkah-langkah Utama
1. **Eksplorasi Data**: Melihat struktur data, menghitung statistik deskriptif, dan mengecek nilai yang hilang.
2. **Preprocessing Data**: Menggunakan pipeline untuk scaling kolom numerik dan one-hot encoding kolom kategorikal.
3. **Pembagian Data**: Memisahkan data menjadi data latih dan data uji (80:20).
4. **Membangun Model SVM**: Membangun model SVM dengan kernel RBF.
5. **Evaluasi Model**: Mengevaluasi performa model menggunakan akurasi, laporan klasifikasi, dan confusion matrix.
6. **Visualisasi Hasil**: Menggunakan confusion matrix dan kurva ROC untuk mengevaluasi model.

## Prasyarat
Pastikan library berikut sudah terinstall:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Menjalankan Proyek
1. Jalankan setiap sel dalam notebook secara berurutan.
2. Lihat hasil evaluasi dan visualisasi untuk memahami performa model.

## Hasil Evaluasi
Hasil evaluasi menunjukkan akurasi model, confusion matrix, serta kurva ROC untuk memeriksa trade-off antara sensitivitas dan spesifisitas.

