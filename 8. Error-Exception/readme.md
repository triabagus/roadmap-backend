# Error & Exception PHP
Dalam proses pembuatan atau proses maintenance suatu program, kadang kita mendapati program tidak dapat berjalan atau mungkin berjalan tetapi tidak sesuai dengan keinginan kita. Ada banyak faktor yang mengakibatkan kegagalan suatu program, bisa jadi karena kesalahan sang programer,user atau mungkin karena faktor lain.
    
## Error
Dalam pemrograman, error merupakan kesalahan atau kegagalan program untuk mengeksekusi sebuah perintah. Biasanya, saat kita coba untuk mengetes program seperti mencobanya di localhost / browser, kita malah mendapatkan tulisan error entah undifined,unexpected, no such file or directory, atau mungkin muncul error code seperti 404 (not found),500 dll.

Beberapa error yang sering kita dapati diantaranya:
1. Parse error (syntax error)
    adalah kesalah dalam penulisan syntax php, pesan kesalah akan muncul ketika di jalankan. Parse error akan menghentikan proses eksekusi script. Parse error biasa terjadi karena typo.

2. Fatal error 
    tidak ada kesalahan dalam penulisan sytax, tapi PHP tidak bisa mengeksekusi perintah. Ini terjadi saat function yang di minta belum didefinisikan atau yang lainnya. Fatal error akan menghentikan proses eksekusi script.

3. Warning error
    salah satunya terjadi saat kita menyertakan file yang tidak ada. Warning error tidak akan menghentikan proses eksekusi script

4. Notice error
    bisa kita dapatkan saat kita mengakases variable yang belum didefinisikan. Notice error tidak akan menghentikan proses eksekusi script

Selain error-error di atas, masih banyak sekali pembagian,tipe dan jenis error, silahkan explore sendiri untuk mengetahui lebih lanjut tentang error di PHP

## Exception
Exception merupakan kondisi pengecualian pada program. Exception akan mengubah alur program ke mode normal jika terjadi error. Dengan kata lain, exception mengabaikan error yang terjadi dan mengerjakan proses tertentu saat exception tertangkap.

Untuk menggunakan exception dilakukan dengan perintah try dan catch. Perintah try berisi kode-kode yang berisi pengecualian program dan perintah catch berfungsi menangkap kode kode yang dikirim oleh pengecualian pada try. Proses pengiriman kode exception ini biasa disebut dengan throw (melempar).


Ketika exception terjadi karena dipicu oleh error, status kode program akan aman karena eksekusi program akan dialihkan ke kode program penanganan exception (exception handler). Jadi pada kondisi ini exception handler akan meresume eksekusi dari status kode yang tersimpan lalu menghentikan eksekusi script dan melanjutkannya dengan kode pada lokasi lain didalam program.

```php
    function new_function($variable) {  
        if_condition(condition){  
            throw new Exception("Message");  
        } return true;  
    }
    
    try {  
        new_function(value);  
        non_error_statement...;  
    }  

    catch(Exception $e) {  
        error_message...;  
    }  
```

## Excercise
1. Coba tampilkan error2 yang ada di penjelasan tadi
2. Coba perbaiki codingan agar error tidak muncul lagi
3. Gunakan exception, lalu coba tampilkan pada line berapa error muncul


## Link
* [Beberapa Jenis Error Yang Mungkin Kamu Temui Saat Menggunakan PHP! - codepolitan](https://www.codepolitan.combeberapa-jenis-error-yang-mungkin-kamu-temui-saat-menggunakan-php)
* [PHP Exception Handling - w3schools](https://www.w3schools.com/php/php_exception.asp)
* [Penanganan Exception pada PHP - nulis-ilmu](https://nulis-ilmu.com/penanganan-exception-pada-php/)
* [Error dan Exception - mrisnawanbudianto](https://mrisnawanbudianto.wordpress.com/2014/05/12/error-dan-exception/)
* [PHP - Error & Exception Handling - tutorialspoint](https://www.tutorialspoint.com/php/php_error_handling.htm)
* [PHP 5 Error Functions - w3schools](https://www.w3schools.com/php/php_ref_error.asp)
* [5 TIPS MENGHADAPI ERROR SAAT NGODING - WEB PROGRAMMING UNPAS](https://www.youtube.com/watch?v=P9369f65RXo)

# Sebelumnya
[Git](https://github.com/triabagus/roadmap-backend/tree/master/7.%20Git)
# Apa Selanjutnya ?
[Authentication](https://github.com/triabagus/roadmap-backend/tree/master/9.%20Authentication)