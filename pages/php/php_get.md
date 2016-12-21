---
title: GET
tags: [formatting,php,while]
keywords: datatables, tables, grids, markdown, multimarkdown
last_updated: July 16, 2016
datatable: true
summary: "Struktur kontrol while"
sidebar: php_sidebar
permalink: php_get.html
folder: php
---

## Superglobals Variable $_GET
	
### Contoh 1 :
`get.php`
```php
<?php
echo '<pre>';
var_dump ($_GET);
echo '</pre>';
?>
```

### Hasil : contoh 1
(Misal pada address bar diketik 'http://localhost/get.php' )
<pre>
array(0) {}
</pre>

### Hasil : contoh 1
(Misal pada address bar diketik 'http://localhost/lat_php/get.php?route=text_di_url')
<pre>
array(1) 
{
  ["route"]=>  string(11) "text_di_url"
}
</pre>

### Hasil : contoh 1
(Misal pada address bar diketik 'http://localhost/lat_php/get.php?route=text_di_url&user=nama_Anda')
<pre>
array(2) 
{
  ["route"]=>  string(11) "text_di_url"
  ["user"]=>  string(9) "nama_Anda"
}
</pre>

{% include links.html %}
