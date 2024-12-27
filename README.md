# hapi-web-server

Proyek ini adalah sebuah server web sederhana yang dibangun menggunakan framework Hapi. Proyek ini dibuat sebagai bagian dari pembelajaran saya mengenai Hapi di platform Dicoding.

## Deskripsi

hapi-web-server adalah server yang menyediakan beberapa rute dasar untuk menangani permintaan HTTP. Server ini dapat diakses melalui beberapa endpoint, termasuk homepage, halaman tentang, dan endpoint untuk menyapa pengguna dengan nama.

## Fitur

- Menyediakan rute untuk homepage (`/`)
- Menyediakan rute untuk halaman tentang (`/about`)
- Menyediakan rute untuk menyapa pengguna dengan nama (`/hello/{name?}`)
- Menangani permintaan dengan metode yang tidak diizinkan
- Menangani rute yang tidak ditemukan

## Instalasi

1. Clone repositori ini ke mesin lokal Anda:
   ```bash
   git clone <URL_REPOSITORI>
2. Masuk ke direktori proyek:
   ```bash
   cd hapi-web-server
3. Install depedensi:
   ```bash
   npm install
Aplikasi akan berjalan pada `http://localhost:9000`

## Menjalankan Server

Untuk menjalankan server, gunakan perintah berikut:
   ```bash
   npm start
  ```
Server akan berjalan pada http://localhost:5000 (atau port yang ditentukan dalam file server.js).

## Rute

Berikut adalah rute yang tersedia di server:

- **GET /** - Menampilkan "Homepage"
- **GET /about** - Menampilkan "About page"
- **GET /hello/{name?}** - Menampilkan sapaan kepada pengguna. Jika tidak ada nama yang diberikan, akan menyapa "stranger".
- Rute lainnya akan menampilkan pesan "Halaman tidak ditemukan".
