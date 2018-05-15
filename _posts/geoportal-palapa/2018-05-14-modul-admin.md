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

[![Konfigurasi Palapa](/images/modul-admin/geoportal-palapa_konfigurasi-palapa.png)](/images/modul-admin/geoportal-palapa_konfigurasi-palapa.png)

Konfigurasi aplikasi hanya dapat dilakukan oleh pengguna Administrator. Konfigurasi tersebut meliputi;

1. Konfigurasi Sistem
2. Manajemen Layer Jelajah
3. Manajemen Front End
4. Membuat Group
5. Mebuat Fitur Group
6. Manajemen Pengguna
7. Manajemen Styles


Tampilan Aplikasi PALAPA dapat dilihat pada gambar berikut:

[![Halaman Login Geoportal Palapa](/images/modul-admin/geoportal-palapa_halaman-login.png)](/images/modul-admin/geoportal-palapa_halaman-login.png)

Secara default administrator pada aplikasi palapa menggunakan login sebagai berikut:

- Isikan “palapa” pada kolom Nama Pengguna
- Isikan “palapa” sebagai password dalam kolom kata kunci

## A. KONFIGURASI SISTEM

Sebelum aplikasi digunakan, admin harus melakukan konfigurasi sistem dengan mengisi beberapa informasi penting sebagai identitas Simpul Jaringan. Secara default sistem sementara di setting sebagai Simpul Nasional. Untuk melakukan pembaharuan konfigurasi dapat dilakukan sebagai berikut:

- Klik pada menu Sistem maka akan muncul tampilan halaman sebagai berikut:

[![Sistem](/images/modul-admin/geoportal-palapa_sistem.png)](/images/modul-admin/geoportal-palapa_sistem.png)

Klik tombol **Sunting Informasi** maka akan muncul tampilan kotak dialog sebagai berikut:

[![Sunting Informasi](/images/modul-admin/geoportal-palapa_sunting-informasi.png)](/images/modul-admin/geoportal-palapa_sunting-informasi.png)

Isikan form yang ada secara lengkap. Untuk Kolom Kode Simpul merupakan kolom yang wajib di isi ( mandatory ). Lalu klik **sunting** maka akan muncul tampilan halaman sebagai berikut:

[![Informasi Simpul Jaringan](/images/modul-admin/geoportal-palapa_informasi-simpul-jaringan.png)](/images/modul-admin/geoportal-palapa_informasi-simpul-jaringan.png)

## B. MANAJEMEN LAYER JELAJAH

Menu ini berfungsi untuk memilih service layer yang ada di geoserver untuk ditampilkan pada halaman frontend menu jelajah. Fungsi ini dapat digunakan apabila data sudah tersedia pada sistem.

[![Layar Jelajah](/images/modul-admin/geoportal-palapa_layar-jelajah.png)](/images/modul-admin/geoportal-palapa_layar-jelajah.png)

[![Layar Jelajah 2](/images/modul-admin/geoportal-palapa_layar-jelajah-2.png)](/images/modul-admin/geoportal-palapa_layar-jelajah-2.png)


Untuk mengaktifkan service layer dapat dilakukan sebagai berikut:

- Pilih salah satu service layer yang akan diaktifkan
- Kemudian beri tanda checklist pada kolom pilih dan Aktif/No Aktif/Non-Aktif.

Sebagai contoh dapat dilihat pada gambar berikut:

[![Layer Default Jelajah Peta](/images/modul-admin/geoportal-palapa_layer-default-jelajah-peta.png)](/images/modul-admin/geoportal-palapa_layer-default-jelajah-peta.png)

- Selanjutnya klik **simpan** selanjutnya akan muncul tampilan notifikasi sebagai berikut:

[![Sukses Di Simpan](/images/modul-admin/geoportal-palapa_sukses-di-simpan.png)](/images/modul-admin/geoportal-palapa_sukses-di-simpan.png)


Setelah tersimpan, selanjutnya user dapat melihat pada halaman front end seperti gambar berikut

[![Geoportal Palapa](/images/modul-admin/geoportal-palapa_geoportal.png)](/images/modul-admin/geoportal-palapa_geoportal.png)

Dari halaman jelajah pada front end ini, user dapat melihat tampilan service layer yang aktif dengan langkah-langkah sebagai berikut:

- Klik tool **layer** dipojok kiri bawah, maka akan muncul tampilan sebagai berikut:

[![Tambah Layer](/images/modul-admin/geoportal-tambah-layer.png)](/images/modul-admin/geoportal-tambah-layer.png)


Dari tampilan tersebut, user dapat aktifkan atau tidak mengaktifkan layer

[![Daftar Layer](/images/modul-admin/geoportal-daftar-layer.png)](/images/modul-admin/geoportal-daftar-layer.png)

Tampilan service layer yang aktif keduanya dapat dilihat pada gambar berikut:

[![Services](/images/modul-admin/geoportal-palapa_services.png)](/images/modul-admin/geoportal-palapa_services.png)

Tampilan service layer salah satu yang tidak aktif dapat dilihat pada gambar berikut:

[![Tampilan Services](/images/modul-admin/geoportal-palapa_tampilan-services.png)](/images/modul-admin/geoportal-palapa_tampilan-services.png)

## C. MANAJEMEN FRONT END

