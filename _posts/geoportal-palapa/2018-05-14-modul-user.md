---
date: 2018-05-14
title: Modul User Geoportal Palapa
categories:
  - geoportal-palapa
description: Petunjuk pemakaian modul user geoportal palapa
type: Document
---

## PENDAHULUAN

Badan Informasi Geospasial (BIG) yang berperan sebagai penghubung simpul jaringan Informasi Geospasial memiliki kewajiban untuk membina Kementerian, Lembaga, Pemerintah Daerah Tingkat I (Provinsi) dan Pemerintah Daerah Tingkat II (Kabupaten/kota) dalam mengembangkan dan membangun simpul jaringan. Kendala
dan keterbatasan yang sering ditemukan dalam pengembangan dan pembinaan simpul jaringan di daerah terletak pada minimnya infrastruktur dan koneksi jaringan internet. Kondisi tersebut tentu saja merupakan tantangan dan kesulitan tersendiri bagi BIG dalam melakukan pengembangan dan pembinaan simpul jaringan. 

BIG saat ini sedang membangun JIGN (Jaringan Informasi Geospasial Nasional). Untuk mendukung ini, maka disediakan aplikasi – aplikasi yang akan dijalankan pada simpul jaringan untuk mendukung terwujudnya JIGN secara utuh. Tidak semua simpul jaringan memiliki dana untuk membangun environment pengembangan simpul jaringan, oleh karena itu BIG menyediakan solusi aplikasi berbasis opensource.

Aplikasi PALAPA yang dikembangan saat ini sebagai fasilitas penghubung simpul jaringan Informasi Geospasial. Aplikasi PALAPA ini dibangun semudah mungkin dengan dilengkapi user interface yang user friendly, sehingga administrator maupun member tidak akan mengalami kesulitan dalam pengoperasiannya.

## MANAJEMEN DATA

Manajemen dataset dapat dilakukan oleh administrator ataupun member yang ada di setiap grup. Masing-masing pengguna mempunyai kewenangan berbeda. Pada sistem PALAPA pengguna administrator selain dapat melakukan konfigurasi sistem juga dapat melakukan manajemen dataset mulai dari upload, delete sampai dengan publishing data. Sedangkan untuk pengguna member hanya diberikan kewenangan untuk upload
data pada database Pengembangan (DEV), melihat dan mendownload data pada database Pengembangan, Produksi, maupun Publikasi.

## PENGGUNA MEMBER

Pengguna dalam kategori member pada setiap grup/SKPD adalah pengguna yang mempunyai akses atau kewajiban untuk melakukan unggah/upload data spasial maupun metdatanya ke dalam sistem PALAPA. Data yang diunggah ke dalam sistem merupakan data hasil kegiatan di masing-masing SKPD baik yang sudah final maupun
masih data sementara. Data-data tersebut akan tersimpan dalam database Pengembangan (DEV). Data yang sudah final dapat diduplikasikan ke sistem database produksi untuk diberbagi data ke SKPD yang lain maupun di publikasi ke publik oleh Pengguna admin/publisher.

[![Pengguna Member](/images/modul-user/geoportal-palapa_pengguna-member.png)](/images/modul-user/geoportal-palapa_pengguna-member.png)

Pada dashboard pengguna member terdapat fasilitas untuk melihat dan melakukan copy data (download) dari grup/SKPD lain dalam satu Simpul Jaringan yaitu melalui menu Database Produksi (PROD). Selain di database, pengguna member juga dapat melihat data-data yang telah ada di Geoserver dalam bentuk service baik spasial maupun metadatanya.

Berikut diuraikan beberapa fungsi yang terdapat pada dashboard aplikasi PALAPA untuk pengguna member;

### 1. Unggah Data KUGI

- Format data : shp
- Format file : zip yang terdiri dari minimal extention (.dbf, .prj, .shp, .shx), nama zip file harus sama dengan nama shpnya, misal: semak.shp, maka nama filenya menjadi semak.zip. Untuk data KUGI ada 3 field pada data yang akan diupload harus terisi dengan benar yaitu; FCODE, SRS_Id, dan Metadata, apabila salah satu field tersebut kosong, maka data tidak dapat diupload ke dalam sistem.

