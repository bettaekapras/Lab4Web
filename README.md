Praktikum 4 - PHP Modular

Persiapan

- Persiapkan text editor misalnya VSCode.
- Buat folder baru dengan nama lab4_php_modular pada docroot webserver (htdocs).
Tugas/Latihan

Implementasikan konsep modularisasi pada kode program praktikum 3 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.
Langkah Praktikum

Buat file baru dengan nama header.php lalu simpan ke dalam folder lab4_php_modular.

<img width="416" alt="image" src="https://github.com/bettaekapras/Lab4Web/assets/169062721/8a224000-ea17-490d-9dde-e3c18d74a511">


Buat file baru dengan nama home.php, kemudian simpan ke dalam folder lab4_php_modular.

<img width="419" alt="image" src="https://github.com/bettaekapras/Lab4Web/assets/169062721/b2246a10-c673-40ee-bca7-4b3364949c3a">


Buat file baru dengan nama tambah.php, kemudian simpan ke dalam folder lab4_php_modular.

<img width="379" alt="image" src="https://github.com/bettaekapras/Lab4Web/assets/169062721/f0a01e83-748b-43e0-9c6e-96a266594b3b">
<img width="334" alt="image" src="https://github.com/bettaekapras/Lab4Web/assets/169062721/b4e278be-67e2-4080-b083-e56c3336d3cc">


Buat file baru dengan nama koneksi.php, kemudian simpan ke dalam folder lab4_php_modular.

<img width="420" alt="image" src="https://github.com/bettaekapras/Lab4Web/assets/169062721/08b16d7e-e56f-4ca9-947e-72eef4186f08">


Membuat Routing
Routing digunakan untuk mempermudah akses halaman web agar SEO Friendly. Langkah awal adalah menyiapkan file utama index.php yang berisi routing untuk mengakses banyak halaman.
Contohnya:

Halaman Home ( http://localhost/lab4_php_modular/index.php?mod=home )

Halaman Tambah ( http://localhost/lab4_php_modular/index.php?mod=tambah )

Buat file baru dengan nama index.php, kemudian simpan ke dalam folder lab4_php_modular.



Aktivasi mod_rewrite (.htaccess)

Mod_rewrite digunakan untuk mengubah URL dari query string menjadi SEO Friendly. Langkah awal yang harus disiapkan adalah aktivasi mod_rewrite pada webserver Apache2 pada 
configurasi httpd.conf.
Cara mengakses httpd.conf :

Klik folder xampp

Pilih folder apache

Pilih folder conf

Pilih httpd.conf, kemudian aktifkan LoadModule mod_rewrite dengan cara melakukan un-comment pada baris tersebut, kemudian restart Apache2. Seperti gambar di bawah ini :

<img width="421" alt="image" src="https://github.com/bettaekapras/Lab4Web/assets/169062721/60c5c11c-e4b0-4cd2-9df3-5a17704366de">

Kemudian membuat file .htaccess, kemudian simpan ke dalam folder lab4_php_modular.

<img width="279" alt="image" src="https://github.com/bettaekapras/Lab4Web/assets/169062721/7c0b01fc-0eb7-4abc-8723-cc11d5e7120d">


Cara aksesnya menjadi :

Halaman Home ( http://localhost/lab4_php_modular/home )

<img width="629" alt="image" src="https://github.com/bettaekapras/Lab4Web/assets/169062721/414fe97f-46f4-4888-a6f4-6c267dbb710f">

Halaman Tambah ( http://localhost/lab4_php_modular/tambah )

<img width="245" alt="image" src="https://github.com/bettaekapras/Lab4Web/assets/169062721/b561e213-6757-4b68-a1a1-ab3a4afaf227">

Terimakasih!
