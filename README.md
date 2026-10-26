# Indonesia Tourism Guide

Website statis bertema destinasi wisata Indonesia. Dibuat dengan HTML dan CSS sebagai latihan halaman beranda, layanan, lokasi, dan profil pembuat.

## Jalankan lokal

Gunakan Python 3 dari root repo:

```powershell
python -m http.server 8080 --bind 127.0.0.1
```

Buka http://127.0.0.1:8080. Hentikan server dengan Ctrl+C. Tidak ada paket npm, proses build, atau database.

## Isi repo

- `index.html`: navigasi, konten wisata, tautan video, peta, dan profil.
- `assets/styles/style.css`: layout serta aturan ukuran layar.
- `assets/script.js`: buka/tutup menu navigasi.
- `assets/images/`: gambar dan logo yang digunakan halaman.
- Folder ikon di `assets/`: SVG yang dirujuk source.

Versi `tugas-akhir-dicoding` dipilih sebagai satu sumber repo. Varian `submission-BDPW-main` mempunyai HTML dan aset yang sama, dengan dua nilai warna CSS berbeda. Kedua varian tidak digabung sebagai dua salinan website.

## Batas penggunaan

Harga dan layanan pada halaman adalah konten latihan. Belum ada reservasi, pembayaran, pengelolaan pesanan, atau integrasi penyedia wisata. Peta Google Maps, video YouTube, serta tautan media sosial memerlukan koneksi internet. Konten profil dan foto berasal dari sumber lokal yang dipertahankan.

## Pemeriksaan

Pemeriksaan source pada 27 Oktober 2026: seluruh rujukan aset HTML/CSS lokal ditemukan dan 1 pemeriksaan syntax JavaScript (berkas atau blok inline) berhasil dengan `node --check`. Tautan anchor ke bagian halaman yang bernama juga ditemukan.

Belum dilakukan uji klik browser, ukuran layar, atau pengambilan screenshot. Hasil pemeriksaan source tidak membuktikan bahwa layanan wisata benar-benar tersedia.

## Asal materi

Nama folder sumber menunjukkan tugas akhir pembelajaran Dicoding. Tidak ditemukan LICENSE yang menetapkan lisensi untuk seluruh proyek; tidak ditambahkan klaim kepemilikan atau lisensi baru atas gambar, ikon, dan materi pihak lain.
