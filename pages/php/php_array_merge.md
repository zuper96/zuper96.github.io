---
title: ARRAY MERGE
tags: [formatting,php,while]
keywords: datatables, tables, grids, markdown, multimarkdown
last_updated: July 16, 2016
datatable: true
summary: "array_merge"
sidebar: php_sidebar
permalink: php_array_merge.html
folder: php
---

Penjelasan
Menggabungkan satu atau lebih elemen _array_ sehingga nilai-nilai ditambahkan pada array sebelummnya dan mengembalikannya sebagai _array_.

Syntax
array array_merge ( array $array1 [, array $... ] )

Jika array yang digabungkan memiliki _key_ atau _index_ yang sama , maka nilainya akan *menimpa* _key array_ sebelumnya. Tapi, jika _key array_ berisi nilai angka, nilai tidak akan menimpa, tapi akan ditambahkan.

Nilai-nilai dalam _array_ dengan _key_ angka akan dinomori ulang dengan _incrementing_ _key_ mulai dari nol dalam array.

Contoh 1 :

```php
<?php

// ++++++++++++++++++++++++++++++++++
$_ = array();
$_['text_affiliate']       = 'Afiliasi';
$_['text_analytics']       = 'Analitik';
$_['text_api']             = 'API';
$_['text_attribute']       = 'Atribut';
$_['text_attribute_group'] = 'Grup Atribut';
$_['text_backup']          = 'Backup / Restore';
$_['text_banner']          = 'Banner';
$_['text_captcha']         = 'Captcha';

$data = array();
$data[1]	               = "Januari";
$data[2]	               = "Februari";
$data[3]	               = "Maret";
$data[4]	               = "April";
$data[5]	               = "Mei";
$data[6]	               = "Juni";
$data[7]	               = "Juli";
$data[8]	               = "Agustus";
$data[9]	               = "September";
$data[10]	               = "Oktober";
$data[11]	               = "November";
$data[12]	               = "Desember";

$data = array_merge($data, $_);

echo '<pre>';
var_dump ($data);
echo '</pre>';
```
hasil : contoh 1 
<pre>
array(20) 
{
  [0]=>                       string(7) "Januari"
  [1]=>                       string(8) "Februari"
  [2]=>                       string(5) "Maret"
  [3]=>                       string(5) "April"
  [4]=>                       string(3) "Mei"
  [5]=>                       string(4) "Juni"
  [6]=>                       string(4) "Juli"
  [7]=>                       string(7) "Agustus"
  [8]=>                       string(9) "September"
  [9]=>                       string(7) "Oktober"
  [10]=>                      string(8) "November"
  [11]=>                      string(8) "Desember"
  ["text_affiliate"]=>        string(8) "Afiliasi"
  ["text_analytics"]=>        string(8) "Analitik"
  ["text_api"]=>              string(3) "API"
  ["text_attribute"]=>        string(7) "Atribut"
  ["text_attribute_group"]=>  string(12) "Grup Atribut"
  ["text_backup"]=>           string(16) "Backup / Restore"
  ["text_banner"]=>           string(6) "Banner"
  ["text_captcha"]=>          string(7) "Captcha"
}
</pre>

{% include links.html %}
