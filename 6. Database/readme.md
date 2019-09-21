# Database
Kalau kita kembali ke Introduction hal ini sudah dibahas sebelumnya untuk area Server Side akan berhubungan langsung dengan servernya. Adapun Database adalah hal yang penting diketahui oleh teman-teman sekalian sebagai Backend Developer.

Pertama kita harus bedakan terlebih dahulu antara Layanan Paket Aplikasi dengan apa yang ada didalam paket itu apa saja.Kita perlu tau semisal kita nantinya akan membutuhkan server yang kita butuhkan saja.

Ada banyak sekali [macam-macam database](https://dosenit.com/kuliah-it/database/macam-macam-database) , namun kalian cukup belajar salah satu Database server untuk kedepannya kalian hanya perlu beradaptasi dengan database lainnya. Konsepnya tetaplah sama yaitu menyimpan data.

# Paket Web Server dan Database
1. [xampp](https://www.apachefriends.org/index.html) (mac,linux,windows)
2. [wamppServer](http://www.wampserver.com/en/) (windows)
3. AMP(Apache-MySQL-PHP) (linux)
4. [Mamp](https://www.mamp.info/en/) (mac)

Alangkah baiknya kalau kalian pengguna linux kalian bisa install yang diperlukan saja.
Sebenarnya di OS lain juga bisa seperti windows atau mac.

# SQL Database
SQL adalah bahasa standar untuk mengakses dan memanipulasi basis data, [materi-w3schooll-sql](https://www.w3schools.com/sql/sql_intro.asp).
# NoSQL Database
Sesuai dengan namanya basis data NoSQL adalah jenis basis data yang tidak menggunakan perintah SQL dalam memanipulasi (menyimpan maupun mengambil data) basis data tersebut. Kebanyakan basis data NoSQL digunakan dalam dunia aplikasi web waktu nyata (real-time web app), [7-basis-data-nosql-populer](https://www.codepolitan.com/7-basis-data-nosql-populer).
1. [Redis](http://redis.io/)
2. [MongoDB](https://www.mongodb.com/)
3. [CouchDB](https://couchdb.apache.org/)
4. [Cassandra](https://cassandra.apache.org/)
5. [Riak](http://basho.com/riak/)
6. [Neo4j](http://neo4j.org/)
7. [OrientDB](http://www.orientechnologies.com/orientdb/)
# Akses Mysql
1. [With-xampp](https://stackoverflow.com/questions/698914/how-can-i-access-the-mysql-command-line-with-xampp-for-windows)
2. With-linux
- Ketik di terminal 
```bash
    mysql -u root -p // tergantung user

    Enter password: // masukkan password

    Welcome to the MySQL monitor.  Commands end with ; or \g.
    Your MySQL connection id is 6
    Server version: 5.7.27-0ubuntu0.18.04.1 (Ubuntu)

    Copyright (c) 2000, 2019, Oracle and/or its affiliates. All rights reserved.

    Oracle is a registered trademark of Oracle Corporation and/or its
    affiliates. Other names may be trademarks of their respective
    owners.

    Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

    mysql> 
```
# PHP Connection MYSQL AND PDO
PHP 5 dan yang lebih baru dapat bekerja dengan database MySQL menggunakan:
- MySQLi extension ("i" berarti perbaikan)
- PDO (PHP Data Objects)
Versi PHP yang lebih lama menggunakan ekstensi MySQL. Namun, ekstensi ini tidak digunakan lagi pada tahun 2012.
## Haruskah saya menggunakan MySQLi atau PDO?
Jika Anda membutuhkan jawaban singkat, itu akan menjadi "Apa pun yang Anda suka".[php_mysql_connect](https://www.w3schools.com/php/php_mysql_connect.asp) dan [materi-w3schooll-sql](https://www.w3schools.com/sql/sql_intro.asp).
Baik MySQLi dan PDO memiliki kelebihan:

| __MySQLi__ | __PDO__ |
|-------------|------------|
| MySQLi hanya akan bekerja dengan database MySQL.| PDO akan bekerja pada 12 sistem basis data yang berbeda     | 
| Menawarkan API prosedural| Tidak menawarkan API prosedural |

1. Jika Anda harus mengganti proyek Anda untuk menggunakan database lain, PDO mempermudah prosesnya. Anda hanya perlu mengubah string koneksi dan beberapa pertanyaan. Dengan MySQLi, Anda harus menulis ulang seluruh kode - termasuk queri.
2. Keduanya berorientasi objek
3. Keduanya mendukung Pernyataan Disiapkan. Pernyataan Disiapkan melindungi dari injeksi SQL, dan sangat penting untuk keamanan aplikasi web.
# Latihan
1. Make connection php with mysql dengan mysqli atau PDO
2. Make data Create Read Update Delete (CRUD)
3. Make Search and Pagination
4. Make contoh menampilkan data yang saling berhubungan [JOIN](https://www.dofactory.com/sql/join)
![alt text](https://github.com/triabagus/roadmap-backend/blob/master/6.%20Database/LEFT-OUTER-JOIN1.jpg)
5. Soal kedua JOIN

![alt text](https://github.com/triabagus/roadmap-backend/blob/master/6.%20Database/SQL-Joins-Left-Outer-Join.png)
# Sebelumnya
[Dependency Injection](https://github.com/triabagus/roadmap-backend/tree/master/5.%20Dependency%20Injection)
# Apa Selanjutnya ?
[Git](https://github.com/triabagus/roadmap-backend/tree/master/7.%20Git)
