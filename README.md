# Taluh Mesiu 🥚

Website resmi **Taluh Mesiu**, penyedia telur ayam segar berkualitas tinggi yang berbasis di Ungasan, Kuta Selatan, Bali.

Nama **Taluh Mesiu** diambil dari bahasa Bali: *Taluh* (Telur) & *Mesiu* (Seribu), melambangkan komitmen kami untuk memberikan nilai tambah sebesar Rp1.000 bagi peternak lokal dari setiap butir telur yang terjual.

## Fitur Utama

1. **Navigasi Terintegrasi & Konsisten:** Menu navigasi (Beranda, Produk, Tentang, Kontak) yang sinkron di seluruh halaman untuk kemudahan akses pengguna.
2. **Form Pemesanan Cepat (`contact_page.html`):**
   - **Live Price Preview:** Pembaruan harga otomatis secara instan berdasarkan jumlah krat telur yang dipilih.
   - **Pilihan Lokasi Fleksibel (Tab-based):**
     - *Share Lokasi GPS:* Mendapatkan lokasi presisi via Geolocation API peramban dengan pratinjau peta Google Maps interaktif.
     - *Ketik Alamat Manual:* Input teks alamat manual disertai input opsional tautan Google Maps.
   - **WhatsApp Message Integration:** Menyusun format pesan WhatsApp pemesanan secara otomatis dari input form.
3. **Optimasi Kinerja & SEO:** Kecepatan muat cepat dengan aset WebP terkompresi dan skema data terstruktur JSON-LD.

## Struktur Folder

- `index.html` - Halaman beranda utama (dilengkapi section Tentang Kami yang terintegrasi).
- `public/template/`
  - `contact_page.html` - Template halaman kontak dan form pemesanan cepat.
  - `index_page.html` - Sub-halaman standalone tentang profil kami.
- `public/static/`
  - `css/style.css` - Desain sistem global, variabel warna, grid, animasi, dan responsivitas.
  - `js/main.js` - Logika interaktivitas global (animasi gulir, navigasi responsif, dll).
- `public/webp/` - Aset gambar yang telah dioptimasi dengan format gambar WebP.

## Cara Menjalankan Secara Lokal

Cukup buka file `index.html` langsung di peramban web pilihan Anda, atau sajikan menggunakan server lokal (seperti Live Server di VS Code).
