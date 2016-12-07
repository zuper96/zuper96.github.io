---
title: WHILE
tags: [formatting,php,while]
keywords: datatables, tables, grids, markdown, multimarkdown
last_updated: July 16, 2016
datatable: true
summary: "Struktur kontrol while"
sidebar: php_sidebar
permalink: php_while.html
folder: php
---

_WHILE_
Jika pada _keyword FOR_ kondisi perulangan harus diketahui misal 10 atau 100 kali, maka pada WHILE tidak perlu tahu kondisi akhir. Hal ini cocok untuk melakukan perulangan dengan kondisi yang belum diketahui.

Kesalahan dalam memahami logika while sering menghasilkan perulangan yang akan memproses secara terus menerus (infinity loop).

Secara umum, semua perulangan FOR bisa dikonversi menjadi perulangan WHILE. Tapi tidak sebaliknya.

Syntaks : 

```php
    while (condition)
       statement
```
sintaks diatas adalah _statement while_ sederhana. PHP akan meng-eksekusi secara berulang-ulang sepanjang _condition_ tersebut bernilai _TRUE_.

alternatif sintaks :

```php
    start;
    while (condition)
    {
        statement;
        statement;
        increment;
    }
```

atau 

```php
    while (ekspresi):
        statement
        ...
    endwhile;
```
	
### Contoh 1 :

```php

<?php

$bulan = array();
$bulan[1]	= "Januari";
$bulan[2]	= "Februari";
$bulan[3]	= "Maret";
$bulan[4]	= "April";
$bulan[5]	= "Mei";
$bulan[6]	= "Juni";
$bulan[7]	= "Juli";
$bulan[8]	= "Agustus";
$bulan[9]	= "September";
$bulan[10]	= "Oktober";
$bulan[11]	= "November";
$bulan[12]	= "Desember";

$i=1;
echo 'Hasil Contoh 1 : <br>';
while ($i <= 10) {
	echo $bulan[$i];
	
	$i++;
	echo " <br>";
}

?>
```

### Hasil : contoh 1

<pre>
Januari 
Februari 
Maret 
April 
Mei 
Juni 
Juli 
Agustus 
September 
Oktober 
</pre>

### Contoh 2 :

```php

<?php

$i = 1;
while ($i <= 10) {
    echo $i++;  
}

?>
```

### Hasil : contoh 2

<pre>
12345678910
</pre>

### Contoh 3 :

```php
<?php

$i = 1;
while ($i <= 10):
    echo $i;
    $i++;
endwhile;

?>
```

### Hasil : contoh 3

<pre>
12345678910
</pre>

{% include links.html %}
