# ✨ Twitterdl

[![HTML](https://img.shields.io/badge/language-HTML-blue.svg)](https://www.w3.org/html/)
[![NPM](https://img.shields.io/badge/package_manager-NPM-green.svg)](https://www.npmjs.com/)


> A simple Twitter downloader built with HTML and Node-fetch.

## ✨ Fitur Utama

* **Pengunduhan Tweet:** Aplikasi ini memungkinkan pengguna mengunduh tweet.  Fungsionalitas ini dicapai melalui integrasi dengan Node-fetch untuk mengambil data tweet dari Twitter.


## 🛠️ Tumpukan Teknologi

| Kategori         | Teknologi      | Catatan                                     |
|-----------------|-----------------|---------------------------------------------|
| Bahasa           | HTML            | Bahasa markup utama untuk antarmuka pengguna. |
| Manajer Paket    | NPM             | Digunakan untuk manajemen dependensi.           |
| Library          | node-fetch      | Untuk melakukan permintaan HTTP ke Twitter.  |


## 🏛️ Tinjauan Arsitektur

Aplikasi ini merupakan aplikasi halaman tunggal sederhana yang dibangun dengan HTML.  Ia bergantung pada library `node-fetch` untuk melakukan permintaan HTTP untuk mengunduh tweet.  Arsitektur aplikasi relatif sederhana, tanpa penggunaan framework front-end atau backend yang kompleks.

## 🚀 Memulai

Berikut adalah langkah-langkah untuk menjalankan aplikasi ini secara lokal:

1. **Kloning Repositori:**
   ```bash
   git clone https://github.com/Fiisya/twitterdl.git
   cd twitterdl
   ```

2. **Instal Dependensi:**
   ```bash
   npm install
   ```

3. **Jalankan Server Pengembangan:**
   ```bash
   npm run dev
   ```

   *(Catatan:  `npm run dev` diasumsikan berdasarkan konvensi umum dan analisis terbatas dari `package.json`.  Perintah aktual mungkin berbeda tergantung implementasi build dari aplikasi.)*


## 📂 Struktur File

```
/
├── index.html
└── package.json
```

* **/index.html:** File HTML utama yang berisi antarmuka pengguna aplikasi.
* **/package.json:** File yang mendefinisikan dependensi proyek dan skrip.

