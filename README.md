🚢 Titanic Survival Prediction

Proyek ini bertujuan untuk memprediksi kelangsungan hidup penumpang kapal Titanic menggunakan algoritma machine learning berbasis Python dan scikit-learn.

📁 Dataset

Dataset yang digunakan adalah Titanic-Dataset.csv, yang berisi informasi penumpang seperti:

Nama

Umur

Jenis Kelamin

Kelas Tiket

Jumlah Saudara/Istri

Embarked (Pelabuhan Naik)

dll.

🧪 Tahapan Analisis

Import Library & Load Data

Menggunakan pustaka seperti pandas, numpy, matplotlib, seaborn, dan sklearn.

Eksplorasi dan Pembersihan Data

Menampilkan informasi dan statistik awal.

Menangani data hilang.

Label encoding untuk fitur kategorikal.

Normalisasi fitur numerik.

Modeling

Menggunakan Support Vector Machine (SVM) dan Random Forest untuk klasifikasi.

Evaluasi model dengan metrik seperti: akurasi, precision, recall, F1-score, confusion matrix.

Evaluasi Hasil

Perbandingan performa kedua model.

Visualisasi menggunakan confusion matrix dan grafik lainnya.

💻 Cara Menjalankan

Pastikan Anda memiliki Python dan dependensi berikut:

pip install pandas numpy scikit-learn matplotlib seaborn
Jalankan notebook Jupyter:

jupyter notebook titanic.ipynb

Pastikan file Titanic-Dataset.csv tersedia di direktori yang sama dengan notebook.

📊 Hasil

Model memberikan prediksi apakah penumpang selamat atau tidak, dengan metrik evaluasi seperti akurasi dan F1-score ditampilkan untuk masing-masing algoritma.