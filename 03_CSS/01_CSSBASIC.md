**Cascading Style Sheets (CSS) - Pengantar dan Dasar-dasar**

# Apa itu CSS?

Cascading Style Sheets (CSS) adalah bahasa desain yang digunakan untuk mengontrol tata letak dan tampilan elemen-elemen dalam sebuah halaman web. CSS memungkinkan pengembang web untuk mengubah warna, font, ukuran, jarak, dan banyak lagi, secara konsisten di seluruh situs web, hanya dengan mengubah satu file.

## Kenapa Kita Membutuhkan CSS?

- Memisahkan struktur (HTML) dan presentasi (CSS) dari halaman web.
- Mengatur tampilan elemen secara konsisten di seluruh situs web.
- Membuat tata letak yang responsif dan dapat diakses di berbagai perangkat.
- Memberikan pengalaman pengguna yang lebih baik dengan desain yang menarik.

# Dasar-dasar CSS

## 1. Selektor

Selektor adalah bagian dari aturan CSS yang menentukan elemen atau elemen-elemen mana yang akan diberi gaya. Contoh selektor termasuk nama elemen, kelas, ID, atau atribut.

```css
/* Contoh selektor menggunakan nama elemen */
p {
    color: blue;
}

/* Contoh selektor menggunakan kelas */
.nama_kelas {
    font-size: 16px;
}

/* Contoh selektor menggunakan ID */
#nama_id {
    background-color: yellow;
}
```

## 2. Properti dan Nilai

Properti adalah karakteristik yang ingin Anda atur, seperti warna, ukuran font, atau jarak. Nilai adalah nilai tertentu yang Anda berikan kepada properti tersebut.

```css
/* Contoh properti dan nilai */
p {
    color: blue; /* Properti: color, Nilai: blue */
    font-size: 18px; /* Properti: font-size, Nilai: 18px */
    margin-top: 20px; /* Properti: margin-top, Nilai: 20px */
}
```

## 3. Komentar

Anda dapat menambahkan komentar ke dalam file CSS Anda untuk menjelaskan kode atau membuatnya lebih mudah dipahami oleh orang lain.

```css
/* Ini adalah komentar CSS */
```

## 4. Kelompokkan Aturan

Anda dapat mengelompokkan beberapa aturan CSS bersama-sama untuk menerapkan gaya yang sama pada beberapa elemen.

```css
/* Mengelompokkan aturan */
h1, h2, h3 {
    font-family: Arial, sans-serif;
    color: #333;
}
```

## 5. Penerusan Nilai

Penerusan nilai memungkinkan Anda mewariskan nilai dari elemen yang lebih tinggi ke elemen yang lebih rendah dalam hierarki.

```html
<div class="kontainer">
    <p class="teks-utama">Ini adalah teks utama</p>
</div>
```

```css
/* Penerusan nilai */
.kontainer {
    font-family: Arial, sans-serif;
}

.teks-utama {
    color: blue; /* Akan mewarisi font-family dari .kontainer */
}
```

## 6. Penggunaan Unit

Nilai properti CSS dapat ditentukan dalam berbagai unit seperti piksel (px), persen (%), em, rem, dan lain-lain.

```css
p {
    font-size: 16px; /* piksel */
    margin-left: 20%; /* persen */
    padding: 1em; /* em */
}
```

## 7. Kaskade dan Prioritas

Kaskade adalah proses menentukan nilai yang akan diterapkan ke suatu elemen berdasarkan aturan CSS yang diterapkan padanya. Prioritas dapat ditentukan oleh spesifisitas, urutan, atau penggunaan !important.

```css
/* Prioritas */
.teks {
    color: red !important; /* Prioritas tertinggi */
}

.teks {
    color: blue; /* Prioritas lebih rendah */
}
```