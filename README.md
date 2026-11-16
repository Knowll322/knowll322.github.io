# Alexsander LL Bot

Landing page satu berkas untuk jasa bot Telegram, monitor stok dan harga, serta web scraper data.

> **Jenis proyek:** Proyek pribadi

[![Live Demo](https://img.shields.io/badge/Live%20Demo-000000?style=for-the-badge&logo=github)](https://knowll322.github.io)

## Ringkasan

Repo ini berisi landing page statis yang menjelaskan layanan automation yang ditawarkan: pembuatan bot Telegram custom, pemantau stok dan harga, serta pengambilan data dari website. Halaman memuat tiga kartu layanan beserta harga, alur kerja empat langkah, dan pemanggilan untuk konsultasi lewat Telegram. Seluruh halaman berada dalam satu berkas `index.html` dengan gaya ditulis inline, tanpa berkas terpisah dan tanpa proses build.

## Fitur

- Header dengan badge "Alexsander LL Bot • Python Bot & Automation", judul utama, dan dua tombol aksi: konsultasi lewat Telegram serta tombol menuju daftar harga.
- Baris angka ringkasan: 34 unit test lulus, monitoring 24/7, rata-rata pengerjaan 2 sampai 7 hari, dan 100 persen kode sumber diserahkan.
- Tiga kartu layanan dengan harga: Bot Telegram Custom mulai Rp350.000, Monitor Stok dan Harga mulai Rp500.000, serta Web Scraper Data mulai Rp400.000, masing-masing dengan daftar cakupan pekerjaan.
- Tautan langsung ke repo kode portofolio `telegram-bot-kit` dan `stock-monitor-kit` pada dua kartu layanan pertama.
- Alur kerja empat langkah: konsultasi gratis, kesepakatan scope dan DP 50 persen, pengerjaan dengan laporan progres, serta serah terima kode sumber dan dokumentasi.
- Section penutup dengan tombol Telegram dan WhatsApp, serta footer yang tertaut ke profil GitHub pemilik.
- Tanpa JavaScript: seluruh tampilan dan interaksi dibangun dari HTML dan CSS inline, sudah responsif hingga lebar 640 px.

## Teknologi

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css)

## Cara Menjalankan

Repo ini statis tanpa proses build. Unduh atau clone repo ini, lalu buka `index.html` langsung di browser. Repo ini juga berfungsi sebagai GitHub Pages, sehingga halamannya dapat diakses langsung melalui alamat https://knowll322.github.io.

## Struktur Proyek

```
knowll322.github.io/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

## Catatan

- Repo ini hanya berisi satu berkas `index.html` (sekitar 8,6 KB) dengan CSS inline dan tanpa berkas JavaScript, sehingga perawatannya sederhana.
- Tombol WhatsApp pada bagian penutup masih mengarah ke nomor contoh dan perlu diganti dengan nomor yang aktif sebelum halaman dipublikasikan.
- Nama brand pada halaman ini adalah "Alexsander LL Bot", berbeda dengan nama pemilik pada profil GitHub ("Zain Yarfa' Mubarok"). Repo `telegram-bot-kit` dan `stock-monitor-kit` juga masih memakai brand "Bot Zen", sehingga konsistensi nama brand perlu dirapikan.
- Halaman memakai emoji pada judul kartu layanan, yang akan tampil berbeda antar sistem operasi.
- Angka ringkasan, harga, dan tautan Telegram ditulis langsung di dalam `index.html`, sehingga perubahannya dilakukan manual di berkas tersebut.

## Lisensi

MIT License — lihat [LICENSE](LICENSE)
