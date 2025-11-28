# Tugas Besar Analisis Data Statistika
Kelompok 3 – Kelas RA – 2025

Alfaya Rafif Abiyyi (124450006)
Sherena Florencia (124450027)
Andra Ilham Bintang (124450060)
Sekar Dini Widya Putri (124450082)

# 1. Cara Menjalankan Script
1. Pastikan struktur folder repository sudah benar: /data/ /code/ /output/ /poster/ README.md
2. Download dataset pada folder: data/Dataset Tugas Besar ADS 2025.xlsx
3. Download script R utama pada folder: code/codeR_6_RA.R
4. Buka script di RStudio lalu install paket yang dibutuhkan:
5. install.packages(c("readxl","dplyr","ggplot2"))
6. Jalankan script dengan menekan:
Ctrl + Shift + Enter, atau
klik Run All

# 2. Paket R yang Digunakan

library(readxl)
library(dplyr)
library(ggplot2)

# 3. Penjelasan Singkat Dataset
Dataset ini berasal dari hasil survey kepada sejumlah mahasiswa dari berbagai program studi, latar belakang dan angkatan dengan 459 responden. Terdapat informasi mengenai Program Studi, IPK Terakhir, Jenis Kelamin, Tinggi Badan, Berat Badan, Pendididkan Terakhir, Rata-rata Belajar, Apakah Penerima Beasiswa, Asal Daerah (Kota beserta Provinsi), Pekerjaan saat ini (selain kuliah), Akses Internet (yang paling sering digunakan), Keterlibatan Organisai, Uang Saku, Jenis Tempat Tinggal, Jarak rumah dari kampus ITERA, Jenis pekerjaan Ayah, Jenis pekerjaan Ibu, Pendapatan Orangtua, jumlah Anggota Keluarga. perbedaan IPK antara lulusan SMA dan SMK, mahasiswa dari SMA memiliki rata-rata IPK lebih tinggi (3.34) dibanding SMK (3.16) dengan variasi IPK yang lebih besar di kalangan lulusan SMK. Perbedaan perlu di analisis menggunakan metode distribusi sampling memastikan signifikansi statistik dari perbedaan tersebut dan memahami karakteristik distribusi IPK dari kedua kelompok pendidikan.

# 4. Struktur Repository
├── ADS_Kelompok 3_RA.Rmd          # Source code R Markdown untuk laporan
├── ADS_Kelompok 3_RA.pdf          # Laporan lengkap dalam format PDF
├── Dataset Tugas Besar ADS 2025.csv  # Dataset yang digunakan untuk analisis
└── README.md                       # Dokumentasi proyek (file ini)
