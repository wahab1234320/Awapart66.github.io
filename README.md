# AWAPART 66 — Android project source

Paket aplikasi: `id.co.awapart66.app`  
Versi awal: `1.0.0`

## Kontak perusahaan
- WhatsApp admin: 085785402106
- Email admin: awapartsukses@gmail.com
- Pembayaran demo: BCA 6037152805 a.n. Abdul Wahhab

## Isi
- Android WebView wrapper (Kotlin) untuk aplikasi AWAPART 66.
- UI responsif: katalog apartemen, formulir booking, rekening transfer BCA, pengajuan kerja sama, dashboard admin demo.
- Pemilih file Android untuk memilih gambar bukti transfer.

## Membuat APK
1. Pasang Android Studio versi terbaru dan Android SDK Platform 35.
2. Buka folder `AWAPART66-Android` melalui Android Studio.
3. Tunggu Gradle Sync selesai.
4. Pilih **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. APK debug akan berada di `app/build/outputs/apk/debug/app-debug.apk`.
6. Untuk distribusi, buat signing key perusahaan melalui **Build → Generate Signed Bundle / APK**. Simpan keystore dan password secara aman.

## Status dan batasan penting
Ini adalah paket sumber Android, bukan APK yang sudah ditandatangani. Lingkungan kerja ini tidak memiliki Android SDK/Gradle, sehingga APK biner tidak dapat dibangun atau diuji di sini.

Aplikasi web di dalamnya masih prototipe lokal. Booking, mitra, dan status demo tersimpan di localStorage perangkat. Form bukti transfer hanya mencatat nama file secara lokal, belum mengunggah gambar ke server. Dashboard admin belum memiliki autentikasi server. Jangan gunakan untuk operasional atau menyatakan pembayaran lunas sebelum backend, autentikasi, database online, upload bukti, dan pemeriksaan mutasi BCA benar-benar diimplementasikan.
