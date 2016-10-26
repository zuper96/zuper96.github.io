---
title:  "Menambahkan Box"
categories: Vagrant
sidebar: vagrant_sidebar
permalink: vagrant-menambahkan-box.html
folder: vagrant
---

Box adalah format package untuk Environment vagrant yang berisi open virtualization format, virtual disk machine format, metadata.json dan Vagrantfile. Box juga mendukung versi sehingga Anda dan team Anda bisa melakukan update box dengan mudah, dan orang yang membuat box bisa berkomunikasi untuk saling memperbaiki.


## Mencari dan Menambahkan Box

Untuk bisa menemukan Box sangat mudah sekali, Anda tinggal mengunjungi [https://atlas.hashicorp.com/boxes/search](https://atlas.hashicorp.com/boxes/search) dan mencari box yang sesuai dengan proyek Anda. Katalog Box berisi banyak sistem operasi sebagai dasarnya, Anda juga bisa mencari Box yang sudah terpasang aplikasi LAMP, Mysql, PHP, Ruby, Phyton, dll sesuai dengan kebutuhan proyek Anda. Box yang berada pada katalog tersedia dengan berbagai provider seperti VirtualBox, VMWare, AWS, dll.

### Menambahkan Box dari katalog atlas.hashicorp.com

Untuk bisa menambahkan Box dari katalog sangat mudah. Didalam katalog ditunjukan cara menambahkannya, atau perintah di command line-nya sebagai berikut :

`vagrant box add USER/BOX`

maka secara default Vagrant akan mendownload dari URL: `https://atlas.hashicorp.com/USER/BOX` dan URL Box yang didownload biasanya https://atlas.hashicorp.com/USER/boxes/BOX/versions/VERSI/providers/virtualbox.box untuk provider VirtualBox.

### Menambahkan Box dari lokal komputer

Jika Anda punya box yang sudah didownload dari browser perintah di command line-nya seperti berikut :

`vagrant box add USER/BOX file://D:/lokasi/file.box`

Jika box berada pada direktori yang sama Anda tinggal mengetikan nama boxnya saja seperti berikit :

`varant box add USER/BOX file.box`

Jika Anda ingin mendownload box dari browser Anda bisa menggunakan url `https://atlas.hashicorp.com/USER/boxes/BOX/versions/VERSI/providers/virtualbox.box` misalnya ingin download `Ubuntu/trusty64 versi 20160926.0.1` untuk provider VirtualBox caranya salin url `https://atlas.hashicorp.com/ubuntu/boxes/trusty64/versions/20160926.0.1/providers/virtualbox.box` ke browser maka browser akan mendownload.

### Menambahkan Box dari `init`

Cara yang paling direkomendasikan adalah dengan menggunakan perintah `vagrant init USER/BOX` karena akan menginisialasi environment vagrant dengan cepat artinya Vagrantfile sudah terkonfigurasi secara otomatis pada direktori saat itu. Jika menggunakan `vagrant box add` maka perlu konfigurasi `Vagrantfile` di user root, misal `config.vm.box = "base"` diubah menjadi config.vm.box = "USER/BOX" jika tidak maka saat dijalankan (`vagrant up`) maka akan error `default: Box 'base' could not be found. Attempting to find and install...`

Jika ingin menambahkan dari lokal komputer perintahnya menjadi`vagrant init USER/BOX file://D:/lokasi/file.box` maka saat dijalankan (`vagrant up`) akan menambahkan box.


{% include links.html %}