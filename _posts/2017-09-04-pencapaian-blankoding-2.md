---
author: Humas
editor: Humas
date: "2017-09-04"
layout: post
license: CC-BY-SA-3.0
title: "Pencapaian BlanKoding 2"
image: /assets/images/omw.png
categories:
- berita
tags:
- berita
---

BlanKoding merupakan kegiatan yang dilakukan pengembang BlankOn Linux secara
bersama-sama di satu tempat untuk mengejar target-target yang telah
ditentukan, baca (hackathon | https://en.wikipedia.org/wiki/Hackathon).
BlanKoding #2 Uluwatu dilaksanakan selama 2 hari, tepatnya Sabtu dan Minggu
26-27 Agustus 2017 di kantor KodeKreatif, Bogor.

[![BlanKoding
#2](https://farm5.staticflickr.com/4378/36716776152_549a2f9543_n.jpg)](https://www.flickr.com/photos/153832225@N06/36716776152/in/album-72157685856829443/
"BlanKoding #2") [![BlanKoding
#2](https://farm5.staticflickr.com/4362/36887772675_15e27fed45_n.jpg)](https://www.flickr.com/photos/153832225@N06/36887772675/in/album-72157685856829443/
"BlanKoding #2") [![BlanKoding
#2](https://farm5.staticflickr.com/4411/36053465124_f6f4d66351_n.jpg)](https://www.flickr.com/photos/153832225@N06/36053465124/in/album-72157685856829443/
"BlanKoding #2")

  
**Berikut beberapa pekerjaan yang dapat diselesaikan ketika BlanKoding #2
Uluwatu:**  
 **\- Mengembalikan layanan ke server Alynne**  
* Memasang irgsh di Alynne. Sehingga alynne sudah bisa digunakan untuk pemaketan  
* Memasang Pabrik-cd di Alynne, Sehingga alynne sudah bisa melakukan penjahitan dan telah diatur (cron) untuk melakukan penjahitan teratur. Hasil cetakan bisa diakses di http://cdimage-dev.blankonlinux.or.id/blankon/  
* Memasang reprepro di Alynne, menarik sid harian via cron. Repo ini dapat diakses di tautan http://arsip-dev.blankonlinux.or.id/blankon/dists/  
  
 **\- Dokumentasi**  
* Wiki baru kini berbasiskan markdown menggantikan dev.boi yang lama. dev.boi yang lama dipindah ke legacy-dev.boi. (domain onprogres). Wiki dilayani menggunakan github page (jekyll + travis). Wiki bisa diakses pada tautan https://blankon.github.io/wiki. Pada halaman wiki ini masih terdapat beberapa kesalahan konten (relevansi, link dan lain lain) dan dalam proses koreksi oleh tim dokumentasi.  
  
 **\- Humas**  
* Proposal Sponsor dan Mitra akan segera rilis  
  
 **\- Kesenian**  
* Paket wallpaper, Grub sudah masuk irghs. siap dijahit  
* Pekerjaan desain Maskot menyisakan Maskot Manajer Rilis dan Jaminan Kualitas belum selesai.  
  
 **Kendala**  
\- Koneksi Internasional untuk alynne lambat, sehingga repo uluwatu di Ananda
blm bisa sepenuhnya ditarik ke alynne. Tim Infra sedang mencari jalan keluar
agar repo Uluwatu di Ananda segera tersalin.  
  
 **Garis Besar Pengembangan**  
  
Tahapan rilis Uluwatu kali ini sangat meleset dari target awal. Di awal
perjalanan Uluwatu, pengembang berkonsentrasi pada pelayanan Infrastruktur
dengan target mampu mereproduksi infra dan layanan yang ada di BlankOn Linux.
Hal ini dikarenakan minimnya dokumentasi dan penurunan catatan dari
pengembang-pengembang awal ke tim pengembangan selanjutnya.  
  
 **Fase Nol | Upgrade mesin mesin blankon**  
\- Penambahan Hardisk 2TB ke Wajinah  
\- Penambahan Hardisk 4TB ke Rani  
\- Penambahan Procesor ke Alynne  
\- Pemasangan Ram ke Alynne | kondisi alyne, 2 CPU, 8 Core, 16GB  
\- Inisiasi Ananda | Digital Ocean 4Core 4GB, 350GB SSD (Repo)  
 **Fase Satu | Riset uji coba replika layanan Blankon  
Fase Dua | Reinstall Alynne dan mengembalikan layanan awal  
Fase Tiga | Reinstall Rani dan mengembalikan layanan awal (On Progress)**  
  
Dari itu proses ini diawali dengan pembuatan server baru ananda.boi untuk uji
coba mereplika layanan IRGSH, Reprepro, dan Pabrik-CD. Setelah ini berjalan,
dilanjutkan dengan pemasangan ulang sistem operasi di Alynne, dan
mengembalikan layanan yang dulu pernah berjalan di Alynne.  
  
Demikian laporan ini kami tulis.  
  
Salam hangat  
  
\- Estu Fardani -


    