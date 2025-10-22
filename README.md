



# Tutorial Menggunakan Git

Petunjuk penggunaan Git dalam membuat project sederhana menggunakan python.


Nama : Varel Nico Ramadhan

NIM : 312510156

Kelas : TI.25.A.2



## Persiapan

Bahan bahan yang akan kita gunakan adalah :

- Python (Jika belum ada, bisa unduh [disini](https://www.python.org/downloads/))

- Git (Jika belum ada, bisa unduh [disini](https://git-scm.com/downloads))

- GitHub (Pastikan sudah memiliki akun GitHub, kalau belum punya silakan [daftar](https://github.com/))



## Instalasi

Jika bahan - bahan di atas sudah ada semua, silakan lewati bagian ini.  



### Menginstal Git 

1. Jalankan file instalasi Git.

2. Maka akan tampil dialog instalasi Git, lalu klik **Next**.



3. Pilih lokasi untuk menginstall Git, lalu klik **Next**.



4. Pilih komponen yang akan digunakan. Kali ini kita biarkan saja default, lalu klik **Next**.


5. Pada tampilan ini, klik **Next**.


6. Pilih text editor favorit anda atau biarkan saja default, lalu klik **Next**.


7. Pilih **Override the default branch name for new repositories** dan biarkan saja namanya **main** agar nama branch default yang ada di Git lokal dan di GitHub sama, lalu setelah itu klik **Next**.

<p align="center"><a href="src/Instalasi GIT/klik-next-terus.png" target="_blank"><img src="src/Instalasi GIT/klik-next-terus.png" width="400" alt="Laravel Logo"></a></p>



8. Selanjutnya klik **Next** terus sampai muncul tampilan ini :

<p align="center"><a href="src/Instalasi GIT/proses-instalasi.png" target="_blank"><img src="src/Instalasi GIT/proses-instalasi.png" width="400" alt="Laravel Logo"></a></p>



9. Kalau prosesnya sudah selesai, klik **Finish**.

<p align="center"><a href="src/Instalasi GIT/instalasi-selesai.png" target="_blank"><img src="src/Instalasi GIT/instalasi-selesai.png" width="400" alt="Laravel Logo"></a></p>



10. Selamat, Git sudah terinstall di komputer anda. Untuk memastikan apakah Git sudah terinstall, anda bisa membuka **Windows Search** lalu ketik "**Git**". Jika sudah muncul aplikasi Git maka Git sudah berhasil terinstall.

<p align="center"><a href="src/Instalasi GIT/cek-git-di-windows-search.png" target="_blank"><img src="src/Instalasi GIT/cek-git-di-windows-search.png" width="600" alt="Laravel Logo"></a></p>



11. Atau bisa juga menggunakan Command Prompt (CMD), ketik ```git -v```. Jika CMD menampilkan pesan "**git version 2.xxx**".

<p align="center"><a href="src/Instalasi GIT/cek-git-di-cmd.png" target="_blank"><img src="src/Instalasi GIT/cek-git-di-cmd.png" width="700" alt="Laravel Logo"></a></p>



### Menginstall Python

1. Jalankan file instalasi Pthon

2. Checklist bagian "**Add python.exe to PATH**", lalu klik "**Install Now**".



3. Tunggu sampai proses instalasi selesai.



4. Lalu klik "**Disable path length limit**", kemudian klik "**Close**".



5. Untuk memastikan apakah Python sudah terinstall di komputer, anda bisa check menggunakan terminal/Command Prompt (CMD) dengan mengetik ```python --version```.



## Mempersiapkan GitHub

1. Buka browser favorit anda, lalu ketikkan "**GitHub.com**" atau bisa juga klik [disini](https://github.com/).



2. Klik **Sign in** terlebih dahulu jika belum memiliki akun, jika sudah memiliki akun maka klik **Sign In**.



3. Setelah itu, maka akn masuk ke halaman beranda GitHub nya. Sekarang buat sebuah repository terlebih dahulu dengan mengklik "**New**".



4. Beri nama untuk repositorinya, misalkan **lab1py**. lalu klik **Create Repository**.



5. Maka akan masuk ke dalam repository yang baru saja dibuat.


## Membuat Project Sederhana

Jika semua bahan yang dibutuhkan sudah ada, sekarang waktunya kita membuat project sederhana menggunakan Python.  



Kita akan membuat 3 buah latihan project seperti berikut:  

1. Latihan 1 : Menampilkan tulisan "Hello" dan menampilkan tulisan "Saya sedang belajar python" menggunakan Python Console.

2. Latihan 2 : Menjumlahkan dua buah bilangan menggunakan variable a dan b.

3. Latihan 3 : Membuat flowchart untuk menentukan bilangan terbesar dari 3 buah bilangan yang diinputkan.  



3 latihan project inilah yang akan kita upload ke GitHub menggunakan Git.



### Membuat Folder

Sebelum memulai project diatas, hal yang harus dilakukan pertama kali ada membuat folder baru untuk menyimpan semua project yang akan kita buat.



1. Cari lokasi untuk menambahkan folder project.

2. Beri nama folder tersebut dengan **lab1py**.

3. Lalu masuk kedalam folder tersebut.

4. Kemudian buat lagi 3 buah folder baru sesuai dengan project yang akan kita buat.



### Inisialisasi Git

Setelah membuat folder, langkah selanjutnya adalah menginisialisasi git pada folder **lab1py**. Ada beberapa cara untuk menginisialisasi git pada folder.



1. Menggunakan Terminal

    - Masuk ke dalam folder **lab1py**, lalu klik kanan untuk memunculkan menu.

    - Klik **Open in Terminal**.

    - Lalu ketik ```git init``` di terminal. Maka akan tampil seperti ini.



2. Menggunakan Git Bash

    - Buka Windows Search, ketikkan Git Bash. Lalu buka aplikasinya.

    - Kemudian masuk ke folder **lab1py**, lalu salin lokasi foldernya.

    - Kembali lagi ke Git Bash, ketik "**cd (spasi) tempel lokasi folder yang dicopy tadi disini**" lalu tekan **Enter** di keyboard. Contoh :

    ```

    cd C:\Project\lab1py

    ```

    - Setelah itu, ketik ```git init``` di Git Bash lalu tekan Enter.



### Membuat Project Latihan 1

1. Buka terminal/Command Promt(CMD).



2. Ketik ```python``` lalu tekan enter.



3. Lalu ketik ```print("Hello")``` dan tekan **enter**.


4. Kemudian ketik lagi ```print("Saya sedang belajar python")``` dan tekan enter.


5. Pastikan hasil output yang tampil sudah benar dan sesuai dengan gambar diatas. Setelah itu ScreenShoot hasil output yang tampil, lalu simpan hasil screenshootnya kedalam folder **Latihan 1**.



6. Setelah itu, buka lagi Git Bash nya dan ketik ```git add .``` lalu tekan **Enter** untuk menambahkan file screenshoot yang ada di folder Latihan 1 ke dalam Git Lokal



### Membuat Project Latihan 2

1. Buka lagi terminal/CMD nya. Sekarang ketik :

```

 a = 8

 b = 6

 print("variable a adalah", a)

 ```

2. Kemudian tekan **Enter**. Maka terminal/CMD akan menampilkan pesan berikut :



>variable a adalah 8



3. Selanjutntya, ketik ```print("variable b adalah", b)``` lalu tekan **Enter**. Maka akan tampil pesan :

>variable b adalah 6



4. Kemudian, ketik lagi ```print("hasil penjumlahan a + b adalah", a+b)``` lalu tekan **Enter**. Maka akan tampil :

> hasil penjumlahan a + b adalah 14



5. Screenshot lagi hasil output dari terminal/cmd-nya, lalu simpan ke folder **Latihan 2**.



6. Setelah itu, buka lagi Git Bash nya dan ketik ```git add .``` lalu tekan **Enter** untuk menambahkan file screenshoot yang ada di folder Latihan 2 ke dalam Git Lokal.



### Git Commit

Commit adalah perintah dalam Git yang digunakan untuk menyimpan perubahan pada repository. Setiap kali Anda melakukan commit, Git akan mencatat revisi tersebut sebagai bagian dari riwayat proyek. Ini memungkinkan Anda untuk melacak perubahan, kembali ke versi sebelumnya, atau memperbaiki kesalahan tanpa perlu menyimpan banyak salinan file.  



1. Buka **Git Bash** lagi. lalu ketik ```git commit -m "pesan yang ingin disimpan"``` contoh :

```

git commit -m "membuat project sederhana menggunakan python"

```
