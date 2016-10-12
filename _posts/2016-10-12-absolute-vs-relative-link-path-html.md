---
title:  "Absolute vs Relative Link/Path HTML"
categories: opencart
permalink: absolute-vs-relative-link-path-html.html
tags: [news]
---

Untuk membuat link pada HTML umumnya sebagai berikut :

```html
<a href="linksaya.html">Klik saya</a>
```

`linksaya.html` adalah link yang akan dihubungkan, file `linksaya.html` masih dalam satu folder. bagaimana jika linksaya.html berada di folder yang berbeda?. Ada dua cara dalam penulisan link yaitu absolute atau relative.

## Absolute Paths

Untuk absolute path caranya dengan menuliskan secara lengkap.

* http://www.webku.com
* http://www.webku.com/images/image.png
* http://www.webku.com/halaman/artikel/index.html

## Relative Paths

Masih dalam satu folder

```html
index.html
```

Masih dalam satu folder tetapi file yang akan dihubungkan berada dalam sub folder `images`

```html
/images/image.jpg
```

Berada di luar folder

```html
../image.jpg
```

Berada diluar folder dan berada di folder `images`

```html
../images/image.jpg
```

Berada di luar folder dua tingkat misal folder saat ini `/folder/saat/ini/index.html` folder yang akan dihubungkan berada `/folder/image/image.jpg`

```html
../../images/image.jpg
```

{% include links.html %}
