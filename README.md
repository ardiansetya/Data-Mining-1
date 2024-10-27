# Data Mining Project: Patient Data Preprocessing

Project ini dirancang untuk melakukan preprocessing pada data pasien yang berisi informasi klinis dan sosial ekonomi. Preprocessing adalah langkah penting sebelum analisis atau penerapan model machine learning untuk memastikan data siap dan dalam format yang sesuai.

## Tabel Isi

- [Deskripsi Proyek](#deskripsi-proyek)
- [Struktur Dataset](#struktur-dataset)
- [Instalasi](#instalasi)
- [Langkah-Langkah Preprocessing](#langkah-langkah-preprocessing)
  - [1. Mengimpor Pustaka](#1-mengimpor-pustaka)
  - [2. Memuat Dataset](#2-memuat-dataset)
  - [3. Melihat Data Awal](#3-melihat-data-awal)
  - [4. Menghapus Kolom Tidak Dibutuhkan](#4-menghapus-kolom-tidak-dibutuhkan)
  - [5. Menangani Nilai Kosong](#5-menangani-nilai-kosong)
  - [6. Mengubah Tipe Data](#6-mengubah-tipe-data)
  - [7. Transformasi Nama Kolom](#7-transformasi-nama-kolom)
  - [8. Visualisasi Awal](#8-visualisasi-awal)
- [Visualisasi Data](#visualisasi-data)
- [Contributing](#contributing)
- [License](#license)

---

## Deskripsi Proyek

Data mining pada data pasien ini bertujuan untuk mengeksplorasi dan memahami fitur-fitur seperti usia, paritas, riwayat hipertensi, obesitas, dan status PE/non-PE pasien. Dataset ini memerlukan beberapa tahap preprocessing untuk memastikan kualitas data, konsistensi, dan kelengkapan sebelum dapat dianalisis lebih lanjut atau digunakan dalam model prediktif.

## Struktur Dataset

Dataset terdiri dari beberapa kolom, termasuk:

- **USIA**: Usia pasien dalam tahun
- **PARITAS**: Jumlah kelahiran yang dimiliki pasien
- **RIWAYAT_HIPERTENSI**: Status hipertensi (Ya/Tidak)
- **OBESITAS**: Status obesitas (Ya/Tidak)
- **PE**: Status PE (Pre-Eklampsia atau Non-PE)
- **Kolom-kolom lainnya** yang berisi informasi tambahan

## Instalasi

1. Pastikan Python 3.6+ sudah terinstal di sistem Anda.
2. Instal pustaka yang diperlukan menggunakan:
   ```bash
   pip install -r requirements.txt
