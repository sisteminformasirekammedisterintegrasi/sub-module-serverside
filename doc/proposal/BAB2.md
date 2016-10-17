BAB II
LANDASAN TEORI

2.1	Sistem 
Sistem adalah serangkaian komponen yang saling berinteraksi dan bekerja sama untuk mencapai suatu tujuan tertentu. [1]  
Informasi 
Informasi adalah sebagai data yang telah diproses sedemikian rupa sehingga menigkatkan pengetahuan seseorang yang menggunakan data tersebut. [2]

2.2	Rekam Medis 
Rekam Medis adalah berkas yang berisi catatan dan dokumen mengenai identitas pasien, hasil pemeriksaan, pengobatan, tindakan dan pelayanan lainnya yang diterima pasien pada saran kesehatan, baik rawat jalan maupun rawat inap. [3]

2.3	Model Proses
Proses pemodelan ini akan menggunakan tool seperti Start UML, Kamus Data yang akan dijelaskan secara definitif.

2.4	Unified Modeling Language (UML)
UML adalah bahasa untuk menspesifikasi, memvisualisasi, membangun dan
mendokumentasikan  artifacts (bagian dari informasi yang digunakan atau dihasilkan 
oleh proses pembuatan perangkat lunak,  artifact  tersebut dapat berupa model,
deskrips i atau perangkat lunak) dari sistem perangkat lunak, seperti pada pemodelan 
bisnis dan sistem non perangkat lunak lainnya [HAN98]. Selain itu UML adalah
bahasa pemodelan yang menggunakan konsep orientasi  object. UML dibuat oleh 
Grady Booch ,  James Rumbaugh , dan  Ivar Jacobsondi bawah bendera  Rational 
Software Corp [4].  



2.4.1	Usecase Diagram 
Menggambarkan sejumlah  external actors dan hubungannya ke  use caseyang  diberikan oleh sistem. Use caseadalah deskripsi fungsi yang disediakan oleh sistem dalam bentuk teks sebagai dokumentasi dari  use case symbol  namun dapat juga  dilakukan dalam  activity diagrams .Use case digambarkan hanya yang dilihat dari luar oleh  actor (keadaan lingkungan sistem yang dilihat user) dan bukan bagaimana fungsi yang ada di dalam sistem [4]
2.4.2	Class Diagram 
2.4.3	Menggambarkan struktur statis class di dalam sistem. Class merepresentasikan sesuatu yang ditangani oleh sistem.  Class dapat berhubungan dengan yang lain melalui berbagai cara:  associated (terhubung satu sama lain),  dependent (satu  class tergantung/menggunakan  class yang lain),  specialed (satu class merupakan spesialisasi dari  class lainnya), atau  package (grup bersama sebagai satu unit). Sebuah sistem biasanya mempunyai beberapa  class diagram. [4]
2.4.4	Sequence Diagram
Menggambarkan  kolaborasi dinamis antara sejumlah  object. Kegunaanya untuk menunjukkan rangkaian pesan yang dikirim antara  object juga interaksi antara  object, sesuatu yang terjadi pada titik tertentu dalam eksekusi sistem.[4]
2.4.5	State Diagram
Menggambarkan semua  state  (kondisi) yang dimiliki oleh suatu  object dari suatu  class dan keadaan yang menyebabkan  stateberu bah. Kejadian dapat berupa  object lain yang mengirim pesan. State class tidak digambarkan untuk semua  class, hanya yang mempunyai sejumlah state yang terdefinisi dengan baik dan kondisi  class berubah oleh stateyang berbeda. [4]
2.4.6	Collaboration Diagram
Menggambarkan kolaborasi dinamis seperti  sequence diagrams . Dalam menunjukkan  pertukaran pesan,  collaboration diagrams menggambarkan  object dan hubungannya (mengacu ke konteks). Jika penekannya pada waktu atau urutan gunakan  sequence diagrams, tapi jika penekanannya pada konteks gunakan collaboration diagram. [4]
2.4.7	Activity Diagram
Menggambarkan rangkaian aliran dari aktivitas, digunakan untuk mendeskripsikan aktifitas yang dibentuk dalam suatu operasi sehingga dapat juga digunakan untuk aktifitas lainnya seperti  use case atau interaksi. [4]
2.4.8	Component Diagram
Menggambarkan struktur fisik kode dari komponent. Komponent dapat berupa source code, komponent biner, atau  executable component . Sebuah komponent berisi informasi tentang logic class atau class yang diimplementasikan sehingga membuat pemetaan dari  logical view ke  component view. [4]
2.4.9	Deployment Diagram
Menggambarkan arsitektur fisik dari perangkat keras dan perangkat lunak sistem, menunjukkan hubungan komputer dengan perangkat (nodes) satu sama lain dan jenis hubungannya. Di dalam  nodes ,   executeable component  dan  objectyang dialokasikan untuk memperlihatkan unit perangkat lunak yang dieksekusi oleh  node tertentu dan ketergantungan komponen. [4]
2.5	Basis Data
Basis data merupakan kumpulan beberapa tabel yang berisi data yang saling berhubungan. Hubungan biasanya ditunjukan dengan kunci dari tiap file yang ada. Penyusunan basis data meliputi proses memasukkan data ke dalam penyimpanan data dan diatur dengan menggunakan perangkat Sistem Manajemen Basis Data (Database Management System). Manipulasi basis data dapat dilakukan dengan  pembuatan pernyataan (query) untuk mendapatkan informasi tertentu, melakukan pembaharuan atau penggantian (update) data, serta pembuatan report data. Tujuan utama DBMS adalah untuk menyediakan tinjauan abstrak dari data bagi user.[5]

