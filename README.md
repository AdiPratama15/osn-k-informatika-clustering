# OSN-K Informatika Clustering

Sebuah website statis untuk melakukan clustering tematik terhadap soal-soal OSN-K Informatika Indonesia tahun 2021–2025, lengkap dengan analisis persentase, tingkat kesulitan, dan tautan langsung ke PDF sumber.

## Fitur

- Clustering per nomor soal
- Label tema utama dan tema sekunder
- Estimasi tingkat kesulitan
- Statistik persentase per cluster
- Filter berdasarkan tahun, cluster, dan urutan
- Tautan langsung ke PDF soal sumber
- Tampilan web statis yang siap di-deploy ke GitHub Pages

## Sumber Data

Data soal diambil dari PDF resmi OSN-K / KSN-K Informatika yang tersedia di arsip Toki:

- OSNK 2025
- OSNK 2024
- OSNK 2023
- OSNK 2022
- KSNK 2021

## Catatan Metodologi

Clustering dibuat dengan pendekatan **manual semantic clustering / thematic coding** berdasarkan:
- struktur soal,
- tema algoritmik dominan,
- paradigma pemecahan masalah,
- dan pola kesulitan yang tampak dari isi soal.

Hasil ini bersifat analitis dan edukatif, bukan klasifikasi resmi penyelenggara.

## Cara Menjalankan

Cukup buka file HTML utama di browser, atau deploy repository ini ke GitHub Pages.

## Struktur Proyek

- `index.html` — aplikasi utama
- `README.md` — dokumentasi
- `LICENSE` — lisensi proyek
- `.gitignore` — file/folder yang diabaikan Git

## Lisensi

Lihat file `LICENSE` untuk detail lisensi proyek.

## Kontribusi

Kontribusi sangat terbuka, terutama untuk:
- perbaikan label cluster,
- penyempurnaan metodologi,
- koreksi tautan sumber,
- dan peningkatan UI/UX.

## Disclaimer

Soal-soal asli tetap menjadi milik pemegang hak cipta masing-masing. Repository ini hanya menyediakan analisis, pengelompokan tematik, dan antarmuka visual untuk keperluan pembelajaran.
