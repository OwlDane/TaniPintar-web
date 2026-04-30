# TaniPintar

TaniPintar adalah platform ekosistem digital terintegrasi yang menghubungkan petani, pembeli, dan pemangku kepentingan untuk meningkatkan efisiensi dan keberlanjutan sektor pertanian di Indonesia.

## Fitur Utama

### 1. Visualisasi Data & Pemetaan
* **Interactive Mapping:** Pemetaan lokasi petani menggunakan Leaflet.js dengan fitur filter berbasis komoditas dan status panen.
* **Real-time Statistics:** Dasbor sebaran komoditas untuk memantau ketersediaan stok di berbagai wilayah.

### 2. Manajemen Komoditas & Harga
* **Digital Catalog:** Inventarisasi produk pertanian dengan klasifikasi organik dan non-organik.
* **Dynamic Pricing:** Informasi harga pasar terkini untuk menjaga transparansi transaksi.

### 3. Panel Administrasi & Analitik
* **Data Analytics:** Pengolahan data pertanian untuk menghasilkan *insight* bagi pengambilan keputusan.
* **Content Management:** Pengelolaan modul edukasi dan artikel pertanian modern.

### 4. Learning Center
* **Educational Resources:** Perpustakaan digital dan tutorial video mengenai teknik bertani modern.
* **Discussion Forum:** Media kolaborasi dan pertukaran informasi antar pengguna.

## Tech Stack

### Frontend
* **Core:** React 18 (Hooks & Functional Components)
* **Styling:** Tailwind CSS
* **State Management:** Redux Toolkit & React Query
* **Mapping:** Leaflet.js
* **Routing:** React Router 6

### Backend
* **Runtime:** Node.js
* **Framework:** Express.js
* **Database:** MariaDB (Relational Database)
* **Authentication:** JSON Web Token (JWT)
* **Real-time:** Socket.io

## Struktur Proyek (Frontend)

* `src/components`: Komponen UI yang dapat digunakan kembali.
* `src/pages`: Representasi halaman utama (Home, Map, Dashboard).
* `src/store`: Konfigurasi Redux untuk manajemen state global.
* `src/hooks`: Custom hooks untuk abstraksi logika bisnis.
* `src/services`: Integrasi API dan penanganan data fetching.

## Instalasi dan Pengembangan

### Prasyarat
* Node.js v14.x atau versi terbaru
* MariaDB

### Langkah-langkah
1. **Clone Repositori**
   ```bash
   git clone https://github.com/OwlDane/TaniPintar-web.git
   cd TaniPintar-web
   ```

2. **Instalasi Dependensi**
   ```bash
   npm install
   ```

3. **Menjalankan Mode Pengembangan**
   ```bash
   npm start
   ```

4. **Build untuk Produksi**
   ```bash
   npm run build
   ```

## Lisensi
Proyek ini didistribusikan di bawah **MIT License**.

## Kontak
Untuk pertanyaan teknis maupun kolaborasi, silakan hubungi tim pengembang melalui [tanipintar.com](mailto:tanipintar@gmail.com).

---
