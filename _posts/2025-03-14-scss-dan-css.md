---
layout: post
title: "SCSS dan CSS"
---

penjelasan tentang perbedaan SCSS dan CSS

<li><b>Pengertian dan definisi CSS dan SCSS</b></li>
CSS(Cascading Style Sheets) adalah bahasa pemograman yang digunakan untuk mengatur tampilan dan layout web. Dengan CSS, pengguna dapat mengontrol tampilan dari elemen HTML seperti font, warna, ukuran, dan tata letak. Sedangkan, SCSS (Sassy Cascading Style Sheets) adalah sebuah preprocessor CSS yang memungkinkan pengguna untuk menulis CSS dengan syntax yang lebih mudah dipahami. SCSS memungkinkan pengguna untuk menggunakan fitur yang tidak tersedia di CSS standar seperti variabel, looping, dan nesting.

<li><b>Perbedaan Fitur CSS dan SCSS</b></li>
<table align ='center' border="1">
    <thead>
        <tr bgcolor="lightblue">
            <th width="150" >Fitur</th> <th width="200">CSS</th> <th width="200">SCSS</th>
        </tr>
    </thead>
    <tbody>
        <tr background-color="white" >
            <td><b>Syntax</b></td> <td>Menggunakan aturan standar CSS yang eksplisit</td> <td>Sintax lebih ringkas dan mirip bahasa pemograman</td>
        </tr>
        <tr>
            <td><b>Variabel</b></td> <td>Tidak mendukung variabel secara narative (sebelum CSS custom properties) </td> <td>Mendukung Variabel ($) untuk warna, ukuran, dll</td>
        </tr>
        <tr>
            <td><b>Nesting</b></td> <td>Tidak mendukung nesting (harus ditulis terpisah). contoh<br><i><br>.title{<br>
                font-size: 16px;<br>
            }</i><br><br>harus mengulang penulisan jika ingin menambahkan hover effect<br><br><i>.title:hover{
                <br>font-size: 10px;<br>
            }</i></td> <td>Mendukung nesting, sehingga lebih terstruktur dan rapi. contoh<br><i><br>.title{<br>
            font-size: 16px;<br><br>&:hover{<br>font-size: 10px<br>}<br>}</i></td>
        </tr>
        <tr>
            <td><b>Looping</b></td> <td>Tidak mendukung perulangan</td> <td>Mendukung perulangan seperti @for, @each, dll</td>
        </tr>
        <tr>
            <td><b>File eksternal</b></td> <td>Bisa menggunakan file external .css saja</td> <td>Bisa menyusun dalam banyak file .scss dan @import</td>
        </tr>
    </tbody>
</table>
<br>
<li><b>Kelebihan dan kekurangan CSS dan SCSS</b></li>
Kelebihan yang dimiliki oleh CSS ialah lebih mudah dipahami, tidak memerlukan waktu belajar yang lama, dan cukup untuk digunakan pada website simple. Namun, disamping kelebihan yang telah disebutkan, CSS juga memiki kekurangan diantaaranya susah untuk digunakan pada website yang kompleks, membutuhkan lebih banyak waktu untuk konfigurasinya, dan memiliki keterbarasan dalam menangani website yang kompleks.
<br><br>Sedangkan, SCSS memiliki kelebihan dimana SCSS mendukung nested properties, memiliki kemampuan variable dan mixin, dan meningkatkan produktivitas saat mendesain website. Terlepas daripada kelebihan SCSS yang terasa lebih unggul, Namun SCSS membutuhkan waktu belajar lebih lama, kurangnya fleksibelitas untuk pengguna pemula, dan kurang ideal untuk website dengan desain yang simple.