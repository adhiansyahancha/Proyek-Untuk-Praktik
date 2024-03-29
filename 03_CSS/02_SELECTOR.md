# Selektor (Selectors)
Selektor digunakan untuk menargetkan elemen HTML yang ingin Anda gayakan dengan CSS. Ada berbagai jenis selektor dalam CSS, mulai dari selektor elemen hingga selektor kelas dan ID.


## Beberapa jenis selektor dalam css yang biasa digunakan

1. **Selektor Elemen**
    Selektor paling dasar yang memilih elemen berdasarkan nama tag HTML.
    
    ```css
    p {
        color: blue;
    }
    ```
    Contoh di atas akan memberikan warna biru pada semua elemen `<p>` di halaman.

2. **Selektor Kelas**
    Memilih elemen berdasarkan kelas tertentu.
    ```css
    .kelas {
        font-weight: bold;
    }
    ```
    Contoh di atas akan memberikan teks tebal pada semua elemen dengan kelas "kelas".

3. **Selektor ID**
    Memilih elemen dengan ID tertentu

    ```css
    #id {
        background-color: yellow;
    }
    ```
    Contoh di atas akan memberikan latar belakang kuning pada elemen dengan ID "id".

4. **Selektor Universal**
    Memilih semua elemen di dalam dokumen.
    ```css
    * {
        margin: 0;
        padding: 0;
    }
    ```
    Contoh di atas akan menghilangkan margin dan padding default dari semua elemen.

5. **Selektor Atribut**
    Memilih elemen berdasarkan atribut HTML-nya.

    ```css
    [type="text"] {
        border: 1px solid black;
    }
    ```
    Contoh di atas akan memberikan border hitam pada semua elemen dengan atribut type yang memiliki nilai "text".

6. **Selektor Nama**
    Memilih elemen berdasarkan nama.

    ```css
    input[name="nama"] {
        width: 200px;
    }
    ```
    Contoh di atas akan memberikan lebar 200px pada semua elemen input dengan atribut name yang memiliki nilai "nama".

7. **Selektor Anak**
    Memilih elemen yang menjadi anak dari elemen lain.

    ```css
    div p {
        font-style: italic;
    }
    ```
    Contoh di atas akan memberikan gaya miring pada semua elemen `<p>` yang berada di dalam elemen `<div>`.

8. **Selektor Keturunan**
    Memilih elemen yang menjadi keturunan langsung dari elemen lain.

    ```css
    div > p {
        color: green;
    }
    ```
    Contoh di atas akan memberikan warna hijau pada semua elemen `<p>` yang langsung menjadi anak dari elemen `<div>`.

9. **Selektor Berdasarkan Hierarki**
    Kombinasi selektor yang memperhitungkan hubungan hierarkis antara elemen-elemen.

    ```css
    header nav ul li a {
        color: white;
    }
    ```
    Contoh di atas akan memberikan warna putih pada semua tautan yang berada di dalam elemen `<header>`, `<nav>`, `<ul>`, `<li>`, dan `<a>`.

10. **Selektor Grup**
    Memilih beberapa elemen sekaligus.

    ```css
    h1, h2, h3 {
        color: red;
    }
    ```
    Contoh di atas akan memberikan warna merah pada semua elemen `<h1>`, `<h2>`, dan `<h3>`.

