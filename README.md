# Ruang Ekonomi

Website belajar Pengantar Ekonomi untuk persiapan UTS. Situs statis satu berkas, tanpa framework, dependensi, maupun proses build; materi dan interaksi dapat dibuka langsung dari `index.html` dan tetap berjalan offline.

## Fitur

- Materi Pengantar Ekonomi pertemuan 1–7 dan kuis 8 soal.
- Grafik interaktif permintaan-penawaran, pergeseran kurva, surplus, dan biaya produksi.
- Kalkulator keseimbangan, surplus, elastisitas (nilai awal dan titik tengah), serta biaya.
- Tampilan responsif untuk ponsel dan desktop.

## Menjalankan

Buka `index.html` di browser. Untuk pratinjau melalui server lokal, jalankan `python -m http.server 8000` dari folder ini lalu buka `http://localhost:8000`.

## Deploy

- **Vercel:** impor repository ini sebagai proyek baru dengan framework preset **Other** dan build command kosong; output dapat disajikan langsung dari root.
- **GitHub Pages:** aktifkan Pages dari branch `main`, folder `/(root)`.

Tidak ada variabel lingkungan atau rahasia yang dibutuhkan.
