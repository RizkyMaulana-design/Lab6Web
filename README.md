
---

# **Portfolio Website – Praktikum 6 (Twitter Bootstrap)**

**Nama:** Rizky Maulana

**NIM:** 312410404

**Program Studi:** Teknik Informatika

**Mata Kuliah:** Pemrograman Web

**Praktikum:** 6 – Twitter Bootstrap

---

## **Deskripsi Proyek**

Proyek ini merupakan tugas dari Praktikum 6 yang bertujuan untuk membuat **halaman Portfolio Sederhana** menggunakan framework **Bootstrap 5**.
Pada tugas ini, saya membuat satu halaman web bernama **portfolio.html** yang menampilkan **profil pribadi, foto, deskripsi diri, dan contoh proyek** yang pernah saya buat.

Website ini dirancang dengan **tema gelap (dark theme)** agar terlihat modern dan elegan.
Struktur layout mengikuti **sistem grid Bootstrap** tanpa menggunakan CSS manual seperti *float* atau *clear*.

---

## **Tujuan Pembuatan**

1. Menerapkan **Bootstrap Grid System** untuk membentuk layout halaman.
2. Menggunakan komponen Bootstrap seperti **Navbar, Card, dan Button**.
3. Mendesain tampilan website yang **menarik, profesional, dan responsif** di berbagai perangkat.
4. Menampilkan **data diri dan hasil karya** dalam bentuk **portfolio pribadi**.

---

## **Struktur Halaman**

Berikut pembagian bagian utama dari file **portfolio.html**:

1. **Navbar**

   * Menggunakan `<nav>` dengan class `navbar navbar-expand-lg navbar-dark bg-dark`.
   * Berisi menu navigasi: **Beranda, Tentang, Portfolio, dan Kontak**.

2. **Hero Section (Beranda)**

   * Latar belakang bertema **luar angkasa 3D** dengan teks sambutan dan tombol menuju portfolio.
   * Menampilkan **nama lengkap (Rizky Maulana)** dan deskripsi singkat bidang keahlian.

3. **Tentang Saya**

   * Menggunakan `.container`, `.row`, dan dua kolom (`col-md-4` dan `col-md-8`).
   * **Kolom kiri:** menampilkan foto pribadi (`rizky.jpg`).
   * **Kolom kanan:** berisi nama, jurusan, kampus, minat, dan deskripsi diri.
   * Bagian ini memiliki **efek gelap semi-transparan (block)** agar foto profil tidak tertutup efek.

4. **Portfolio Saya**

   * Menggunakan `.row` dan beberapa `.col-md-4` yang berisi komponen `.card`.
   * Setiap card merepresentasikan hasil karya saya:

     * **Website Profil Pribadi**
     * **UI Design Project**
     * **Responsive Web Layout**

5. **Kontak**

   * Bagian sederhana dengan tombol **“Kirim Email”** menggunakan `mailto:` link.
   * Dilengkapi dengan informasi kontak lain seperti **WhatsApp, Telegram, dan CapCut Link**.

6. **Footer**

   * Menampilkan teks hak cipta:

     > “© 2025 Rizky Maulana. All Rights Reserved.”

---

## **Teknologi yang Digunakan**

* **HTML5**
* **Bootstrap 5.3.3 (CDN)**
* **CSS Internal (minor styling)**
* **Dark Theme Design**
* **Responsive Design** untuk semua ukuran layar

---

## **Struktur File Proyek**

1. `index.html`
2. `portfolio.html`
3. `home.html`
4. `ui-design.html`
5. `README.md`

---

## **Kesimpulan**

Melalui tugas ini, saya belajar bagaimana cara membangun **website portfolio modern dan responsif** menggunakan **Bootstrap**.
Saya memahami penggunaan komponen seperti **Navbar, Grid, Card, dan Container** untuk menyusun tampilan dengan cepat tanpa banyak kode CSS tambahan.

Hasil akhir dari tugas ini adalah **halaman portfolio pribadi bertema gelap (dark mode)** dengan desain futuristik yang menampilkan identitas dan karya saya, **Rizky Maulana**, sebagai mahasiswa Teknik Informatika.

---
