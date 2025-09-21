# How to Use Beras Angsa Putih Landing Page

Dokumen ini memberikan petunjuk tentang cara menggunakan dan mengatur proyek landing page Beras Angsa Putih.

## Deployment

### Cara 1: Deploy dengan Mudah (Rekomendasi untuk Pemula)

Jika kamu tidak familiar dengan coding, kamu bisa langsung menggunakan file ZIP yang sudah disediakan:

1. Cari file ZIP yang bernama `beras-angsa-putih-landing-page.zip`
2. Upload file ZIP tersebut ke server hosting kamu
3. Extract file ZIP tersebut di dalam server
4. Pastikan server kamu diatur untuk membuka file `index.html` secara otomatis saat website dibuka

### Cara 2: Deploy untuk Developer

Jika kamu terbiasa dengan tools developer, ikuti langkah-langkah berikut:

1. Buka terminal atau command prompt
2. Masuk ke folder project ini
3. Jalankan perintah `npm run build` untuk membangun versi final website
4. Setelah selesai, unggah semua file yang ada di folder `public` ke server hosting kamu
5. Konfigurasikan server agar membuka `index.html` sebagai halaman utama

### Kebutuhan Website

Agar website ini berjalan dengan baik, kamu memerlukan:

- Server yang bisa menampilkan file statis (seperti Apache, Nginx, atau layanan seperti Netlify/Vercel)
- Koneksi internet agar icon dan font dari luar bisa tampil dengan benar

## Pengembangan

Untuk mengembangkan proyek ini, pastikan kamu telah memenuhi kebutuhan berikut:

- Node.js (versi 14 atau lebih baru)
- npm (biasanya sudah termasuk dalam instalasi Node.js)

Ikuti langkah-langkah berikut:

1. **Unduh proyek**: Klik tombol "Clone" atau unduh file ZIP proyek ini, lalu ekstrak file ZIP tersebut
2. **Buka proyek**: Buka folder proyek yang sudah diekstrak tadi di aplikasi pengedit kode (seperti VS Code, Sublime Text, dll)
3. **Pasang komponen**: Buka terminal atau command prompt di dalam folder proyek, lalu ketik `npm install` dan tekan Enter
4. **Jalankan server uji coba**: Ketik `npm run dev` di terminal untuk menjalankan server pengembangan
5. **Lihat situs**: Buka file [/public/index.html](./public/index.html) di browser kamu atau gunakan live server bila ada di editor kamu
6. **Edit kode**: Ubah-ubah kode sumber sesuai keinginan kamu, lalu simpan perubahan tersebut
7. **Lihat hasil otomatis**: Setiap kali kamu menyimpan perubahan, halaman website akan otomatis memuat ulang di browser

## Bantuan

Jika kamu mengalami masalah atau memiliki pertanyaan, silakan hubungi tim pengembang atau lihat dokumentasi dari lingkungan server lokal kamu.
