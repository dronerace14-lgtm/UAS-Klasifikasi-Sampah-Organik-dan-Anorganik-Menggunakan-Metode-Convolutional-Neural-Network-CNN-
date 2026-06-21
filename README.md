# 🗑️ Implementasi Convolutional Neural Network (CNN) untuk Klasifikasi Sampah Organik dan Anorganik Berdasarkan Citra Digital

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk mengimplementasikan metode **Convolutional Neural Network (CNN)** dalam mengklasifikasikan citra sampah ke dalam dua kategori, yaitu **sampah organik** dan **sampah anorganik**. Sistem dibangun menggunakan **Python**, **TensorFlow**, dan **Keras** untuk mempelajari karakteristik visual dari gambar sampah sehingga dapat melakukan klasifikasi secara otomatis.

Melalui proyek ini diharapkan dapat menjadi langkah awal dalam pengembangan sistem pemilahan sampah otomatis berbasis kecerdasan buatan (Artificial Intelligence).

---

## 🎯 Tujuan Proyek

* Mengimplementasikan metode CNN untuk klasifikasi sampah organik dan anorganik.
* Melatih model menggunakan dataset citra sampah.
* Mengevaluasi performa model menggunakan accuracy, confusion matrix, dan classification report.
* Melakukan prediksi terhadap citra baru yang belum pernah digunakan pada proses pelatihan.

---

## 🛠️ Teknologi yang Digunakan

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-Learn
* Google Colab

---

## 📂 Struktur Proyek

```bash
├── dataset/
│   ├── organik/
│   └── anorganik/
│
├── model/
│   └── model_sampah.h5
│
├── notebook/
│   └── klasifikasi_sampah.ipynb
│
├── hasil/
│   ├── accuracy.png
│   ├── loss.png
│   └── confusion_matrix.png
│
└── README.md
```

---

## 🧠 Arsitektur CNN

Model CNN yang digunakan terdiri dari:

* Conv2D (32 Filter, ReLU)
* MaxPooling2D
* Conv2D (64 Filter, ReLU)
* MaxPooling2D
* Conv2D (128 Filter, ReLU)
* MaxPooling2D
* Flatten Layer
* Dense Layer (128 Neuron)
* Dropout (0.5)
* Output Layer (Sigmoid)

---

## 📊 Hasil Pengujian

| Parameter           | Hasil               |
| ------------------- | ------------------- |
| Training Accuracy   | 96,44%              |
| Validation Accuracy | 77,63%              |
| Epoch               | 10                  |
| Optimizer           | Adam                |
| Loss Function       | Binary Crossentropy |

Model mampu mengidentifikasi citra sampah organik dan anorganik dengan cukup baik berdasarkan hasil evaluasi menggunakan confusion matrix dan classification report.

---

## 📄 Dokumentasi

### PPT Presentasi

https://docs.google.com/presentation/d/1yCpuWHmWaAmWFkGVHmJDRu_nMkKCSyCI/edit?usp=drive_link&ouid=105584124612817838847&rtpof=true&sd=true

### Video Demo

Tambahkan link video demo di sini

### Dataset

Tambahkan link dataset di sini

---

## 🚀 Cara Menjalankan Proyek

1. Clone repository:

```bash
git clone https://github.com/username/nama-repository.git
```

2. Install library yang diperlukan:

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

3. Jalankan notebook:

```bash
jupyter notebook klasifikasi_sampah.ipynb
```

atau buka melalui Google Colab.

---

## 👨‍🎓 Penulis

**Salim Zaky Achmad**

Teknik Elektro
Universitas Brawijaya

---

## 📚 Referensi

1. Goodfellow, I., Bengio, Y., & Courville, A. *Deep Learning*. MIT Press, 2016.
2. Chollet, F. *Deep Learning with Python*. Manning Publications, 2021.
3. TensorFlow Documentation.
4. Keras Documentation.
5. Berbagai jurnal klasifikasi sampah menggunakan CNN.
