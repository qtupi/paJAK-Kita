# paJAK-Kita

**paJAK-Kita** adalah website informasi publik yang dirancang untuk membantu warga memahami penerimaan pajak daerah dan belanja APBD Jakarta dengan bahasa yang lebih mudah dipahami. Proyek ini mengutamakan penyajian informasi yang jelas, sumber data yang terbuka, dan konteks yang dapat diperiksa.

## Fitur

- Halaman informasi tentang penerimaan pajak daerah, belanja APBD, dan istilah perpajakan.
- Pembuat Kartu Insight untuk membuat kartu informasi yang dapat dibagikan.
- Tampilan responsif untuk desktop dan perangkat seluler.
- Identitas visual dengan logo dan maskot Ondi.

## Teknologi

- HTML
- CSS
- JavaScript
- Tidak memerlukan instalasi package melalui npm.

## Menjalankan secara lokal

1. Clone repository ini dan buka folder proyek di VS Code.
2. Buka terminal pada folder proyek.
3. Jalankan server lokal:

   ```powershell
   python -m http.server 3000
   ```

   Jika perintah `python` tidak tersedia di Windows, coba:

   ```powershell
   py -m http.server 3000
   ```

4. Buka [http://localhost:3000](http://localhost:3000) di browser.

## Struktur proyek

- `index.html` — halaman utama.
- `css/` — stylesheet halaman dan Pembuat Kartu Insight.
- `js/` — JavaScript untuk interaksi halaman dan pembuatan kartu.
- `assets/` — logo, maskot, ikon, dan motif visual.

## Catatan data

Periksa sumber, periode, dan metode sebelum menggunakan atau membagikan angka yang ditampilkan. Data penerimaan pajak dan belanja APBD perlu diverifikasi terhadap sumber resmi; jangan menganggap teks contoh atau data yang belum diverifikasi sebagai angka resmi.

## Kontribusi

Kontribusi dan masukan untuk meningkatkan kejelasan informasi, aksesibilitas, serta kualitas sumber data sangat terbuka. Silakan buat issue atau pull request di repository ini.