Menu Font End berfungsi untuk melakukan perubahan tampilan halaman muka layout/luar dari website geoportal palapa.

[![Konfigurasi Palapa Front End](/images/modul-admin/geoportal-palapa_konfigurasi-palapa-front-end.png)](/images/modul-admin/geoportal-palapa_konfigurasi-palapa-front-end.png)

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

## D. MEMBUAT GROUP USER

Group user adalah wadah untuk suatu kelompok kerja pembuat atau penghasil data. Secara default pada sistem telah ada group ADMIN dan KUGI. Dalam menu ini pengguna administrator dapat melakukan penambahan, pembaharuan, dan menghapus grup yang ada.

[![Group User](/images/modul-admin/geoportal-palapa_group-user.png)](/images/modul-admin/geoportal-palapa_group-user.png)

### 1. Penambahan Grup
Untuk dapat melakukan penambahan Grup dapat dilakukan sebagai berikut:

- Klik menu Grup, lalu klik tombol **tambah group**
- Isikan seluruh kolom yang ada, apabila sudah selesai klik **tambah** Sebagai catatan kolom isian Nama Grup dan Nama Organisai merupakan isian wajib. Nama Grup di isi dengan satu kata tanpa “spasi
spasi” merupakan nama singkatan dari suatu kelompok kerja/instansi, misal : BPLH, sedangkan Nama
Organisasi merupakan nama atau keterangan detail dari Nama Grup, misal: Badan Pengendalian Lingkungan Hidup.

[![Tambah Group](/images/modul-admin/geoportal-palapa_tambah-group.png)](/images/modul-admin/geoportal-palapa_tambah-group.png)

Pada saat penambahan grup sistem secara otomatis akan membuat Workspace, Role, Store, dan Set Layer Properties di Geoserver. Selain itu sistem juga akan membuat DB dengan nama sesuai nama grup yang dibuat di PostGIS/PostgreSQL.

[![DB PostGIS](/images/modul-admin/geoportal-palapa_db-post-gis.png)](/images/modul-admin/geoportal-palapa_db-post-gis.png)

## 2. Pembaharuan Grup
- Klik icon untuk melakukan pembaharuan dengan mengedit isian yang perlu diperbaharui, setelah itu klik **simpan**

[![Sunting Group](/images/modul-admin/geoportal-palapa_sunting-group.png)](/images/modul-admin/geoportal-palapa_sunting-group.png)

## 3. Menghapus Grup
Menghapus grup berarti sistem secara otomatis akan menghapus seluruh data yang terkait dengan grup tersebut; user, layer, dan metada pada grup yang dihapus. Oleh karena itu fungsi ini sebaiknya digunakan apabila data belum terisi. Untuk melakukan penghapusan hapusan grup dari Simpul Jaringan dengan mengklik icon maka sistem akan mengeluarkan notifikasi untuk melanjutkan proses penghapusan.

[![Hapus Group](/images/modul-admin/geoportal-palapa_hapus-group.png)](/images/modul-admin/geoportal-palapa_hapus-group.png)

## 4. FITUR GROUP
Fitur group ini berfungsi untuk hak akses dalam pengelolaan fitur data KUGI yang diberikan kepada grup member, (Baca Dokumen KUGI Versi. 4).

[![Fitur Group](/images/modul-admin/geoportal-palapa_fitur-group.png)](/images/modul-admin/geoportal-palapa_fitur-group.png)

Adapun tahapan yang dapat dilakukan adalah sebagai berikut:

- Klik icon dropdown  Kemudian tentukan skala data yang dipilih dengan mengklik dropdown
pada menu Group, seperti terlihat pada gambar berikut:

[![Dropdown Pilih Group](/images/modul-admin/geoportal-palapa_drop-down-group.png)](/images/modul-admin/geoportal-palapa_drop-down-group.png)

pada menu Skala.

[![Dropdown Pilih Skala](/images/modul-admin/geoportal-palapa_drop-down-skala.png)](/images/modul-admin/geoportal-palapa_drop-down-skala.png)

- Pada menu Kategori, klik dropdown Selanjutnya pada menu fitur, klik fitur yang tersedia untuk dikelola kemudian untuk memilih kategori yang diinginkan.

[![Kategori](/images/modul-admin/geoportal-palapa_kategori.png)](/images/modul-admin/geoportal-palapa_kategori.png)

- Selanjutnya pada menu fitur, klik fitur yang tersedia untuk dikelola kemudian untuk memilih kategori yang diinginkan secara otomatis akan pindah ke menu Fitur yang dikelola, seperti terlihat pada gambar berikut:

[![Pengelolaan Fitur](/images/modul-admin/geoportal-palapa_pengelolaan-fitur.png)](/images/modul-admin/geoportal-palapa_pengelolaan-fitur.png)

- Sedangkan untuk menghilangkan fitur pada menu Fitur yang dikelola, dikelola tinggal diklik, maka secara otomatis fitur tersebut akan hilang di menu Fitur yang dikelola.
- Setelah menentukan fitur yang akan dikelola, selanjutnya klik **simpan**  maka akan muncul notifikasi sebagai berikut:

[![Disimpan](/images/modul-admin/geoportal-palapa_disimpan.png)](/images/modul-admin/geoportal-palapa_disimpan.png)

