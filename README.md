# Proyek Pemrograman Mobile — Aplikasi Pertama

## Deskripsi & Tujuan
Aplikasi latihan dasar Flutter untuk pemenuhan tugas praktikum Pemrograman Berbasis Mobile. Proyek ini bertujuan menguji konfigurasi SDK, struktur proyek multiplatform, serta implementasi alur Git workflow dan integrasi layanan perbankan digital (studi kasus SeaBank).

## Pengembang
- **Nama:** Md. Pradiptha Pradnyaswari
- **Akun GitHub:** pradipthapradnyaswari

## Rencana Fitur Utama (Studi Kasus SeaBank)
1. **Pencatatan Bunga Harian:** Simulasi perhitungan suku bunga tabungan harian yang kompetitif dan transparan.
2. **Transfer & E-Wallet Bebas Biaya:** Transaksi transfer antarrekening dan top-up e-wallet tanpa biaya admin.
3. **Quick QRIS Payment:** Opsi pembayaran transaksi kasir cepat untuk nominal kecil guna memangkas antrean.

## Panduan Menjalankan Aplikasi
Jalankan perintah berikut di dalam direktori proyek:

```bash
# Mengunduh seluruh dependensi paket Flutter
flutter pub get

# Menjalankan aplikasi pada perangkat yang terhubung (HP fisik / Emulator)
flutter run
```

## Catatan Setup & Kendala yang Diselesaikan
- Penanganan lisensi Android melalui `flutter doctor --android-licenses`.
- Pemasangan manual dependensi **NDK versi 28.2.13676358** pada Android Studio SDK Tools untuk mengatasi *crash* CLI saat *build* perdana.