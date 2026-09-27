# PRIVAT PASSWORD GENERATOR — PWA

## Isi
- index.html — aplikasi utama
- manifest.webmanifest — konfigurasi PWA
- sw.js — Service Worker / offline cache
- icons/ — ikon aplikasi

## Cara menjalankan
PWA membutuhkan HTTPS atau localhost. Jangan hanya membuka file index.html
dengan double-click jika ingin fitur install PWA.

Cara termudah:
1. Upload seluruh folder ini ke GitHub Pages / hosting HTTPS.
2. Buka URL-nya di Chrome/Edge.
3. Pilih Install app / Tambahkan ke layar utama.

Aplikasi generator password tetap bekerja lokal. Password tidak dikirim ke server.
Randomisasi menggunakan Web Crypto API.
