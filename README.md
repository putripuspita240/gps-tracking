Software Requirements Specification for GPS Tracking Motorcycle Version 1.0 Disetujui

Disusun Oleh :
Putri Puspitasari (22091397097)
Danu Teguh Heri Prasetyo (22091397100)
Amallia Berliany Putri (22091397102)

D4 Manajemen Informatika
Fakultas Vokasi Universitas Negeri Surabaya
2023

Daftar Isi
1.	Pengantar
1.1	Tujuan
1.2	Konvensi Dokumen
1.3	Audiens Yang Dituju
1.4	Lingkup Produk
1.5	Referensi
2.	Deskripsi Keseluruhan
2.1	Perspektif Produk
2.2	Fungsi Produk
2.3	Kelas dan Karakteristik Pengguna
2.4	Lingkungan Pengembangan
2.5	Kendala Desain dan Implementasi
2.6	Dokumentasi Pengguna
2.7	Asumsi dan Dependensi
3.	Persyaratan Antarmuka
3.1	Antarmuka Pengguna
3.2	Antarmuka Perangkat Keras
3.3	Antarmuka Perangkat Lunak
3.4	Antarmuka Komunikasi
4.	Fitur Sistem
4.1	Lokasi secara Real-Time
4.2	Riwayat Lokasi
4.3	Temukan Lokasi
4.4	Terhuung dengan Sepeda motor
4.5	Notifikasi
5.	Persyaratan Fungsional Lainnya
5.1	Persyaratan Performa
5.2	Persyaratan Keamanan Pengguna
5.3	Persyaratan Keamanan GPS Tracking Motorcycle
5.4	Atribut Kualitas Perangkat Lunak
5.5	Proses Bisnis
5.6	Persyaratan


1.	Pengantar

1.1	Tujuan
Tujuan pembuatan website GPS Tracking Motorcycle antara lain :

1.	Meningkatkan keamanan pengendara
2.	Meminimalisir risiko pencurian sepeda motor
3.	Meningkatkan efisiensi lalu lintas
4.	Melacak posisi sepeda motor yang hilang
5.	Memberikan informasi lokasi sepeda motor
6.	Memantau aktivitas berkendara

1.2	 Konvensi Dokumen
Website yang akan dikembangkan adalah GPS Tracking Motorcycle, sebuah aplikasi yang memungkinkan pemilik sepeda motor untuk melacak dan memantau pergerakan sepeda motornya secara real-time. Website ini memanfaatkan teknologi GPS (Global Positioning System) untuk menentukan posisi sepeda motor. GPS Tracking Motorcycle dapat melakukan hal-hal berikut ini :

1.	Sistem dapat menampilkan menu pendaftaran akun untuk login ke aplikasi
2.	Sistem dapat menampilkan menu login
3.	Sistem harus mampu melacak posisi sepeda motor secara real-time
4.	Sistem dapat menampilkan posisi sepeda motor pada peta
5.	Sistem harus mampu mengirimkan notifikasi pada pengguna jika terjadi situasiyang tidak diinginkan
6.	Sistem harus mampu mencatat riwayat perjalanan sepeda motor, seperti waktu, lokasi,dan rute yang ditempuh
7.	Sistem harus memiliki fitur manajemen pengguna
8.	Sistem dapat diintegrasikan dengan aplikasi lain
9.	Sistem dapat menganalisis data lokasi dan waktu
10.	Sistem harus mampu bergerak dengan berbagai jenis sepeda motor
11.	Sistem dapat memantau kecepatan motor
12.	Sistem harus bekerja dengan menggunakan daya baterai sepeda motor seperti baterai internal atau tenaga surya
13.	Sistem memiliki tampilan yang mudah dipahami
14.	Sistem dapat dioperasikan sesuai fungsinya dengan baik termasuk fitur-fitur yang diinginkan
15.	Sistem harus dapat diandalkan
16.	Sistem harus tersedia dan dapat diakses oleh pengguna kapan saja
17.	Sistem harus memiliki performa yang baik dan responsive
18.	Sistem dapat mengatasi pertumbuhan pengguna dan data yang semakin besar
19.	Sistem harus dilengkapi dengan dukungan teknis yang baik
20.	Sistem dapat menjamin keamanan data akun
21.	Sistem dapat diakses dengan smartphone
22.	Sistem harus meminim kesalahan dari masalah

1.3	Audiens Yang Dituju
Pengguna yang dituju untuk pengembangan website GPS tracking untuk sepeda motor dapat mencakup beberapa kelompok, antara lain :

1.	Pemilik Sepeda Motor: Pemilik sepeda motor adalah target utama untuk website GPS tracking. Mereka akan menggunakan website tersebut untuk melacak lokasi sepeda motor mereka dalam situasi tertentu, seperti pencurian atau jika mereka ingin memantau pergerakan sepeda motor mereka.
2.	Perusahaan Rental Sepeda Motor: Perusahaan rental sepeda motor dapat menjadi audiens yang potensial untuk website GPS tracking. Mereka dapat menggunakan website tersebut untuk melacak dan mengelola sepeda motor yang mereka sewakan kepada pelanggan mereka.
3.	Penyedia Layanan Kurir atau Pengiriman: Penyedia layanan kurir atau pengiriman juga dapat menjadi target audiens. Mereka dapat menggunakan aplikasi GPS tracking untuk melacak posisi sepeda motor kurir dan memantau pengiriman barang dengan lebih efisien.
4.	Klub atau Komunitas Sepeda Motor: Klub atau komunitas sepeda motor juga bisa menjadi audiens yang berpotensi. Mereka dapat menggunakan website GPS tracking untuk mengorganisir perjalanan bersama atau acara lainnya, sehingga anggota dapat melihat posisi sepeda motor satu sama lain dalam waktu nyata.
5.	Pemilik Flotila Sepeda Motor: Jika ada pemilik bisnis atau organisasi yang memiliki flotilla sepeda motor, seperti layanan pengantaran makanan atau layanan kurir. Website ini dapat membantu mereka mengawasi sepeda motor dan meningkatkan efisiensi operasional.