## F. PENGGUNA (MEMBER)

Member merupakan pengguna aplikasi yang dapat melakukan manajemen data spasial dan metadata di group masing-masing. masing masing. Administrator pada menu ini dapat melakukan penambahan member, pembaharuan password passwo rd member, dan menghapus member dari satu grup. Secara default pada sistem PALAPA sudah dibuatkan member dengan nama pengguna palapa sebagai administrator sistem.

[![Daftar Pengguna](/images/modul-admin/geoportal-palapa_daftar-pengguna.png)](/images/modul-admin/geoportal-palapa_daftar-pengguna.png)

### 1. Menambah Pengguna

Untuk dapat melakukan penambahan pengguna, dapat dilakukan sebagai berikut:

- Pada menu Pengguna, klik tombol **tambah pengguna**
- Isikan semua data pada kolom yang tersedia, seperti tampilan berikut:

[![Tambah Pengguna](/images/modul-admin/geoportal-palapa_tambah-pengguna.png)](/images/modul-admin/geoportal-palapa_tambah-pengguna.png)

- Selah data terisi, selanjutnya klik **tambah** maka akan muncul notifikasi pemberitahuan sebagai berikut:

[![Tambah Pengguna Berhasil](/images/modul-admin/geoportal-palapa_tambah-pengguna-berhasil.png)](/images/modul-admin/geoportal-palapa_tambah-pengguna-berhasil.png)

Pada saat menambah pengguna, maka sistem secara otomatis akan membuat user di Geoserver.

[![Konfirmasi Pengguna](/images/modul-admin/geoportal-palapa_konfirmasi-pengguna.png)](/images/modul-admin/geoportal-palapa_konfirmasi-pengguna.png)

### 2. Pembaharuan Password dan Grup User

Pembaharuan password dapat dilakukan sebagai berikut:

- Pada menu Pengguna, Pengguna pilih salah satu member/user  Kemudian klik icon maka akan muncul tampilan sebagai berikut

[![Edit Pengguna](/images/modul-admin/geoportal-palapa_edit-pengguna.png)](/images/modul-admin/geoportal-palapa_edit-pengguna.png)

- Isikan kata kunci baru pada kolom password
- Setelah kata kunci baru terisi, selanjutnya klik **edit**
- Selain password dapat juga dilakukan pembaharuan Grup apabila user tersebut berganti /berpindah tempat. Pilih Grup yang baru, selanjutnya klik **edit**

### 3. Menghapus Pengguna

Untuk melakukan penghapusan user/pengguna dapat dilakukan sebagai berikut:

- Pada menu Pengguna, Pengguna Pilih salah satu member/user
- Kemudian klik icon User maka akan muncul tampilan notifikasi sebagai berikut:

[![Hapus Pengguna](/images/modul-admin/geoportal-palapa_hapus-pengguna.png)](/images/modul-admin/geoportal-palapa_hapus-pengguna.png)

## G. MANAJEMEN STYLE (SLD)

Style Layer merupakan simbologi kenampakan layer pada halaman browser, sebagai contoh sungai berbentuk garis dengan warna biru. Fungsi yang ada pada menu ini adalah menambah dan menghapus style.

[![Manajemen Style](/images/modul-admin/geoportal-palapa_manajemen-style.png)](/images/modul-admin/geoportal-palapa_manajemen-style.png)

### 1. Menambah Style

Untuk dapat melakukan penambahan style dapat dilakukan sebagai berikut:

- Klik Menu Style (SLD)
- Kemudian klik **tambah style** maka akan muncul kotak dialog sebagai berikut:

[![Tambah Style](/images/modul-admin/geoportal-palapa_tambah-style.png)](/images/modul-admin/geoportal-palapa_tambah-style.png)

- Klik **choose file** untuk mengupload style

[![Pilih Style](/images/modul-admin/geoportal-palapa_pilih-style.png)](/images/modul-admin/geoportal-palapa_pilih-style.png)

- Setelah style di upload maka sistem akan menampilkan progres upload

[![Upload Style](/images/modul-admin/geoportal-palapa_upload-style.png)](/images/modul-admin/geoportal-palapa_upload-style.png)

- Selanjutnya klik **tutup**

### Menghapus Style

Untuk dapat melakukan penghapusan style dapat dilakukan sebagai berikut:

- Klik salah satu Style yang akan di hapus, misalnya jalan_merah

[![Hapus Style](/images/modul-admin/geoportal-palapa_hapus-style.png)](/images/modul-admin/geoportal-palapa_hapus-style.png)

- Selanjutnya klik **x** maka akan muncul tampilan notifikasi sebagai berikut:

[![Pop Up Hapus Style](/images/modul-admin/geoportal-palapa_pop-up-hapus-style.png)](/images/modul-admin/geoportal-palapa_pop-up-hapus-style.png)

## MANAJEMEN DATABASE

Manajemen dataset dapat dilakukan oleh administrator ataupun member yang ada di setiap grup. Masing-masing pengguna mempunyai kewenangan berbeda. Pada sistem PALAPA pengguna administrator selain dapat melakukan konfigurasi sistem juga dapat melakukan manajemen dataset mulai dari upload, delete sampai dengan publishing
data. Sedangkan untuk pengguna member hanya diberikan kewenangan untuk upload data pada database Pengembangan (DEV), melihat dan mendownload data pada database Pengembangan, Produksi, maupun Publikasi.

