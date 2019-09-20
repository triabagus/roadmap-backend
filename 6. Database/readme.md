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
[w3schooll-sql](https://www.w3schools.com/sql/sql_intro.asp)
# NoSQL Database
[7-basis-data-nosql-populer](https://www.codepolitan.com/7-basis-data-nosql-populer)

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