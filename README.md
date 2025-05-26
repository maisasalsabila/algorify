![Header](https://github.com/maisasalsabila/algorify/raw/main/Image/Header%20(2).png)

<p align="center">
  <a href="#-tentang">Tentang</a> •
  <a href="#-deskripsi-project">Deskripsi Project</a> •
  <a href="#-diagram-alir">Diagram Alir</a> •
  <a href="#-demo">Demo</a> •
  <a href="#-insight">Insight</a> •
  <a href="#-struktur-folder">Struktur Folder</a> •
  <a href="#-meet-our-team">Meet Our Team</a> 
</p>

## 📝 Tentang
<div align="justify">
Berdasarkan data Sakernas 2021–2022, pasar tenaga kerja Indonesia menunjukkan tren pemulihan dengan meningkatnya jumlah angkatan kerja dan TPAK, serta turunnya TPT. Namun, tingginya proporsi pekerja informal dan rentan menandakan belum meratanya kualitas pekerjaan di berbagai provinsi. Proyek ini bertujuan mengelompokkan provinsi berdasarkan indikator ketenagakerjaan seperti TPT, TPAK, persentase pekerja rentan, pekerja sektor informal, dan penduduk usia kerja yang bekerja. Metode klasterisasi K-Means dan K-Medoids digunakan untuk mendukung segmentasi wilayah dan penyusunan kebijakan ketenagakerjaan yang lebih tepat sasaran.
</div>

## 🔍 Deskripsi Project
<div align="justify">
Proyek ini menggunakan data Sakernas tahun 2021 dan 2022 yang bersumber dari BPS, dengan fokus pada indikator pasar tenaga kerja antar provinsi di Indonesia. Tujuan dari analisis ini adalah untuk mengidentifikasi pola klaster provinsi berdasarkan karakteristik ketenagakerjaan menggunakan pendekatan unsupervised learning.

Metode yang digunakan adalah algoritma **K-Means** dan **K-Medoids**, dengan evaluasi menggunakan metrik **Silhouette Coefficient** dan **Calinski Harabasz** untuk menentukan jumlah klaster optimal.  

Adapun variabel yang dianalisis meliputi:
- Tingkat Partisipasi Angkatan Kerja (TPAK)
- Tingkat Pengangguran Terbuka (TPT)
- Persentase pekerja rentan (pekerja bebas)
- Persentase pekerja sektor informal
- Persentase penduduk usia kerja yang bekerja

</div>

## 🔄 Diagram Alir 
Proses analisis dilakukan menggunakan bahasa pemrograman **Python**.
<div align="center">
<img src="https://github.com/maisasalsabila/algorify/raw/main/Image/fflowchart.png" alt="Image" width="600"/>
</div>

## 🚀 Demo

Peta Sebaran 2021
![Image](https://github.com/maisasalsabila/algorify/raw/main/Image/peta_2021.PNG)

Peta Sebaran 2022
![Image](https://github.com/maisasalsabila/algorify/raw/main/Image/peta_2022.PNG)

seperti yang dilihat tidak ada perubahan anggota klaster pada dua tahun berturut-turut. Hal ini tidak mengartikan bahwa tidak ada perubahan nilai pada tiap indikator, melainkan ada perubahan tetapi tidak terlalu signifikan yang dapat dilihat pada nilai rata-ratanya di bawah ini.

Karakteristik Rata-Rata 2021
![Image](https://github.com/maisasalsabila/algorify/raw/main/Image/karakteristik_2021.PNG)

Karakteristik Rata-Rata 2022
![Image](https://github.com/maisasalsabila/algorify/raw/main/Image/karakteristik_2022.PNG)

## :bulb: Insight
*Klaster 0: "Provinsi Ketenagakerjaan Unggul" (6 Provinsi)**
Kelompok provinsi ini menunjukkan kondisi pasar kerja yang sangat kuat. Provinsi-provinsi dalam klaster ini memiliki tingkat pengangguran yang paling rendah dan partisipasi angkatan kerja yang tinggi. Mereka juga memiliki proporsi pekerja rentan dan informal yang minim. Selain itu, penduduk usia produktif di provinsi ini cenderung aktif bekerja, menjadikannya sebagai benchmark ideal dalam sektor ketenagakerjaan di Indonesia.

**Klaster 1: "Provinsi Ketenagakerjaan Moderat" (20 Provinsi)**
Klaster ini merepresentasikan kondisi ketenagakerjaan yang lebih seimbang atau rata-rata di Indonesia. Provinsi-provinsi di klaster ini memiliki indikator yang berada di tengah spektrum, dengan kekuatan dan tantangan yang seimbang. Meskipun berada di posisi moderat, kelompok ini memiliki potensi besar untuk berkembang lebih lanjut dengan adanya kebijakan dan perbaikan yang tepat.

**Klaster 2: "Provinsi Prioritas Intervensi Ketenagakerjaan" (8 Provinsi)**
Kelompok provinsi ini menghadapi tantangan ketenagakerjaan yang cukup serius. Mereka memiliki tingkat pengangguran yang tinggi, partisipasi angkatan kerja yang rendah, serta dominasi pekerja rentan dan sektor informal. Selain itu, proporsi penduduk usia produktif yang aktif bekerja juga sangat rendah. Oleh karena itu, provinsi dalam klaster ini membutuhkan perhatian dan intervensi kebijakan yang lebih intensif untuk mengatasi masalah ketenagakerjaan yang mereka hadapi.

## 📁 Struktur Folder
- `data/` → Dataset dari Sakernas
- `Image/` → Gambar visualisasi, gambar flowchart dan header
- `notebooks/` → Notebook analisis

## 👩‍👩‍👧‍👧 Meet Our Team

🌝 <a href="https://github.com/Carlyaagmis">Carlya Agmis Aimandiga</a><br>
🐝 <a href="https://github.com/maisasalsabila">Maisa Salsabila</a><br>
🦢 <a href="https://github.com/Naufaliaa">Naufalia Alfiryal</a><br>
🐢 <a href="https://github.com/Reyuliandespa">Reyuli Andespa</a>


