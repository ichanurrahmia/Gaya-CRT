# DETEKTIF GAYA — IPAS Kelas 4

Paket siap deploy ke Netlify.

## Isi
- `index.html` — halaman utama
- `style.css` — desain, responsif, animasi
- `script.js` — navigasi, game, skor, timer, simulasi, hasil
- `assets/` — folder aset lokal

## Percobaan digital
1. Gaya Otot — slider kekuatan dan animasi mendorong kotak.
2. Gaya Gravitasi — slider ketinggian dan animasi benda jatuh.
3. Gaya Magnet — slider jarak dan simulasi tarik klip/pengujian benda nonmagnet.
4. Gaya Gesek — pilihan permukaan, gaya dorong, dan perbandingan jarak gerak.

## Animasi
- transisi antarhalaman
- tombol dan kartu interaktif
- animasi jawaban benar/salah
- animasi percobaan digital
- efek streak dan suara sederhana
- konfeti saat misi selesai
- elemen dekoratif bergerak

## Menjalankan
Buka `index.html` di browser modern. Tidak membutuhkan server atau database.

## Netlify
Upload seluruh isi folder ini. Pastikan `index.html` berada di root folder yang di-deploy.

Catatan: hasil permainan disimpan menggunakan `localStorage`, sehingga data halaman guru tersimpan pada browser/perangkat yang digunakan. Jika ingin semua perangkat mengirim hasil ke satu database, diperlukan backend atau layanan database.
