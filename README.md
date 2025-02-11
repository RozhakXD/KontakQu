# MyContact - Pengelola Kontak Sederhana dalam C++
![MyContact Logo](https://github.com/user-attachments/assets/03f8bb2f-f164-442c-be5e-48d7fc83a09f)

Sebuah aplikasi pengelolaan kontak berbasis CLI (Command Line Interface) yang dibangun menggunakan bahasa C++. Program ini memanfaatkan struktur data **Linked List**, **Stack**, dan **Queue** untuk menyimpan, mengelola, dan mencari data kontak secara efisien.

## 📋 Deskripsi
MyContact adalah program sederhana untuk menyimpan dan mengelola informasi kontak seperti nama, nomor telepon, dan kategori. Dibuat dengan pendekatan modular, program ini menawarkan fitur pencarian berdasarkan nama, nomor, atau kategori, serta kemampuan menampilkan seluruh kontak yang tersimpan. Cocok untuk pembelajaran struktur data dan operasi dasar CRUD (Create, Read, Update*).

> Catatan: *Fitur _update_ dan _delete_ belum tersedia dalam versi ini.

## 🚀 Fitur Utama
![Fitur](https://github.com/RozhakXD/Kontak-Ku/assets/65714340/1d113e54-5935-49f1-9e0d-9fab3cbffe5e)

## 🧠 Struktur Data & Algoritma
Aplikasi ini menggunakan struktur data **Linked List** untuk menyimpan data kontak utama dengan operasi penambahan dan pencarian. Selain itu, **Stack** digunakan untuk pencarian berdasarkan nomor (LIFO: Last-In-First-Out) dan **Queue** untuk pencarian berdasarkan kategori (FIFO: First-In-First-Out). Pengurutan kontak berdasarkan nama dilakukan dengan algoritma _Bubble Sort_.

## 📌 Catatan
- Kompatibel dengan sistem operasi Windows dan Linux (sesuaikan perintah `system("clear")`/`system("cls")` di kode).
- Data disimpan secara _volatile_ (hilang setelah program ditutup).
- Batas maksimal penyimpanan: **100 kontak** untuk Stack dan Queue.

## 📜 Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).
