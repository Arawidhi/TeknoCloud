# Rangkuman Artikel 4 Materi

## A.	Perbedaan SaaS, PaaS, dan IaaS
### SaaS - Layanan sebagai Perangkat Lunak :
* SaaS juga dikenal sebagai layanan aplikasi Cloud (komputasi awan). SaaS menggunakan browser web untuk mengirimkan aplikasi yang dikelola oleh vendor pihak ketiga. Antarmuka perangkat lunak tersebut adalah antarmuka yang menghadap ke klien. Perangkat lunak SaaS lebih mudah digunakan dan hampir tidak perlu mengunduh atau menginstal file apa pun. Sebagian besar dari mereka dapat digunakan menggunakan URL situs web, dan beberapa prosedur pembuatan akun yang diperlukan. Perangkat lunak SaaS yang paling populer adalah yang digunakan untuk email dan kolaborasi, CRM dan aplikasi perawatan kesehatan. 
Beberapa platform SaaS yang paling populer adalah Google Apps, Workday, Salesforce, dan lainnya.

### PaaS - Platform sebagai Layanan:
* PaaS juga dapat disebut sebagai layanan platform Cloud. Mereka menyediakan komponen cloud untuk beberapa perangkat lunak. Namun, mereka terutama digunakan untuk aplikasi. PaaS lebih cenderung digunakan oleh pengembang yang mendapatkan kerangka dasar menggunakan PaaS yang dapat mereka kembangkan lebih lanjut. Ini membantu dalam pengembangan dan penyesuaian aplikasi. Ini memudahkan proses pengembangan, pengujian dan penyebaran aplikasi. Hal ini juga sangat hemat biaya. PaaS memungkinkan perusahaan untuk mengelola perangkat lunak operasi, server, penyimpanan, jaringan, dan virtualisasi. 
Keuntungan utama menggunakan PaaS untuk perusahaan adalah meminimalkan persyaratan pengkodean serta mengotomatiskan kebijakan bisnis. Beberapa platform PaaS yang paling populer adalah Google App Engine, Windows Azure dan Magento Commerce Cloud.

### IaaS - Infrastruktur sebagai Layanan:
* Layanan IaaS atau Infrastruktur Cloud adalah model layanan mandiri yang membantu mengakses, mengelola, dan memantau infrastruktur pusat data jarak jauh. Pada dasarnya, kita dapat mengelola layanan komputasi, penyimpanan, jaringan, dan jaringan. 
Pengguna yang bekerja pada IaaS bertanggung jawab untuk mengelola aplikasi, runtime, data, middleware, dan sistem operasi.  Beberapa platform IaaS yang paling populer adalah Amazon Web Services, Microsoft Azure, Google Compute Engine dan Joyent.

## B.	Arsitektur Platform SaaS ( Perangkat Lunak Sebagai Layanan)

### Arsitektur SAAS:

* Dengan model ini, satu versi aplikasi, dengan konfigurasi tunggal digunakan untuk semua pelanggan. 

* Aplikasi diinstal pada beberapa mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). 

* Dalam beberapa kasus, versi kedua dari aplikasi diatur untuk menawarkan sekelompok pelanggan tertentu dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian. 

* Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode unik. Meskipun pengecualian , beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola sejumlah besar pelanggan dengan biaya yang efektif. 

### Dua jenis utama SaaS:

* SaaS Vertikal 
    ####  Perangkat Lunak yang menjawab kebutuhan industri tertentu (misalnya, perangkat lunak untuk perawatan kesehatan, pertanian, real estat, industri keuangan)
* SaaS Horizontal 
    #### Produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.


## C.	SaaS sebagai Perangkat Lunak Arsitektur 

SaaS juga merupakan salah satu pilar utama komputasi awan. Didorong oleh penyedia layanan cloud seperti Microsoft dengan Azure, Amazon Web Services (AWS), Oracle, dan IBM, telah melihat pertumbuhan produk dan layanan lain yang dikirimkan melalui internet termasuk model SaaS berikut:
* Infrastruktur sebagai Layanan
* Platform sebagai Layanan
* Pembelajaran Mesin sebagai Layanan

Setiap pembaruan atau tambalan ke aplikasi SaaS semuanya ditangani oleh penyedia. Pelanggan tidak perlu mengunduh pemutakhiran atau menginstal ulang versi baru produk karena perangkat lunak dikirimkan melalui internet.

### Keuntungan menggunakan layanan SaaS :
* Konsumen
Salah satu cara termudah dan dapat diandalkan untuk menggunakan layanan atau produk digital. Kita cukup mengaksesnya melalui web, membayar layanan, dan menggunakannya. Contoh layanan aplikasi SaaS :
Netflix, Microsoft Office 365, Amazon Perdana, Facebook,dll

