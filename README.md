![Header](https://github.com/maisasalsabila/algorify/raw/main/Image/Header%20(2).png)

<p align="center">
  <a href="#-tentang">Tentang</a> •
  <a href="#-deskripsi-project">Deskripsi Project</a> •
  <a href="#-demo">Demo</a> •
  <a href="#-struktur-folder">Struktur Folder</a>
</p>

## 📝 Tentang

Berdasarkan data Sakernas 2021–2022, pasar tenaga kerja Indonesia menunjukkan tren pemulihan dengan meningkatnya jumlah angkatan kerja dan TPAK, serta turunnya TPT. Namun, tingginya proporsi pekerja informal dan rentan menandakan belum meratanya kualitas pekerjaan di berbagai provinsi. Proyek ini bertujuan mengelompokkan provinsi berdasarkan indikator ketenagakerjaan seperti TPT, TPAK, persentase pekerja rentan, pekerja sektor informal, dan penduduk usia kerja yang bekerja. Metode klasterisasi **K-Means** dan **K-Medoids** digunakan untuk mendukung segmentasi wilayah dan penyusunan kebijakan ketenagakerjaan yang lebih tepat sasaran.

## 🔍 Deskripsi Project

Proyek ini menggunakan data Sakernas tahun 2021 dan 2022 yang bersumber dari BPS, dengan fokus pada indikator pasar tenaga kerja antar provinsi di Indonesia. Tujuan dari analisis ini adalah untuk mengidentifikasi pola klaster provinsi berdasarkan karakteristik ketenagakerjaan menggunakan pendekatan unsupervised learning.

Metode yang digunakan adalah algoritma **K-Means** dan **K-Medoids**, dengan evaluasi menggunakan metrik **Silhouette Coefficient** dan **Calinski Harabasz** untuk menentukan jumlah klaster optimal.  

Adapun variabel yang dianalisis meliputi:
- Tingkat Partisipasi Angkatan Kerja (TPAK)
- Tingkat Pengangguran Terbuka (TPT)
- Persentase pekerja rentan (pekerja bebas)
- Persentase pekerja sektor informal
- Persentase penduduk usia kerja yang bekerja

Proses analisis dilakukan menggunakan bahasa pemrograman **Python**.

![Image](https://github.com/maisasalsabila/algorify/raw/main/Image/Storyboard.png)

## 📁 Struktur Folder
- `data/` → Dataset dari Sakernas
- `Image/` → Gambar visualisasi, gambar flowchart dan header
- `notebooks/` → Notebook analisis
