---
author: Faiq
editor: Estu
date: 2020-12-15 07:27:17+00:00
layout: post
license: CC-BY-SA-3.0
title: IRGSH-go, Perkakas Baru dari BlankOn Linux
image: /assets/posts/2020-12/rafi.jpeg
categories:
- berita
tags:
- infra

---

IRGSH merupakan perkakas untuk membangun paket dalam format Deb, kemudian menyuntikkannya dalam lumbung BlankOn. IRGSH diinisiasi oleh pengembang senior, di era Bapak Fajran, MDAMT dan Pak Aftian. IRGSH mulai aktif beroperasi pada rilis BlankOn Lontara. IRGSH mengalami kendala karena keterbatasan dukungan pustaka Python 2.6 yang sudah mulai ditinggalkan oleh para perawat pustaka Python, sehingga tidak dapat beroperasi dengan sebagaimana mestinya. Oleh karena itu para pengembang BlankOn melakukan pengembangan IRGSH sehingga lahirlah IRGSH-go.

![Siklus kerja irgsh](/assets/posts/2020-12/irgsh-flow.png){: .text-center }

Pengembangan IRGSH-go ini antara lain bertujuan agar dapat digunakan memasang paket individual secara terpisah dengan irgsh-chief, irgsh-repo, irgsh-builder, dan irgsh-cli.

IRGSH-go merupakan penulisan ulang dari irgsh lama. IRGSH (dibaca irgis) merupakan alat untuk membuat dan memelihara distribusi GNU / Linux yang diturunkan dari Debian. IRGSH dapat menjalankan tugas mulai pemaketan sampai ke lumbung, dari ISO build hingga manajemen rilis. Catatan tentang penggunaan irgish-go ditemukan pada halaman [github BlankOn](https://github.com/BlankOn/irgsh-go/).

Menurut Mohammad Anwari, salah satu pengembang senior BlankOn, nama IRGSH berasal dari rangkaian kata ir. Robot Gedek.sh. (insinyur Robot Gedek, Sarjana Hukum).

    "Dulu hanya berupa pabrik paket. Karena robot, mau dinamakan apa, ingatnya pak Robot Gedek , terdakwa kasus kriminal bertahun-tahun lalu. Kemudian robot ini berupa skrip shell, jadi harus diberi nama berkasnya: robot-gedek.sh. Tapi karena dari nama di atas ternyata mengandung gelar kesarjanaan (.sh), maka supaya komplet maka dikasih gelar Insinyur honoris causa, jadi: ir-robot-gedek.sh. Karena kepanjangan, maka disingkat jadi irgsh," demikian penuturan pak Mohammad Anwari di grup milis pengembang BlankOn.

Salam
