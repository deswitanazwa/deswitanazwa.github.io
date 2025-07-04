---
layout : post
title : Local Database Development
---

penjelasan mengenai Local Database Development

Local database development adalah proses mengelola dan menguji database langsung dikomputer lokal(bukan di serve online). Ini merupakan bagian penting dalam pengembangan aplikasi, karena memungkan pengembangan untuk membuat, mengedit, dan menjalankan query database tanpa koneksi internet atau risiko mengganggu data produksi. Tools yang umum digunakan diantaranya;
<ol type = 1>
    <li>XAMPP</li>
        <img src="/assets/image/xampp.jpeg" width="300" >
        <br>XAMPP adalah paket perangkat lunak gratis yang digunakan untuk membuat server lokal di komputer. Nama XAMPP merupakan dingkatan dari (Xcross-paltform, Apache, MySQL, Php, Perl). XAMPP sangat populer dalam pengembangan web karena memudahkan pengembangan untuk menjalankan dan menguji aplikasi berbasis PHP dan database secara lokal, tanpa harus langsung tekoneksi ke serve online. Didalamnya juga sudah tersedia phpMyAdmin, antarmuka web yang memudahkan pengelolaan database MySQL.
    <li>POSTGRESQL</li>
        <img src="/assets/image/postgresSQL.jpeg" width="300" >
        <br>PostgreSQL adalah sistem manajemen basis data relasional (RDBMS) bersifat open-source yang kuat dan andal. PostgresSQL dikenal karena keamanannya, stabilitasnya, dan skalabilitasnya, sehingga cocok digunakan untuk aplikasi kecil hingga skala besar. Banyak digunakan diperusahaan, startup, hingga proyek open-source karena flesibilitas dan kinerjanya yang tinggi.
    <li>MongoDB</li>
        <img src="/assets/image/mongodb.jpeg" width="300" >
        <br>MongoDB adalah sistem manajemen basis data dalam format dokumen JSON(dikenal sebagai BSON), bukan dalam bentuk tabel seperti pada database relasional. MongoDB memiliki beberapa keunggulan diantaranya;
        <ul>
            <li>cocok untuk data yang tidak terstruktur atau berubah-ubah</li>
            <li>skalabilitas tinggi, mendukung big data dan aplikasi real-time</li>
            <li>Tidak perlu skema tetap, jado flesibel saat mengembangkan aplikasi
        </ul>
    <li>SQLite</li>
        <img src="/assets/image/SQLite.jpeg" width="300" >
        SQLite adalah sistem database relasional(RDBMS) yang ringan, sederhana, dan tidak memerlukan server. Semua data disimpan dalam satu file di komputer lokal. Keunggulan SQLite ini diantaranya;
        <ul>
            <li>Tidak perlu instalasi server database</li>
            <li>Cocok untuk aplikasi kecil, prototipe, atau aplikasi mobile</li>
            <li>cepat, efisien, dan mudah dibawa ke mana-mana</li>
        </ul>
    <li>DBeaver</li>
        <img src="/assets/image/dbreaver.jpeg" width="300" >
        DBreaver adalah aplikasi GUI (Graphical User Interface) untuk mengelola berbagai jenis database, termasuk MySQL, PostgresSQL, MongoDB, SQLite, dan lainnya. DBreave memiliki fungsi diantaranya;
        <ul>
            <li>Membuat, mengedit, dan menelusuri tabel atau dokumen database</li>
            <li>Menjalankan query SQL atau MongoDB dengan antarmuka yang ramah pengguna</li>
            <li>Menyediakan tools visual seperti diagram relasi dan ekspor data</li>
        </ul>
</ol>

