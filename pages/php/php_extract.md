---
title: EXTRACT
tags: [formatting,php,while]
keywords: datatables, tables, grids, markdown, multimarkdown
last_updated: July 16, 2016
datatable: true
summary: "Fungsi Extract"
sidebar: php_sidebar
permalink: php_extract.html
folder: php
---


Penjelasan

Fungsi ini akan meng-_import variable_ dari _array_  kedalam tabel simbol saat ini.

Juga memeriksa setiap _key array_ untuk melihat apakah memiliki nama variabel yang valid. Hal ini juga memeriksa bentrok dengan variabel yang ada dalam tabel simbol.

syntaxt :

int extract ( array &$array [, int $flags = EXTR_OVERWRITE [, string $prefix = NULL ]] )

`$array` = Array yang akan di _extract_
`$flags` = langkah lanjut yang diberikan jika terjadi bentrokan flag ini terdir dari :
EXTR_OVERWRITE = Jika bentrok, _overwrite variable_ yang ada.
EXTR_SKIP = Jika bentrok, jangan overwrite variable yang ada atau lewatkan.
EXTR_PREFIX_SAME = Jika bentrok, _prefix_ nama _variable_ dengan _prefix_.
EXTR_PREFIX_ALL = Prefix semua nama _variable_ dengan _prefix_.
EXTR_PREFIX_INVALID = Hanya yang memiliki nomor key dan yang _invalid_ yang diberikan _prefix_.
EXTR_IF_EXISTS = _Overwrite variable_ jika sudah ada pada table simbol, yang lainnya tidak. Ini membantu untuk mendefiniskan daftar _variable valid_ dan kemudian meng--extract_ hanya _variable_ yang sudah Anda definisikan misalnya `$_REQUEST`.
EXTR_PREFIX_IF_EXISTS = Hanya membuat nama _variable prefix_ jika versi _non-prexixed_ dari _variable_ yang sama ada dalam table saat ini.
EXTR_REFS = ekstact _variable_ sebagai referensi.

`$prefix` = Catatan bahwa _prefix_ ini jika menggunakan `$flags` EXTR_PREFIX_SAME, EXTR_PREFIX_ALL, EXTR_PREFIX_INVALID atau EXTR_PREFIX_IF_EXISTS. Jika hasil diawali bukan nama _variable_ yang valid maka tidak diimpor ke tabel simbol. _Prefix_ secara otomatis dipisahkan dari kunci array dengan karakter garis bawah.

Contoh 1 :

```php
<?php
$data = array();
$data['satu']	                   = "Januari";
$data['dua']	                   = "Februari";
$data['tiga']	                   = "Maret";
$data['empat']	                   = "April";
$data['lima']	                   = "Mei";
$data['enam']	                   = "Juni";
$data['tujuh']	                   = "Juli";
$data['delapan']	               = "Agustus";
$data['sembilan']	               = "September";
$data['sepuluh']	               = "Oktober";
$data['sebelas']	               = "November";
$data['duabelas']	               = "Desember";

extract($data);

echo $satu.'<br>';
echo $dua.'<br>';
echo $tiga.'<br>';
echo $empat.'<br>';
echo $lima.'<br>';
echo $enam.'<br>';
echo $tujuh.'<br>';
echo $delapan.'<br>';
echo $sembilan.'<br>';
echo $sepuluh.'<br>';
```

hasil : contoh 1 
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

{% include links.html %}
