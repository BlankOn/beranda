---
author: Herpiko Dwi Aguno
date: 2020-11-20 19:27:17+00:00
layout: post
license: CC-BY-SA-3.0
title: Kunjungan Fisik Waljinah
image: /assets/images/omw.png
categories:
- Announcements
tags:
- infrastructure

---

Waljinah merupakan salah satu dari beberapa mesin yang dirawat oleh proyek BlankOn. Berdasarkan catatan resmi yang ada di wiki, mesin ini merupakan donasi dari ID-SIRTII (sekarang bagian dari Badan Sandi dan Siber Negara). Colocation dan bandwithnya disponsori oleh Soerabaia Networks (sekarang mesinnya dikoordinasikan di bawah manajemen Wheehost).


### Kunjungan pertama

Setelah bebeberapa bulan mesin Waljinah dan layanan-layanan yang menyertainya mati, akhirnya Tim Pengembang berkesempatan melakukan kunjungan ke data center di gedung Tifa, Jakarta, untuk menjenguk mesin Waljinah pada 27 Oktober 2020. Tim Pengembang yang diutus adalah Estu Fardani (@tuanpembuan) dan Herpiko Dwi Aguno (@herpiko) dengan surat pengantar dari Slamet Santoso (Koordinator Humas).

![97324317-4b2ee600-18a4-11eb-858d-5fcd0492c7a0](https://user-images.githubusercontent.com/2534060/99906181-3c531c00-2d08-11eb-9839-9aca6bb3fc65.jpg)
Penampakan Waljinah saat dijenguk.

Setelah diperiksa tim menemukan beberapa isu, yaitu mesin tidak mengirim sinyal ke layar monitor setelah proses boot selesai di initramfs dan konesksi jaringan mesin tidak stabil saat mesin dikembalikan ke rak. Staf dari data center membantu tim BlankOn untuk menggantikan kabel jaringannya dan memastikan koneksi kembali stabil.

Tim lalu membawa SSD dan HDD Waljinah untuk mengupgrade sistem operasinya dari Wheezy sampai ke Stretch. Setelah diupgrade, SSD dan HDD dikembalikan dan dipasangkan kembali ke mesin. 

Setelah dipastikan semua berjalan lancar, tim meninggalkan data center. Dalam perjalanan pulang, didapati Waljinah tidak dapat lagi diakses.

### Kunjungan kedua

Pada 7 November 2020, BlankOn kembali mengutus tim yang sama dengan tujuan mengecek kembali Waljinah dan mengupgrade SSD waljinah dari 32GB ke 128GB. Upgrade SSD dilakukan dengan mengkloning secara penuh dan pemasangan ulang bootloader.

![98463958-fc614480-21f1-11eb-9e24-6a772acd405d](https://user-images.githubusercontent.com/2534060/99906564-67d70600-2d0a-11eb-83e4-e47e86713fe0.jpg)
SSD lama Waljinah yang berukuran 32GB.

Setelah investigasi intensif ditemukan bahwa penyuplai daya (power supply) mesin di rak peladen tidak berfungsi dengan benar, yang mengakibatkan HDD tidak dikenali dan sistem tidak dapat diboot. Karena permasalahan di luar kuasa tim, tim berkoordinasi dengan sponsor dan tindak lanjut diambil alih oleh sponsor.

Esoknya, sponsor mengabarkan bahwa Waljinah telah hidup namun kemudian kembali bermasalah setelah kurang dari 24 jam. Kesimpulan dari sponsor, permasalahan terletak pada mesin (motherboard).

### Penggalangan donasi

Setelah dilakukan rapat pengembang, tim pengembang tergerak untuk melakukan pendekatan ulang ke beberapa sponsor utama yang ada saat ini serta melakukan penggalangan dana untuk membuka peluang donasi individual.

Urunan/penggalangan dana dilakukan di Kitabisa.com, silakan kunjungi di [pranala berikut ini](https://kitabisa.com/campaign/urunanpengembanganblankon).

Apakah Waljinah akan mendapatkan rumah baru atau bahkan dipensiunkan lalu digantikan oleh mesin baru? Nantikan cerita berikutnya di blog ini.

