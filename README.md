# TCT - Ujian

> Apriliana Puspitasari

> 163210008

> Komputerisasi Akuntansi

---

**DockerFile** merupakan script atau file teks sederhana dengan serangkaian perintah 
yang akan dieksekusi secara otomatis dan berurutan untuk membuat sebuah image,
perintah tersebut terdapat pada setiap baris.

---

***Contoh Penggunaannya :***

1. Membuat dockerfile terlebih dahulu, karena pada saat praktikum saya pernah menggunakan 
katakoda maka dalam membuat dockerfile saya masuk dalam aplikasi katakoda.

![13](https://github.com/Apriliana2424/tct-docker-apriliana/blob/master/images/13.png)

Dari perintah diatas digunakan untuk menginstall dockerfile melalui nginx:alpine setelah mengcopy 
dari nginx/html secara otomatis dockerfile akan muncuk dibagian sebelah kiri yang menunjukkan bahwa dockerfile
telah terinstall disitu.

2. setelah dockerfile dibuat kemudian membuat **image** dengan nama **webserver-image:v1**

![14](https://github.com/Apriliana2424/tct-docker-apriliana/blob/master/images/14.png)

> Untuk memastikan bahwa image telah dibuat maka untuk mengeceknya dapat menggunakan perintah **docker images**

![15](https://github.com/Apriliana2424/tct-docker-apriliana/blob/master/images/15.png)

3. Membuat container untuk digunakan oleh image

Namun disini pembuatan container tidak diberi nama atau secara otomatis tanpa nama.

![16](https://github.com/Apriliana2424/tct-docker-apriliana/blob/master/images/16.png)

> Port yang digunakan dalam pembuatan container tersebut adalah port 80:80

4. Mencoba container dalam localhost menggunakan perintah curl.

![17](https://github.com/Apriliana2424/tct-docker-apriliana/blob/master/images/17.png)

Untuk dapat dijalankan dibrowser dapat membuka dengan menuliskan url alamat ip dari computer yang digunakan.

---