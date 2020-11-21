# Definisi Devops 
> DevOps adalah serangkaian praktik yang mengotomatiskan proses antara pengembangan aplikasi dan tim pengembang agar mereka dapat melakukan proses _build_, _test_ dan _release_ perangkat lunak lebih cepat dan lebih maksimal. [Referensi 1](https://www.codepolitan.com/berkenalan-dengan-devops-5ab7bbe4947b4)
# Kenapa DevOps Sangat Penting dalam Perusahaan?
> Adanya DevOps dalam perusahaan tentu akan sangat penting karena dapat mengurangi jumlah kesalahan, _recovery_ lebih cepat dan _deploy_ lebih banyak sehingga menjadi lebih efisien. [Referensi 2](https://medium.com/purwadhikaconnect/mengapa-devops-penting-27dd08115ad3#:~:text=Adanya%20DevOps%20dalam%20perusahaan%20tentu,%2C%20multi%2Dtenant%20dan%20cloud.)
# Bagaimana Flow Devops dari awal hingga ke production?
> ![image](https://miro.medium.com/max/4096/1*57INuyf56018l0Y_Pel0ig.png)
> Secara berurutan, langkah-langkah proses DevOps adalah:
* **_Plan:_** Ini adalah bagian dari _project_ dimana Andi mengatur tugas, jadwal dan bisa juga menyiapkan _project management tools_. Tujuannya adalah menjabarkan tugas dalam bentuk _user story_ dalam metodologi _agile_ yang memungkinkan pihak _Dev_ dan _Ops_ memahami apa saja hal yang perlu dikembangkan.    
* **_Code:_** Di sini pihak _Dev_ melakukan pengembangan kode dan peninjauan kode. Ketika kode sudah siap, mereka menggabungkannya. Dalam praktik DevOps, penting untuk berbagi alat kode antara pihak _Ops_ dan pihak _dev_ seperti Github atau Gitlab.
* **_Build:_** Langkah ini adalah langkah pertama menuju otomatisasi. Tujuannya di sini adalah untuk membangun _source code_ menjadi satu format yang diinginkan, menyusun, menguji, dan menerapkan di tempat infrastruktur tertentu. Setelah langkah ini dilakukan, alat integrasi berkelanjutan (_Continous Integration_) dan pengiriman (_Continous Delivery_) dapat memeriksa dan memverifikasi _source code_ dari _Source Code Management_ dan membangunnya.
* **_Test:_** Proses pengujian berkelanjutan bisa mengurangi risiko. Dengan pengujian berkelanjutan, otomatis memastikan bahwa tidak ada _bug_ yang akan diterapkan dalam produksi. Andi harus menerapkan alat pengujian dalam alur kerja untuk memastikan kualitas pengembangan terbaik untuk perangkat lunak.
* **_Release:_** Kode yang telah lulus proses pengujian dan siap untuk di _deploy_.
* **_Deploy:_** Pihak _Ops_ menerapkan fitur baru dalam produksi. Namun karena otomatisasi adalah salah satu prinsip DevOps, penerapan berkelanjutan (_Continous Deployment_) dimungkinkan.
* **_Operate/ configure infrastructure:_** Pihak _Ops_ membangun atau memelihara infrastruktur yang dapat diskalakan, infrastruktur sebagai kode (_IaC_) dan memeriksa masalah keamanan dan manajemen _log_.
* **_Monitor:_** Pemantauan merupakan langkah penting karena jika ditemukan insiden, memungkinkan untuk memperbaiki lebih cepat dan untuk menciptakan pengalaman yang lebih baik bagi _end-user_.
> DevOps bertujuan untuk meningkatkan kepuasan _user_ secara signifikan, Itulah mengapa DevOps selalu diilustrikan sebagai alur kerja atau _loop_ tanpa akhir.
[Referensi 3](https://www.padok.fr/en/blog/devops-process)