1.4	Lingkup Produk
GPS tracking untuk sepeda motor melibatkan penggunaan teknologi Global Positioning System (GPS) untuk melacak lokasi, pergerakan, dan informasi relevan lainnya dari sepeda motor secara real-time. Hal ini menawarkan berbagai manfaat, termasuk pencegahan pencurian, manajemen armada, dan peningkatan keamanan. Berikut adalah beberapa aspek dan fitur utama terkait GPS tracking untuk sepeda motor :

1.	Pelacakan lokasi real-time: Sistem GPS tracking memungkinkan pemilik sepeda motor atau manajer armada untuk memantau lokasi sepeda motor secara real- time melalui satelit GPS. Informasi ini biasanya dapat diakses melalui platform berbasis web.
2.	Pencegahan dan pemulihan pencurian: GPS tracker menyediakan cara yang efektif untuk mencegah pencurian sepeda motor. Pada saat terjadinya pencurian, pemilik dapat melacak lokasi sepeda motor yang dicuri dan berkoordinasi dengan pihak berwenang untuk melakukan pemulihan.
3.	Geofencing: fitur yang memungkinkan pengguna untuk mengatur batas virtual atau geofence di sekitar area tertentu. Ketika sepeda motor yang dilengkapi dengan GPS tracker memasuki atau keluar dari batas-batas ini, sistem akan mengirimkan peringatan kepada pemilik atau manajer armada, memberikan notifikasi secara langsung.
4.	Riwayat rute: GPS tracking juga dapat menyimpan riwayat rute yang telah ditempuh oleh sepeda motor. Informasi ini dapat digunakan untuk analisis perjalanan, pemantauan kinerja, dan perencanaan perjalanan di masa depan.
5.	Fitur tambahan: Selain fitur utama yang disebutkan di atas, beberapa GPS tracker untuk sepeda motor juga dapat dilengkapi dengan fitur tambahan seperti pemantauan kecepatan, notifikasi kebocoran bahan bakar, pemadaman mesin dari jarak jauh, dan sebagainya.
6.	GPS tracking untuk sepeda motor memberikan kemudahan dan keamanan tambahan bagi pemilik sepeda motor atau perusahaan yang memiliki armada sepeda motor. Dengan memanfaatkan teknologi GPS, mereka dapat melacak dan mengawasi sepeda motor secara efektif dalam berbagai situasi.

1.5	Referensi
Dokumen ini merujuk pada hasil observasi yang berkaitan dengan kebutuhan dan mencakup data secara umum, diperlukannya dan penulis dokumen berdasarkan pada:

1.	https://moladin.com/blog/fungsi-gps-tracker-motor/
2.	https://gpsku.co.id/gps-motor/
3.	https://www.sologlobaltracker.com/mengenal-gps-tracker-fungsi-manfaat-dan- penggunaannya-dalam-kehidupan-sehari-hari/
4.	https://openlibrary.telkomuniversity.ac.id/pustaka/files/162743/jurnal_eproc/pera ncangan-gps-tracking-untuk-penyewaan-kendaraan-bermotor.pdf
5.	https://appmaster.io/id/blog/proses-pengembangan-aplikasi-gps-dan-contohnya
6.	https://cartrack.id/id/5-fitur-gps-tracker-yang-wajib-ada-dalam-sistem-pemantauan-kendaraan


2.	Deskripsi Keseluruhan

2.1	Perspektif Produk
GPS tracking untuk sepeda motor adalah produk yang sangat berguna dan inovatif dalam mengamankan dan melacak sepeda motor. Dari perspektif produk, berikut adalah beberapa poin penting yang perlu diperhatikan :

1.	Keamanan: GPS tracking untuk sepeda motor memberikan perlindungan tambahan terhadap pencurian. Dengan fitur pelacakan real-time, pemilik dapat dengan mudah melacak lokasi sepeda motor mereka jika terjadi pencurian. Ini memberikan rasa aman dan meningkatkan peluang pemulihan kendaraan yang dicuri.
2.	Pemantauan armada: Produk GPS tracking juga bermanfaat bagi perusahaan atau pemilik sepeda motor dengan armada yang besar. Mereka dapat menggunakan sistem GPS untuk memantau posisi, status, dan kinerja sepeda motor dalam satu platform. Ini membantu dalam pengelolaan armada secara efisien dan meningkatkan produktivitas.
3.	Geofencing: Fitur geofencing memungkinkan pengguna untuk membuat area virtual dan menerima notifikasi saat sepeda motor memasuki atau  meninggalkan area tersebut. Ini sangat berguna untuk pengawasan wilayah terbatas atau area yang diinginkan. Misalnya, jika sepeda motor keluar dari wilayah yang ditentukan, pemilik akan menerima peringatan segera.
4.	Integrasi dengan aplikasi dan platform: Produk GPS tracking sering dilengkapi dengan aplikasi mobile atau platform berbasis web yang mudah digunakan. Ini memungkinkan pemilik untuk mengakses informasi dan mengontrol sepeda motor dari jarak jauh melalui perangkat mereka. Pengguna juga dapat melihat riwayat perjalanan, mengatur peringatan khusus, dan melacak kinerja kendaraan.
5.	Pemantauan kinerja: Beberapa sistem GPS tracking juga menyediakan informasi tentang kecepatan, akselerasi, konsumsi bahan bakar, dan parameter lainnya. Ini membantu pemilik sepeda motor untuk memantau kinerja kendaraan, mengidentifikasi masalah potensial, dan meningkatkan efisiensi.

Dari perspektif pengguna, GPS tracking untuk sepeda motor merupakan alat yang sangat berharga untuk meningkatkan keamanan, melacak sepeda motor, dan meningkatkan efisiensi penggunaan kendaraan. Produk ini memberikan ketenangan pikiran dan memberikan kontrol yang lebih besar atas aset berharga mereka.

2.2	Fungsi Produk
Produk GPS tracking untuk sepeda motor memiliki berbagai fungsi yang berguna dalam penggunaan sehari-hari. Berikut ini adalah beberapa fungsi produk GPS tracking untuk sepeda motor :

