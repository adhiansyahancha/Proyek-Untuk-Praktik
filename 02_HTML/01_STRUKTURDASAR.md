# Struktur Dasar HTML
HTML (_HyperText Markup Language_) adalah bahasa markah yang umum digunakan untuk membuat dokumen Web. Berkas HTML bisa disimpan dalam ekstensi ".html" atau ".htm" (ekstensi yang terakhir digunakan secara historis ketika komputer hanya mendukung tiga karakter).

Struktur dasar HTML yang umum digunakan adalah seperti ini:

```html
<!-- Struktur dasar --->
<!DOCTYPE html>
<html lang="id">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
</head>
<body>
	<p>Halo, Dunia!</p>
</body>
</html>
```
Bedah rincian:

```html
<!DOCTYPE html>
```
Elemen pembuka ini dinamakan Doctype, bertujuan agar peramban web menampilkan dokumen Web dalam standar modern dan menjaga kompatibilitas halaman web. Kalau tidak, peramban akan menampilkannya dalam mode _quirk_, yaitu mode tampilan halaman di peramban Netscape/Internet Explorer dari tahun 90-an.

```html
<html lang="id">
```