[![Data Zip](/images/modul-user/geoportal-palapa_data-zip.png)](/images/modul-user/geoportal-palapa_data-zip.png)

Skema data : KUGI Versi. 4 (Lihat dokumen di http://kugi.ina-sdi.or.id/)

Langkah-langkah yang dilakukan yaitu;

- Pilih menu **Pengembangan (DEV)**

[![Pengembangan DEV](/images/modul-user/geoportal-palapa_pengembangan-dev.png)](/images/modul-user/geoportal-palapa_pengembangan-dev.png)

- Klik tombol **Unggah Data**

[![Unggah Data](/images/modul-user/geoportal-palapa_unggah-data.png)](/images/modul-user/geoportal-palapa_unggah-data.png)

- Lakukan pemilihan skala, kategori, fitur, dan pilih data spasial yang akan di upload dengan klik icon **Choose File**

[![Upload File](/images/modul-user/geoportal-palapa_upload-file.png)](/images/modul-user/geoportal-palapa_upload-file.png)

[![File Uploaded](/images/modul-user/geoportal-palapa_file-uploaded.png)](/images/modul-user/geoportal-palapa_file-uploaded.png)

- Apabila data berhasil diunggah, akan muncul windows

[![Upload Berhasil](/images/modul-user/geoportal-palapa_upload-berhsil.png)](/images/modul-user/geoportal-palapa_upload-berhsil.png)

- Pada menu Informasi Data Constrain pilih Public, Goverment, atau Private
- Unggah metada dari data yang telah berhasil di unggah dengan klik icon **Choose File** pilih file metadata dalam format xml dari komputer lalu klik Open

[![Open File](/images/modul-user/geoportal-palapa_open-file.png)](/images/modul-user/geoportal-palapa_open-file.png)

- Apabila data berhasil diunggah, akan muncul windows

[![Uploaded Sukses](/images/modul-user/geoportal-palapa_upload-suskse.png)](/images/modul-user/geoportal-palapa_upload-suskse.png)

### 2. Unggah Data Usulan KUGI

- Format data : shp
- Format file : zip yang terdidri dari minimal extention (.dbf, .prj, .shp, .shx), nama zip file harus sama dengan nama shp-nya, misal: jalan_semarang.shp, maka nama filenya menjadi jalan_semarang.zip
- Skema data : bebas

Langkah-langkah yang dilakukan yaitu;

- Pilih menu **Pengembangan (DEV)**

[![Pengembangan DEV](/images/modul-user/geoportal-palapa_pengembangan-dev-2.png)](/images/modul-user/geoportal-palapa_pengembangan-dev-2.png)

- Klik tombol **Unggah Data**

[![PUnggah Data 2](/images/modul-user/geoportal-palapa_unggah-data-2.png)](/images/modul-user/geoportal-palapa_unggah-data-2.png)

- Klik menu **Unggah Usulan KUGI** maka akan muncul tampilan progres sebagai berikut:

[![Tambah Layer](/images/modul-user/geoportal-palapa_tambah-layer.png)](/images/modul-user/geoportal-palapa_tambah-layer.png)

- pilih data spasial yang akan di upload dengan klik icon **Choose Files** pada baris **Pilih Berkas (ZIP)**

[![Berkas ZIP](/images/modul-user/geoportal-palapa_berkas-zip.png)](/images/modul-user/geoportal-palapa_berkas-zip.png)

sistem akan otomatis mengunggah data ke sistem database. Setelah selesai akan muncul tampilan notifikasi

[![Notifikasi](/images/modul-user/geoportal-palapa_notifikasi.png)](/images/modul-user/geoportal-palapa_notifikasi.png)

- Klik **Lanjut** untuk progres tahap 2

[![Tambah Layer 2](/images/modul-user/geoportal-palapa_tambah-layer-2.png)](/images/modul-user/geoportal-palapa_tambah-layer-2.png)

- Klik **Simpan Layer** maka jika berhasil data akan langsung dibuatkan service di Geoserver untuk kepentingan publikasi.

[![Layer Tersimpan](/images/modul-user/geoportal-palapa_layer-tersimpan.png)](/images/modul-user/geoportal-palapa_layer-tersimpan.png)

- Selanjutnya klik **Lanjut** untuk progres tahap 3

[![Tahap 3](/images/modul-user/geoportal-palapa_tahap-3.png)](/images/modul-user/geoportal-palapa_tahap-3.png)

- Jika memilih Minimal pada menu Tipe Metadata, maka langsung klik **Simpan Metadata**
- Apabila memilih Unggah Metadata, maka tampilannya sebagai berikut:

[![Tambah Layer Lagi](/images/modul-user/geoportal-palapa_tambah-layer-lagi.png)](/images/modul-user/geoportal-palapa_tambah-layer-lagi.png)

- Klik **Choose File** pada menu Pilih Berkas (XML)

[![Pilih File](/images/modul-user/geoportal-palapa_pilih-file.png)](/images/modul-user/geoportal-palapa_pilih-file.png)

- Klik **Simpan Metadata** maka akan muncul tampilan notifikasi

[![Upload Metadata](/images/modul-user/geoportal-palapa_upload-metadata.png)](/images/modul-user/geoportal-palapa_upload-metadata.png)

- Klik **Selesai** maka akan muncul tampilan Layer Spasial

[![Layer Spasial](/images/modul-user/geoportal-palapa_layer-spasial.png)](/images/modul-user/geoportal-palapa_layer-spasial.png)

### 3. Manajemen Database Skema KUGI

Data yang telah diunggah melalui aplikasi PALAPA akan disimpan pada database Pengembangan (DEV). Data tersebut merupakan data milik grup/SKPD yang mengunggah data. Pengguna dapat melakukan manajemen melalui menu Database Pengembangan (DEV) sebagai berikut;

[![Manajemen Database](/images/modul-user/geoportal-palapa_manajemen-database.png)](/images/modul-user/geoportal-palapa_manajemen-database.png)

- Melihat metadata, klik icon **i**, maka akan muncul windows:

[![Berkas Metadata](/images/modul-user/geoportal-palapa_berkas-metadata.png)](/images/modul-user/geoportal-palapa_berkas-metadata.png)

- Mengupload ulang metadata apabila ada perbaikan, klik icon , maka akan muncul windows. lakukan tahapan seperti saat melakukan unggah data.

[![Upload Ulang](/images/modul-user/geoportal-palapa_upload-ulang.png)](/images/modul-user/geoportal-palapa_upload-ulang.png)

- Migrasi data ke database Produksi (PROD), klik icon , maka akan muncul windows

[![Migrasi Data](/images/modul-user/geoportal-palapa_migrasi-data.png)](/images/modul-user/geoportal-palapa_migrasi-data.png)

- Menghapus data, klik icon **x**, maka akan muncul windows

[![Hapus Dataset](/images/modul-user/geoportal-palapa_hapus-dataset.png)](/images/modul-user/geoportal-palapa_hapus-dataset.png)

- Download data, pilih menu Database Produksi (PROD), kili icon , maka secara otomatis data akan tersimpan ke komputer personal.

### 4. Manajemen Data Usulan Skema KUGI

Berbeda dengan manajemen database skema KUGI, data usulan KUGI yang telah diunggah akan disimpan pada database tersendiri berdasarkan grup/SKPD yang mempunyai data. Manajemen data yang dapat dilakukan adalah melalui service data tersebut yang sudah ada di Geoserver. Manajemen tersebut dapat dilakukan
pada menu Publikasi - Layer Spasial.

[![Manajemen Data](/images/modul-user/geoportal-palapa_hmanajemen-data.png)](/images/modul-user/geoportal-palapa_hmanajemen-data.png)

fungsi yang ada pada menu ini antara lain;

- Melihat data, pilih data yang akan dilihat, klik icon  maka akan muncul windows

[![Peta Jalan](/images/modul-user/geoportal-palapa_peta-jalan.png)](/images/modul-user/geoportal-palapa_peta-jalan.png)

- Memperbaharui informasi data, klik icon  maka akan muncul windows.

[![Peta Jalan 2](/images/modul-user/geoportal-palapa_peta-jalan-2.png)](/images/modul-user/geoportal-palapa_peta-jalan-2.png)

- Setelah layar diedit, klik **Simpan** maka akan muncul notifikasi sebagai berikut:

[![Notifikasi Edit](/images/modul-user/geoportal-palapa_notifikas-edit.png)](/images/modul-user/geoportal-palapa_notifikas-edit.png)

## APLIKASI PALAPA UNTUK PENGGUNA UMUM

Aplikasi PALAPA memiliki dua sisi aplikasi yaitu aplikasi front-end yang ditujukan bagi pengguna dan aplikasi back-end (CMS) yang ditujuan bagi pengelola aplikasi. Aplikasi untuk backend diuraikan pada Bab 2 dan 3, sedangkan aplikasi untuk fornt-end atau pengguna umum terdapat 3 menu utama yaitu; [a] menu beranda, [b] menu jelajah, dan [c] menu cari. Menu beranda aplikasi PALAPA menyajikan penjelasan umum dari aplikasi PALAPA dan geoportal PALAPA. Menu jelajah aplikasi PALAPA menyajikan viewer webGIS aplikasi yang dilengkapi dengan pemilihan peta dasar dan pemeilihan layer peta yang ingin ditampilkan disamping tool navigasi setandar untuk sebuah aplikasi webGIS. Sedangkan menu cari aplikasi PALAPA merupakan fitur pencarian dataset yang ada pada geoportal PALAPA. 

### 1. Menu Beranda

Menu beranda aplikasi PALAPA memuat informasi tentang aplikasi Geoportal PALAPA terdiri dari arti PALAPA itu sendiri, Pengguna, Administrator, Pengembang, dan Kontak. Untuk melihat seluruh halaman beranda dapat dilakukan dengan scrolling pada browser.

[![Beranda](/images/modul-user/geoportal-palapa_beranda.png)](/images/modul-user/geoportal-palapa_beranda.png)
[![Beranda 2](/images/modul-user/geoportal-palapa_beranda-2.png)](/images/modul-user/geoportal-palapa_beranda-2.png)
[![Beranda 3](/images/modul-user/geoportal-palapa_beranda-3.png)](/images/modul-user/geoportal-palapa_beranda-3.png)
[![Beranda 4](/images/modul-user/geoportal-palapa_beranda-4.png)](/images/modul-user/geoportal-palapa_beranda-4.png)

### 2. Menu Jelajah

Menu Jelajah merupakan menu yang dapat digunakan oleh pengguna umum untuk melihat data-data spasial yang dapat diakses melalui browser webGIS yang dibangun dengan framework OpenLayer. Pada menu jelajah pengguna
memilih peta dasar, menampilkan layer data spasial, melakukan navigasi.

[![Menu Jelajah](/images/modul-user/geoportal-palapa_menu-jelajah.png)](/images/modul-user/geoportal-palapa_menu-jelajah.png)

## Memilih Peta Dasar

- Klik **Peta Dasar** dibawah pojok kiri, maka akan muncul windows

[![Peta Dasar](/images/modul-user/geoportal-palapa_peta-dasar.png)](/images/modul-user/geoportal-palapa_peta-dasar.png)

- Secara default aplikasi PALAPA menampilkan peta dari OSM Standar. Untuk mengganti dengan peta dasar lainnya (Rupabumi Indonesia) klik pada peta yang diinginkan, maka peta dasar langsung berubah.

[![Peta Dasar Berubah](/images/modul-user/geoportal-palapa_peta-dasar-berubah.png)](/images/modul-user/geoportal-palapa_peta-dasar-berubah.png)

## Menampilkan Layer

- Klik **Layer** maka akan muncul tampilan windows

[![Tampil Layer](/images/modul-user/geoportal-palapa_tampil-layer.png)](/images/modul-user/geoportal-palapa_tampil-layer.png)

- Layer aktif dan di visualisasikan pada peta

[![Layer Aktif](/images/modul-user/geoportal-palapa_layer-aktif.png)](/images/modul-user/geoportal-palapa_layer-aktif.png)

- Sedangkan layer aktif tidak ditampilkan di peta

[![Layer Tidak Aktif](/images/modul-user/geoportal-palapa_layer-tidak-aktif.png)](/images/modul-user/geoportal-palapa_layer-tidak-aktif.png)

- Zoom in layer aktif, klik , maka windows akan membesar ke layer yang dipilih.

[![Zoom In](/images/modul-user/geoportal-palapa_zoom-in.png)](/images/modul-user/geoportal-palapa_zoom-in.png)

- Mengaktif dan non aktifkan fungsi identify, klik **i**
- Menghapus layer dari peta, klik
- Memindahkan posisi layer, klik 
- Mengaktifkan layer di peta, klik 
- Menambahkan layer, klik **Tambahkan Layer** pilih server yang menyediakan service.

[![Layer Service](/images/modul-user/geoportal-palapa_layer-service.png)](/images/modul-user/geoportal-palapa_layer-service.png)

[![Layer Service 2](/images/modul-user/geoportal-palapa_layer-service-2.png)](/images/modul-user/geoportal-palapa_layer-service-2.png)

- Klik tanda **+** pada layer yang ingin ditampilkan pada peta, lalu klik **Selesai**

[![Peta](/images/modul-user/geoportal-palapa_peta.png)](/images/modul-user/geoportal-palapa_peta.png)

## Fungsi Navigasi

- **+ Zoom In** Memperbesar tampilan peta pada area tertentu
- **- Zoom Out** Memperkecil tampilan peta pada area tertentu
- **Full Extent**  Menampilkan peta pada extent yang sudah ditetapkan
- **Identifikasi** Identifikasi pada layer aktif
- **Ukur** Mengukur jarak pada peta
- **Legenda** Melampirkan Legenda pada layer aktif
- **Opacity** Mengatur transparasi pada layer aktif

### 3. Menu Cari

Menu Cari merupakan menu yang berfungsi sebagai katalog metadata. Pada menu ini pengguna dapat melakukan pencarian data berdasarkan kata kunci yang terdapat pada metadata ataupun berdasarkan wilayah cakupan. Pada halaman ini akan ditampilkan data-data yang sudah di publikasi pada satu Simpul Jaringan. Adapun fungsi yang terdapat pada menu ini adalah;

[![Menu Cari](/images/modul-user/geoportal-palapa_menu-cari.png)](/images/modul-user/geoportal-palapa_menu-cari.png)

- Mencari data berdasarkan kata kunci, ketikkan kata kunci pada kolom **Search word** lalu klik **Search** maka aplikasi akan menampilkan hasil pencarian tersebut:

[![Keyword](/images/modul-user/geoportal-palapa_mkeyword.png)](/images/modul-user/geoportal-palapa_mkeyword.png)

- Menampilkan layer peta wms, klik **Lihat Peta** maka aplikasi akan menampilkan data spasialnya secara utuh dalam bentuk service wms.

[![Service WMS](/images/modul-user/geoportal-palapa_service-wms.png)](/images/modul-user/geoportal-palapa_service-wms.png)

- Mendownload daa spasial utuh dalam bentuk wfs, klik **Unduh** untuk data dengan kategori publik pengguna langsung dapat mendownload dan data langsung disimpan ke komputer personal. Untuk data dengan kategori Guvermen dan Private, pengguna harus memasukkan user dan password yang sudah terdaftar pada Simpul Jaringan untuk mendapatkan data tersebut

[![Auth](/images/modul-user/geoportal-palapa_auth.png)](/images/modul-user/geoportal-palapa_auth.png)

- Menampilkan metadata, klik **Metadata** maka aplikasi akan menampilkan metadata dari data yang dipilih dalam format minimal. Untuk informasi metadata secara lengkap dapat mengklik **Metadata Lengkap**

[![Metadata Lengkap](/images/modul-user/geoportal-palapa_metadata-lengkap.png)](/images/modul-user/geoportal-palapa_metadata-lengkap.png)

[![Metadata Lengkap](/images/modul-user/geoportal-palapa_metadata-lengkap-2.png)](/images/modul-user/geoportal-palapa_metadata-lengkap-2.png)