1.	Pelacakan Lokasi: Fungsi utama GPS tracking untuk sepeda motor adalah melacak lokasi kendaraan secara real-time. Pemilik sepeda motor dapat melihat posisi tepat sepeda motor mereka melalui aplikasi atau platform yang terhubung dengan GPS tracker. Hal ini membantu dalam mengetahui lokasi sepeda motor jika terjadi pencurian atau untuk memantau perjalanan.
2.	Pencegahan Pencurian: Dengan GPS tracking, sepeda motor dapat dilacak dengan mudah jika terjadi pencurian. Pemilik dapat mengaktifkan fitur alarm atau notifikasi yang akan memberi tahu mereka jika sepeda motor bergerak tanpa izin atau meninggalkan wilayah yang ditentukan. Ini membantu dalam pencegahan pencurian dan memungkinkan pemilik untuk mengambil tindakan segera.
3.	Geofencing: Fungsi geofencing memungkinkan pemilik untuk membuat batas virtual di sekitar area tertentu. Jika sepeda motor keluar atau memasuki batas ini, pemilik akan menerima pemberitahuan instan. Fitur ini berguna untuk membatasi wilayah perjalanan sepeda motor atau mengawasi sepeda motor yang dipinjam oleh orang lain.\
4.	Riwayat Perjalanan: GPS tracking juga dapat menyimpan riwayat perjalanan sepeda motor. Informasi ini meliputi waktu perjalanan, jarak yang ditempuh, dan rute yang diambil. Pemilik sepeda motor dapat menggunakan data ini untuk memantau aktivitas sepeda motor, melacak penggunaan bahan bakar, atau melakukan analisis perjalanan.
5.	Pemantauan Kinerja: Beberapa GPS tracking untuk sepeda motor menyediakan informasi tentang kecepatan, konsumsi bahan bakar, dan parameter lainnya. Fungsi ini membantu pemilik untuk memantau kinerja sepeda motor, mengidentifikasi kebiasaan berkendara yang buruk, atau mendeteksi masalah teknis.
6.	Notifikasi Darurat: Beberapa GPS tracker dilengkapi dengan tombol darurat yang memungkinkan pengguna untuk mengirimkan sinyal darurat ke kontak yang ditentukan. Fitur ini sangat berguna dalam situasi darurat atau keadaan mendesak di jalan.

GPS tracking untuk sepeda motor merupakan alat yang bermanfaat dalam meningkatkan keamanan, pemantauan, dan efisiensi penggunaan sepeda motor. Dengan fungsi-fungsinya yang beragam, produk ini memberikan keuntungan bagi pemilik sepeda motor dalam menjaga keamanan kendaraan mereka dan memantau aktivitasnya.

2.3	Kelas dan Karakteristik Pengguna
Pengguna GPS tracking untuk sepeda motor adalah individu atau perusahaan yang memiliki sepeda motor dan ingin meningkatkan keamanan, pemantauan, dan efisiensi penggunaannya. Berikut adalah deskripsi pengguna GPS tracking untuk sepeda  motor:

1.	Pemilik Sepeda Motor Pribadi: Pengguna ini adalah individu yang memiliki sepeda motor untuk penggunaan pribadi. Mereka menggunakan GPS tracking untuk memastikan keamanan sepeda motor mereka. Mereka dapat melacak lokasi sepeda motor secara real-time dan menerima pemberitahuan jika ada aktivitas mencurigakan atau sepeda motor keluar dari area yang ditentukan. Pemilik sepeda motor pribadi juga dapat menggunakan fitur riwayat perjalanan untuk memantau penggunaan sepeda motor dan mengidentifikasi pola perjalanan.
2.	Pemilik Rental Motor: Pengguna ini adalah pemilik bisnis rental sepeda motor. Mereka menggunakan GPS tracking untuk memantau dan melacak sepeda motor yang disewakan kepada pelanggan. GPS tracking memungkinkan pemilik rental motor untuk mengetahui lokasi sepeda motor yang disewakan, memastikan pemakaian yang sesuai, dan memungkinkan pemulihan sepeda motor jika terjadi pelanggaran kontrak atau pencurian.
3.	Perusahaan Kurir atau Pengiriman: Perusahaan pengiriman menggunakan GPS tracking untuk mengawasi dan mengoptimalkan pengiriman paket atau barang dengan sepeda motor. Mereka dapat melacak posisi sepeda motor kurir dalam perjalanan, memantau waktu pengiriman, dan mengatur rute yang efisien. Fitur geofencing juga membantu dalam mengatur batasan wilayah kerja dan memberikan peringatan jika sepeda motor keluar dari rute yang ditentukan.
4.	Perusahaan Armada Sepeda Motor: Perusahaan dengan armada sepeda motor menggunakan GPS tracking untuk manajemen armada mereka. Mereka dapat melacak lokasi dan aktivitas setiap sepeda motor dalam armada secara real- time, memantau performa dan penggunaan bahan bakar, serta melakukan perencanaan perawatan yang efektif. GPS tracking juga membantu dalam mengoptimalkan jadwal pengiriman atau pemeliharaan sepeda motor.

Pengguna GPS tracking untuk sepeda motor memiliki kepentingan yang beragam, termasuk keamanan kendaraan, pemantauan penggunaan, efisiensi operasional, dan peningkatan layanan pelanggan. Dengan menggunakan GPS tracking, mereka dapat memaksimalkan penggunaan sepeda motor, mengurangi risiko pencurian, dan meningkatkan efektivitas dalam manajemen armada atau operasi pengiriman.

2.4	Lingkungan Pengembangan
Peralatan operasional untuk GPS tracking sepeda motor terdiri dari beberapa komponen yang bekerja secara bersama-sama untuk melacak dan memantau sepeda motor. Berikut adalah peralatan utama yang terlibat dalam operasional GPS tracking sepeda motor :

