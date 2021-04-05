# Praktikum 1: HTML Dasar
# Mata Kuliah Pemrograman WEB
```
Nama  : Abdul Majid
NIM   : 311810693
Kelas : TI.19.C.1
Universitas Pelita Bangsa
```
## Persiapan
Buka VSCode dan Browser lalu buat file HTML baru. Setelah itu tambahkan tag dasar dokumen HTML.
```html
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
```
![1_persiapan](https://user-images.githubusercontent.com/81838946/113591534-32e6a280-965e-11eb-9e70-ba146dad2858.PNG)

## 1. Membuat Paragraf
Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut.
```html
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
    HTML.</p>
    
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
```
![2_membuat-paragraf](https://user-images.githubusercontent.com/81838946/113591985-cd46e600-965e-11eb-8db4-2d710248ef90.PNG)

kemudian atur atribut paragraf seperti berikut, dan amati perubahannya.
```html
<!-- Ini adalah paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
```
![3_align-1](https://user-images.githubusercontent.com/81838946/113592776-ca002a00-965f-11eb-9963-d75bd4298a8d.PNG)

Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.
```html
<!-- Ini adalah paragraf pertama -->
<p align=”justify”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align=”justify”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
```
![3_align-2](https://user-images.githubusercontent.com/81838946/113593005-151a3d00-9660-11eb-8e22-eff87a057120.PNG)

## 2. Menambahkan Judul
Tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
```html
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
![4_manambahkan-judul](https://user-images.githubusercontent.com/81838946/113593620-d0db6c80-9660-11eb-99cc-f0bdfc2f6e63.PNG)

## 3. Memformat Teks
Pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
```html
    <!-- Ini adalah paragraf pertama -->
    <!-- judul paragraf pertama -->
    <h1>Belajar Dasar HTML</h1>
    <p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi 
    <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama yang kami dapat 
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
    HTML.</p>
 ```
![5_memformat-teks](https://user-images.githubusercontent.com/81838946/113594724-46940800-9662-11eb-817b-95e56bea64a4.PNG)

 ## 4. Menyisipkan Gambar
 Untuk menyisipkan gambar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. seperti berikut.

![6_file-gambar](https://user-images.githubusercontent.com/81838946/113595195-e05bb500-9662-11eb-8272-586d0f77f7a9.PNG)

Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.
```html
    <!-- sub judul paragraf -->
    <h3>Menambahkan Gambar</h3>

    <!-- menambahkan gambar pada dokumen -->
    <img src="logo_upb.png" width="200" title="Logo Univeritas Pelita Bangsa">
```

![7_menyisipkan-gambar](https://user-images.githubusercontent.com/81838946/113595599-6841bf00-9663-11eb-8e8e-63e48893e3f0.PNG)

## 5. Menambahkan Hyperlink
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
```html
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
</nav>
<hr>  
```
![8_menambahkan-hyperlink](https://user-images.githubusercontent.com/81838946/113596942-2dd92180-9665-11eb-862d-fa10dafc514b.PNG)

Membuat 1 file halaman lagi dengan nama lab1_halaman2.html
```html
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>
    <!-- menambahkan link navigasi -->
    <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a>
        <a href="lab1_halaman2.html">Halaman 2</a>
        <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr> 

    <!-- Ini adalah paragraf pertama -->
    <!-- judul paragraf pertama -->
    <h1>Halaman 2</h1>

    <!-- menambahkan gambar pada dokumen -->
    <img src="logo_perguruanTinggi_1.png" width="200" title="Logo Univeritas Pelita Bangsa">

    <hr>

    <q><i>Alhamdulillah, saya dapat bergabung dengan kampus Pelita Bangsa yang mampu mencetak pebisnis handal untuk kemajuan bangsa.</i></q>

</body>
</html>
```
![9_halaman2"](https://user-images.githubusercontent.com/81838946/113597281-ac35c380-9665-11eb-84ac-832d56f02735.PNG)


## JAWAB PERTANYAAN
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah 
error ketika terjadi kesalahan penulisan tag?
```
Ada, ketika lupa atau salah menempatkan penutup tag dan salah mengetik nama tag, tampilan halaman html mnegalami error.
```
2. Apa perbedaan dari tag < p> dengan tag < br>, berikan penjelasannya!
```
Dari hasil praktik yang sudah dilakukan, perbedaan  tag <p> memberikan spasi setiap kali ganti paragraf, sedangkan tag <br> memberikan spasi setiap ganti baris.
```
3. Apa perbedaan atribut *title* dan *alt* pada tag < img>, berikan penjelasannya!
```
title adalah sebuah balon teks yang muncul saat sebuah gambar disentuh kursor mouse tanpa diklik. sedangkan alt merupakan keterangan singkat sebuah dari sebuah gambar.
```
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar 
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
tidak, lebih baik diisi salah satunya saja. misal yang diisi hanya width-nya saja, maka heiht-nya akan menyesuaikan width-nya sehingga ukuran gambar akan lebih terlihat proporsional.
```
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, 
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
_blank untuk membuka link di tab baru.
_self untuk membuka link di halaman link itu berada.
_top untuk membuka link ke tampilan penuh atau fullscreen.
_parent untuk membuka link dalam kerangka induk.
```
