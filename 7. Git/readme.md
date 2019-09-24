# Git
[Git](https://git-scm.com/doc) adalah version control system yang digunakan para developer untuk mengembangkan software secara bersama-bersama. Fungsi utama git yaitu mengatur versi dari source code program anda dengan mengasih tanda baris dan code mana yang ditambah atau diganti.

Git ini sebenernya memudahkan programmer untuk mengetahui perubahan source codenya dari pada harus membuat file baru seperti Program.java, ProgramRevisi.java,  ProgramRevisi2.java, ProgramFix.java. Selain itu, dengan git kita tak perlu khawatir code yang kita kerjakan bentrok, karena setiap developer bias membuat branch sebagai workspacenya.Fitur yang tak kalah keren lagi, pada git kita bisa memberi komentar pada source code yang telah ditambah/diubah, hal ini mempermudah developer lain untuk tahu  kendala apa yang dialami developer lain.

## Beberapa perintah dasar Git :
* Git init : untuk membuat repository pada file lokal yang nantinya ada folder .git
* Git status : untuk mengetahui status dari repository lokal
* Git add : menambahkan file baru pada repository yang dipilih
* Git commit : untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository.
* Git push : untuk mengirimkan perubahan file setelah di commit ke remote repository.
* Git branch : melihat seluruh branch yang ada pada repository
* Git checkout : menukar branch yang aktif dengan branchyang dipilih
* Git merge : untuk menggabungkan branch yang aktif dan branch yang dipilih
* Git clone : membuat Salinan repository lokal
* Git pull : untuk mengambil commit terbaru dari remote repository.

## Contoh menggunakan Git :
* Git Init
    - ketik diterminal
    ``` bash
        git init
    ```
    untuk membuat repository(folder) pada file lokal yang nantinya ada folder .git

* Git Add
    - ketik diterminal
    ``` bash
        git add . atau git add *
    ```
    menambahkan file baru pada repository(folder) keseluruhan

    atau

    ``` bash
        git add (nama file)
    ```
    menambahkan file baru pada repository(folder) yang dipilih

* Git Status
    - ketik diterminal
    ``` bash
        git status
    ```
    untuk mengetahui status dari repository lokal apakah sudah diadd dan dihapus atau belum

* Git Commit
    - ketik diterminal
    ``` bash
        git commit -m "(pesan yang apa kamu lakukan)"
    ```
    untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository(folder).

* Git Push
    - ketik diterminal
    ``` bash
        git push origin master
    ```
    untuk mengirimkan perubahan file setelah di commit ke remote repository(folder).

* Git Pull
    - ketik diterminal
    ``` bash
        git pull origin master
    ```
    untuk mengambil commit terbaru dari remote repository(folder).

## Exercise
1. Coba buat repository di github atau gitlab
2. Coba untuk menclone dari github atau gitlab
3. Coba untuk mengepush ke github atau gitlab



## Link belajar Git
* [Basic Git](https://git-scm.com/doc)
* [Workflow Git](https://medium.com/quick-code/top-tutorials-to-learn-git-for-beginners-622289ffdfe5)

## Beberapa application Git :
* [Github](https://github.com)
* [Gitlab](https://about.gitlab.com)
* [Bitbucket](https://bitbucket.org)
* [Assembla](https://www.assembla.com/home)

# Sebelumnya
[Database](https://github.com/triabagus/roadmap-backend/tree/master/6.%20Database)
# Apa Selanjutnya ?
[Error & Exception](https://github.com/triabagus/roadmap-backend/tree/master/8.Error-Exception)