1.	GPS Tracker: GPS tracker adalah perangkat yang dipasang pada sepeda motor untuk melacak lokasi dan mengirimkan data melalui sinyal GPS. GPS tracker dapat berbentuk perangkat kecil yang terpasang di bawah jok, di bawah bodi, atau di bagian lain yang tersembunyi pada sepeda motor. Ini berfungsi untuk mengumpulkan informasi lokasi dan mentransmisikannya ke server atau platform yang terhubung.
2.	GPS Satelit: GPS tracker menggunakan sinyal dari jaringan satelit GPS untuk menentukan lokasi yang akurat. Jaringan satelit ini mengorbit di sekitar Bumi dan menyediakan sinyal yang diterima oleh GPS tracker untuk menentukan koordinat geografis sepeda motor.
3.	SIM Card: Beberapa GPS tracker membutuhkan kartu SIM untuk mengirim data lokasi dan informasi melalui jaringan seluler. Kartu SIM ini digunakan untuk menghubungkan GPS tracker dengan server atau platform yang dikelola, sehingga data dapat dikirim secara real-time.
4.	Server atau Platform: Data yang dikumpulkan oleh GPS tracker dikirim  ke server atau platform yang terhubung. Ini bisa berupa server perusahaan atau platform berbasis web yang dapat diakses melalui aplikasi mobile atau situs web. Server atau platform ini menerima dan menyimpan data lokasi, riwayat perjalanan, dan informasi lainnya dari sepeda motor yang dilacak.
5.	Aplikasi Mobile atau Web: Pengguna GPS tracking dapat mengakses informasi dan mengendalikan sepeda motor melalui aplikasi mobile atau platform berbasis web. Aplikasi ini biasanya menyediakan tampilan real-time dari posisi sepeda motor, notifikasi, riwayat perjalanan, dan fitur pengaturan lainnya seperti geofencing atau alarm.

Selain komponen utama ini, ada juga perangkat tambahan yang dapat digunakan dalam operasional GPS tracking sepeda motor, seperti sensor tambahan untuk pemantauan kecepatan atau status mesin, dan perangkat pemancar alarm atau tombol darurat untuk situasi darurat. Peralatan operasional GPS tracking sepeda motor bekerja secara bersama-sama untuk mengumpulkan, mentransmisikan, dan menganalisis data lokasi dan informasi terkait sepeda motor. Ini memberikan pemilik atau pengguna sepeda motor kemampuan untuk memantau dan  melindungi kendaraan mereka secara efektif.

2.5	Kendala Desain dan Implementasi
Pengujian GPS Tracking Motorcycle sudah dilakukan dan tidak ada kendala. Semua sistem sudah berjalan sesuai yang diharapkan dan berjalan dengan baik. Desain dan implementasi GPS tracking untuk sepeda motor melibatkan beberapa langkah dan komponen teknis. Berikut adalah langkah-langkah umum yang terlibat dalam desain dan implementasi GPS tracking untuk sepeda motor :

1.	Pemilihan GPS Tracker: Langkah pertama adalah memilih GPS tracker yang sesuai untuk sepeda motor. Pilihlah GPS tracker yang ukurannya kecil, tahan air, dan tahan terhadap getaran atau guncangan yang umum terjadi pada sepeda motor. Pastikan GPS tracker yang dipilih kompatibel dengan sistem operasi dan platform yang akan digunakan.
2.	Pemasangan GPS Tracker: GPS tracker dipasang pada sepeda motor dengan aman dan tersembunyi agar tidak terlihat oleh orang lain. Tempatkan  GPS tracker di lokasi yang aman, seperti di bawah jok, di bawah bodi atau di bagian yang tidak mudah dijangkau. Pastikan GPS tracker terpasang dengan kokoh dan terlindung dari kerusakan atau pencurian.
3.	Pengaturan Koneksi Data: Jika GPS tracker menggunakan kartu SIM, pastikan untuk memasang dan mengaktifkan kartu SIM yang sesuai dengan jaringan seluler yang mendukung. Lakukan pengaturan koneksi data dan pastikan GPS tracker terhubung dengan jaringan seluler untuk mentransmisikan data.
4.	Konfigurasi Perangkat: Setelah GPS tracker terpasang, lakukan konfigurasi perangkat sesuai dengan instruksi yang diberikan oleh produsen. Ini melibatkan mengatur pengaturan seperti interval pelacakan, pengiriman notifikasi, dan parameter lainnya yang sesuai dengan kebutuhan pengguna.
5.	Pembuatan Akun dan Pengaturan Server: Buat akun pengguna di server atau platform yang terkait dengan GPS tracker. Ikuti langkah-langkah pendaftaran yang diberikan dan lakukan pengaturan server yang diperlukan. Tambahkan sepeda motor ke akun pengguna dan ikuti proses registrasi yang mungkin diperlukan.
6.	Penggunaan Aplikasi atau Platform: Setelah akun dan server dikonfigurasi, unduh aplikasi mobile atau akses platform berbasis web yang terkait dengan GPS tracker. Masuk ke akun pengguna dan ikuti petunjuk untuk menghubungkan sepeda motor yang dilacak. Aplikasi atau platform akan menyediakan tampilan real-time dari posisi sepeda motor, riwayat perjalanan, notifikasi, dan fitur lainnya.
7.	Uji Coba dan Pemantauan: Setelah GPS tracking sepeda motor diimplementasikan, lakukan uji coba untuk memastikan bahwa sistem berfungsi dengan baik. Periksa pelacakan lokasi, notifikasi, dan fitur lainnya untuk memastikan semua berjalan sesuai yang diharapkan. Lakukan pemantauan secara berkala untuk memastikan bahwa GPS tracking beroperasi dengan lancar dan memberikan informasi yang akurat.

Desain dan implementasi GPS tracking untuk sepeda motor melibatkan pemilihan perangkat yang tepat, pemasangan yang benar, konfigurasi yang akurat, dan penggunaan aplikasi atau platform yang sesuai. Penting untuk mengikuti panduan dari produsen GPS tracker dan platform yang digunakan untuk memastikan keberhasilan implementasi dan penggunaan yang efektif.

2.6	Dokumentasi Pengguna
Berikut adalah panduan penggunaan GPS tracking untuk sepeda motor 

