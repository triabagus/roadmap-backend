# Looping and Conditional Statement
Dalam pemrograman komputer, loop kondisional atau struktur kontrol berulang adalah cara bagi program komputer untuk mengulangi satu atau lebih berbagai langkah tergantung pada kondisi yang ditetapkan baik oleh programmer pada awalnya atau waktu-nyata oleh program yang sebenarnya.[wikipedia-conditional-looping](https://en.wikipedia.org/wiki/Conditional_loop).

## Manfaat
1. Agar bisa menggulang data yang akan ditampilkan. (looping)
2. Untuk menentukan kondisi tertentu dari sebuah program. (conditional)
3. Looping dan conditional sangat digunakan dalam program apapun, sebab inilah yang sebenarnya sangat membantu dalam kemudahan manusia dalam menggunakan komputer.
## Conditional Statement 
Dalam ilmu komputer, pernyataan kondisional, ekspresi kondisional, dan konstruksi kondisional adalah fitur dari bahasa pemrograman, yang melakukan perhitungan atau tindakan yang berbeda tergantung pada apakah kondisi boolean yang ditentukan pemrogram mengevaluasi benar atau salah.

![alt text](https://github.com/triabagus/roadmap-backend/tree/master/3.Looping%20and%20Conditional%20Statement/image/ifelse.gif)
### If Else 
Sangat sering ketika Anda menulis kode, Anda ingin melakukan tindakan berbeda untuk kondisi yang berbeda. Anda dapat menggunakan pernyataan kondisional dalam kode Anda untuk melakukan ini.

Dalam PHP kami memiliki pernyataan kondisional berikut:
1. if statement - mengeksekusi beberapa kode jika satu syarat benar.
2. if...else statement - mengeksekusi beberapa kode jika suatu kondisi benar dan kode lain jika kondisi itu salah.
3. if...elseif...else statement - mengeksekusi kode yang berbeda untuk lebih dari dua kondisi.
[if-else-conditional-php-w3school](https://www.w3schools.com/php/php_if_else.asp).

### Switch Case
Switch statement - digunakan untuk melakukan tindakan yang berbeda berdasarkan kondisi yang berbeda, [swicth-case](https://www.w3schools.com/php/php_switch.asp).

## Looping Statement
Perulangan yang dieksekusi untuk mengulang kode yang sama berkali-kali. Jumlah repetisinya itu beragam sesuai jumlah pengulangan.

![alt text](https://github.com/triabagus/roadmap-backend/tree/master/3.Looping%20and%20Conditional%20Statement/image/while.gif)
### While Loop
Seringkali saat Anda menulis kode, Anda ingin blok kode yang sama berulang kali berturut-turut. Alih-alih menambahkan beberapa baris kode yang hampir sama dalam sebuah skrip, kita dapat menggunakan loop untuk melakukan tugas seperti ini.


Dalam PHP, kami memiliki pernyataan perulangan berikut:

1. while - loop melalui blok kode selama kondisi yang ditentukan benar.
2. do ... while - loop melalui blok kode sekali, dan kemudian mengulangi loop selama kondisi yang ditentukan benar.

[while-looping-w3schooll](https://www.w3schools.com/php/php_looping.asp).
### For Loop
- jalankan blok kode beberapa kali.
```php
    for (init counter; test counter; increment counter) {
        code to be executed;
    }
```
Parameter: 
1. init counter: Menginisialisasi nilai penghitung loop .
2. test counter: Dievaluasi untuk setiap iterasi loop. Jika bernilai TRUE, loop berlanjut. Jika mengevaluasi ke FALSE, loop berakhir. 
3. increment counter: Meningkatkan nilai loop counter.
### Foreach Loop 
- hanya bekerja pada array, dan digunakan untuk mengulang setiap pasangan kunci / nilai dalam array.
```php
    foreach ($array as $value) {
        code to be executed;
    }
```
Untuk setiap iterasi loop, nilai elemen array saat ini ditetapkan ke $ value dan pointer array digerakkan oleh satu, sampai mencapai elemen array terakhir.
[for-foreach-looping-statement-w3schooll](https://www.w3schools.com/php/php_looping_for.asp).
### Nested Loop
Merupakan looping yang bersarang atau sering digunakan untuk mengulang perulangan yang diulang dalam kondisi tertentu,  [nested-looping](https://www.improgrammer.net/php-nested-loop/).

![alt text](https://github.com/triabagus/roadmap-backend/tree/master/3.Looping%20and%20Conditional%20Statement/image/nested.png)
## Latihan
1. Deret ganjil, genap, fibonacci, prima.
2. Membuat bintang segitiga siku, segitiga sama kaki, segitiga pascal.
3. Membuat matrix penjumlahan dan perkalian.

## Materi Sebelumnya
[Firts Touch](https://github.com/triabagus/roadmap-backend/tree/master/2.Firts%20Touch)
## Apa Selanjutnya ?
[Object Oriented Programming](https://github.com/triabagus/roadmap-backend/tree/master/4.Object%20Oriented%20Programming)

