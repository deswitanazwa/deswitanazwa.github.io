---
layout : post
title : Koneksi database dan PHP
---
  penjelasan mengenai koneksi database dan php

  <img src="/assets/image/koneksi-php.jpg" width="500">

  <h2>Penjelasan:</h2>
  <p>Koneksi antara PHP dan MySQL sangat penting dalam pengembangan aplikasi web dinamis. PHP digunakan sebagai bahasa pemrograman server-side, sedangkan MySQL adalah sistem manajemen basis data (DBMS) yang sering digunakan untuk menyimpan data secara terstruktur.</p>

  <p>Agar aplikasi dapat berfungsi dengan baik, PHP harus bisa berkomunikasi dengan MySQL melalui koneksi yang aman dan stabil.</p>

  <h2>Langkah-langkah Dasar Membuat Koneksi:</h2>
  <ul>
    <li>Gunakan fungsi <code>mysqli_connect()</code> atau objek <code>PDO</code>.</li>
    <li>Siapkan parameter koneksi seperti:
      <ul>
        <li><strong>Host:</strong> biasanya <code>localhost</code>.</li>
        <li><strong>Username:</strong> default-nya adalah <code>root</code>.</li>
        <li><strong>Password:</strong> kosong untuk default XAMPP.</li>
        <li><strong>Database:</strong> nama database yang ingin digunakan.</li>
      </ul>
    </li>
    <li>Cek apakah koneksi berhasil atau tidak menggunakan kondisi <code>if</code>.</li>
  </ul>

  <h2>Contoh Kode Koneksi Menggunakan <code>mysqli</code>:</h2>
  <pre><code>&lt;?php
$host = "localhost";
$user = "root";
$pass = "";
$db = "nama_database";

$conn = mysqli_connect($host, $user, $pass, $db);

if (!$conn) {
    die("Koneksi gagal: " . mysqli_connect_error());
}
echo "Koneksi berhasil!";
?&gt;</code></pre>

  <h2>Penjelasan Kode:</h2>
  <ul>
    <li><code>$host</code>: alamat server database, umumnya <code>localhost</code>.</li>
    <li><code>$user</code>: username database, default XAMPP adalah <code>root</code>.</li>
    <li><code>$pass</code>: password database, seringkali kosong pada XAMPP lokal.</li>
    <li><code>$db</code>: nama database yang telah kamu buat di phpMyAdmin.</li>
    <li><code>mysqli_connect()</code>: fungsi untuk menghubungkan PHP ke database MySQL.</li>
    <li><code>mysqli_connect_error()</code>: menampilkan pesan error jika koneksi gagal.</li>
  </ul>

  <h2>Tips Tambahan:</h2>
  <ul>
    <li>Pastikan Apache dan MySQL aktif saat menggunakan XAMPP.</li>
    <li>Cek kembali nama database yang digunakan agar sesuai.</li>
    <li>Simpan file PHP di folder <code>htdocs</code> agar bisa diakses melalui browser (misalnya: <code>localhost/koneksi.php</code>).</li>
  </ul>

  