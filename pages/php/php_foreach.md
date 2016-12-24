---
title: FOREACH
tags: [formatting,php,foreach]
keywords: datatables, tables, grids, markdown, multimarkdown
last_updated: July 16, 2016
datatable: true
summary: "Struktur kontrol FOREACH"
sidebar: php_sidebar
permalink: php_foreach.html
folder: php
---

_FOREACH_ adalah perulangan yang khusus menangani semua data _array_.

Perulangan _foreach_ otomatis dijalankan sebanyak element yang ada di dalam _array_.

sintaksnya :

```php
    foreach ($data as $value){
    	statement ... $value ...
    }
```
atau

```php
    foreach ($data as $index => $value){
    	statement ... $key ... $value ...
    }
```
	
### Contoh 1 :

```php

<?php
// Data Bulan dalam Array
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

// Menampilkan data
foreach ($bulan as $nama) {
	echo $nama;
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
November 
Desember 
</pre>


### Contoh 2 :

```php

// Data masih sama dengan contoh 1

echo 'Hasil Contoh 2 : <br>';
foreach ($bulan as $index => $namaBulan) {
	echo "Bulan ke - $index adalah $namaBulan";
	echo " <br>";
}
```

### Hasil : contoh 2

<pre>
Bulan ke - 1 adalah Januari 
Bulan ke - 2 adalah Februari 
Bulan ke - 3 adalah Maret 
Bulan ke - 4 adalah April 
Bulan ke - 5 adalah Mei 
Bulan ke - 6 adalah Juni 
Bulan ke - 7 adalah Juli 
Bulan ke - 8 adalah Agustus 
Bulan ke - 9 adalah September 
Bulan ke - 10 adalah Oktober 
Bulan ke - 11 adalah November 
Bulan ke - 12 adalah Desember 
</pre>

### Contoh 3 :

```php
<?php

$bulan = array();
$bulan[01]	= "Januari";
$bulan[02]	= "Februari";
$bulan[03]	= "Maret";
$bulan[04]	= "April";
$bulan[05]	= "Mei";
$bulan[06]	= "Juni";
$bulan[07]	= "Juli";
$bulan[08]	= "Agustus";
$bulan[09]	= "September";
$bulan[10]	= "Oktober";
$bulan[11]	= "November";
$bulan[12]	= "Desember";

// Menampilkan data
echo 'Hasil Contoh 3 : <br>';
foreach ($bulan as $nama) {
	echo $nama;
	echo " <br>";
}

?>
```

### Hasil : contoh 3

<pre>
Januari 
Februari 
Maret 
April 
Mei 
Juni 
Juli 
September 
Oktober 
November 
Desember 
</pre>

Harapannya adalah bulan Agustus dan September ditampilkan ternyata tidak ada, kenapa?
angka 0 di depan menandakan bahwa index menggunakan bilangan octal (0-7) sedangkan 8 dan 9 bukan bilangan octal.

### Contoh 4 (dua dimensi) :

```php
<?php
$queryrows = array();
$queryrows[0]["language_id"] = "2";
$queryrows[0]["name"] = "Bahasa Indonesia";
$queryrows[0]["code"] = "id";
$queryrows[0]["locale"] = "id_ID.UTF-8,id_ID,id-id,Indonesia";
$queryrows[0]["image"] = "id.png";
$queryrows[0]["directory"] = "indonesia";
$queryrows[0]["sort_order"] = "1";
$queryrows[0]["status"] = "1";

foreach ($queryrows as $result) {
	$languages[$result['code']] = $result;
}

echo '<pre>';
var_dump ($queryrows);
echo '</pre>';
echo '============= <br>';
echo '<pre>';
var_dump ($languages);
echo '</pre>';
?>
```

### hasil : Contoh 4

<pre>
array(1) 
{
  [0]=>  array(8) 
  {
    ["language_id"]=>    string(1) "2"
    ["name"]=>    string(16) "Bahasa Indonesia"
    ["code"]=>    string(2) "id"
    ["locale"]=>    string(33) "id_ID.UTF-8,id_ID,id-id,Indonesia"
    ["image"]=>    string(6) "id.png"
    ["directory"]=>    string(9) "indonesia"
    ["sort_order"]=>    string(1) "1"
    ["status"]=>    string(1) "1"
  }
}
=============
array(1) {
  ["id"]=>  array(8) 
  {
    ["language_id"]=>    string(1) "2"
    ["name"]=>    string(16) "Bahasa Indonesia"
    ["code"]=>    string(2) "id"
    ["locale"]=>    string(33) "id_ID.UTF-8,id_ID,id-id,Indonesia"
    ["image"]=>    string(6) "id.png"
    ["directory"]=>    string(9) "indonesia"
    ["sort_order"]=>    string(1) "1"
    ["status"]=>    string(1) "1"
  }
}
</pre>

{% include links.html %}