## PENGGUNA MEMBER

Pengguna dalam kategori member pada setiap grup/SKPD adalah pengguna yang mempunyai akses atau kewajiban untuk melakukan unggah/upload data spasial maupun metdatanya ke dalam sistem PALAPA. Data yang diunggah ke dalam sistem merupakan data hasil kegiatan di masing-masing SKPD baik yang sudah final maupun
masih data sementara. Data-data tersebut akan tersimpan dalam database Pengembangan (DEV). Data yang sudah final dapat diduplikasikan ke sistem database produksi untuk diberbagi data ke SKPD yang lain maupun di publikasi ke publik oleh Pengguna admin/publisher

[![Pengguna Member](/images/modul-admin/geoportal-palapa_pengguna-member.png)](/images/modul-admin/geoportal-palapa_pengguna-member.png)

Pada dashboard pengguna member terdapat fasilitas untuk melihat dan melakukan copy data (download) dari grup/SKPD lain dalam satu Simpul Jaringan yaitu melalui menu Database Produksi (PROD). Selain di database, pengguna member juga dapat melihat data-data yang telah ada di Geoserver dalam bentuk service baik spasial maupun metadatanya.

Berikut diuraikan beberapa fungsi yang terdapat pada dashboard aplikasi PALAPA untuk pengguna member;

### 1. Unggah Data KUGI

- Format data : shp

- Format file : zip yang terdiri dari minimal extention (.dbf, .prj, .shp, .shx), nama zip file harus sama dengan nama shpnya, misal: semak.shp, maka nama filenya menjadi semak.zip. Untuk data KUGI ada 3 field pada
data yang akan diupload harus terisi dengan benar yaitu; FCODE, SRS_Id, dan Metadata, apabila salah satu field tersebut kosong, maka data tidak dapat diupload ke dalam sistem.

[![Data Zip](/images/modul-admin/geoportal-palapa_data-zip.png)](/images/modul-admin/geoportal-palapa_data-zip.png)