* Bisnis
Memungkinkan bisnis menawarkan produk mereka dalam skala besar, secara global, memungkinkan mereka untuk mempertahankan kontrol keseluruhan atas produk mereka. Manfaat lain SaaS dalam bisnis yaitu : Mengurangi waktu ke pasar, biaya perawatan yang lebih rendah, peningkatan otomatisasi, dll

### Kekurangan Platform SaaS
-	Kurang kontrol, karena aplikasi SaaS dihosting dilingkungan SaaS vendor dan kita hanya memiliki sedikit atau tidak ada kendali ke perangkat lunak yang kita gunakan.
-	Ekosistem terbatas, mulai dari pertunjukan dimana aplikasi internal berjalan lebih cepat daripada produk yang dikirimkan melalui internet dan masalah data.
Komponen Utama Platform Saas
-	Keamanan, melindungi data pelanggan di platform SaaS kita adalah yang paling penting karena itu produk SaaS melayani ratusan bahkan ribuan pengguna.
-	Pribadi, privasi merupakan komponen penting untuk mempertimbangkan saat merancang produk SaaS kita sendiri.
-	Kostumisasi dan Konfigurasi, mempertimbangkan ekstensibilitas ke arsitektur SaaS sangatlah penting, kita dapat melakukannya dengan mengirimkan label putih dengan menerapkan mekanisme plugin.




## D.	Cara Membangun Aplikasi SaaS Berbasis Cloud

-	Membangun untuk cloud
Karena pada saat ingin membangun aplikasi SaaS (global) kemungkinan besar membangunnya di cloud.

-	Memulai aplikasi SaaS dengan memilih bahasa pemograman
Membangun produk untuk cloud berarti membangun produk dengan bahasa pemograman modern, karena selain kemampuan dan keterampilan pribadi, pilihan bahasa pemograman akan dipengaruhi oleh kemungkinan setiap bahasa. Bahasa pemograman yang bisa dijadikan sebagai pilihan yang tepat adalah python, karena merupakan bahasa pemograman yang cukup populer dan mudah digunakan.

-	Memilih basis data sempurna untuk aplikasi SaaS
Pada bagian ini, disarankan untuk menggunakan database berorientasi dokumen. Mengapa memilih database berorientasi dokumen? karena database dokumen mendapatkan informasi jenisnya dari data itu sendiri. Jadi setiap contoh data dapat berbeda dari yang lain.Hal ini memungkinkan lebih banyak fleksibilitas, terutama ketika berhadapan dengan perubahan. Dan itu sering mengurangi ukuran basis data. Contoh : MongoDB.

### Sistem Antrian Untuk Aplikasi SaaS

Sistem Antrian
-	Dikenal sebagai teknologi Message Queuing (MSMQ) yang memungkinkan aplikasi web berjalan pada waktu yang berbeda dan untuk berkomunikasi dengan berbagai integrasi pihak ke-3 / API / dan layanan lainnya secara asinkron.
-	Sebuah pesan (misalnya kueri yang meminta layanan pihak ketiga melalui API) ditempatkan ke dalam antrian. Itu disimpan di sana sampai penerima mengambilnya.
-	Antrian pesan memiliki batasan mengenai ukuran dan jumlah data yang dikirimkan dalam antrian. 

KelinciMQ
-	RabbitMQ adalah sistem antrian open source yang berjalan di semua sistem operasi utama. Karena berdasarkan pengalaman menjalankan aplikasi web kami di AWS EC2 di mana RabbitMQ dapat dijalankan dan dijalankan dengan sangat lancar.


AWS & EC2
-	AWS memungkinkan kita untuk menghosting dan menjalankan aplikasi web serta melakukan pekerjaan batch besar-besaran dengan kinerja tinggi. Dengan Elastic Compute Cloud (EC2), AWS menyediakan server virtual yang dapat diskalakan untuk setiap bisnis.
-	Amazon EC2 merupakan inti dari sistem kami yang menyediakan kapasitas komputasi yang dapat diubah ukurannya. Server EC2 tersebar di seluruh dunia. Bergantung pada kebutuhan kita untuk menskalakan dan pasar geografis mana yang menjadi target pertama.

Penyimpanan Web S3
-	Amazon Simple Storage Service (S3) mudah digunakan, menyimpan, dan mengambil data dalam jumlah berapa pun. Apakah Amazon S3 hanya dapat digunakan dengan layanan AWS lainnya? tidak. Itu juga dapat digunakan sendiri atau dengan repositori dan gateway penyimpanan pihak ketiga lainnya. Dan tentu saja, ini bekerja sangat baik dengan EC2.

