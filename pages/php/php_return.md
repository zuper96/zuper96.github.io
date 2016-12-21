---
title: RETURN
tags: [formatting,php,while]
keywords: datatables, tables, grids, markdown, multimarkdown
last_updated: July 16, 2016
datatable: true
summary: "return"
sidebar: php_sidebar
permalink: php_return.html
folder: php
---

_Return_

return

keyword retun pada php berfungsi untuk mengembalikan nilai dan mengakhiri suatu fungsi atau global scope.

Jika dipanggil dari dalam fungsi, pernyataan return akan mengakhiri tugas fungsi tersebut dan mengembalikan nilai fungsi.

```php
<?php
function tambah($satu,$dua)
{
$hasil = $satu + $dua;
return $hasil;
}

$a=tambah(9,6);
echo $a;
?>
```

Output :

<pre>
15
</pre>


Jika dipanggil dari global scope, pernyataan return akan mengakhiri tugas dari script tersebut dan mengembalikan nilai jika script tersebut di panggil dengan keyword include atau require.

Contoh 1

file `world.php`

```php
<?php
include("hello.php");
echo "world";
?>
```

file `hello.php`

```php
<?php
echo "hello ";
return;
?>
```

Jika file `world.php` di eksekusi berikut outputnya Contoh 1:
<pre>
hello world
</pre>

Contoh 2

file `return.php`

```php
<?php
return [
  'nomor' => 123,
  'nama' => 'agus',
  'pekerjaan' => 'pengusaha'
];
?>
```

file `call_return.php`

```php
<?php
$data = require ('return.php');

echo $data['nomor']. '<br>';
echo $data['nama']. '<br>';
echo $data['pekerjaan']. '<br>';
?>
```

Jika file `world.php` di eksekusi berikut outputnya Contoh 2:
<pre>
123
agus
pengusaha
</pre>


{% include links.html %}
