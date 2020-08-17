Image Repo pada Docker Hub

Untuk dapat memulai praktik ini, kita harus memiliki akun docker.hub terlebih dahulu dan membuat repository pada docker.hub tersebut

Disini saya menggunakan akun docker.hub dengan nama "amharnh13" dan membuat repository dengan nama "testing" ~

Pada docker terminal, kita harus melakukan login akun docker terlebih dahulu dengan mengetikan perintah Docker Login kemudian isikan dengan data akun milik kita ~

Kemudian kita membuat file Dockerfile yang akan digunakan sebagai isi dari image yang akan kita buat nanti ~

Solusi lain untuk membuat file Dockerfile tersebut yaitu bisa dengan menggunakan editor Visual Studio Code atau dengan mengetikannya pada Notepad lalu menghilangan ekstensinya secara manual

Hal selanjutnya yang kita lakukan yaitu membangun Docker Build menggunakan repository yang telah kita buat dengan menggunakan perintah Docker Build ~

Setelah itu kita dapat melakukan pengujian dengan menjalankan docker image tersebut dengan menggunakan perintah docker run ~

Dan juga disini kita dapat melakukan penyimpanan image tersebut pada repository testing yang telah kita buat dengan menggunakan perintah docker push

~

Yang nantinya akan terlihat terdapat file yang telah terupload ke repository testing yang merupakan hasil dari docker push tersebut ~
