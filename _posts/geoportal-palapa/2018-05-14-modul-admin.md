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

## A. KONFIGURASI SISTEM

Sebelum aplikasi digunakan, admin harus melakukan konfigurasi sistem dengan mengisi beberapa informasi penting sebagai identitas Simpul Jaringan. Secara default sistem sementara di setting sebagai Simpul Nasional. Untuk melakukan pembaharuan konfigurasi dapat dilakukan sebagai berikut:

- Klik pada menu Sistem maka akan muncul tampilan halaman sebagai berikut:

![sistem]()

Klik tombol maka akan muncul tampilan kotak dialog sebagai berikut:

![suntig informasi]()

Isikan form yang ada secara lengkap. Untuk Kolom Kode Simpul merupakan kolom yang wajib di isi ( mandatory ). Lalu klik maka akan muncul tampilan halaman sebagai berikut:

![informasi simpul jaringan]()

## B. MANAJEMEN LAYER JELAJAH

Menu ini berfungsi untuk memilih service layer yang ada di geoserver untuk ditampilkan pada halaman frontend menu jelajah. Fungsi ini dapat digunakan apabila data sudah tersedia pada sistem.

![layar jelajah]()

![jelajah]()

Untuk mengaktifkan service layer dapat dilakukan sebagai berikut:

- Pilih salah satu service layer yang akan diaktifkan
- Kemudian beri tanda checklist pada kolom pilih dan Aktif/No Aktif/Non-Aktif.

Sebagai contoh dapat dilihat pada gambar berikut:

![layer default jelajah peta]()

- Selanjutnya klik selanjutnya akan muncul tampilan notifikasi sebagai berikut:

![sukses disimpan]()


Setelah tersimpan, selanjutnya user dapat melihat pada halaman front end seperti gambar berikut

![geoportal palapa]()

Dari halaman jelajah pada front end ini, user dapat melihat tampilan service layer yang aktif dengan langkah-langkah sebagai berikut:

- Klik tool dipojok kiri bawah, maka akan muncul tampilan sebagai berikut:

![tambahkan layer]()


Dari tampilan tersebut, user dapat aktifkan atau tidak mengaktifkan layer

![daftar layer]()

Tampilan service layer yang aktif keduanya dapat dilihat pada gambar berikut:

![services]()

Tampilan service layer salah satu yang tidak aktif dapat dilihat pada gambar berikut:

![tampilan service]()

## C. MANAJEMEN FRONT END

Menu Font End berfungsi untuk melakukan perubahan tampilan halaman muka layout/luar dari website geoportal palapa.

![konfigurasi palapa front end]()

Untuk dapat melakukan perubahan (editing) pada tampilan website, maka dapat dilakukan sebagai berikut:

- Untuk mengganti tema, dapat dilakukan dengan mengklik dropdown pada kolom Tipe.
- Untuk mengganti julul website dapat diganti pada menu Judul Situs
- Untuk mengganti logo website dapat diganti dengan mengklik pada menu Logo Situs kemudian pilih gambar untuk menguploadnya.
- Untuk mengganti slide background website dapat diganti dengan mengklik pada menu Berkas Gambar 1 & Berkas Gambar 1 kemudian pilih gambar untuk menguploadnya
- Untuk mengganti keterangan gambar, dapat diganti pada menu Keterangan
Gambar 1 dan Keterangan Gambar 2
- Untuk mengganti judul berita, dapat diganti pada menu Judul Headline
- Untuk mengganti Keterangan berita, dapat diganti pada menu Keterangan Headline
- Untuk mengganti judul artikel, dapat diganti pada menu Judul Feature
- Untuk mengganti keterangan artikel, dapat diganti pada menu Keterangan Feature


