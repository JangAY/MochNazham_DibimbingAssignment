# Survervised Learning Stundent Scores
Dataset ini berisi data mengenai jumlah jam belajar (Hours) dan skor ujian (Scores) dari 25 siswa. Tujuan dari analisis ini adalah memahami hubungan antara jumlah jam belajar dan skor ujian, serta mengevaluasi performa berbagai model regresi untuk memprediksi skor berdasarkan jam belajar.

## Tujuan Analisis 
1. Menentukan hubungan antara jam belajar dengan skor ujian.
2. Menganalisis distribusi data, termasuk outlier, data duplikat, dan nilai yang hilang (Missing Value).
3. Melakukan pemodelan regresi untuk memprediksi skor berdasarkan jumlah jam belajar.
4. Mengevaluasi performa model regresi menggunakan metrik R-squared dan Mean Squared Error (MSE).
5. Memberikan rekomendasi berdasarkan hasil analisis untuk meningkatkan akurasi prediksi.

## Insight
1. Hubungan Jam Belajar dan Skor: Terdapat hubungan linear positif antara jumlah jam belajar dan skor ujian.
   Semakin banyak jam belajar, semakin tinggi kemungkinan memperoleh skor ujian yang lebih baik.
3. Distribusi Data:
  - Tidak ada duplikasi data.
  - Tidak terdapat nilai yang hilang dalam dataset.
  - Tidak ada outlier signifikan pada kolom "Hours" maupun "Scores".
3. Hasil Pemodelan:
  - Linear Regression: Memberikan hasil yang baik dengan hubungan linear sederhana.
  - Decision Tree: Menangkap pola data dengan fleksibilitas tinggi, tetapi cenderung berisiko overfitting pada dataset kecil.
  - Random Forest: Memberikan performa terbaik dengan akurasi tinggi, stabilitas, dan ketahanan terhadap overfitting.

## Advices
1. Penggunaan Jam Belajar: Jika ingin memaksimalkan skor ujian, siswa disarankan untuk mengatur jam belajar secara konsisten.
Pemilihan Model:
  - Gunakan Random Forest Regressor untuk prediksi yang lebih akurat dalam dataset ini.
  - Jika interpretabilitas lebih penting, Linear Regression adalah pilihan terbaik karena kesederhanaannya.
3. Evaluasi Tambahan: Untuk analisis lebih mendalam, tambahkan fitur lain (seperti metode belajar atau motivasi siswa) untuk meningkatkan akurasi model.
4. Dataset yang Lebih Besar: Model seperti Decision Tree dan Random Forest akan bekerja lebih baik jika dilatih pada dataset yang lebih besar dengan lebih banyak variabel.
