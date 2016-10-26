---
title:  "Vagranfile"
categories: Vagrant
permalink: vagrant-vagrantfile.html
sidebar: vagrant_sidebar
folder: vagrant
---

Fungsi utama dari `Vagrantfile` adalah untuk menggambarkan jenis mesin yang dibutuhkan untuk proyek, dan bagaimana mengkonfigurasi dan menyiapkan mesin ini. Vagrant akan menjalankan `Vagrantfile` per proyek. `Vagrantfile` portable di seluruh platform vagrant.

Karena Vagrant berbasis Ruby, `Vagrantfile` pun ditulis dengan sintaks Ruby. Pengetahuan tentang Ruby tidak begitu ditekankan karena `Vagrantfile` menggunakan variabel yang sederhana dan mudah dipahami, tapi akan sangat membantu jika mengerti Ruby.

## Mencari PATH

Ketika Anda menjalankan perintah `vagrant` ( perintah apapun itu), Vagrant akan mencari `Vagrantfile` di lokasi yang sedang berjalan (current directory) atau loaksi yang paling dekat dengan proyek. misal Anda menjalankan perintah Vagrant di linux dengan direktori `/home/zuper/proyek/vagrant-saya` berikut urutan Vagrant dalam mencari `Vagrantfile` :

```
/home/zuper/proyek/vagrant-saya/Vagrantfile
/home/zuper/proyek/Vagrantfile
/home/zuper/Vagrantfile
/home/Vagrantfile
/Vagrantfile
```

Anda dapat mengubah urutan pencarian `Vagrantfile` dengan melakukan setting variabel environment `VAGRANT_CWD`
ke dalam PATH lain.

## Load Order dan Merge Vagrantfile

Konsep penting yang harus dipahami adalah bagaimana Vagrant menjalankan atau membaca `Vagrantfile`. Sebenarnya, ada serangkaian `Vagrantfile` yang dimuat Vagrant. Setiap `Vagrantfile` berikutnya dimuat akan menimpa pengaturan yang ditetapkan sebelumnya. `Vagrantfile` yang dimuat dan urutannya adalah sebagai berikut :

1. `Vagrantfile` dari direktori gem akan dimuat. Semua ini berisi default dan tidak boleh di edit.
2. `Vagrantfile` dari direktori box akan dimuat jika box spesifik. `Vagrantfile` ini yang dikemas dengan box jika Anda menjalankan menggunakan pilihan `--vagrantfile` saat pengemasan.
3. `Vagrantfile` dari direktori home (secara default `~/.vagrant.d/) akan dimuat jika ada. `Vagrantfile` ini membolehkan Anda untuk melakukan beberapa set default yang mungkin menjadi spesifik untuk user.
4. `Vagrantfile` dari direktori proyek akan dimuat. Ini biasanya file yang sangat dekat dengan user.

Oleh karena itu, `Vagrantfile` yang ada dalam direktori proyek akan menimpa setiap konfigurasi yang bertentangan dari direktori home kemudian direktori home akan menimpa pada direktori box kemudian dirketori box akan menimpa file default jika ada konfigurasi yang berbeda maka akan digabungkan.

## Pilihan Vagrantfile

Banyak sekali pilihan yang tersedia untuk mengkonfigurasi Vagrant. Pilihan ini termasuk menentukan box yang digunakan, share folder, konfigurasi network, dan lain-lain. Semua pilihan tersedia seperti dibawah ini :

* config.nfs.map_uid        
* config.nfs.map_gid          
* config.package.name         
* config.ssh.username         
* config.ssh.host                 
* config.ssh.port              
* config.ssh.guest_port       
* config.ssh.max_tries        
* config.ssh.timeout          
* config.ssh.private_key_path 
* config.ssh.forward_agent    
* config.ssh.forward_x11      
* config.ssh.shell            
* config.vagrant.dotfile_name 
* config.vagrant.host         
* config.vm.auto_port_range   
* config.vm.base_mac          
* config.vm.boot_mode         
* config.vm.box               
* config.vm.box_url           
* config.vm.customize         
* config.vm.define            
* config.vm.forward_port      
* config.vm.guest             
* config.vm.host_name         
* config.vm.network           
* config.vm.provision         
* config.vm.share_folder      

{% include links.html %}