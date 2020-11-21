# Apa itu Ansible?
> Ansible adalah _tool automation_ yang dimiliki oleh perusahaan yang bergerak dibidang teknologi yaitu RedHat. Ansible adalah perangkat lunak _open source_ yang mengotomatiskan pemasangan perangkat lunak, manajemen konfigurasi, dan beberapa tugas lainnya. Ansible terhubung dengan _client remote_ nya menggunakan ssh. 

# Apa Kelebihan Ansible?
### 1. Mudah digunakan
> Ansible mudah digunakan karena dapat langsung digunakan dengan 1 command line.
### 2. Mudah dipahami
> Selain digunakan langsung dengan 1 command line, ansible juga mendukung pengumpulan tugas yang biasa disebut dengan _ansible-playbook_, playbook ini berisikan pekerjaan pekerjaan yang akan dieksekusi secara berurutan. Playbook ini dibuat dengan format yaml yang mudah dipahami. Dengan menggunakan dan juga semua konfigurasi saat ini tetap sama seperti konfigurasi di hari berikutnya.
### 3. Terdokumentasi 
> Penggunaan ansible cukup membuat 1 konfigurasi dan bisa dieksekusi berkali-kali dengan hasil yang sama.
### 4. Mendukung _Command Bash_
> Ansible memiliki banyak _module_ yang bisa digunakan. Jika ingin mengeksekusi perintah tertentu namun belum ada di _module_ ansible, pengguna tetap bisa mengesekusinya dengan _module command_ dan kemudian bisa kalian isi dengan _command_ yang ingin dieksekusi.

> [Referensi 1](https://sibunglon.com/2019/01/19/berkenalan-dengan-ansible/)
 
# Apa Kekurangan Ansible?
### 1. _User Interface_ kurang memadai
> AWX GUI (_Graphical User Interface_) terkadang tidak sinkron dengan _command line_, sehingga menghasilkan _query_ yang berbeda.
### 2. Dukungan Windows kurang memadai
> Ansible masih awal dalam upayanya untuk memperluas dukungan untuk Windows. Pada versi 1.7, Ansible mendukung node Unix / Linux dan Windows. Untuk yang terakhir, ia menggunakan remote PowerShell asli (sebagai lawan dari SSH), dan mesin kontrol Linux masih diperlukan untuk mengelola host Windows.
### 3. Ansible terbatas dalam dukungan community
> Ansible memiliki komunitas pengembang / pengguna terkecil dibandingkan dengan Chef atau Puppet dan memiliki materi paling sedikit di web untuk bantuan mandiri dan pemecahan masalah. Lebih sedikit berarti bahwa masalah tertentu seperti _bug_, dan masalah perangkat lunak mungkin belum terungkap.
> [Referensi 2](https://www.upguard.com/blog/top-5-best-and-worst-attributes-of-ansible)
