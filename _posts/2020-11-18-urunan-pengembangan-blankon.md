---
author: Estu
editor: Herpiko
date: 2020-11-18 19:27:17+00:00
layout: post
license: CC-BY-SA-3.0
title: Urunan Pengembangan BlankOn
image: /assets/posts/2020-12/boni.png
categories:
- berita
tags:
- humas

---

![](/assets/posts/2020-12/boni.png){: .text-center .img-responsive }

Hallo Pengguna BlankOn!

Tim Pengembang BlankOn memutuskan untuk membuka kanal donasi untuk pengembangan BlankOn melalui media KitaBisa.com. Silahkan menuju halaman [kitabisa.com](https://kitabisa.com/campaign/urunanpengembanganblankon) untuk mulai berdonasi.

# Sekilas BlankOn Linux

BlankOn Linux merupakan salah satu distribusi GNU/Linux berisikan perangkat lunak legal yang dapat digunakan untuk keperluan desktop, laptop, dan workstation serta dirancang sesuai dengan kebutuhan penggunaan komputer umum di Indonesia. BlankOn Linux merupakan bagian dari proyek BlankOn yang memiliki tujuan yang lebih luas lagi, yakni mengembangkan kompetensi sumber daya manusia  Indonesia dalam konteks perangkat lunak bebas dan terbuka.

Saat ini Proyek BlankOn sedang  mengembangkan versi terbaru dengan nama kode Verbeek yang akan dirilis pada 2021 dengan tim baru dan semangat baru. Tim sempat vakum beberapa waktu karena keterbatasan waktu, sumber daya manusia, dan sumberdaya mesin. Tim kembali menggeliat sejak awal Oktober 2020.

# Progres Terkini
## Modernisasi Infrastruktur

Tim pengembang telah melakukan modernisasi pada sebagian besar infrastruktur yang ada dengan memperbarui sistem, mengadopsi teknologi-teknologi baru terutama dari Cloud Native (container, envoy), implementasi dinding api (dingap/firewall dengan csf dan tendang) dan manajemen akses yang lebih baik. Beberapa mesin dari infrastruktur BlankOn perlu peremajaan untuk mendukung keberlangsungan proyek ke depan.

## Penulisan Ulang Pabrik paket IRGSH
IRGSH adalah nama layanan pembuatan paket khas di blankon. Pertama kali ditulis menggunakan Python 2.6 pada tahun 2009, kemudian terus dirawat dan membantu proses pengembangan hingga rilis BlankOn Uluwatu. Namun tak lama setelahnya IRGSH gagal bekerja kembali akibat keterbatasan kompatibilitas dengan sistem operasi terkini.

Dengan beberapa pertimbangan, tim pengembang telah memutuskan menulis ulang pabrik paket IRGSH dalam bahasa Go. IRGSH, yang selama ini menjadi tulang punggung pengembangan distribusi BlankOn Linux, kini lebih mudah digunakan dan dipelihara. Saat ini IRGSH versi penulisan ulang (selanjutnya disebut dengan irgsh-go) telah memasuki versi beta dan sedang dalam pengembangan dan pengujian yang intensif.

Irgsh-go memiliki beberapa komponen dengan fungsi yang berbeda-beda, antara lain sebagai perkakas CLI (command line interface) pemaket, pabrik pembangun paket, manajemen kunci GPG pemaket, serta manajemen lumbung paket (repository). Beberapa komponen tersebut di-deploy ke mesin yang berbeda-beda.

## Pabrik Penjahit ISO BlankOn
Penjahitan ISO distribusi saat ini menggunakan perkakas live-build sebagai pengganti perkakas pabrik cd warisan rilis sebelumnya yang sudah tidak dipelihara dan sudah ditinggalkan. Adopsi live-build adalah salah satu proses transisi tim pengembang untuk mengikuti protokol dan standar pengembangan distribusi turunan Debian. Dengan menggunakan live-build, distribusi BlankOn Linux kesempatan yang sama atas akses terhadap teknologi-teknologi baru yang dipakai pada distribusi modern turunan Debian lainnya seperti Ubuntu, PopOS, Elementary dan lainnya. Keluaran dari riset ini adalah konfigurasi final bagaimana BlankOn Verbeek dijahit menggunakan perkakas live-build.

Salam,  
Tim Pengembang BlankOn