1.	Instalasi GPS Tracker: Pasang GPS tracker pada sepeda motor sesuai petunjuk yang diberikan oleh produsen. Pastikan GPS tracker terpasang dengan aman dan terlindung dari kerusakan atau pencurian.
2.	Aktivasi SIM Card (jika diperlukan): Jika GPS tracker menggunakan kartu SIM, pasang kartu SIM yang sesuai dan aktifkan layanan data.
3.	Unduh Aplikasi atau Akses Platform: Unduh aplikasi mobile yang terkait dengan GPS tracker atau akses platform berbasis web melalui perangkat yang terhubung ke internet.
4.	Buat Akun Pengguna: Buat akun pengguna di aplikasi atau platform dengan mengikuti petunjuk pendaftaran yang diberikan. Pastikan menggunakan informasi yang akurat dan aman.
5.	Tambahkan Sepeda Motor: Setelah berhasil masuk ke akun pengguna, tambahkan sepeda motor ke akun Anda dengan mengikuti petunjuk yang disediakan oleh aplikasi atau platform. Ini biasanya melibatkan memasukkan nomor seri atau kode unik dari GPS tracker.
6.	Pantau Posisi Sepeda Motor: Setelah sepeda motor ditambahkan ke akun Anda, Anda dapat melacak posisi sepeda motor secara real-time melalui aplikasi mobile atau platform berbasis web. Pastikan Anda terhubung ke internet untuk menerima data yang akurat.
7.	Terima Notifikasi: Aktifkan notifikasi dalam aplikasi atau platform untuk menerima pemberitahuan jika terjadi aktivitas mencurigakan, sepeda motor keluar dari area yang ditentukan, atau situasi darurat lainnya.
8.	Riwayat Perjalanan: Gunakan fitur riwayat perjalanan untuk melihat catatan perjalanan sepeda motor Anda. Anda dapat melihat waktu perjalanan, jarak yang ditempuh, dan rute yang diambil.
9.	Pengaturan Tambahan: Beberapa GPS tracker menyediakan pengaturan tambahan seperti geofencing, alarm, atau fitur lainnya. Gunakan pengaturan ini sesuai dengan kebutuhan dan preferensi Anda.
10.	Pemeliharaan dan Pemantauan: Lakukan pemeliharaan rutin pada GPS tracker, seperti memeriksa daya baterai atau penggantian kartu SIM jika diperlukan. Selalu periksa koneksi dan fungsionalitas GPS tracker secara berkala untuk memastikan operasional yang baik.

Pastikan untuk merujuk pada panduan pengguna yang disediakan oleh produsen GPS tracker dan aplikasi atau platform yang digunakan. Panduan ini akan memberikan informasi lebih detail tentang fungsi dan fitur spesifik dari perangkat Anda.

2.7	Asumsi dan Dependensi
Asumsi dan ketergantungan GPS tracking untuk sepeda motor melibatkan beberapa faktor yang perlu dipertimbangkan. Berikut adalah beberapa asumsi umum dan ketergantungan yang terkait dengan GPS tracking untuk sepeda motor :

1.	Sinyal GPS: GPS tracking bergantung pada ketersediaan sinyal GPS yang kuat dan stabil. Asumsinya adalah bahwa sepeda motor berada dalam area yang dapat menerima sinyal GPS dengan baik, seperti di luar ruangan atau daerah terbuka. Jika sepeda motor berada di area yang memiliki gangguan sinyal GPS, seperti di dalam gedung atau daerah dengan perlindungan sinyal, akurasi pelacakan mungkin terpengaruh.
2.	Ketersediaan Jaringan Seluler: Jika GPS tracker menggunakan kartu SIM dan mengirim data melalui jaringan seluler, asumsinya adalah bahwa ada ketersediaan jaringan seluler yang stabil dan cakupan yang memadai di lokasi sepeda motor. Jika sepeda motor berada di daerah dengan sinyal seluler yang lemah atau tidak ada sinyal sama sekali, GPS tracker mungkin tidak dapat mengirim data secara real-time.
3.	Daya Baterai: GPS tracker membutuhkan daya baterai untuk beroperasi. Asumsinya adalah bahwa daya baterai GPS tracker cukup untuk mempertahankan operasional dalam rentang waktu yang diinginkan. Namun, ketergantungan pada daya baterai berarti bahwa pengguna harus memastikan bahwa baterai GPS tracker terisi penuh atau diisi ulang secara teratur.
4.	Ketersediaan Akses Internet: Untuk mengakses data GPS tracker melalui aplikasi mobile atau platform berbasis web, pengguna perlu memiliki akses internet yang stabil. Asumsinya adalah bahwa pengguna memiliki akses internet yang memadai dan stabil untuk mengakses informasi dan mengontrol GPS tracker.
5.	Keandalan Perangkat: Ketergantungan pada GPS tracking sepeda motor juga bergantung pada keandalan perangkat itu sendiri. Asumsinya adalah bahwa GPS tracker berfungsi dengan baik dan tidak mengalami kerusakan atau kegagalan yang signifikan. Penting untuk memilih GPS tracker berkualitas tinggi dan menjaga perangkat dalam kondisi yang baik.
6.	Kepatuhan dan Perlindungan Data: GPS tracking melibatkan pengumpulan dan pengiriman data pengguna dan lokasi sepeda motor. Asumsinya adalah bahwa pengguna mematuhi kebijakan privasi dan perlindungan data yang diberlakukan oleh produsen GPS tracker atau platform yang digunakan. Penting untuk memahami bagaimana data dikumpulkan, digunakan, dan dilindungi untuk menjaga privasi dan keamanan informasi

Asumsi dan ketergantungan ini harus dipertimbangkan ketika menggunakan GPS tracking untuk sepeda motor. Penting untuk memahami batasan dan memastikan bahwa kondisi dan faktor-faktor tersebut terpenuhi untuk memperoleh hasil  yang akurat dan efektif dari GPS tracking.


3.	Persyaratan Antarmuka

3.1	Antarmuka Pengguna
Berikut adalah deskripsi tentang tentang aplikasi GPS Tracking Motorcycle : 

Didalam tampilan pertama saat membuka aplikasi GPS Tracking Motorcycle, user diminta untuk login jika sudah mempunyai akun dan sign up (daftar) jika belum mempunyai akun. Setelah mendaftar atau login, user akan dialihkan ke halaman utama aplikasi. Didalam halaman utama ini terdapat tampilan nama user, setting, dan berbagai menu seperti real-time location, find location, connect to motorcycle, history location dan notification.

