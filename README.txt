RIDER PART — FINALISASI PROTOTYPE
=================================

Isi website:
- index.html      : landing page utama dengan katalog 9 produk
- style.css       : desain responsif premium minimal, merah/hitam/putih
- script.js       : tahun otomatis, navigasi aktif, menu mobile
- produk-1.html sampai produk-9.html : halaman detail produk
- README.txt      : petunjuk penggantian placeholder

MENJALANKAN WEBSITE
1. Ekstrak ZIP.
2. Buka index.html di browser.
3. Internet diperlukan untuk Bootstrap CDN dan Google Fonts.

LINK YANG SUDAH DIATUR
- WhatsApp: https://wa.me/62895412899255
- Toko Shopee: https://shopee.co.id/riderparts_

DATA YANG MASIH PERLU DILENGKAPI
1. Logo Rider Part final (saat ini logo prototype).
2. Foto asli untuk masing-masing dari 9 produk.
3. Nama produk JRP yang sebenarnya untuk setiap kartu.
4. Fungsi, manfaat, spesifikasi, dan kompatibilitas masing-masing produk.
5. Tautan Shopee langsung untuk masing-masing produk (saat ini tombol detail mengarah ke etalase toko).
6. Bila tersedia: harga, stok, garansi, dan informasi pengiriman yang ingin ditampilkan.
7. Konfirmasi bahwa nomor WhatsApp dan link Shopee di atas benar.

CARA GANTI FOTO
Untuk tiap halaman, cari bagian placeholder produk. Ganti elemen ilustrasi placeholder dengan:
<img src="assets/nama-foto.jpg" alt="Nama produk" class="product-photo">
Simpan foto dalam folder assets, lalu tambahkan ke style.css:
.product-photo { width:100%; height:100%; object-fit:contain; padding:24px; }

CATATAN
- Ini website statis tanpa database/backend.
- Logo Rider Part dan simbol Shopee masih berupa prototype visual.
- Nama dan informasi 9 produk belum diisi dengan klaim spesifik karena data produk asli belum diberikan.
- Untuk publikasi, hosting statis seperti GitHub Pages atau Netlify dapat digunakan.
