---
title:  "Menghapus multi komentar PHP dengan notepad++"
categories: notepad++
permalink: notepad-pp-multi-replace.html
tags: [news]
---



Untuk menghapus satu atau dua komentar di dalam kode program cukup dengan menggunakan tombol delete saja sudah selesai, tapi bagaimana jika kita ingin menghapus banyak komentar yang posisinya terkadang terselip dengan kode program atau banyak file?. Jika melakukan dengan select all delete tentu semua kode program akan ikut terhapus dan apabila melakukan select satu persatu tentu akan memakan waktu. Berikut cara melakuka replace/delete dengan notepad++

![notepad++ replace](images/notepad-replace.jpg)

### Menghapus dalam satu file

Cara mendelete semua comment `/* Block Comment */` pada notepad++ :

1. Pilih search-find... (ctrl+f), pilih tab Replace
2. Search mode : regular expression
3. ketik pada find what : `/\*.*?\*/`
  `/\* artinya dimulai dari /*`
  `.*? artinya karakter apapun`
  `\*/ artinya diakhiri */`
4. kosongkan replace with
5. Klik replace.

Cara mendelete semua comment `//line comment` pada notepad++ :

1. Pilih search-find... (ctrl+f), pilih tab Replace
2. Search mode : regular expression
3. ketik pada find what : `//.*?(?=\r?$)`
  `// artinya dimulai dari //`
  `.*? artinya karakter apapun`
  `(?=\r?$) artinya diakhiri akan mencari akhir baris`
4. kosongkan replace with
5. Klik replace.

![notepad++ replace multi file](images/notepad-replace-multi-file.jpg)

### Menghapus banyak file sekaligus

Cara mendelete semua comment `/* Block Comment */` pada notepad++ :

1. Pilih search-find... (ctrl+f), pilih tab Find in Files
2. Search mode : regular expression
3. ketik pada find what : `/\*.*?\*/`
  `/\* artinya dimulai dari /*`
  `.*? artinya karakter apapun`
  `\*/ artinya diakhiri */`
4. Pilih Directory file yang akan di hapus
5. kosongkan replace with
6. Klik replace.

Cara mendelete semua comment `//line comment` pada notepad++ :

1. Pilih search-find... (ctrl+f), pilih tab Find in Files
2. Search mode : regular expression
3. ketik pada find what : `//.*?(?=\r?$)`
  `// artinya dimulai dari //`
  `.*? artinya karakter apapun`
  `(?=\r?$) artinya diakhiri akan mencari akhir baris`
4. Pilih Directory file yang akan di hapus
5. kosongkan replace with
6. Klik replace.

{% include links.html %}
