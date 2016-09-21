---
title:  "Membuat Jekyll Portable"
published: true
permalink: jekyll-portable.html
summary: "Membuat Jekyll potable untuk Windows"
tags: [news, getting_started, jekyll]
---

Jekyll adalah site statis generator yang berbasis interpreter Ruby maka untuk menjalankan aplikasi Jekyll diperlukan interpreter Ruby dan beberapa Rubygem.

## Persiapan

Untuk membuat jekyl portable pertama harus disiapkan berikut ini :

1. [Ruby 2.2.5](http://rubyinstaller.org/downloads/)
2. [Ruby Development Kit](http://rubyinstaller.org/downloads/)

## Langkah-langkah pemasangan

1. Buat folder untuk menempatkan aplikasi misal folder `jekyll-potable`
2. Di dalam folder `jekyll-portable` buat folder baru untuk menempatkan intepreter Ruby misal `ruby`
3. Install Ruby yang sudah di download tadi.
4. Masih di Dalam folder `jekyll-portable` buat folder baru utnuk menempatkan Ruby Development kit misal diberi nama `rubyDevKit`
5. Ekstrak Ruby Developmnet kit yang sudah di download tadi ke folder `rubyDevKit`
6. Buat file `cmd` beri nama `setpath.cmd` (bebas menggunakan nama apa saja) ketik seperti berikut :

   ```
   @ECHO OFF
   
   SET RUBY_PATH=%~dp0App\Ruby
   SET DEVKIT_PATH=%~dp0App\RubyDevKit
   
   ECHO PATH sudah di tambahkan.
   ECHO WELCOME To JEKYLL-PORTABLE
   
   SET PATH=%RUBY_PATH%\bin;%DEVKIT_PATH%\bin;%DEVKIT_PATH%\mingw\bin;%PATH%;
   
   ruby -v
   
   CALL cmd /k
   ```

7. Double klik file `setpath.cmd` yang dibuat tadi
8. Sekarang masuk ke folder `rubyDevKit` dan ketik pada terminal `ruby dk.rb init` setelah selesai ketik lagi `ruby dk.rb install` setelah itu kembali lagi ke folder `jekyll-potable`
9. Install Bundler : ketik `gem install bundler`
10. Inisialisasi Bundler : ketik `bundle inti` maka secara otomatis akan membuat file `Gemfile`
11. Dengan teks editor buka file `Gemfile` secara default berikut isinya :

    ```
    # A sample Gemfile
    source "https://rubygems.org"
    
    # gem "rails"
    ```
    
    di dalam file `Gemfile` kita bisa memasang jekyll secara otomatis dan beberapa paket gem berikut gem yang di install ( untuk memasang gem butuh koneksi internet ) berikut daftar gem:

    [jekyll](https://rubygems.org/gems/jekyll),  '3.0.3'
    [RedCloth](https://rubygems.org/gems/RedCloth),  '4.2.9'
    [activesupport](https://rubygems.org/gems/activesupport),  '4.2.5.1'
    [addressable](https://rubygems.org/gems/addressable),  '2.3.8'
    [coffee-script](https://rubygems.org/gems/coffee-script),  '2.4.1'
    [coffee-script-source](https://rubygems.org/gems/coffee-script-source),  '1.10.0'
    [colorator](https://rubygems.org/gems/colorator),  '0.1'
    [ethon](https://rubygems.org/gems/ethon),  '0.8.1'
    [execjs](https://rubygems.org/gems/execjs),  '2.6.0'
    [faraday](https://rubygems.org/gems/faraday),  '0.9.2'
    [ffi](https://rubygems.org/gems/ffi),  '1.9.10'
    [gemoji](https://rubygems.org/gems/gemoji),  '2.1.0'
    [github-pages](https://rubygems.org/gems/github-pages),  '52'
    [github-pages-health-check](https://rubygems.org/gems/github-pages-health-check),  '1.0.1'
    [html-pipeline](https://rubygems.org/gems/html-pipeline),  '2.3.0'
    [i18n](https://rubygems.org/gems/i18n),  '0.7.0'
    [jekyll-coffeescript](https://rubygems.org/gems/jekyll-coffeescript),  '1.0.1'
    [jekyll-feed](https://rubygems.org/gems/jekyll-feed),  '0.4.0'
    [jekyll-gist](https://rubygems.org/gems/jekyll-gist),  '1.4.0'
    [jekyll-mentions](https://rubygems.org/gems/jekyll-mentions),  '1.0.1'
    [jekyll-paginate](https://rubygems.org/gems/jekyll-paginate),  '1.1.0'
    [jekyll-redirect-from](https://rubygems.org/gems/jekyll-redirect-from),  '0.9.1'
    [jekyll-sass-converter](https://rubygems.org/gems/jekyll-sass-converter),  '1.3.0'
    [jekyll-seo-tag](https://rubygems.org/gems/jekyll-seo-tag),  '1.3.1'
    [jekyll-sitemap](https://rubygems.org/gems/jekyll-sitemap),  '0.10.0'
    [jekyll-textile-converter](https://rubygems.org/gems/jekyll-textile-converter),  '0.1.0'
    [jekyll-watch](https://rubygems.org/gems/jekyll-watch),  '1.3.1'
    [jemoji](https://rubygems.org/gems/jemoji),  '0.5.1'
    [json](https://rubygems.org/gems/json),  '1.8.3'
    [kramdown](https://rubygems.org/gems/kramdown),  '1.9.0'
    [liquid](https://rubygems.org/gems/liquid),  '3.0.6'
    [listen](https://rubygems.org/gems/listen),  '3.0.6'
    [mercenary](https://rubygems.org/gems/mercenary),  '0.3.5'
    [mini_portile2](https://rubygems.org/gems/mini_portile2),  '2.0.0'
    [minitest](https://rubygems.org/gems/minitest),  '5.8.4'
    [multipart-post](https://rubygems.org/gems/multipart-post),  '2.0.0'
    [net-dns](https://rubygems.org/gems/net-dns),  '0.8.0'
    [nokogiri](https://rubygems.org/gems/nokogiri),  '1.6.7.2'
    [octokit](https://rubygems.org/gems/octokit),  '4.2.0'
    [public_suffix](https://rubygems.org/gems/public_suffix),  '1.5.3'
    [rb-fsevent](https://rubygems.org/gems/rb-fsevent),  '0.9.7'
    [rb-inotify](https://rubygems.org/gems/rb-inotify),  '0.9.7'
    [rdiscount](https://rubygems.org/gems/rdiscount),  '2.1.8'
    [redcarpet](https://rubygems.org/gems/redcarpet),  '3.3.3'
    [rouge](https://rubygems.org/gems/rouge),  '1.10.1'
    [safe_yaml](https://rubygems.org/gems/safe_yaml),  '1.0.4'
    [sass](https://rubygems.org/gems/sass),  '3.4.21'
    [sawyer](https://rubygems.org/gems/sawyer),  '0.6.0'
    [terminal-table](https://rubygems.org/gems/terminal-table),  '1.5.2'
    [thread_safe](https://rubygems.org/gems/thread_safe),  '0.3.5'
    [typhoeus](https://rubygems.org/gems/typhoeus),  '0.8.0'
    [tzinfo](https://rubygems.org/gems/tzinfo),  '1.2.2'
    [wdm](https://rubygems.org/gems/wdm), '>= 0.1.0'

    untuk ingin memasang jekyll bisa menggunakan perintah `gem install jekyll` pada terminal, memasang Redcloth `gem install Redcloth` dan seterusnya. Dengan cara manual tersebut akan sangat merepotkan dan memakan waktu lama dengan memasukan ke `Gemfile` maka akan secara otomatis terinstall	berikut isi `Gemfile`nya :

    ```
    # A sample Gemfile
    source "https://rubygems.org"
    
    # gem "rails"
    gem 'jekyll',  '3.0.3'
    gem 'RedCloth',  '4.2.9'
    gem 'activesupport',  '4.2.5.1'
    gem 'addressable',  '2.3.8'
    gem 'coffee-script',  '2.4.1'
    gem 'coffee-script-source',  '1.10.0'
    gem 'colorator',  '0.1'
    gem 'ethon',  '0.8.1'
    gem 'execjs',  '2.6.0'
    gem 'faraday',  '0.9.2'
    gem 'ffi',  '1.9.10'
    gem 'gemoji',  '2.1.0'
    gem 'github-pages',  '52'
    gem 'github-pages-health-check',  '1.0.1'
    gem 'html-pipeline',  '2.3.0'
    gem 'i18n',  '0.7.0'
    gem 'jekyll-coffeescript',  '1.0.1'
    gem 'jekyll-feed',  '0.4.0'
    gem 'jekyll-gist',  '1.4.0'
    gem 'jekyll-mentions',  '1.0.1'
    gem 'jekyll-paginate',  '1.1.0'
    gem 'jekyll-redirect-from',  '0.9.1'
    gem 'jekyll-sass-converter',  '1.3.0'
    gem 'jekyll-seo-tag',  '1.3.1'
    gem 'jekyll-sitemap',  '0.10.0'
    gem 'jekyll-textile-converter',  '0.1.0'
    gem 'jekyll-watch',  '1.3.1'
    gem 'jemoji',  '0.5.1'
    gem 'json',  '1.8.3'
    gem 'kramdown',  '1.9.0'
    gem 'liquid',  '3.0.6'
    gem 'listen',  '3.0.6'
    gem 'mercenary',  '0.3.5'
    gem 'mini_portile2',  '2.0.0'
    gem 'minitest',  '5.8.4'
    gem 'multipart-post',  '2.0.0'
    gem 'net-dns',  '0.8.0'
    gem 'nokogiri',  '1.6.7.2'
    gem 'octokit',  '4.2.0'
    gem 'public_suffix',  '1.5.3'
    gem 'rb-fsevent',  '0.9.7'
    gem 'rb-inotify',  '0.9.7'
    gem 'rdiscount',  '2.1.8'
    gem 'redcarpet',  '3.3.3'
    gem 'rouge',  '1.10.1'
    gem 'safe_yaml',  '1.0.4'
    gem 'sass',  '3.4.21'
    gem 'sawyer',  '0.6.0'
    gem 'terminal-table',  '1.5.2'
    gem 'thread_safe',  '0.3.5'
    gem 'typhoeus',  '0.8.0'
    gem 'tzinfo',  '1.2.2'
    gem 'wdm', '>= 0.1.0'
    ```
    
    ketik `bundle install` maka gem yang ada di daftar `Gemfile` akan didownload secara otomatis tunggu hingga download selesai.

12. Jekyll dan gem lainnya sudah terinstal. jalankan `jekyll-portable` melalui `setpath.cmd`. Jika berhasil akan tampil sebagai berikut :

    ```
	PATH sudah di tambahkan.
    WELCOME To JEKYLL-PORTABLE
    ruby 2.2.5p319 (2016-04-26 revision 54774) [i386-mingw32]
    D:\Jekyll-portable>
	```

	ketik `jekyll -v` jika tampil `jekyll 3.0.3` berarti jekyll sudah terpasang dengan benar.
{% include links.html %}
