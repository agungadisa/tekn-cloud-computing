Pertemuan ke-4 Praktikum Teknologi Cloud
Instalasi Openstack pada Ubuntu 18.04.3

Sebelum memulai praktikum kali ini, kita harus menyiapkan OS yang akan digunakan yaitu Ubuntu 18.04.3 dengan ketentuan spesifikasi sebagai berikut.

~

Maka dari ini pada proses instalasi Ubuntu pada Virtualbox Manager kita sesuaikan dengan spesifikasi yang diminta ~

   Update Ubuntu

Karena kita masih baru saja menggunakan OS Ubuntu tersebut maka semua software yang ada telah lama tidak ter-update maka dari itu kita memerlukan proses update untuk software - softwarenya ~ ~ ~

Setelah proses Update telah selesai, kita harus melakukan reboot terlebih dahulu agar software yang telah diupdate dapat berjalan dengan baik

~

   Tambah User Stack

Pada praktikum kali ini kita menggunakan user baru dengan nama "stack" pada Ubuntu ~ ~

   Install Git dan download devstack

untuk proses install git dan download devstack disini kita akan melakukannya pada user stack ~ ~

   Membuat konfigurasi file devstack

Bagian ini merupakan bagian paling penting dikarenakan setiap pengaturan pada masing - masing pengguna akan berbeda. Yang membedakan yaitu ada pada host IP Untuk mengecek berapa host IP yang dimiliki oleh kita yaitu dengan menggunakan perintah ifconfig

~

host IP tersebut nantinya akan digunakan di dalam pengaturan file local.conf

~ ~

   Install Openstack

Untuk melakukan instalasi Openstack dapat dengan menggunakan perintah ./stack.sh , namun proses ini membutuhkan waktu lumayan lama tergantung koneksi internet yang dimiliki ~

Bila proses telah selesai maka hasil akhirnya akan menampilkan tampilan berikut ~
