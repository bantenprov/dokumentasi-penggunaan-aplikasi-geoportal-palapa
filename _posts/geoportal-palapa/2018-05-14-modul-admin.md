---
date: 2018-05-14
title: Modul Admin Geoportal Palapa
categories:
  - geoportal-palapa
description: Petunjuk pemakaian modul admin geoportal palapa
type: Document
---

## PENDAHULUAN

Badan Informasi Geospasial (BIG) yang berperan sebagai penghubung simpul jaringan Informasi Geospasial memiliki kewajiban untuk membina Kementerian, Lembaga,Pemerintah Daerah Tingkat I (Provinsi) dan Pemerintah Daerah Tingkat II (Kabupaten/kota) dalam mengembangkan dan membangun simpul jaringan. Kendala dan keterbatasan yang sering ditemukan dalam pengembangan dan pembinaan simpul jaringan di daerah terletak pada minimnya infrastruktur dan koneksi jaringan internet.
Kondisi tersebut tentu saja merupakan tantangan dan kesulitan tersendiri bagi BIG dalam melakukan pengembangan dan pembinaan simpul jaringan.

BIG saat ini sedang membangun JIGN (Jaringan Informasi Geospasial Nasional). Untuk mendukung ini, maka disediakan aplikasi – aplikasi yang akan dijalankan pada simpul jaringan untuk mendukung terwujudnya JIGN secara utuh. Tidak semua simpul jaringan memiliki dana untuk membangun environment pengembangan simpul jaringan, oleh karena itu BIG menyediakan solusi aplikasi berbasis opensource.

Aplikasi PALAPA yang dikembangan saat ini sebagai fasilitas penghubung simpul jaringan Informasi Geospasial. Aplikasi PALAPA ini dibangun semudah mungkin dengan dilengkapi user interface yang user friendly, sehingga administrator maupun member tidak akan mengalami kesulitan dalam pengoperasiannya.

## KONFIGURASI

Menu konfigurasi aplikasi PALAPA merupakan suatu sub halaman yang terdapat dalam admin panel. Fungsi dari fasilitas ini adalah untuk mengatur bagaimana basisdata aplikasi PALAPA ini berjalan sesuai dengan keinginan user/pengguna. Banyak yang bisa dilakukan pada menu konfigurasi ini, mulai dari pengaturan pengguna sistem maupun penggunaan style.

![konfigurasi palapa]()

Konfigurasi aplikasi hanya dapat dilakukan oleh pengguna Administrator. Konfigurasi tersebut meliputi;

1. Konfigurasi Sistem
2. Manajemen Layer Jelajah
3. Manajemen Front End
4. Membuat Group
5. Mebuat Fitur Group
6. Manajemen Pengguna
7. Manajemen Styles


Tampilan Aplikasi PALAPA dapat dilihat pada gambar berikut:

![halaman login geoportal palapa]()


Secara default administrator pada aplikasi palapa menggunakan login sebagai berikut:

- Isikan “palapa” pada kolom Nama Pengguna
- Isikan “palapa” sebagai password dalam kolom kata kunci

A. KONFIGURASI SISTEM

Sebelum aplikasi digunakan, admin harus melakukan konfigurasi sistem dengan mengisi beberapa informasi penting sebagai identitas Simpul Jaringan. Secara default sistem sementara di setting sebagai Simpul Nasional. Untuk melakukan pembaharuan konfigurasi dapat dilakukan sebagai berikut:

- Klik pada menu Sistem maka akan muncul tampilan halaman sebagai berikut:

![]()

Klik tombol maka akan muncul tampilan kotak dialog sebagai berikut:

![]()

Isikan form yang ada secara lengkap. Untuk Kolom Kode Simpul merupakan kolom yang wajib di isi ( mandatory ). Lalu klik maka akan muncul tampilan halaman sebagai berikut: