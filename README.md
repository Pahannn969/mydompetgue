# My Dompet — PWA iPhone

## Isi
- `index.html`: aplikasi tabungan
- `manifest.json`: konfigurasi instalasi PWA
- `sw.js`: cache dasar agar app dapat dibuka kembali saat offline
- `icon-192.png` dan `icon-512.png`: ikon aplikasi

## Deploy lewat GitHub dan Vercel
1. Buat repository GitHub, misalnya `tabungan-met`.
2. Upload semua file di folder ini ke root repository (bukan ke dalam subfolder lain).
3. Import repository tersebut di Vercel dan deploy sebagai static site. Build command dan output directory biasanya dibiarkan kosong/default.
4. Buka URL HTTPS Vercel di Safari pada iPhone.
5. Tekan tombol Share (kotak dengan panah ke atas), pilih `Add to Home Screen` / `Tambahkan ke Layar Utama`.
6. Jika pilihan `Open as Web App` muncul, aktifkan, lalu tekan Add.

## Catatan data
Data tabungan tersimpan di localStorage browser/aplikasi pada perangkat ini. Data tidak otomatis tersinkron dengan perangkat lain. Jangan hapus data situs atau browser sebelum mengekspor riwayat CSV sebagai cadangan. Ekspor CSV tersedia di bagian Riwayat tabungan.

Ini adalah aplikasi pencatatan, bukan rekening bank dan tidak memindahkan uang sungguhan.
