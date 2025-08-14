# Ecommerce-Smakensa

**Ecommerce-Smakensa** is a modern and robust e-commerce platform built with **Laravel 12** and **MySQL**, providing a seamless shopping experience for users and an intuitive management system for administrators. The frontend is powered by **Bootstrap** for a clean, responsive design.

## Fitur Unggulan

- **Autentikasi Pengguna:** Sistem registrasi dan login yang aman.
- **Katalog Produk:** Jelajahi berbagai produk dengan deskripsi dan gambar yang mendetail.
- **Keranjang Belanja:** Tambahkan, hapus, dan kelola produk di keranjang belanja Anda.
- **Checkout Aman:** Proses pembayaran yang lancar dan aman.
- **Riwayat Pesanan:** Lihat pesanan sebelumnya dan lacak statusnya.
- **Dashboard Admin:** Kelola produk, pesanan, dan pengguna dari dashboard yang mudah digunakan.

## Teknologi yang Digunakan

- **Backend:**
  - Laravel 12
  - MySQL
- **Frontend:**
  - Bootstrap 5
  - Blade Templates
- **Lainnya:**
  - PHP
  - Composer

## Instalasi

Untuk menjalankan proyek ini di lingkungan lokal Anda, ikuti langkah-langkah berikut.

### Prasyarat

- Web server (seperti XAMPP, WAMP, atau Laragon)
- PHP (versi 8.2 atau lebih tinggi)
- Composer
- MySQL

### Langkah-langkah

1.  **Clone repositori:**
    ```bash
    git clone https://github.com/Vendetta666/Ecommerce-Smakensa.git
    cd Ecommerce-Smakensa
    ```
2.  **Instal dependensi Composer:**
    ```bash
    composer install
    ```
3.  **Salin file `.env`:**
    ```bash
    cp .env.example .env
    ```
4.  **Konfigurasi file `.env`:**
    Buka file `.env` dan sesuaikan pengaturan database Anda:
    ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=nama_database_anda
    DB_USERNAME=user_database_anda
    DB_PASSWORD=password_database_anda
    ```
5.  **Buat database baru** di MySQL dengan nama yang sesuai.
6.  **Jalankan migrasi database:**
    ```bash
    php artisan migrate
    ```
7.  **Jalankan seeder** (opsional, untuk data dummy):
    ```bash
    php artisan db:seed
    ```
8.  **Jalankan server pengembangan Laravel:**
    ```bash
    php artisan serve
    ```

Aplikasi sekarang dapat diakses di `http://127.0.0.1:8000`.

## Penggunaan

- **Jelajahi Produk:** Kunjungi halaman utama untuk melihat semua produk yang tersedia.
- **Buat Akun:** Daftar untuk mulai menambahkan produk ke keranjang belanja.
- **Akses Admin:** Login dengan akun admin untuk mengakses dashboard dan mengelola toko.

## Kontribusi

Kami menerima kontribusi! Jika Anda memiliki saran atau menemukan bug, silakan buka *issue* atau buat *pull request*.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE). Lihat file `LICENSE` untuk detail lebih lanjut.

## Kontak

- **Tautan Proyek:** [https://github.com/Vendetta666/Ecommerce-Smakensa](https://github.com/Vendetta666/Ecommerce-Smakensa)
