# AWAPART 66 PRO v1.2 — Perbaikan tampilan Android

## Perubahan
- Menambahkan aturan CSS responsif untuk dashboard admin pada layar kecil.
- Kartu statistik menggunakan dua kolom dan mencegah teks angka meluber.
- Form tambah unit menggunakan satu kolom pada layar ponsel.
- Tabel reservasi dan pengajuan mitra berubah menjadi baris berbentuk kartu dengan label agar mudah dibaca di HP.
- Mencegah elemen utama melampaui lebar layar.
- Versi aplikasi dinaikkan menjadi 1.2.0 (versionCode 3).

## Batasan yang tetap berlaku
Versi ini masih prototipe lokal. UI belum terhubung ke backend PostgreSQL; booking, bukti transfer, unit, dan status masih menggunakan localStorage. Login admin aman, sinkronisasi multi-perangkat, upload bukti ke server, dan verifikasi pembayaran produksi belum aktif. Jangan gunakan untuk menerima pembayaran/booking live sebelum integrasi dan pengujian backend selesai.

## Build
Unggah isi folder proyek ke repository GitHub, lalu jalankan workflow `Build AWAPART 66 APK`. Unduh artifact APK dari hasil workflow yang berhasil.
