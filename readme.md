# 🌍 Advanced Shapefile Viewer

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 📋 Deskripsi

Advanced Shapefile Viewer adalah aplikasi web interaktif yang memungkinkan Anda untuk mengunggah, memvisualisasikan, dan melakukan analisis spasial pada file shapefile dengan mudah dan cepat. Aplikasi ini dibangun menggunakan Leaflet dan Turf.js untuk memberikan pengalaman GIS yang profesional langsung di browser Anda.

![Screenshot Aplikasi](screenshot.png)

## ✨ Fitur Utama

### 📤 Upload dan Visualisasi
- Mendukung file ZIP berisi shapefile (.shp, .shx, .dbf, .prj)
- Mendukung file individual shapefile dengan komponen pendukungnya
- Visualisasi file shapefile berukuran besar (hingga puluhan GB)
- Menampilkan peta dengan latar belakang OpenStreetMap

### 📊 Informasi dan Analisis
- Tampilan detail properties dari setiap feature
- Statistik komprehensif tentang dataset
- Navigasi mudah dengan dropdown selector antar fitur
- Informasi tipe data untuk setiap property

### 🛠️ Geoprocessing Tools (seperti ArcGIS)
- **Clip** - Memotong geometri menggunakan layer lain
- **Intersect** - Menemukan area yang bersinggungan
- **Union** - Menggabungkan geometri dari dua layer
- **Erase** - Menghapus bagian yang overlap
- **Dissolve** - Menggabungkan features berdasarkan atribut
- **Buffer** - Membuat zona buffer dengan jarak tertentu
- **Merge** - Menggabungkan multiple layer
- **Spatial Join** - Menggabungkan atribut berdasarkan relasi spasial
- **Split** - Membagi fitur berdasarkan geometri lain
- **Select by Location** - Memilih fitur berdasarkan posisi
- **Update** - Memperbarui geometri atau atribut
- **Identity** - Menggabungkan fitur sambil mempertahankan batas

### 🎯 Interaksi dengan Peta
- Mode seleksi aktif untuk memilih fitur di peta
- Toggle antara mode seleksi dan pan
- Zoom ke fitur yang dipilih
- Export fitur yang dipilih

## 🚀 Cara Menggunakan

1. **Upload File**
   - Klik tombol "Pilih File" atau drag & drop file shapefile Anda
   - Aplikasi mendukung format ZIP berisi shapefile atau file .shp dengan komponen pendukungnya

2. **Visualisasi dan Eksplorasi**
   - Lihat shapefile Anda ditampilkan di peta
   - Jelajahi properties dari setiap fitur
   - Lihat statistik tentang dataset Anda

3. **Analisis Spasial**
   - Pilih fitur pada peta dengan mengklik
   - Pilih tool geoprocessing yang ingin digunakan
   - Ikuti instruksi untuk melakukan operasi geoprocessing
   - Lihat hasil operasi ditampilkan di peta

## 💻 Teknologi yang Digunakan

- **Leaflet.js** - Library peta JavaScript open-source
- **Turf.js** - Library analisis geospasial JavaScript
- **HTML5/CSS3** - Struktur dan tampilan aplikasi
- **JavaScript** - Logika aplikasi dan interaktivitas

## 📝 Kontribusi

Kontribusi selalu diterima dengan baik! Jika Anda ingin berkontribusi:

1. Fork repositori ini
2. Buat branch fitur baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan Anda (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buka Pull Request

## 📄 Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.

## 📞 Kontak

Nama Anda - [@twitter_handle](https://twitter.com/twitter_handle) - email@example.com

Link Proyek: [https://github.com/username/advanced-shapefile-viewer](https://github.com/username/advanced-shapefile-viewer)