Didalam menu settings terdapat fitur untuk mengganti nama, email, nama brand sepeda motor, password, plat nomor sepeda motor, dan nomor telepon. Didalam menu setting juga user bisa memilih mode pelacakan yang akan digunakan seperti :
a.	Mode real-time yang memungkinkan pengguna untuk melihat lokasi sepeda motor secara langsung dan akurat.
b.	Mode interval yang akan memperbarui lokasi pada interval waktu tertentu seperti setiap 1 menit, 5 menit, atau 15 menit. Mode ini berguna untuk menghematdaya baterai pada perangkat dan mengurangi penggunaan data.
c.	Mode geofencing yang akan memperbarui lokasi ketika memasuki atau meninggalkan wilayah tertentu.
d.	Mode non aktif tidak akan memperbarui lokasi apapun

Dalam menu real-time yang ada disebelah kiri terdapat beberapa fitur yaitu untuk memungkinkan pengguna websitw atau user untuk melihat lokasi sepeda  motor secara langsung dan akurat dalam waktu nyata. Informasi lokasi yang terus diperbarui memungkinkan pengguna untuk melacak pergerakan sepeda motor secara aktif. Disana juga terdapat beberapa pilihan seperti rute, simpan, informasi, estimasi waktu tempuh, informasi, dan bagikan. Sedangkan gambar yang disebelah kanan merupakan tampilan dari menu find location. Fitur ini berguna untuk mencari lokasi yang akan dituju. Fitur ini juga memungkinkan pengguna untuk menemukan lokasi sepeda motor secara cepat dan efisien. Pengguna dapat menggunakan fitur  pencarian dalam aplikasi untuk menemukan posisi sepeda motor yang mungkin terparkir di tempat yang tidak dikenal atau hilang.

Terdapat tampilan dari menu connect to motorcycle. Didalamnya user diminta untuk menscan barcode yang terdapat pada alat gps untuk disambungkan ke website. Dalam gambar yang berada dikiri merupakan tampilan dari menu history location yang berisi tentang histori lokasi yang telah dikunjungi pada hari ini atau hari sebelumnya. Didalam histori ini juga menampilkan waktu atau jam pada saat mengunjungi lokasi tersebut. Dalam gambar yang beraada disebelah kanan merupakan tampilan dari menu notification yang tampilannya hampir mirip dengan history location, yaitu menampilkan notifikasi pada hari ini atau sebelumnya. Didalam tampilan tersebut juga sudah dilengkapi dengan tanggal dan waktu kapan notifikasi tersebut masuk.

3.2	Antarmuka Perangkat Keras
Berikut adalah beberapa hardware interfaces (antarmuka perangkat keras) dalam aplikasi GPS Tracking Motorcycle :

a.	Modul GPS: Menghubungkan modul GPS ke sepeda motor untuk menerima sinyal satelit dan memberikan informasi lokasi.
b.	Antena GPS: Digunakan untuk menerima sinyal satelit yang diperlukan untuk pelacakan lokasi.
c.	Unit Pengendali (Server): Menghubungkan unit pengendali atau pemroses untuk mengelola data pelacakan GPS.
d.	Layar atau Tampilan: Menampilkan informasi pelacakan GPS kepada pengemudi, seperti posisi, kecepatan, dan jarak.
e.	Tombol atau Pengontrol: Memberikan pengendalian atau interaksi kepada pengemudi untuk mengaktifkan fitur pelacakan atau melakukan operasi lainnya.
f.	Sensor Tambahan: Menghubungkan sensor tambahan, seperti sensor kecepatan atau suhu, untuk memberikan data tambahan.

3.3	Antarmuka Perangkat Lunak
Dalam aplikasi GPS tracking sepeda motor, terdapat beberapa software interfaces penting:
API untuk komunikasi dengan sistem lain, antarmuka pengguna untuk interaksi dengan pengemudi, database untuk penyimpanan data, antarmuka geospasial untuk interaksi dengan data peta dan lokasi, antarmuka komunikasi jaringan untuk pertukaran data, dan antarmuka perangkat keras untuk komunikasi dengan perangkat fisik. Semua antarmuka ini penting untuk integrasi yang baik dan pengalaman pengguna yang lancar.

3.4	Antarmuka Komunikasi
Dalam website GPS Tracking Motorcycle, Communications Interfaces meliputi :

a.	Koneksi Jaringan: Digunakan untuk mengirim dan menerima data pelacakan melalui Wi-Fi dan jaringan seluler.
b.	Protokol Komunikasi: Memastikan pengiriman data yang andal melalui protokol seperti TCP/IP.
c.	API: Digunakan untuk berkomunikasi dengan sistem backend, mengirim dan menerima data lokasi serta informasi rute.
d.	SMS: Menggunakan pesan teks untuk mengirim data pelacakan, notifikasi, atau perintah ke perangkat GPS.
e.	Bluetooth: Antarmuka komunikasi dengan perangkat lain yang terhubung ke sepeda motor, seperti wearables atau sensor tambahan.
f.	Push Notification: Mengirim notifikasi langsung ke pengguna, seperti peringatan zona terlarang.
g.	Streaming Data: Mengirim data pelacakan secara kontinu dalam waktu nyata ke server atau aplikasi GPS Tracking Motorcycle.


4.	Fitur Sistem
Sistem aplikasi GPS tracking untuk sepeda motor memiliki beberapa fitur penting yang mencakup :

4.1	Real-Time Location (Lokasi secara Real-Time)
Fitur ini memungkinkan pengguna aplikasi untuk melihat lokasi sepeda motor secara langsung dan akurat dalam waktu nyata. Informasi lokasi yang terus diperbarui memungkinkan pengguna untuk melacak pergerakan sepeda motor secara aktif.

4.2	History Location (Riwayat Lokasi)
Fitur ini memungkinkan pengguna untuk melihat riwayat lokasi sepeda motor dalam jangka waktu tertentu. Pengguna dapat memeriksa rute yang telah dilewati, jarak yang ditempuh, dan titik-titik lokasi yang dikunjungi sebelumnya.

