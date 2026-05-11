# KasirKu Desktop POS

KasirKu adalah aplikasi kasir desktop berbasis Electron untuk toko, minimarket, grosir, retail, dan UMKM. Aplikasi ini membungkus web app POS dengan PHP portable, wizard konfigurasi database, mode multi komputer kasir, silent print struk, customer display, dan build installer Windows.

## Fitur

- POS cepat dengan barcode scanner, live search produk, multi-tab transaksi, diskon, kembalian real-time, dan cetak struk thermal.
- Manajemen produk, kategori, stok, harga beli, harga jual, harga grosir, supplier, foto produk, lokasi rak, dan minimal stok.
- Metode pembayaran dinamis: tunai, QRIS, transfer bank, dan metode custom.
- Pelanggan/member, loyalty poin, voucher, dan tier pelanggan.
- Promo cerdas: harga grosir, diskon nominal, diskon persen, harga promo, BOGO, dan tebus murah.
- Shift kasir, laci kasir, customer display, audit trail, dan export akuntansi.
- Laporan omzet, HPP, laba, diskon, stok movement, produk terlaris, pelanggan top spender, export CSV/Excel, dan BI JSON feed.
- Security center: user role admin/kasir, PIN supervisor, 2FA admin, backup/restore, rate limit, CSRF, dan enkripsi data sensitif.
- Support banyak komputer kasir dalam satu jaringan toko dengan data transaksi dan stok terpusat.

## Mode Instalasi Aplikasi

KasirKu Launcher mendukung tiga mode:

- `standalone`: satu komputer menjalankan aplikasi dan database lokal.
- `server`: komputer utama membuka server LAN agar bisa diakses komputer kasir lain.
- `client`: komputer kasir lain terhubung ke URL server KasirKu.

Konfigurasi ini bisa dilakukan dari setup wizard aplikasi.
