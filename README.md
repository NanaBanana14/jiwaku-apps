# Jiwa Ku Care

## Overview

**Jiwa Ku Care** adalah platform yang menyediakan dukungan dan sumber daya untuk kesehatan mental. Website ini bertujuan untuk memberikan informasi, alat bantu, dan layanan yang dapat membantu pengguna dalam menjaga kesehatan mental mereka.

## Prerequisites

Pastikan Anda sudah menginstal perangkat lunak berikut sebelum menjalankan proyek ini:

- **NVM (Node Version Manager)**: Untuk mengelola versi Node.js.
- **Node.js dan npm**: Menggunakan NVM untuk menginstal dan mengelola versi Node.js.

## Installation

Ikuti langkah-langkah berikut untuk menginstal dan mengatur proyek ini:

1. **Instal NVM**  
   Instal NVM (Node Version Manager) dengan menjalankan perintah berikut di terminal:

   ```bash
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
   ```

2. **Muat NVM**  
   Setelah instalasi, muat NVM ke sesi terminal Anda:

   ```bash
   source ~/.nvm/nvm.sh
   ```

3. **Instal Node.js**  
   Instal Node.js dengan menggunakan NVM:

   ```bash
   nvm install node
   ```

4. **Aktifkan Node.js**  
   Aktifkan Node.js versi terbaru:

   ```bash
   nvm use node
   ```

5. **Verifikasi Instalasi**  
   Pastikan Node.js dan npm telah terinstal dengan benar:

   ```bash
   node -v
   npm -v
   ```

6. **Instal Dependensi Proyek**  
   Instal semua dependensi yang diperlukan untuk menjalankan proyek:

   ```bash
   npm install
   ```

## Scripts

Berikut adalah daftar skrip yang tersedia dalam file `package.json` dan penjelasannya:

- **`npm run build:prod`**  
  Build proyek dalam mode produksi menggunakan Webpack. File yang dihasilkan akan dioptimalkan untuk kinerja.

  ```bash
  npm run build:prod
  ```

- **`npm run build:dev`**  
  Build proyek dalam mode pengembangan dengan Webpack Dev Server. Mendukung hot-reloading dan debugging.

  ```bash
  npm run build:dev
  ```

- **`npm run prettier:check`**  
  Periksa konsistensi format kode di seluruh proyek sesuai dengan aturan Prettier tanpa mengubah file.

  ```bash
  npm run prettier:check
  ```

- **`npm run prettier:format`**  
  Format seluruh kode dalam proyek sesuai dengan aturan Prettier dan secara otomatis menulis perubahan.

  ```bash
  npm run prettier:format
  ```

- **`npm test`**  
  Placeholder untuk menjalankan tes. Saat ini, skrip ini akan menampilkan pesan kesalahan karena belum ada tes yang diimplementasikan.

  ```bash
  npm test
  ```

## Forking and Cloning the Project

Jika Anda ingin menggunakan atau berkontribusi pada proyek ini, Anda dapat memulainya dengan melakukan **fork** dan **clone** proyek ini.

### Forking the Project

1. Masuk ke halaman GitHub dari proyek **Jiwa Ku Care**.
2. Klik tombol **Fork** di bagian kanan atas halaman untuk membuat salinan repositori di akun GitHub Anda.

### Cloning the Project

Setelah melakukan fork, Anda dapat meng-clone repositori ke mesin lokal Anda untuk mulai bekerja:

1. Buka terminal Anda dan jalankan perintah berikut untuk meng-clone repositori:

   ```bash
   git clone https://github.com/username/Jiwa-Ku-Care.git
   ```

   Gantilah `username` dengan nama pengguna GitHub Anda.

2. Masuk ke direktori proyek:

   ```bash
   cd Jiwa-Ku-Care
   ```

3. Instal semua dependensi yang diperlukan:

   ```bash
   npm install
   ```

4. Mulailah bekerja pada proyek Anda!

## Contributing

Kami menyambut kontribusi dari komunitas! Untuk berkontribusi pada proyek **Jiwa Ku Care**, ikuti langkah-langkah berikut:

1. **Fork repositori** dan buat salinan lokal.
2. **Buat branch baru** untuk fitur atau perbaikan Anda:

   ```bash
   git checkout -b fitur-atau-perbaikan-baru
   ```

3. **Lakukan perubahan** dan pastikan semua pengujian berhasil.
4. **Commit perubahan Anda** dengan pesan yang jelas:

   ```bash
   git commit -m "Menambahkan fitur X atau Memperbaiki masalah Y"
   ```

5. **Push branch Anda** ke repositori forked Anda:

   ```bash
   git push origin fitur-atau-perbaikan-baru
   ```

6. **Buat Pull Request** di GitHub dari branch Anda ke branch `main` proyek ini.

Kami akan meninjau Pull Request Anda dan memberi umpan balik. Terima kasih sudah berkontribusi!
