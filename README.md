# Lab2Web
## Langkah - langkah Praktikum
### 1. Membuat Dokumen HTML
Buatlah dokumen HTML seperti berikut
![image](/screenshot/ss1.png) <p>
Selanjutnya buka pada browser untuk melihat hasilnya
![image](/screenshot/ss2.png)
### 2. Mendeklarasikan CSS Internal
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.
![image](/screenshot/ss3.png) <p>
Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat
hasilnya.
![image](/screenshot/ss4.png)
### 3. Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag <p> seperti berikut.
< p style="text-align: center; color: #ccd8e4;"> <p>
Simpan kembali dan refresh kembali browser untuk melihat perubahannya.
![image](/screenshot/ss5.png)
### 4. Membuat CSS Eksternal
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.
![image](/screenshot/ss6.png) <p>
Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head>
< head>
<!-- menyisipkan css eksternal -->
< link rel="stylesheet" href="style_eksternal.css" type="text/css">
< /head>
Selanjutnya refresh kembali browser untuk melihat perubahannya.
![image](/screenshot/ss7.png)