4.3	Find Location (Temukan Lokasi)
Fitur ini memungkinkan pengguna untuk menemukan lokasi sepeda motor secara cepat dan efisien. Pengguna dapat menggunakan fitur pencarian dalam aplikasi untuk menemukan posisi sepeda motor yang mungkin terparkir di tempat yang tidak dikenal atau hilang.

4.4	Connect to Motorcycle (Terhubung dengan Sepeda Motor)
Fitur ini memungkinkan aplikasi untuk terhubung dengan perangkat yang terpasang di sepeda motor, seperti modul GPS atau perangkat pelacakan lainnya. Koneksi ini memungkinkan aplikasi untuk menerima data pelacakan secara real-time dan mengirimkan perintah atau notifikasi ke sepeda motor.

4.5	Notification (Notifikasi)
Fitur ini memberikan notifikasi kepada pengguna terkait dengan informasi penting terkait sepeda motor. Notifikasi dapat mencakup peringatan ketika sepeda motor meninggalkan zona yang ditentukan, peringatan kecepatan berlebih, atau informasi lain yang relevan dengan pelacakan dan keamanan sepeda motor.

Dengan kombinasi fitur-fitur ini, pengguna aplikasi GPS tracking sepeda motor dapat memantau lokasi sepeda motor secara real-time, m0elihat riwayat perjalanan, menemukan lokasi yang hilang, terhubung dengan perangkat di sepeda motor, dan menerima notifikasi penting terkait dengan pelacakan dan keamanan sepeda motor.


5.	Persyaratan Fungsional Lainnya

5.1	Persyaratan Performa
Aplikasi GPS Tracking Motorcycle dapat beroperasi dengan efektif dan efisien dalam melakukan pelacakan sepeda motor apabila user (pengendara) dan admin menjalankan aplikasi ini secara optimal.

Berikut beberapa performance requirements diperlukan dalam aplikasi GPS Tracking Motorcycle :

Hardware Requirements:
1.	Smartphone atau perangkat GPS
2.	Koneksi Internet
3.	Mounting atau pemasangan
4.	Sumber daya

Software Requirements:
1.	Aplikasi GPS Tracking
2.	Akses ke lokasi
3.	Akun pengguna
4.	Pembaruan perangkat lunak

5.2	Persyaratan Keamanan Pengguna
Keamanan ini sangat penting terhadap server dan database, agar memberikan penggunaan aplikasi yang lebih aman, meminimalkan gangguan saat berkendara, melindungi privasi dan kerusakan, serta menghadirkan fitur darurat yang dapat membantu pengendara dalam situasi yang membutuhkan. Berikut beberapa safety requirements diperlukan dalam aplikasi GPS Tracking Motorcycle :

1.	Keamanan Pengendara: Dapat memastikan bahwa aplikasi tidak mengganggu konsentrasi pengendara motor. Pengendara harus tetap fokus pada jalan dan lalu lintas, dan tidak teralihkan oleh aplikasi. Oleh karena itu, aplikasi harus memiliki antarmuka yang intuitif dan pengoperasian yang mudah agar pengendara dapat menggunakan aplikasi dengan aman tanpa mengorbankan keselamatan mereka.
2.	Penggunaan yang Aman saat Berkendara: Dapat mendorong penggunaan yang aman dari aplikasi. saat pengendara sedang berkendara. Misalnya, fitur seperti instruksi suara dan peringatan perubahan rute dapat membantu pengendara tetap fokus pada jalan tanpa mengganggu konsentrasi mereka.
3.	Privasi dan Keamanan Data: Harus melibatkan perlindungan privasi dan keamanan data pengguna. Aplikasi harus melindungi informasi pribadi dan data lokasi pengendara dengan mengimplementasikan protokol keamanan yang kuat. Selain itu, aplikasi harus menjaga kerahasiaan informasi pengguna dan menghindari penggunaan data yang tidak sah atau penyalahgunaan oleh pihak ketiga.
4.	Pemantauan Penggunaan oleh Administrator: Harus melibatkan fitur pemantauan yang dapat digunakan oleh administrator atau pemilik kendaraan untuk memastikan penggunaan yang aman dan sesuai dengan kebijakan perusahaan atau organisasi.
5.	Respons Darurat: Aplikasi ini harus mempertimbangkan kemungkinan keadaan darurat, seperti kecelakaan atau situasi darurat lainnya, karena mengharuskan aplikasi menyediakan fitur untuk memanggil bantuan darurat atau memberikan lokasi pengendara dengan cepat kepada pihak yang berwenang.

5.3	Persyaratan Keamanan GPS Tracking Motorcycle
Keamanan ini sangat penting terhadap server dan database, agar menjaga kerahasiaan dan integritas pengguna, melindungi aplikasi dari serangan dan penyusupan, serta memastikan bahwa penggunaan aplikasi tetap aman dan terlindungi. Berikut beberapa security requirements diperlukan dalam aplikasi GPS tracking motorcycle :

1.	Perlindungan Data Pengguna: Dapat memastikan bahwa data pengguna, termasuk informasi pribadi dan lokasi, terlindungi secara adekuat dari akses yang tidak sah atau penyalahgunaan. Aplikasi harus mengimplementasikan mekanisme keamanan yang kuat, seperti enkripsi data dan otentikasi yang aman, untuk mencegah akses oleh pihak yang tidak berwenang.
2.	Pencegahan Penyusupan dan Serangan: Dapat membantu melindungi aplikasi dari penyusupan dan serangan oleh pihak yang tidak berwenang. Aplikasi harus memiliki langkah-langkah keamanan yang efektif untuk memastikan kelancaran operasi aplikasi dan keamanan data pengguna.
3.	Keamanan Komunikasi: Aplikasi ini mengirimkan data secara real-time antara perangkat GPS dan server aplikasi, karena dapat memastikan bahwa komunikasi antara perangkat dan server dilakukan melalui saluran yang aman dan terenkripsi. Ini mencegah penyadapan atau manipulasi data saat dikirimkan melalui jaringan.
4.	Keamanan Perangkat: Harus mempertimbangkan keamanan perangkat yang digunakan untuk aplikasi dan memastikan bahwa perangkat yang terhubung aman dan dilindungi dari serangan perangkat keras atau perangkat lunak yang mungkin mengancam keamanan pengguna atau aplikasi itu sendiri.
5.	Manajemen Akses Pengguna: Harus mencakup manajemen akses pengguna yang baik untuk aplikasi, termasuk penerapan autentikasi yang kuat, pengelolaan hak akses berdasarkan peran, dan perlindungan terhadap serangan percobaan login yang tidak sah.

