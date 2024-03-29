**Cascading Style Sheets (CSS) - Pengantar dan Dasar-dasar**

# Apa itu CSS?

Cascading Style Sheets (CSS) adalah bahasa desain yang digunakan untuk mengontrol tata letak dan tampilan elemen-elemen dalam sebuah halaman web. CSS memungkinkan pengembang web untuk mengubah warna, font, ukuran, jarak, dan banyak lagi, secara konsisten di seluruh situs web, hanya dengan mengubah satu file.

## Kenapa CSS Penting?

- Pemisahan antara konten dan presentasi: CSS memungkinkan Anda untuk memisahkan struktur dan konten dari tampilan sebuah halaman web. Hal ini membuat pengelolaan dan pemeliharaan situs web menjadi lebih mudah.
- Konsistensi: Dengan menggunakan CSS, Anda dapat memastikan konsistensi tampilan di seluruh situs web Anda. Anda dapat menerapkan gaya tertentu ke banyak elemen dengan mudah.
- Responsif: CSS memungkinkan Anda untuk membuat situs web responsif, yang berarti situs Anda dapat menyesuaikan tampilan dan tata letaknya tergantung pada perangkat yang digunakan oleh pengguna.

# Cara Menggunakan CSS

1. **Inline CSS**: Anda dapat menambahkan gaya langsung ke elemen HTML menggunakan atribut `style`. Contohnya:

    ```html
    <p style="color: blue; font-size: 16px;">Ini adalah teks dengan gaya langsung.</p>
    ```

2. **Internal CSS**: Anda juga dapat menempatkan kode CSS di dalam tag `<style>` di bagian `<head>` dari halaman HTML. Ini akan berlaku untuk seluruh halaman tersebut. Contohnya:

    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            p {
                color: blue;
                font-size: 16px;
            }
        </style>
    </head>
    <body>
        <p>Ini adalah teks dengan gaya internal.</p>
    </body>
    </html>
    ```

3. **External CSS**: Untuk penggunaan yang lebih efisien, Anda dapat membuat file CSS eksternal yang berdiri sendiri dan memuatnya ke dalam halaman HTML menggunakan tag `<link>`. Contohnya:

    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <link rel="stylesheet" type="text/css" href="styles.css">
    </head>
    <body>
        <p>Ini adalah teks dengan gaya eksternal.</p>
    </body>
    </html>
    ```

    Di file `styles.css`, Anda dapat menempatkan semua gaya CSS Anda:

    ```css
    p {
        color: blue;
        font-size: 16px;
    }
    ```

4. **Aturan @import CSS**: Anda juga dapat mengimpor file CSS lain ke dalam file CSS Anda menggunakan aturan `@import`. Ini memungkinkan Anda untuk memisahkan gaya Anda menjadi beberapa file yang terpisah untuk lebih mudah dikelola. Contohnya:

    Di dalam file `styles.css`:

    ```css
    @import url('reset.css');
    @import url('layout.css');
    @import url('colors.css');
    ```

    Dengan cara ini, Anda dapat mengelompokkan gaya berdasarkan fungsinya dan mengimpornya ke dalam file utama CSS Anda.

# Komentar (Comments)
Komentar dalam CSS digunakan untuk memberikan catatan atau penjelasan pada kode CSS Anda. Komentar tidak akan ditampilkan di halaman web, tetapi dapat membantu Anda atau orang lain memahami tujuan atau fungsi dari potongan kode CSS tertentu.

```css
/* Ini adalah komentar dalam CSS */
```