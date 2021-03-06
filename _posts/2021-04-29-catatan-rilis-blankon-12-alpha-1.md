---
author: Samsul Ma'arif
editor: Rania
date: "2021-04-29"
layout: post
license: CC-BY-SA-3.0
title: "Catatan Rilis BlankOn 12 Alpha-1"
image: /assets/images/boni-pose3.png
categories:
- berita
tags:
- berita
---

Salam untuk para pecinta Linux dan pejuang perangkat lunak bebas dan terbuka!

Tepat pada hari ke-17 Ramadhan tahun 1442 H atau bertepatan dengan tanggal 29 April 2021 M, kami para pengembang BlankOn, secara resmi meluncurkan rilis Alpha-1. Pada rilis ini pengembang BlankOn hanya meluncurkan untuk arsitektur amd64 versi pengembangan yang ditujukan untuk pengujian dan pengguna ahli. Karena merupakan versi pengembangan, masih akan ditemukan banyak kutu untuk diperbaiki pada rilis pengembangan versi berikutnya.

![verbeek_29_04_2021_08_26_02](https://user-images.githubusercontent.com/1231314/116491661-98782880-a8c4-11eb-8076-15db8c0d9460.png)

Berkas ISO untuk Alpha-1 ini dapat diunduh di: <https://cdimage.blankonlinux.or.id/blankon/rilis/verbeek/Alpha-1/>

Daftar masalah yang diketahui pada rilis Alpha-1 ini dapat dibaca di <https://github.com/BlankOn/Verbeek/labels/Jahitan>

Apabila menemukan masalah pada Rilis Alpha-1 BlankOn 12 Verbeek, silakan laporkan melalui <https://lapor.blankon.id>

Beberapa catatan untuk rilis Alpha-1 kali ini:

- Para pengembang menggunakan alat pengembangan [irgsh-go](https://blankon.id/berita/2020/12/15/irgsh-perkakas-blankon.html) yang merupakan penulisan ulang dari awal ([rewrite from scratch](https://github.com/BlankOn/irgsh-go/#why-rewrite-it)) dari IRGSH (dibaca irgis) lama.
- Untuk meracik berkas ISO Alpha-1 ini dan seterusnya, para pengembang BlankOn menggunakan [live-build](https://github.com/BlankOn/blankon-live-build).
- Lingkungan desktop menggunakan GNOME 3.38.5
- Installer menggunakan Calamares #168
- Menyertakan ekstensi desktop pop-shell #154

Untuk saaat ini, kami TIDAK MENYARANKAN pengguna BlankON meng-upgrade sistem dari BlankOn 11 Uluwatu ke versi ini karena versi ini masih tahap awal pengembangan.

Target untuk rilis pengembangan berikutnya adalah:

- Menambah dukungan untuk UEFI
- Implementasi branding BlankOn
- Perbaikan kutu yang ditemukan pada Alpha-1

Plt. Manajer Rilis BlankOn,

Samsul Ma'arif
