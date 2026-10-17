# J-DET — Jambi Digital Economic Twin

**Prototipe sistem pendukung keputusan spasial untuk mitigasi kebakaran hutan dan lahan (karhutla), perlindungan ekonomi, dan ketahanan pangan di Provinsi Jambi.**

🌐 **Website demo:** https://faiq210.github.io/J-DET-Jambi/

## Tentang J-DET

J-DET merupakan prototipe yang dirancang untuk membantu pengguna mengeksplorasi hubungan antara riwayat deteksi hotspot, informasi risiko karhutla, paparan ekonomi, dan alternatif kebijakan mitigasi di Provinsi Jambi.

J-DET bertujuan mendukung analisis wilayah dan membantu membandingkan pilihan intervensi. Prototipe ini belum merupakan sistem prediksi kebakaran yang tervalidasi atau sistem operasional pemerintah.

## Fitur Utama

### 1. Peta Risiko
Menampilkan analisis wilayah kabupaten/kota dengan skor risiko simulasi untuk membantu mengeksplorasi prioritas mitigasi.

### 2. Analisis Hotspot 2025
Mengolah catatan deteksi satelit tahun 2025 untuk menampilkan jumlah deteksi per wilayah, peringkat, indeks relatif, dan distribusi bulanan.

### 3. Analisis Dampak Ekonomi
Memungkinkan pengguna mengubah pilihan wilayah, sektor ekonomi, dan parameter risiko untuk mengeksplorasi perubahan indeks paparan produksi serta pendapatan dalam simulasi.

### 4. Simulasi Kebijakan
Membandingkan tiga alternatif intervensi:
- Patroli dan pencegahan dini.
- Pemulihan lahan dan sekat kanal.
- Perlindungan zona ekonomi kritis.

Perbandingan ini menggunakan asumsi demonstrasi dan tidak membuktikan efektivitas aktual kebijakan.

## Teknologi dan Berkas Proyek

- **HTML, CSS, dan JavaScript:** antarmuka dan interaksi website.
- **CSV:** data deteksi hotspot historis tahun 2025.
- **GeoJSON:** data spasial wilayah jika digunakan oleh versi website.
- **GitHub Pages:** publikasi website statis.

Berkas utama:
- `index.html`
- `JDET_hotspot_Jambi_2025.csv`
- `jambi.geojson`

## Sumber Data

Data hotspot diolah dari berkas CSV proyek. Keterangan sumber asli, produk satelit, periode pengamatan, tanggal unduh, dan metode pengolahan perlu dicantumkan berdasarkan metadata dataset yang digunakan.

## Batasan dan Validasi

J-DET masih merupakan prototipe demonstrasi. Skor risiko, indeks dampak ekonomi, serta besaran perubahan dalam simulasi kebijakan belum tervalidasi sebagai hasil pengukuran aktual.

Deteksi satelit tidak selalu sama dengan kejadian kebakaran yang telah dikonfirmasi. Jumlah deteksi saja juga tidak cukup untuk menentukan tingkat risiko atau besarnya kerugian ekonomi.

Pengembangan lebih lanjut membutuhkan integrasi data yang relevan, pemeriksaan kualitas data, pengujian terhadap catatan kejadian kebakaran, dan validasi hasil menggunakan data ekonomi serta kondisi lapangan.

## Status Proyek

**Status:** Prototipe demonstrasi.

Pengembangan berikutnya berfokus pada penguatan integrasi data, validasi analisis, evaluasi skenario kebijakan, dan pengujian sebelum penggunaan operasional.
