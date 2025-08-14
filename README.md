E-Commerce App
Selamat datang di repositori proyek website e-commerce! Proyek ini dibangun menggunakan Laravel 12 dan bertujuan untuk menyediakan platform belanja online yang modern dan fungsional.

<!-- Fitur Utama
Manajemen Produk: Tambah, edit, hapus, dan lihat detail produk.

Kategori Produk: Mengorganisir produk ke dalam kategori yang berbeda.

Keranjang Belanja: Pengguna dapat menambah, menghapus, atau mengubah kuantitas produk di keranjang.

Proses Checkout: Alur checkout yang sederhana dan aman.

Manajemen Pesanan: Halaman untuk melihat riwayat pesanan.

Autentikasi Pengguna: Sistem login dan registrasi yang aman.

Teknologi yang Digunakan -->

### Teknologi yang Digunakan

Backend: Laravel 12

Frontend:

Bootstrap 5 (untuk tampilan responsif)

Vite (sebagai bundler frontend)

Database: MySQL (atau sesuai konfigurasi Anda)

Dependency Manager: Composer (PHP) dan NPM (JavaScript)

Persyaratan Sistem
Pastikan Anda telah menginstal software berikut di komputer Anda:

PHP 8.2 atau lebih tinggi

Composer

Node.js & NPM

MySql

Git

Panduan Instalasi
Ikuti langkah-langkah di bawah ini untuk menjalankan proyek di lingkungan lokal Anda.

1. Kloning Repositori
Buka terminal dan jalankan perintah berikut untuk mengkloning proyek:

git clone https://github.com/Vendetta666/Ecommerce-Smakensa.git
cd Ecommerce-Smakensa

2. Instal Dependensi
Instal dependensi PHP menggunakan Composer dan dependensi JavaScript menggunakan NPM:

composer install
npm install

3. Konfigurasi Lingkungan (.env)
Salin file .env.example ke .env dan konfigurasikan detail database Anda.

cp .env.example .env

Setelah itu, buka file .env dan sesuaikan variabel berikut:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nama_database_anda
DB_USERNAME=root
DB_PASSWORD=

4. Buat Kunci Aplikasi & Jalankan Migrasi
Jalankan perintah untuk membuat kunci enkripsi aplikasi dan melakukan migrasi database.

php artisan key:generate
php artisan migrate

5. Jalankan Server Lokal
Jalankan server Laravel dan bundler Vite secara bersamaan.

# Buka terminal baru dan jalankan server
php artisan serve

# Buka terminal lain dan jalankan Vite
npm run dev

Sekarang, Anda bisa mengakses aplikasi di http://127.0.0.1:8000.

Kontribusi
Kami menerima kontribusi dari siapa pun! Jika Anda ingin berkontribusi, silakan ikuti langkah-langkah berikut:

Fork repositori ini.

Buat branch baru (git checkout -b fitur-baru).

Lakukan perubahan dan commit (git commit -m 'Menambahkan fitur baru').

Push ke branch Anda (git push origin fitur-baru).

Buka Pull Request baru.

Lisensi
Proyek ini dirilis di bawah lisensi MIT.

Kontak
Jika Anda memiliki pertanyaan, hubungi tim pengembang di email@example.com.