Skema data : KUGI Versi. 4 (Lihat dokumen di http://kugi.ina-sdi.or.id/)

Langkah-langkah yang dilakukan yaitu;

- Pilih menu **Pengembangan (DEV)**

[![Pengembangan Dev](/images/modul-admin/geoportal-palapa_pengembangan-dev.png)](/images/modul-admin/geoportal-palapa_pengembangan-dev.png)

- Klik tombol **Unggah Data**

[![Unggah Data](/images/modul-admin/geoportal-palapa_unggah-data.png)](/images/modul-admin/geoportal-palapa_unggah-data.png)

- Lakukan pemilihan skala, kategori, fitur, dan pilih data spasial yang akan di
upload dengan klik icon **shoose file**

[![Pilih File](/images/modul-admin/geoportal-palapa_pilih-file.png)](/images/modul-admin/geoportal-palapa_pilih-file.png)

[![Pilih File 2](/images/modul-admin/geoportal-palapa_pilih-file-2.png)](/images/modul-admin/geoportal-palapa_pilih-file-2.png)

- Apabila data berhasil diunggah, akan muncul windows

[![Pop Up](/images/modul-admin/geoportal-palapa_pop-up.png)](/images/modul-admin/geoportal-palapa_pop-up.png)

- Pada menu Informasi Data Constrain pilih Public, Goverment, atau Private
- Unggah metada dari data yang telah berhasil di unggah dengan klik icon **choose file** pilih file metadata dalam format xml dari komputer lalu klik Open

[![Meta Data](/images/modul-admin/geoportal-palapa_meta-data.png)](/images/modul-admin/geoportal-palapa_meta-data.png)

- Apabila data berhasil diunggah, akan muncul windows

[![Pop Up Upload Sukses](/images/modul-admin/geoportal-palapa_pop-up-upload-suskses.png)](/images/modul-admin/geoportal-palapa_pop-up-upload-suskses.png)

### 2. Unggah Data Usulan KUGI

- Format data : shp
- Format file : zip yang terdiri dari minimal extention (.dbf, .prj, .shp, .shx), nama zip file harus sama dengan nama shpnya, misal: jalan_semarang.shp, maka nama filenya menjadi jalan_semanarang.zip
- Skema data : Bebas

Langkah-langkah yang dilakuka yaitu;

- Pilih menu **Pengembangan (DEV)**

[![Pengembangan DEV 2](/images/modul-admin/geoportal-palapa_pengembangan-dev-2.png)](/images/modul-admin/geoportal-palapa_pengembangan-dev-2.png)

- Klik tombol **Ungga Data**

[![Unggah Data DEV](/images/modul-admin/geoportal-palapa_unggah-data-dev.png)](/images/modul-admin/geoportal-palapa_unggah-data-dev.png)

- Klik menu **Unggah Usulan KUGI** maka akan muncul tampilan progres sebagai berikut:

[![Unggah Data Usulan](/images/modul-admin/geoportal-palapa_unggah-usulan.png)](/images/modul-admin/geoportal-palapa_unggah-usulan.png)

- Pilih data spasial yang akan di upload dengan klik icon **choose files** pada baris **Pilih Berkas (ZIP)**

[![Pilih Berkas](/images/modul-admin/geoportal-palapa_pilih-berkas.png)](/images/modul-admin/geoportal-palapa_pilih-berkas.png)

 sistem akan otomatis mengunggah data ke sistem database. Setelah selesai akan muncul tampilan notifikasi

[![Tampil Notif](/images/modul-admin/geoportal-palapa_ptampil-notif.png)](/images/modul-admin/geoportal-palapa_ptampil-notif.png)

- Klik **Lanjut** untuk progres tahap 2

[![Tahap 2](/images/modul-admin/geoportal-palapa_tahap-2.png)](/images/modul-admin/geoportal-palapa_tahap-2.png)

- Klik **SImpan Layar** maka jika berhasil data akan langsung dibuatkan service di Geoserver untuk kepentingan publikasi.

[![Simpan Layar](/images/modul-admin/geoportal-palapa_simpan-layar.png)](/images/modul-admin/geoportal-palapa_simpan-layar.png)

- Selanjutnya klik **Lanjut** untuk progres tahap 3

[![Tahap 3](/images/modul-admin/geoportal-palapa_tahap-tiga.png)](/images/modul-admin/geoportal-palapa_tahap-tiga.png)

- Jika memilih Minimal pada menu Tipe Metadata, maka langsung klik **Simpan Metadata**
- Apabila memilih Unggah Metadata, maka tampilannya sebagai berikut:

[![Tambah Metadata](/images/modul-admin/geoportal-palapa_tambah-metadata.png)](/images/modul-admin/geoportal-palapa_tambah-metadata.png)

- Klik **choose file** pada menu Pilih Berkas (XML)

[![Pilih File RAR](/images/modul-admin/geoportal-palapa_pilih-file-rar.png)](/images/modul-admin/geoportal-palapa_pilih-file-rar.png)

- Klik **Simpan Metadata**  maka akan muncul tampilan notifikasi

[![Simpan Metadata](/images/modul-admin/geoportal-palapa_simpan-metadata.png)](/images/modul-admin/geoportal-palapa_simpan-metadata.png)

- Klik **Selesai** maka akan muncul tampilan Layer Spasial

[![Layar Spasial](/images/modul-admin/geoportal-palapa_layar-spasial.png)](/images/modul-admin/geoportal-palapa_layar-spasial.png)

### 3. Manajemen Database Skema KUGI

Data yang telah diunggah melalui aplikasi PALAPA akan disimpan pada database Pengembangan (DEV). Data tersebut merupakan data milik grup/SKPD yang mengunggah data. Pengguna dapat melakukan manajemen melalui menu Database Pengembangan (DEV) sebagai berikut;

[![Pengembangan DEV Again](/images/modul-admin/geoportal-palapa_pengembangan-dev-again.png)](/images/modul-admin/geoportal-palapa_pengembangan-dev-again.png)

- Melihat metadata, klik icon **i** , maka akan muncul windows.

[![Berkas Metadata](/images/modul-admin/geoportal-palapa_berkas-metadata.png)](/images/modul-admin/geoportal-palapa_berkas-metadata.png)

- Mengupload ulang metadata apabila ada perbaikan, klik icon maka akan muncul windows. Lakukan tahapan seperti saat melakukan unggah data.

[![Berkas Metadata Again](/images/modul-admin/geoportal-palapa_berkas-metadata-again.png)](/images/modul-admin/geoportal-palapa_berkas-metadata-again.png)

- Migrasi data ke database Produksi (PROD), klik icon , maka akan muncul windows

[![Eksport Databse](/images/modul-admin/geoportal-palapa_eksport-databse.png)](/images/modul-admin/geoportal-palapa_eksport-databse.png)

- Menghapus data, klik icon **x**, maka akan muncul windows

[![Hapus Dataset](/images/modul-admin/geoportal-palapa_hapus-dataset.png)](/images/modul-admin/geoportal-palapa_hapus-dataset.png)

- Download data, pilih menu Database Produksi (PROD), klik icon , maka secara otomatis data akan tersimpan ke komputer personal.

### 4. Manajemen Data Usulan Skema KUGI

Berbeda dengan manajemen database skema KUGI, data usulan KUGI yang telah diunggah akan disimpan pada database tersendiri berdasarkan grup/SKPD yang mempunyai data. Manajemen data yang dapat dilakukan adalah melalui service data tersebut yang sudah ada di Geoserver. Geoserver. Manajemen tersebut dapat dilakukan pada menu Publikasi - Layer Spasial.

[![Layar Spasial](/images/modul-admin/geoportal-palapa_layar-spasial-2.png)](/images/modul-admin/geoportal-palapa_layar-spasial-2.png)

Fungsi yang ada pada menu ini antara lain;

- Melihat data, pilih data yang akan dilihat, klik icon **i** maka akan muncul windows

[![I](/images/modul-admin/geoportal-palapa_i.png)](/images/modul-admin/geoportal-palapa_i.png)

- Memperbaharui informasi data, klik icon maka akan muncul windows.

[![Jalan](/images/modul-admin/geoportal-palapa_jalan.png)](/images/modul-admin/geoportal-palapa_jalan.png)

- Setelah layer diedit, klik **simpan** maka akan muncul notifikasi sebagai berikut:

[![Simpan](/images/modul-admin/geoportal-palapa_simpan-again.png)](/images/modul-admin/geoportal-palapa_simpan-again.png)

## PENGGUNA ADMIN/PUBLISHER

Pengguna dalam kategori admin/publisher dibuat untuk memanajemen satu Simpul Jaringan. Pengguna level ini hanya mempunyai wewenang untuk memilih data-data data yang ada di Database Produksi untuk di publikasi baik ke internal Simpul Jaringan atau ke pengguna umum melalui layanan service. Mekanisme kerja dari pengguna admin/publisher diuraikan sebagai berikut;

### 1. Manajemen Database Produksi (PROD)

Pada menu Database Produksi (PROD) di aplikasi PALAPA ada beberapa fungsi yang dapat dijalankan oleh pengguna admin/publisher yaitu;

[![Manajemen PROD](/images/modul-admin/geoportal-palapa_manajemen-prod.png)](/images/modul-admin/geoportal-palapa_manajemen-prod.png)

- Melihat metadata, klik icon **i** maka akan muncul windows.

[![Berkas Metadata XML](/images/modul-admin/geoportal-palapa_berkas-metadata-xml.png)](/images/modul-admin/geoportal-palapa_berkas-metadata-xml.png)

- Mengupload ulang metadata apabila ada perbaikan perbaikan, klik icon maka akan muncul windows. Lakukan tahapan seperti saat melakukan unggah data.

[![Berkas Metadata XML 2](/images/modul-admin/geoportal-palapa_berkas-metadata-xml-2.png)](/images/modul-admin/geoportal-palapa_berkas-metadata-xml-2.png)

- Migrasi data ke database Publikasi (PUB), klik icon , maka akan muncul windows

[![Export Dataset](/images/modul-admin/geoportal-palapa_export-dataset.png)](/images/modul-admin/geoportal-palapa_export-dataset.png)

- Menghapus data, klik icon , maka akan muncul windows

[![Hapus Dataset 2](/images/modul-admin/geoportal-palapa_hapus-dataset-2.png)](/images/modul-admin/geoportal-palapa_hapus-dataset-2.png)

- Download data, klik icon  maka secara otomatis data akan tersimpan ke komputer personal.

### 2. Manajemen Database Publikasi (PUB)

Pada menu Database Publikasi (PUB) di aplikasi PALAPA ada beberapa fungsi yang dapat dijalankan oleh pengguna admin/publisher yaitu;

[![Publikasi PUB](/images/modul-admin/geoportal-palapa_publikasi-pub.png)](/images/modul-admin/geoportal-palapa_publikasi-pub.png)

- Mengupload ulang metadata apabila ada perbaikan, klik icon maka akan muncul windows. Lakukan tahapan seperti saat melakukan unggah data.

[![Berkas Metadata Again and Again](/images/modul-admin/geoportal-palapa_berkas-metadata-again-and-again.png)](/images/modul-admin/geoportal-palapa_berkas-metadata-again-and-again.png)

- Menghapus data, klik icon **x** maka akan muncul windows

[![Hapus Dataset Again](/images/modul-admin/geoportal-palapa_hapus-dataset-happen-again.png)](/images/modul-admin/geoportal-palapa_hapus-dataset-happen-again.png)

### 3. Manajemen Publikasi

Pada menu Publikasi (PUB) di aplikasi PALAPA ada beberapa fungsi yang dapat dijalankan oleh pengguna admin/publisher yaitu;

## Publikasi Layer KUGI

Menu publikasi layer KUGI adalah menu untuk membuat service data KUGI ke Geoserver.

[![Publikasi Layar KUGI](/images/modul-admin/geoportal-palapa_publikasi-layar-kugi.png)](/images/modul-admin/geoportal-palapa_publikasi-layar-kugi.png)

- Membuat service ke Geoserver, klik  maka akan muncul windows

[![Publikasi Dataset](/images/modul-admin/geoportal-palapa_publikasi-dataset.png)](/images/modul-admin/geoportal-palapa_publikasi-dataset.png)

- Setelah di klik **Publikasikan** maka akan muncul tampilan notifikasi

[![Publikasikan](/images/modul-admin/geoportal-palapa_publikasikan.png)](/images/modul-admin/geoportal-palapa_publikasikan.png)

## Layer Spasial

Pada dashboard ini pengguna dapat melakukan operasi standar yaitu melihat, menghapus, dan mengedit informasi. Operasi tersebut dapat dilakukan dengan prosedur dur yang sama dengan menu lainnya. Untuk mempublikasi data tahapannya adalah sebagai berikut;

[![Layer Spasial](/images/modul-admin/geoportal-palapa_layer-spasial.png)](/images/modul-admin/geoportal-palapa_layer-spasial.png)

- Pilih data yang akan di publikasi

[![Pilih Data](/images/modul-admin/geoportal-palapa_pilih-data.png)](/images/modul-admin/geoportal-palapa_pilih-data.png)

- Klik icon  set status advertise maka akan muncul tampilan berikut:

[![Status Advertise](/images/modul-admin/geoportal-palapa_status-advertise.png)](/images/modul-admin/geoportal-palapa_status-advertise.png)

- Klik **proses**  maka akan muncul notifikasi

[![Proses](/images/modul-admin/geoportal-palapa_proses.png)](/images/modul-admin/geoportal-palapa_proses.png)

Berikut tampilan layer yang sudah diaktifkan pada geoserver yang dapat dilihat pada kolom Aktif.

[![Layer Aktif](/images/modul-admin/geoportal-palapa_layer-aktif.png)](/images/modul-admin/geoportal-palapa_layer-aktif.png)

## Metadata KUGI/Usulan KUGI

Pada dasboard ini pengguna dapat melakukan operasi standar yaitu melihat dan mengedit informasi metadata baik KUGI maupun usulan KUGI. Operasi tersebut dapat dilakukan dengan prosedur yang sama dengan menu lainnya. Untuk mempublikasi metadata KUGI atau usulan KUGI menjadi file csw atau menghilangkan publikasinya dapat dilakukan dengan cara sebagai berikut:

[![Manajemen Kugi 1](/images/modul-admin/geoportal-palapa_manajemen-kugi-1.png)](/images/modul-admin/geoportal-palapa_manajemen-kugi-1.png)

[![Manajemen Kugi 2 Again](/images/modul-admin/geoportal-palapa_manajemen-kugi-2-again.png)](/images/modul-admin/geoportal-palapa_manajemen-kugi-2-again.png)

- Publikasi data, klik icon [ ] maka akan muncul tampilan berikut

[![Publish Metadata (1)](/images/modul-admin/geoportal-palapa_publish-metadata-11.png)](/images/modul-admin/geoportal-palapa_publish-metadata-11.png)

- Klik **Publikasi Metadata** maka akan muncul tampilan notifikasi

[![Notifikasi Metadata](/images/modul-admin/geoportal-palapa_notofikasi-metadata.png)](/images/modul-admin/geoportal-palapa_notofikasi-metadata.png)

- Unpublikasi klik **x** hilangkan publikasi metadata ke servis CSW, maka akan muncul tampilan notifikasi sebagai berikut

[![Unpublish Metadata](/images/modul-admin/geoportal-palapa_unpublish-metadata.png)](/images/modul-admin/geoportal-palapa_unpublish-metadata.png)

- Klik **Unpublish!** maka muncul notfikasi seperti gambar berikut:

[![Gambar Unpublish Metadata](/images/modul-admin/geoportal-palapa_gambar-unpublish-metadata.png)](/images/modul-admin/geoportal-palapa_gambar-unpublish-metadata.png)

## APLIKASI PALAPA UNTUK PENGGUNA UMUM

Aplikasi PALAPA memiliki dua sisi aplikasi yaitu aplikasi front-end yang ditujukan bagi pengguna dan aplikasi back-end (CMS) yang ditujuan bagi pengelola aplikasi. Aplikasi untuk backend diuraikan pada Bab 2 dan 3, sedangkan aplikasi untuk fornt-end atau pengguna umum terdapat 3 menu utama yaitu; [a] menu beranda, [b] menu jelajah, dan [c] menu cari. Menu beranda aplikasi PALAPA menyajikan penjelasan umum dari aplikasi PALAPA dan geoportal PALAPA. Menu jelajah aplikasi PALAPA menyajikan viewer webGIS aplikasi yang dilengkapi dengan pemilihan peta dasar dan pemeilihan layer peta yang ingin ditampilkan disamping tool navigasi setandar untuk sebuah aplikasi webGIS. Sedangkan menu cari aplikasi PALAPA merupakan fitur pencarian dataset yang ada pada geoportal PALAPA. 

### 1. Menu Beranda

Menu beranda aplikasi PALAPA memuat informasi tentang aplikasi Geoportal PALAPA terdiri dari arti PALAPA itu sendiri, Pengguna, Administrator, Pengembang, dan Kontak. Untuk melihat seluruh halaman beranda dapat dilakukan dengan scrolling pada browser.

[![Untuk Pengguna Umum](/images/modul-admin/geoportal-palapa_untuk-pengguna-umum.png)](/images/modul-admin/geoportal-palapa_untuk-pengguna-umum.png)
[![Untuk Pengguna Umum 2](/images/modul-admin/geoportal-palapa_untuk-pengguna-umum-2.png)](/images/modul-admin/geoportal-palapa_untuk-pengguna-umum-2.png)
[![Untuk Pengguna Umum 3](/images/modul-admin/geoportal-palapa_untuk-pengguna-umum-3.png)](/images/modul-admin/geoportal-palapa_untuk-pengguna-umum-3.png)
[![Untuk Pengguna Umum 4](/images/modul-admin/geoportal-palapa_untuk-pengguna-umum-4.png)](/images/modul-admin/geoportal-palapa_untuk-pengguna-umum-4.png)

### 2. Menu Jelajah

Menu Jelajah merupakan menu yang dapat digunakan oleh pengguna umum untuk melihat data-data data spasial yang dapat diakses melalui browser webGIS yang dibangun dengan framework OpenLayer. Pada menu jelajah pengguna dapat memilih peta dasar, menampilkan layer data spasial, melakukan navigasi.

[![Menu Jelajah](/images/modul-admin/geoportal-palapa_menu-jelajah.png)](/images/modul-admin/geoportal-palapa_menu-jelajah.png)

## Memilih Peta Dasar

- Klik **Menu Jelajah** dibawah pojok kiri, maka akan terbuka windows

[![Menu Jelajah 2](/images/modul-admin/geoportal-palapa_menu-jelajah-2.png)](/images/modul-admin/geoportal-palapa_menu-jelajah-2.png)

- Secara default aplikasi PALAPA menampilkan peta dari OSM Standar. Untuk mengganti dengan peta dasar lainnya (Rupabumi Indonesia) klik pada peta yang diinginkan, maka peta dasar langsung berubah.

[![Peta Dasar](/images/modul-admin/geoportal-palapa_peta-dasar.png)](/images/modul-admin/geoportal-palapa_peta-dasar.png)

## Menampilkan Layer

- Klik **Layer** maka akan muncul tampilan windows

[![Tambah Layer](/images/modul-admin/geoportal-palapa_tambah-layer.png)](/images/modul-admin/geoportal-palapa_tambah-layer.png)

- Layer aktif dan di visualisasikan pada peta

[![Layer Aktif Lagi](/images/modul-admin/geoportal-palapa_layer-aktif-lagi.png)](/images/modul-admin/geoportal-palapa_layer-aktif-lagi.png)

- Sedangkan layer aktif tidak ditampilkan di peta

[![Layer Tidak Aktif Lagi](/images/modul-admin/geoportal-palapa_layer-tidak-aktif-lagi.png)](/images/modul-admin/geoportal-palapa_layer-tidak-aktif-lagi.png)

- Zoom in layer aktif, klik , maka windows akan membesar ke layer yang dipilih.

[![Zoom](/images/modul-admin/geoportal-palapa_zoom.png)](/images/modul-admin/geoportal-palapa_zoom.png)

- Mengaktif dan non aktifkan fungsi identify, klik
- Menghapus layer dari peta, klik 
- Memindahkan posisi layer, klik
- Mengaktifkan layer di peta, klik
- Menambahkan layer, klik **Tambahkan Layer** pilih server yang menyediakan service.

[![Menyediakan Service](/images/modul-admin/geoportal-palapa_menyediakan-service.png)](/images/modul-admin/geoportal-palapa_menyediakan-service.png)

[![Menyediakan Service 2](/images/modul-admin/geoportal-palapa_menyediakan-service-2.png)](/images/modul-admin/geoportal-palapa_menyediakan-service-2.png)

- Klik tanda **+** pada layer yang ingin ditampilkan pada peta, lalu klik **Selesai**

[![Selesai](/images/modul-admin/geoportal-palapa_selesai.png)](/images/modul-admin/geoportal-palapa_selesai.png)

## Fungsi Navigasi

- **+ Zoom In** Memperbesar tampilan peta area tertentu
- **- Zoom Out** Memperkecil tampila peta area tertentu
- **Full Extent** Menampilkan peta pada extent yang sudah ditetapkan
- **Identifikasi** Identifikasi pada layer aktif
- **Ukur** Mengukur jarak pada peta
- **Legenda** Menampilkan legenda pada layer aktif
- **Opacity** Mengatur transparasi pada layer aktif

### 3. Menu Cari

Menu Cari merupakan menu yang berfungsi sebagai katalog metadata. Pada menu ini pengguna dapat melakukan pencarian data berdasarkan kata  kunci yang terdapat pada metadata ataupun berdasarkan wilayah cakupan. Pada halaman ini akan ditampilkan data-data yang sudah dipublikasi pada satu Simpul Jaringan.  Adapun fungsi yang terdapat pada menu ini adalah; 

[![Menu Cari](/images/modul-admin/geoportal-palapa_menu-cari.png)](/images/modul-admin/geoportal-palapa_menu-cari.png)

- Mencari data berdasarkan kata kunci, ketikkan kata kunci pada kolom **Search Word** lalu klik **Search** maka aplikasi akan menampilkan
hasil pencarian tersebut:

[![Search Word](/images/modul-admin/geoportal-palapa_search-word.png)](/images/modul-admin/geoportal-palapa_search-word.png)

- Menampilkan layer peta wms, klik **Lihat Peta** maka aplikasi akan menampilkan data spasialnya secara utuh dalambentuk service wms.

[![WMS](/images/modul-admin/geoportal-palapa_wms.png)](/images/modul-admin/geoportal-palapa_wms.png)

- Mendownload data spasial utuh dalam bentuk wfs, kilik **Unduh** untuk data dengan kategori publik pengguna langsung dapat mendownload dan data langsung disimpan ke komputer personal. Untuk data dengan kategori Guvermen dan Private, pengguna harus memasukkan user dan password yang sudah terdaftar pada Simpul jaringan untuk mendapatkan data tersebut 

[![Auth](/images/modul-admin/geoportal-palapa_auth.png)](/images/modul-admin/geoportal-palapa_auth.png)

- Menampilkan metadata, klik **Metadata** maka aplikasi akan menampilkan metadata dari data yang dipilih format minimal. Untuk informasi metadata secara lengkap dapat mengklik **Metadata Lengkap**

[![metadata](/images/modul-admin/geoportal-palapa_metadata.png)](/images/modul-admin/geoportal-palapa_metadata.png)

[![metadata](/images/modul-admin/geoportal-palapa_metadata-2.png)](/images/modul-admin/geoportal-palapa_metadata-2.png)