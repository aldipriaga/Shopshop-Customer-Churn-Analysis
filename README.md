# Analisis Customer Churn Shopshop

Deskripsi Proyek
Proyek ini merupakan studi kasus analisis data untuk mengidentifikasi pemicu customer churn di Shopshop, sebuah perusahaan e-commerce. Tujuan utamanya adalah untuk menemukan wawasan bisnis yang dapat ditindaklanjuti guna membantu tim manajemen mengembangkan strategi retensi pelanggan yang lebih efektif.

Metodologi Analisis
Proyek ini menggunakan pendekatan Analisis Data Eksploratif (EDA) untuk memahami pola data dan menemukan insight yang tersembunyi. Tahapan utamanya meliputi:
- Pembersihan Data: Mengidentifikasi dan menangani nilai yang hilang.
- Analisis Pola Data Hilang: Menguji hipotesis bahwa data yang hilang bukanlah acak (Missing Not At Random / MNAR), melainkan memiliki makna bisnis.
- Analisis Korelasi: Mengidentifikasi hubungan antara berbagai fitur (seperti Complain dan Tenure) dengan Churn.
- Visualisasi Data: Membuat grafik dan visualisasi untuk menyajikan temuan secara jelas dan ringkas.

Temuan Kunci
1. Keluhan Pelanggan adalah Pemicu Utama: Analisis korelasi menunjukkan bahwa Complain memiliki korelasi positif yang kuat dengan Churn (0.25).
2. Data Hilang adalah Sinyal Bisnis:
  -. Pelanggan dengan data Tenure yang hilang memiliki tingkat Churn jauh lebih tinggi (~30.7%), mengindikasikan churn prematur.
  -. Pelanggan dengan data OrderCount yang hilang menunjukkan tingkat Churn yang sangat rendah (~7%), mengindikasikan segmen pelanggan yang berpotensi sangat loyal.
3. Faktor Operasional Lain: Masalah operasional seperti WarehouseToHome juga berkorelasi positif dengan Churn.

Rekomendasi Bisnis
Berdasarkan temuan di atas, berikut adalah rekomendasi strategis untuk Shopshop:
1. Fokus pada Pelanggan Baru: Prioritaskan customer support untuk pelanggan baru dan terapkan program onboarding yang lebih baik.
2. Manfaatkan Segmen Loyal: Ciptakan program retensi yang berfokus pada pelanggan yang menunjukkan sinyal loyalitas (OrderCount hilang) untuk mendorong mereka agar mulai berbelanja.
3. Investigasi Operasional: Selidiki masalah pada logistik pengiriman dan CityTier yang memiliki tingkat Churn tinggi.
