# hacktoberfest-how-to-use-git
Mari berkontribusi membuat tutorial cara menggunakan GIT dengan bahasa Indonesia.

## Daftar isi:

- [Instalasi Git](#instalasi)
- [Konfigurasi Git](#konfigurasi)
- [Membuat repository](#membuat-repository)
- [Cloning repository](#cloning-repository)
- [Membuat branch](#membuat-branch)
- [Push repository](#push-repository)
- ucom

## Instalasi

- #### Debian/Ubuntu
    - Untuk versi stabil terbaru rilis Debian / Ubuntu
        Buka terminal window, masukkan perintah
        `sudo apt-get install git`
    - Untuk Ubuntu, PPA ini menyediakan versi stabil upstream Git terbaru
        `sudo add-apt-repository ppa:git-core/ppa` 
        `sudo apt update; sudo apt install git`
- #### Windows
    - Unduh git untuk windows [disini](https://gitforwindows.org/).
    - Setelah selesai unduh, lakukan proses instalasi
    - Pada saat instalasi ada beberapa tahap :
        1. Informasi, Berisikan tentang lisensi aplikasi
        2. Select Component, Pilih komponen yang akan diinstall
        3. Choosing the default editor used by Git, memilih editor standar untuk git. Rekomendasi saya menggunakan Visual Studio Code
        4. Adjusting your PATH environment, ada beberapa pilihan. Git hanya bisa dijalankan di Git Bash, Menggunakan Git dari Command Prompt Windows, Semua unix terminal dan Git bas akan terpasang. Rekomendasi pilih yang kedua : Use Git from the Windows Command Prompt
        5. Choosing HTTPS transport backend, Pilih tipe SSL/TLS librari yang ingin digunakan Git. Rekomendasi gunakan Open SSL
        6. Configuration the line ending conversions, pilih pada pilihan pertama. Git akan melakukan konversi file dari LF ke CRLF
        7. COnfiguration the terminal emulator to use with Git Bash, Pilih pada pilihan ke dua Use Windows's default console windows. Karena command prompt lebih enak untuk digunakan dan lebih cepat
        8. Configuration extra options, ini optional untuk menghemat memori file system caching baiknya di disable, untuk memeprmudah login ke akun yang berbeda Git Credential Manager di disable tapi sebaliknya jika cuma untuk 1 akun baiknya di aktifkan jadi setiap proses push tidak perlu login ulang
        9. Lalu klik install
    - Setelah selesai proses instalasi/ pemasangan buka command prompt dan ketikan
        `git --version`
        Jika yang muncul adalah versi git yang anda pasang, selamat kamu berhasil
- #### Mac
    - Cara termudah memasang Git pada Mac yaitu sama seperti pada Windows, melalui aplikasi tunggal
    - Unduh Git terbaru dan stabil [disini](https://sourceforge.net/projects/git-osx-installer/files/).
    - Setelah selesai di unduh dan di install
    - Lakukan pengecekan diterminal apakah Git sudah bisa digunakan. Ketik diterminal :
        `git --version`
        Jika muncul adalah versi Git yang anda pasang, selamat kamu berhasil

## Konfigurasi

## Membuat repository

## Cloning repository

## Membuat branch

## Push repository
