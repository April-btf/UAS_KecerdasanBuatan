# 🩺 SkinVision AI: Klasifikasi Penyakit Kulit Menggunakan Deep Learning (CNN)

## Deskripsi Proyek

Proyek ini merupakan tugas Ujian Akhir Semester (UAS) mata kuliah Kecerdasan Buatan yang bertujuan membangun model Deep Learning menggunakan algoritma Convolutional Neural Network (CNN) untuk mengklasifikasikan berbagai jenis penyakit kulit berdasarkan citra digital.

Model dilatih menggunakan dataset citra penyakit kulit sehingga mampu mengenali karakteristik visual setiap kelas penyakit. Sistem ini diharapkan dapat membantu proses identifikasi awal penyakit kulit secara otomatis sebagai Decision Support System (DSS) dan bukan sebagai pengganti diagnosis dokter.

# 🎯 Tujuan Proyek
- Membangun model klasifikasi penyakit kulit menggunakan Deep Learning (CNN).
- Mengidentifikasi jenis penyakit kulit berdasarkan citra digital.
- Mengevaluasi performa model menggunakan Accuracy, Precision, Recall, F1-Score, dan Confusion Matrix.
- Menghasilkan model dengan performa yang baik dalam mengklasifikasikan penyakit kulit.

# 📊 Dataset
- Nama Dataset : Skin Classification Normal-Acne-Oily-Dry-Wrinkle
- Sumber Dataset : Kaggle
- Pembuat Dataset : Rajesh Pandhare
- Jenis Data : Image Classification
- Jumlah Data : 732 gambar
- Jumlah Kelas : 7 kelas
- Format Gambar : JPG/PNG
- Ukuran Input Model : 224 × 224 piksel

Dataset proyek berada pada folder:

```text
data/dataset/
```

# 🤖 Algoritma yang Digunakan

- Mobile NetV2
- Convolutional Neural Network (CNN)


# 📋 Tahapan Pengerjaan
## 1. Business Understanding
Menentukan permasalahan yang akan diselesaikan, tujuan penelitian, manfaat implementasi Artificial Intelligence pada bidang kesehatan, serta melakukan studi literatur berdasarkan jurnal ilmiah yang relevan.
## 2. Data Understanding

Mempelajari karakteristik dataset, struktur folder, jumlah kelas, serta memahami data yang akan digunakan pada proses pelatihan model.

## 3. Exploratory Data Analysis (EDA)

Melakukan eksplorasi data dengan menampilkan contoh gambar, distribusi kelas, dan karakteristik visual masing-masing penyakit kulit.

## 4. Data Preparation

Melakukan preprocessing data dengan tahapan:

- Resize gambar menjadi 224 × 224 piksel.
- Normalisasi nilai piksel.
- Data Augmentation.
- Pembagian data menjadi data training dan validation.

## 5. Modeling

Membangun model menggunakan algoritma **Convolutional Neural Network (CNN)** dengan TensorFlow dan Keras.

## 6. Evaluation

Evaluasi model dilakukan menggunakan:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# 📈 Hasil

Model berhasil melakukan klasifikasi penyakit kulit berdasarkan citra digital.

| Metrik | Hasil |
|---------|-------|
| Training Accuracy | *(Isi hasil Anda)* |
| Validation Accuracy | *(Isi hasil Anda)* |
| Training Loss | *(Isi hasil Anda)* |
| Validation Loss | *(Isi hasil Anda)* |

> Hasil lengkap dapat dilihat pada notebook dan file **Laporan.md**.

---

# 📁 Struktur Repository

```text
UAS_Kecerdasan-Buatan/
│
├── README.md
├── Laporan.md
├── Klasifikasi Kulit Berbasis Computer Vision.ipynb
│
├── data/
│   ├── dataset/
│   └── jurnal/
│
├── images/
│   ├── accuracy.png
│   ├── loss.png
│   ├── confusion_matrix.png
│   └── sample_prediction.png
│
├── model/
│   ├── skin_disease_model.keras
│   └── class_names.npy
│
└── requirements.txt
```

---

# 📚 Referensi

1. Esteva, A., et al. (2017). *Dermatologist-level classification of skin cancer with deep neural networks*. Nature.
2. Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.
3. Chollet, F. (2021). *Deep Learning with Python (2nd Edition)*. Manning Publications.

---

# 👩‍🎓 Penulis

**Nama** : *(Nama Anda)*

**NIM** : *(NIM Anda)*

**Mata Kuliah** : Kecerdasan Buatan

**Program Studi** : *(Program Studi Anda)*
