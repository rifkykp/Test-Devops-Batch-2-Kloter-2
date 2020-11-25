# Install aplikasi web server Nginx pada server Ubuntu WSL 2
1. Untuk memulai menginstall Nginx kita bisa dengan mengetikan perintah _sudo apt-get install nginx_, lalu ketikkan _y_ untuk melanjutkan.
> ![image](https://user-images.githubusercontent.com/74203416/99876930-dc3b7780-2c2c-11eb-9dd9-dfc3b841ec0f.png)

> **Sebelum ke langkah ke 2, perlu diketahui saya menggunakan WSL 2 Ubuntu pada Windows 10 yang menggunakan _Sysvinit Command_**
2. Jika instalasi sudah selesai maka kita jalankan web server nginx dengan perintah _sudo service nginx start_, lalu cek status nginx nya apakah sudah running atau belum dengan cara mengetikan perintah _sudo service nginx status_. 
> ![image](https://user-images.githubusercontent.com/74203416/99877166-bca54e80-2c2e-11eb-8579-d833ff03f6b2.png)

3. Setelah itu bisa dicek server nginx di browser dengan mengetikkan _localhost_
> ![image](https://user-images.githubusercontent.com/74203416/100212238-b1f4fd00-2f3f-11eb-8a2c-e3e8c63b261b.png)

# Install PHP di web server
1. Instalasi dengan cara mengetikkan perintah _sudo apt-get install php libapache2-mod-php_, lalu ketikkan _y_ untuk melanjutkan.
> ![image](https://user-images.githubusercontent.com/74203416/99877815-61c22600-2c33-11eb-8451-9397f3e162ba.png)
2. Lalu cek PHP yang terinstall
> ![image](https://user-images.githubusercontent.com/74203416/99878484-43aaf480-2c38-11eb-97fc-e651e70f7c11.png)
3. Konfigurasikan PHP ke nginx _default host_. 
> a. Pertama menambahkan _index.php_ ke _sudo nano /etc/nginx/sites-available/default_ dan menghilangkan tanda _**#**_ sesuai pada gambar.
  
> *Before* 
> > ![image](https://user-images.githubusercontent.com/74203416/100214055-faadb580-2f41-11eb-9ec6-33481ed4901b.png)
> > ![image](https://user-images.githubusercontent.com/74203416/100216409-d43d4980-2f44-11eb-98a8-66087bf5182d.png)

> *After*
> > ![image](https://user-images.githubusercontent.com/74203416/100216763-42820c00-2f45-11eb-8409-2d3f88921e98.png)
> > ![image](https://user-images.githubusercontent.com/74203416/100217011-8c6af200-2f45-11eb-98a2-a81f398e1d4b.png)

> b. Lalu tekan _Ctrl+S_ untuk save dan _Ctrl+X_ untuk keluar, restart nginx dan php-fpm

4. Menguji php 
> a. Membuat file index.php dengan perintah _sudo touch /var/www/html/index.php_. 

> b. Edit dengan perintah _sudo nano /var/www/html/index.php_

> c. Lalu tambahkan sesuai pada gambar, simpan dan keluar. 
> > ![image](https://user-images.githubusercontent.com/74203416/100218444-59296280-2f47-11eb-9155-99a59222e3c0.png)

> d. ketikkan _localhost_ di browser untuk melihat _index.php_
> > ![image](https://user-images.githubusercontent.com/74203416/100219307-6561ef80-2f48-11eb-8f70-eb019de03ebe.png)
