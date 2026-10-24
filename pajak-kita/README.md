# paJAK-Kita — Starter Website

Starter ini dibuat sebagai **fondasi frontend awal yang terpisah** dari repository anggota. Tujuannya menguji design system baru dan bukan menggantikan repository tim secara otomatis.

## Teknologi
- HTML
- CSS
- JavaScript vanilla
- Tidak membutuhkan `npm install`

## Cara menjalankan di Windows / VS Code
1. Ekstrak ZIP.
2. Buka folder `paJAK-Kita-starter` di VS Code.
3. Buka Terminal > New Terminal.
4. Jalankan:
   ```powershell
   python -m http.server 3000
   ```
   Jika `python` tidak dikenali, coba `py -m http.server 3000`.
5. Buka `http://localhost:3000`.

Bisa juga membuka `index.html` langsung, tetapi server lokal lebih disarankan.

## Isi
- `index.html`: kerangka beranda dan bagian utama.
- `css/styles.css`: palet, tipografi, spacing, tombol, kartu, motif, dan responsive layout.
- `js/main.js`: menu navigasi mobile.
- `assets/logo-pajakkita-monas-grafik.svg`: logo yang dipilih.
- `assets/maskot-ondi/`: enam pose maskot final (PNG dan SVG).

## Keputusan visual
- Warm Paper `#F8F3E9`
- Clean White `#FFFFFF`
- Betawi Brick Red `#B82025`
- Monas Gold `#E5AD27`
- Betawi Green `#207A5B`
- Editorial Charcoal `#211F1D`
- Font utama: Inter dengan fallback system sans-serif.
- Motif pita di bawah hero diperbarui menjadi deret segitiga merah-emas yang terinspirasi aksen dasar pada logo.
- Pose Ondi menyambut menggunakan SVG agar kedua grup tangan dapat diberi animasi lambaian sederhana.

## Catatan penting
- Angka penerimaan pajak, anggaran, dan realisasi belum dimasukkan karena harus diisi setelah dataset resmi diaudit. Jangan memperlakukan teks contoh sebagai data faktual.
- Tautan navigasi saat ini mengarah ke section kerangka awal. Halaman dashboard dan interaksi data belum diimplementasikan.
- Bandingkan starter ini dengan PRD revisi dan kode repository tim sebelum memutuskan integrasi. Jangan menimpa repository utama tanpa persetujuan tim dan branch kerja.
