# Install aplikasi web server Nginx pada server Ubuntu WSL 2
1. Untuk memulai menginstall Nginx kita bisa dengan mengetikan perintah _sudo apt-get install nginx_, lalu ketikkan _y_ untuk melanjutkan.
> ![image](https://user-images.githubusercontent.com/74203416/99876930-dc3b7780-2c2c-11eb-9dd9-dfc3b841ec0f.png)

> **Sebelum ke langkah ke 2, perlu diketahui saya menggunakan WSL 2 Ubuntu pada Windows 10 yang menggunakan _Sysvinit Command_**
2. Jika instalasi sudah selesai maka kita jalankan web server nginx dengan perintah _sudo service nginx start_, lalu cek status nginx nya apakah sudah running atau belum dengan cara mengetikan perintah _sudo service nginx status_. 
> ![image](https://user-images.githubusercontent.com/74203416/99877166-bca54e80-2c2e-11eb-8579-d833ff03f6b2.png)

# Install PHP di web server
1. Instalasi dengan cara mengetikkan perintah _sudo apt-get install php libapache2-mod-php_, lalu ketikkan _y_ untuk melanjutkan.
> ![image](https://user-images.githubusercontent.com/74203416/99877815-61c22600-2c33-11eb-8451-9397f3e162ba.png)
2. Lalu cek PHP yang terinstall
> ![image](https://user-images.githubusercontent.com/74203416/99878484-43aaf480-2c38-11eb-97fc-e651e70f7c11.png)

 
