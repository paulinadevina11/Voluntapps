# Voluntapps - Datathon 2025
**Platform Penghubung Relawan dengan Proyek Sosial di Indonesia**

---

## Deskripsi Singkat

**Voluntapps** adalah sistem rekomendasi yang membantu **relawan (volunteers)** menemukan **proyek sosial** yang paling sesuai dengan **keahlian**, **lokasi**, **minat**, dan **ketersediaan waktu** mereka.
Sistem ini mendukung organisasi sosial dalam menemukan relawan yang relevan dan berkomitmen, serta membantu mahasiswa memenuhi program volunteer kampus mereka.

---

## Tujuan Proyek

1. Memberikan kemudahan bagi para volunteer dalam mengakses proyek kerja sosial yang ada di wilayah Indonesia.
2. Mendukung Organisasi dalam menemukan relawan yang memiliki kemampuan yang relevan dengan yang dibutuhkan.
3. Menjadikan platform ini sarana edukasi bagi generasi muda Indonesia dalam meningkatkan keterlibatan sosial melalui kegiatan relawan.

---

## Fitur Utama

| Fitur                          | Deskripsi                                                                                   |
| -------------------------------| ------------------------------------------------------------------------------------------- |
| Smart Matching                 | Mencocokkan keahlian relawan dengan proyek menggunakan **TF-IDF + cosine similarity**.      |
| Regression Score               | Menggabungkan **kecocokan keahlian dan ketersediaan waktu** untuk menentukan skor total.    |
| Clustering Lokasi              | Mengelompokkan proyek berdasarkan **kemiripan geografis** dengan lokasi relawan.            |
| Neural Collaborative Filtering | Rekomendasi berbasis model deep learning untuk **personalized suggestions**.                |
| Input Interaktif               | Pengguna dapat memilih keahlian, lokasi, minat, dan ketersediaan dari daftar yang tersedia. |

---

## Struktur Dataset

Dataset ini diambil melalui https://github.com/junaediakbar/Capstone-Bangkit-2022-Relasia/blob/master/Machine%20Learning/indorelawan.csv dengan jumlah baris 371, dengan detail kolom:

| Kolom                      | Deskripsi                                   |
| -------------------------- | ------------------------------------------- |
| **nomor**                  | Nomor urut (index)                          |
| **nama**                   | Nama organisasi atau proyek relawan         |
| **keahlian 1**             | Keahlian utama yang dibutuhkan proyek       |
| **keahlian 2**             | Keahlian tambahan                           |
| **lokasi**                 | Lokasi proyek relawan (kota + provinsi)     |

---

## Teknologi & Library

* **Python 3**
* `pandas`, `numpy`, `matplotlib`, `seaborn`
* `scikit-learn` (TF-IDF, KMeans, Regression)
* `TensorFlow / Keras` (Neural Collaborative Filtering)
* `cosine_similarity`, `TfidfVectorizer`, `KMeans`, `LinearRegression`, `RandomForestRegressor`

---