2.6	PHP (Hypertext Preprocesor)
Untuk membuat halaman web yang dinamis digunakan bahasa pemograman PHP yang merupakan bahasa server-side scripting yang menyatu dengan HTML. Maksud server-side scripting adalah pada dokumen HTML disisipkan sintaks dan perintah-perintah yang sepenuhnya dijalankan di server. Untuk menuliskan dan memperkenalkan kode PHP, memulainya harus dengan tanda <?php, setelah tanda tersebut, dapat melanjutkan dengan kode program isi di dalamnya. Untuk mengakhiri kode program yang dibuat, dapat menutupnya dengan tanda ?>. [6]


2.7	Apache Web Server
Apache Web Server adalah Web server yang digunakan untuk melayani permintaan browser client yang meminta akses ke suatu halaman website yang berada di sisi server. Apache bertanggung jawab pada request-response HTTP. Apache Web Server memiliki fitur-fitur canggih seperti pesan kesalahan yang dapat dikonfigurasi, autentifikasi berbasis basis data dan lain-lain. Apache juga didukung antarmuka pengguna berbasis grafik (GUI) yang memungkinkan penanganan server menjadi mudah.[7]


2.8	MySQL
MySQL (My Structure Query Language) merupakan database yang sangat kuat dan cukup stabil untuk digunakan sebagai media penyimpanan data. Oleh karena itu, database ini merupakan database yang paling banyak digunakan untuk mengolah database. Penggunaan bahasa query standar yang dimiliki SQL (Structur Query Language) merupakan kelebihan lain dari MySQL. [5]

2.9	Web Service 
Web service adalah sebuah sistem softwareyang di desain untuk mendukung interoperabilitas interaksi mesin ke mesin melalui sebuah jaringan. Interfaceweb service dideskripsikan dengan menggunakan format yang mampu diproses oleh mesin (khususnya WSDL). Sistem lain yang akan berinteraksi dengan web service hanya memerlukan SOAP, yang biasanya disampaikan dengan HTTP dan XML sehingga mempunyai korelasi dengan standar Web. [9]

2.10	Pengujian
Pengujian blackbox testing merupakan pengujian yang diturunkan dari spesifikasi program atau komponen. Sistem merupakan kotak hitam yang perilakunya hanya dapat ditentukan dengan mempelajari input dan ditentukan dengan mempelajari input dan output yang berkaitan. 
Blackbox testing memfokuskan pada kebutuhan fungsional dari software. Pengujian ini memperbolehkan software engineer menurunkan sejumlah input yang ditunjukkan untuk menguji kebutuhan fungsional dari suatu program
Tujuan metode ini mencari kesalahan pada :
1.	Fungsi yang salah atau hilang
2.	Kesalahan pada interface
3.	Kesalahan pada struktur data atau akses database
4.	Kesalahan performansi
5.	Kesalahan inisialisasi dan tujuan akhir [8]


