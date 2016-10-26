---
title:  "Menampilkan Halaman Login pada PhpMyAdmin"
categories: notepad++
permalink: menampilkan-halaman-login-phpmyadmin.html
tags: [news]
---

Secara default PhpMyadmin tidak menampilkan halaman login ketika kita membuka halaman PhpmyAdmin. Untuk menampilkan halaman login kita hanya mengedit file `config.inc.php` yang berada di direktori xampp\phpMyAdmin, 

Default :

```
$cfg['Servers'][$i]['auth_type'] = ‘config’;
```

Ubah `config` menjadi `cookie` :

```
$cfg['Servers'][$i]['auth_type'] = ‘cookie’;
```

Setelah itu refresh halaman http://localhost/phpmyadmin.

Diatas hanya untuk menampilkan halaman login saja sedangkan untuk menambah user dan memberikan password bisa di tab setting `User Accounts`. Untuk menambahkan user, saya pribadi langsung dari database mysql.

{% include links.html %}
