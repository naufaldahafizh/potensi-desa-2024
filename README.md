# Analisis Potensi Desa di Indonesia: Dari Data Mentah Menjadi Visualisasi Peta
Repositori ini berisi alur kerja lengkap untuk menganalisis dan memvisualisasikan data Potensi Desa di Indonesia. Proyek ini mengolah data mentah dari sumber publik, termasuk data geospasial, menjadi visualisasi yang menggambarkan karakteristik desa di berbagai tingkat daerah.

## Latar Belakang: Apa Itu Potensi Desa?
Potensi Desa adalah sumber daya seperti alam, manusia, dan kelembagaan yang dimiliki oleh sebuah desa dan dapat dimanfaatkan untuk meningkatkan kesejahteraan warganya. Memahami potensi ini adalah kunci untuk merancang program pembangunan yang efektif dan tepat sasaran. Proyek ini bertujuan untuk mengidentifikasi potensi tersebut melalui pencarian insight dalam hal kesejahteraan, infrastruktur, dan ekonomi.

## Tujuan
Menggabungkan data tabular dari berbagai sumber dan mengolah data geospasial untuk visualisasi peta. Peta geospasial dibuat pada Tableau Public yang menampilkan sebaran desa, kategori BUMDes, infrastruktur, dan Indeks Desa Membangun (IDM) di Indonesia.

## Sumber Data
Proyek ini menggunakan data dari tiga sumber:
- Badan Pusat Statistik (BPS): Data karakteristik desa
- Portal Data Kementerian Desa (Kemendesa): Data BUMDes
- Badan Informasi Geospasial: Data Batas Wilayah Desa

## Metodologi
Proyek ini dibagi menjadi tiga tahap utama: Pengumpulan Data, Analisis Data, dan Visualisasi Peta.

1. Pengumpulan Data
Data diambil dari ketiga sumber untuk data yang berkaitan dengan potensi desa. Data mentah disimpan dalam folder /data

2. Analisis Data
Pengolahan Data dengan Python untuk membersihkan data, menggabungkan data, dan mengeksplor serta menganalisis data untuk dijadikan visualisasi peta. Hasil pembersihan data disimpan dalam folder /data/processed

3. Visualisasi Peta dengan Tableau Public
Data yang sudah bersih dan teragregasi kemudian divisualisasikan di Tableau untuk menghasilkan peta dengan data lokasi yang sudah diolah menjadi format geojson. Data yang siap divisualisasikan di Tableau dibuat dalam format excel