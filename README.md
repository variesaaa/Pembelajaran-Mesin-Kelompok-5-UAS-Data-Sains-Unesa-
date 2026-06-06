# 🩸 Blood Cell Classification for Cancer Detection using SVM and CNN
📌 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan klasifikasi citra sel darah menggunakan pendekatan Machine Learning dan Deep Learning pada dataset Blood Cell Images for Cancer Detection.

Penelitian dilakukan dengan membandingkan performa dua model klasifikasi:

Support Vector Machine (SVM) menggunakan fitur morfologi hasil ekstraksi nucleus.
Convolutional Neural Network (CNN) menggunakan citra hasil preprocessing secara langsung.

Sebelum proses pemodelan, dilakukan tahap preprocessing berupa segmentasi nucleus menggunakan HSV Thresholding, operasi morfologi, ROI Cropping, dan resizing citra menjadi 224×224 piksel.

Hasil penelitian menunjukkan bahwa model CNN memberikan performa yang jauh lebih baik dibandingkan SVM dalam mengklasifikasikan lima jenis sel darah.

🎯 Tujuan
Melakukan preprocessing citra sel darah menggunakan segmentasi nucleus.
Mengekstraksi fitur morfologi nucleus.
Membangun model klasifikasi menggunakan SVM.
Membangun model klasifikasi menggunakan CNN.
Membandingkan performa kedua model menggunakan berbagai metrik evaluasi.
📂 Dataset

Dataset yang digunakan:

Blood Cell Images for Cancer Detection

Kaggle:

https://www.kaggle.com/datasets/sumithsingh/blood-cell-images-for-cancer-detection

Dataset terdiri dari 5 kelas:

Basophil
Erythroblast
Monocyte
Myeloblast
Segmented Neutrophil
