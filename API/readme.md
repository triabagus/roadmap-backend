# API
Application Programming Interface merupakan sekumpulan fungsi,perintah dan protokol untuk membuat perangkat lunak. API merupakan interface yang berupa kumpulan fungsi yang bisa dipanggil atau dijalankan oleh program lain.

Penerapan API bisa sangat luas, diantaranya:
* Bahasa pemrograman
    - salah satu contoh yaitu connect ke database menggunakan PDO atau mysqli di dalam bahasa PHP
* Framework / Library
    - contohnya saat menggunakan JQuery kita sering mengambil data menggunakan ajax
* Sistem Operasi
    - di dalam sistem operasi terdapat script2 yang bisa menghubungkan kita ke dalam sistem OS tersebut
* Web API / Web Service
    - website traveloka mengambil data (harga,jadwal,status) dari web lain

## Web API / Web Service
merupakan sebuah sistem perangkat lunak yang di buat untuk mendukung interaksi antar 2 aplikasi yang berbeda memalui jaringan

## REST API
gaya arsitektural perangkat lunak yang di dalamnya mendefinisikan aturan-aturan untuk membuat web service. Lebih mudah nya kita anggap RESt API itu berisi aturan2 mengenai data apa saja yang bisa di akses.
Dengan menggunakan REST API kita bisa menggunakan fitur CRUD.

## JWT
merpuakan singkatan dari JSON Web Token, JWT ini adalah sebuah token berbentuk string panjang yang sangat random yang berguna untuk melakukan sistem Authentifikasi dan pertukaran informasi.
Setelah user berhasil login maka serve akan memberikan sebuah token yang akan disimpan di local storage atau cookie browser dan bila user ingin mengakses halaman tersebut maka harus menyertakan token tersebut. Untuk itu user mengirimkan kembali token yang ada sebagai bukti bahwa user telah login.

## Excercise
1. Ikuti REST API series dari Web Programming UNPAS

## Link
* [REST API Series - Web Progamming UNPAS](https://www.youtube.com/watch?v=vQJJ_K1JbEA&list=PLFIM0718LjIW7AsIbnhFg15t9yx4H-sQ0)
* [What is API - MuleSoft Videos](https://www.youtube.com/watch?v=s7wmiS2mSXY)
* [REST vs RESTful - stackoverflow](https://stackoverflow.com/questions/1568834/whats-the-difference-between-rest-restful)
* [Memahami konsep JWT - dumetschool](https://www.dumetschool.com/blog/mengenal-konsep-json-web-token-jwt)
* [Build and testing REST API dengan aplikasi laravel - medium](https://medium.com/@tedoharischandra29/membangun-dan-testing-rest-api-dengan-crud-sederhana-laravel-687a7d96ab3b)
* [Implementing JWT on laravel 5.8 - medium](https://medium.com/@manuelmauriciozamarrn/implementing-jwt-on-laravel-5-8-edc39f545886)