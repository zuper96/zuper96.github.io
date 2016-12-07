---
title: ISSET EMPTY
tags: [formatting,php,isset, empty]
keywords: datatables, tables, grids, markdown, multimarkdown
last_updated: July 16, 2016
datatable: true
summary: "isset dan empty"
sidebar: php_sidebar
permalink: php_isset_empty.html
folder: php
---

### isset
isset akan menentukan apakah suatu variabel telah didefinisikan.

```php
$var=null;
var_dump(isset($var)); //hasilnya FALSE karena isinya NULL
$var=0;
var_dump(isset($var)); //hasilnya TRUE
$var="";
var_dump(isset($var)); //hasilnya TRUE
$var="0";
var_dump(isset($var)); //hasilnya TRUE
$var=array();
var_dump(isset($var)); //hasilnya TRUE
$var=false;
var_dump(isset($var)); //hasilnya TRUE
$var="this is a string";
var_dump(isset($var)); //hasilnya TRUE
```

### empty
empty akan menentukan apakah suatu variabel tidak didefinisikan.

```php
$var=null;
var_dump(empty($var)); //hasilnya TRUE krn isinya NULL
$var=0;
var_dump(empty($var)); //hasilnya TRUE krn 0 dianggap kosong/empty
$var="";
var_dump(empty($var)); //hasilnya TRUE krn "" krn isinya string kosong
$var="0";
var_dump(empty($var)); //hasilnya TRUE krn "0" dianggap kosong/empty
$var=array();
var_dump(empty($var)); //hasilnya TRUE krn berisi array kosong
$var=false;
var_dump(empty($var)); //hasilnya TRUE krn bool false dianggap kosong/empty
$var=" ";
var_dump(empty($var)); //hasilnya FALSE krn " " ada spasi didlm var tsb
$var="this is a string";
var_dump(empty($var)); //hasilnya FALSE
$var=2;
var_dump(empty($var)); //hasilnya FALSE krn 2 adalah angka yg valid

```

| parameter | isset | empty |
| ----------|-------|-------|
| NULL      | FALSE | TRUE  |
| 0         | TRUE  | TRUE  |
| ''        | TRUE  | TRUE  | 
| ""        | TRUE  | TRUE  |
| ' '       | TRUE  | FALSE |
| " "       | TRUE  | FALSE |
| 'teks'    | TRUE  | FALSE |
| "teks"    | TRUE  | FALSE |
| 2         | TRUE  | FALSE |

Selesai.

{% include links.html %}
