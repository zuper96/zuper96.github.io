---
title:  "Info (Callouts) pada Jekyll Documentation Theme"
categories: jekyll Documenatation theme
permalink: info-callout.html
tags: [news, jekyll, documentation]
---


Info (Callout) digunakan  untuk memberikan informasi, catatan atau keterangan pada content.

Ada beberapa cara untuk memberikan info berikut contohnya :

### Kode HTML biasa

Contoh kodenya :

```html
<div class="alert alert-info" role="alert"><span class="glyphicon glyphicon-question-sign"></span> Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. </div>
```

Hasil :

<div class="alert alert-info" role="alert"><span class="glyphicon glyphicon-question-sign"></span> Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. Ini adalah info khusus. </div>

### Dengan `include callout.html`

```
{% raw %}{% include callout.html content="Ini adalah info dengan menggunakan tag include callout.html. umumnya info digunakan untuk memberikan informasi dengan banyak paragraf." type="primary" %} {% endraw %}
```

Hasil dalam HTML :

```html
<div class="bs-callout bs-callout-primary">Ini adalah info dengan menggunakan tag include callout.html. umumnya info digunakan untuk memberikan informasi dengan banyak paragraf.</div>
```

Tampilan:

{% include callout.html content="Ini adalah info dengan menggunakan tag include callout.html. umumnya info digunakan untuk memberikan informasi dengan banyak paragraf." type="primary" %}

Property yang tersedia untuk `include` :

| Property | description |
|-------|--------|
| content | isi informasi yang ingin dibagikan |
| type | style untuk callout. berikut pilihnnya `danger`, `default`, `primary`, `success`, `info`, and `warning`.|

Ini adalah contoh dari masing-masing type callout :

{% include callout.html content="Ini adalah callout type **danger**. Warna sisi sebelah kiri akan berubah sesuai dengan type callout." type="danger" %}

{% include callout.html content="Ini adalah callout type **default**. Warna sisi sebelah kiri akan berubah sesuai dengan type callout." type="default" %}

{% include callout.html content="Ini adalah callout type **primary**. Warna sisi sebelah kiri akan berubah sesuai dengan type callout." type="primary" %}

{% include callout.html content="Ini adalah callout type **success**. Warna sisi sebelah kiri akan berubah sesuai dengan type callout." type="success" %}

{% include callout.html content="Ini adalah callout type **info**. Warna sisi sebelah kiri akan berubah sesuai dengan type callout." type="info" %}

{% include callout.html content="Ini adalah callout type **warning**. Warna sisi sebelah kiri akan berubah sesuai dengan type callout." type="warning" %}

Jika informasi lebih dari satu paragraf maka bisa menggunkan tag `<br/><br/>` milik html berikut contohnya :

```
{% raw %}{% include callout.html content="**Informasi Penting**: Ini adalah informasi penting, Warna sisi sebelah kiri bisa Anda ganti dengan memasukan type parameter. Umumnya callout digunakan untuk memberikan informasi yang lebih dari satu paragraf. <br/><br/> Ini adalah paragraf baru setelah disisipkan tag break. karena terlalu banyak informasi yang perlu saya bagi. Mungkin Anda bertanya-tanya kenapa tidak menggunakan tag div saja?. Ini karena Kramdown memproses Markdown lebih baik daripada div. Anda bisa memasukan syntax Markdown di dalam HTML. Biasanya tidak boleh ada syntax Markdwon, tapi disini diperbolehkan." type="primary" %} {% endraw %}
```

Tampilan :

{% include callout.html content="**Informasi Penting**: Ini adalah informasi penting, Warna sisi sebelah kiri bisa Anda ganti dengan memasukan type parameter. Umumnya callout digunakan untuk memberikan informasi yang lebih dari satu paragraf. <br/><br/> Ini adalah paragraf baru setelah disisipkan tag break. karena terlalu banyak informasi yang perlu saya bagi. Mungkin Anda bertanya-tanya kenapa tidak menggunakan tag div saja?. Ini karena Kramdown memproses Markdown lebih baik daripada div. Anda bisa memasukan syntax Markdown di dalam HTML. Biasanya tidak boleh ada syntax Markdwon, tapi disini diperbolehkan." type="primary" %}

### Menggunakan liquid

Berikut kodenya:

{% raw %}
```
{{site.data.alerts.callout_info}}Ini adalah informasi khusus. </div>
```
{% endraw %}

Hasil dalam kode HTML :

```html
<div class="bs-callout bs-callout-info"> Ini adalah informasi khusus. </div>
```

Tampilan:

{{site.data.alerts.callout_info}}Ini adalah informasi khusus. </div>

Anda juga dapat menggunkan type yang lain :

{% raw %}
```
{{site.data.alerts.callout_default}}
{{site.data.alerts.callout_primary}}
{{site.data.alerts.callout_success}}
{{site.data.alerts.callout_info}}
{{site.data.alerts.callout_warning}}
```
{% endraw %}

Anda bisa lihat di `_data\alert.yml`

{% include links.html %}
