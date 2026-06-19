# Klasifikasi Sampah Organik dan Anorganik Menggunakan CNN

## Deskripsi Proyek

Proyek ini bertujuan untuk mengklasifikasikan gambar sampah menjadi dua kategori, yaitu sampah organik dan sampah anorganik menggunakan metode Convolutional Neural Network (CNN).

## Dataset

Dataset terdiri dari 1858 gambar yang dibagi menjadi dua kelas:

* Organik
* Anorganik

Pembagian data:

* Data Training : 1487 gambar (80%)
* Data Validasi : 371 gambar (20%)

## Preprocessing

Tahapan preprocessing yang dilakukan:

1. Resize gambar menjadi 128 × 128 piksel.
2. Normalisasi nilai piksel menggunakan rescale = 1/255.
3. Pembagian data training dan validation menggunakan validation_split = 0.2.

## Arsitektur CNN

Input Layer (128×128×3)

↓

Conv2D (32 Filter)

↓

MaxPooling2D

↓

Conv2D (64 Filter)

↓

MaxPooling2D

↓

Conv2D (128 Filter)

↓

MaxPooling2D

↓

Flatten

↓

Dense (128)

↓

Dropout (0.5)

↓

Output Layer (Sigmoid)

## Hasil Pelatihan

* Training Accuracy : 96.44%
* Validation Accuracy : 77.63%

## Teknologi yang Digunakan

* Python
* TensorFlow
* Keras
* Google Colab
* NumPy
* Matplotlib
* Scikit-learn

## Cara Menjalankan

1. Upload dataset ke Google Colab.
2. Jalankan notebook Klasifikasi_Sampah.ipynb.
3. Lakukan training model.
4. Simpan model menggunakan model.save().
5. Upload gambar baru untuk melakukan prediksi.

## Kesimpulan

Model CNN berhasil mengklasifikasikan sampah organik dan anorganik dengan akurasi validasi sebesar 77.63%. Hasil ini menunjukkan bahwa CNN mampu mengenali karakteristik visual sampah dan dapat digunakan sebagai dasar sistem pemilahan sampah otomatis.
# UAS-Klasifikasi-Sampah-Organik-dan-Anorganik-Menggunakan-Metode-Convolutional-Neural-Network-CNN-
