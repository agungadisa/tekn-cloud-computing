Docker Compose

Pada praktikum ke 8 ini kita masih sama menggunakan terminal dari Docker toolbox yang telah kita install pada praktikum sebelumnya ~

Namun pada praktikum kali ini kita akan mencoba mengenal tentang Docker Compose Docker-compose disini adalah sebuah alat dari docker yang digunakan untuk mendefinisikan dan menjalankan aplikasi multi kontainer. Dengan docker-compose kita bisa menjalankan kontainer 1 dengan yang lainya dengan 1 perintah . Docker-compose juga menggunakan yaml file untuk menyimpan konfigurasi dari service yang dibuat.

Dalam praktikum ini kita akan membuat folder baru sebagai tempat untuk melakukan praktikum bernama composetest ~

    Membuat file setup

app.py

~
requirements.txt

~

   Membuat Dockerfile

~

   Membuat docker-compose.yml untuk konfigurasi service ~

   Menjalankan compose-up

~

Dihasil akhir nantinya kita akan mengakses localhost:5000 di browser