5.4	Atribut Kualitas Perangkat Lunak
Kualitas kelebihan dari sistem ini terhadap perangkat lunak berupa keamanan dan pengawasan data sangat dijaga yang meningkatkan kenyamanan pengguna dalam menjaga kendaraan atau objek lainnya dan dapat memberikan kualitas yang baik, performa yang andal, serta pengalaman pengguna yang memuaskan. Bila hal-hal yang tidak diinginkan terjadi, bisa dengan mudah melacak posisi objek yang dipasangkan alat GPS Tracking Motorcycle.

Berikut beberapa Software Quality Attributes yang relevan pada aplikasi GPS Tracking Motorcycle :

1.	Keandalan (Reliability): Aplikasi harus dapat beroperasi secara konsisten dan dapat diandalkan. Keandalan yang baik berarti aplikasi dapat melacak dan melaporkan posisi motor secara akurat dan tanpa kegagalan yang sering.
2.	Kinerja (Performance): Aplikasi harus responsif dan mampu mengolah data secara efisien. Ini termasuk kecepatan dalam melacak perubahan posisi motor, waktu respons aplikasi, dan kemampuan untuk menangani jumlah pengguna yang tinggi dengan lancar.
3.	Usability: Aplikasi harus mudah digunakan dan memiliki antarmuka yang intuitif. Pengguna harus dapat dengan mudah mengoperasikan aplikasi, mengakses informasi yang diperlukan, dan memahami fungsi-fungsi yang tersedia.
4.	Keterukuran (Maintainability): Aplikasi harus mudah diperbaiki, dikembangkan, dan dipelihara. Ini mencakup struktur kode yang baik, dokumentasi yang lengkap, serta penggunaan praktik pengembangan perangkat lunak yang baik.
5.	Keamanan (Security): Aplikasi harus memiliki lapisan keamanan yang kuat untuk melindungi data pengguna, mencegah akses yang tidak sah, dan menjaga kerahasiaan informasi pribadi.
6.	Portabilitas (Portability): Aplikasi harus dapat berjalan pada berbagai platform atau perangkat, seperti smartphone dengan sistem operasi yang berbeda. Ini memungkinkan pengguna untuk menggunakan aplikasi pada perangkat yang mereka pilih tanpa batasan yang signifikan.
7.	Efisiensi (Efficiency): Aplikasi harus menggunakan sumber daya perangkat, seperti daya baterai dan jaringan, secara efisien. Hal ini penting agar pengguna dapat menggunakan aplikasi tanpa mengorbankan daya baterai atau melambatkan koneksi data mereka.
8.	Skalabilitas (Scalability): Aplikasi harus dapat menangani pertumbuhan jumlah pengguna dan perangkat yang terhubung dengan lancar. Kemampuan untuk meningkatkan kapasitas dan kinerja aplikasi sesuai dengan kebutuhan adalah aspek yang penting.
9.	Interoperabilitas (Interoperability): Aplikasi harus dapat berinteraksi dengan perangkat atau sistem lain dengan mudah. Ini termasuk kemampuan untuk berintegrasi dengan perangkat GPS motor yang berbeda atau layanan pihak ketiga yang relevan.
10.	Keamanan Data (Data Security): Aplikasi harus melindungi data pengguna, baik dalam penyimpanan maupun saat ditransmisikan. Penggunaan enkripsi dan tindakan keamanan data lainnya adalah komponen penting dari atribut ini.

5.5	Proses Bisnis
Business rules ini mengatur interaksi dan fungsi aplikasi GPS Tracking Motorcycle dari sudut pandang pengendara dan admin. Dengan demikian, aplikasi dapat memberikan pengalaman yang lebih baik dan memberdayakan pengendara serta memberikan kontrol kepada admin untuk mengelola sistem dengan lebih efisien. Berikut adalah penjelasan mengenai business rules yang telah disebutkan :

1.	Pengendara:
a.	Daftar/Login: Pengendara harus mendaftar dan membuat akun atau masuk ke dalam akun yang ada sebelum dapat menggunakan fitur-fitur website.
b.	Memasukkan Data Kendaraan: Setelah pengendara berhasil masuk, mereka harus memasukkan data kendaraan mereka, seperti nomor plat, merek, tipe, dan informasi lainnya yang relevan.
c.	Melihat Lokasi Kendaraan: Pengendara dapat melihat lokasi real-time dari kendaraan mereka melalui website GPS tracking motorcycle. Ini memungkinkan mereka untuk mengetahui di mana kendaraan mereka berada saat ini.
d.	Melihat Riwayat Perjalanan: Pengendara dapat melihat riwayat perjalanan kendaraan mereka. Informasi yang tersedia dalam riwayat perjalanan meliputi waktu yang diambil, jarak yang ditempuh, dan rute yang diambil selama perjalanan.
2.	Admin:
a.	Mengelola Akun: Admin bertanggung jawab untuk mengelola akun pengguna, termasuk pembuatan akun baru, penghapusan akun, atau pembaruan informasi pengguna.
b.	Menetapkan Pemberitahuan/Notifikasi : Admin dapat menetapkan pemberitahuan atau notifikasi tertentu kepada pengendara. Misalnya, admin dapat mengirimkan pemberitahuan jika ada pemeliharaan rutin yang harus dilakukan pada kendaraan atau pemberitahuan penting lainnya.
c.	Merekam Riwayat Perjalanan : Admin dapat merekam riwayat perjalanan kendaraan. Ini melibatkan penyimpanan informasi perjalanan, seperti waktu, jarak, dan rute, untuk tujuan dokumentasi atau analisis lebih lanjut.

