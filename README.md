***Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut***
```
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>HTML Lanjutan</title>
</head>
<body>
 <header>
 <h1>Membuat List</h1>
 </header>
</body>
</html>
```
***Kemudian tambahkan kode untuk membuat Ordered List seperti berikut***
```
 <section id="order-list">
 <h2>Ordered List</h2>
 <ol>
 <li>Pemrograman Web</li>
 <li>Sistem Informasi</li>
 <li>Basis Data 2</li>
 </ol>
 </section>
 ```
 ![1](https://user-images.githubusercontent.com/81580084/114474380-4c6c8900-9c20-11eb-824a-755969e5987c.png)
 
 ***Membuat Unorderd List***
 ```
 <section id="unorder-list">
 <h2>Unordered List</h2>
 <ul type="square">
 <li>Jaringan Komputer</li>
 <li>Struktur Data</li>
 <li>Algoritma &amp; Pemrograman</li>
 </ul>
 </section>
 ```
 ![2](https://user-images.githubusercontent.com/81580084/114475063-b9345300-9c21-11eb-8dbe-a791f107d292.png)

***Membuat Description List***
```
 <section id="unorder-list">
 <h2>Description List</h2>
 <dl>
 <dt>Fakultas Teknik</dt>
 <dd>Teknik Industri</dd>
 <dd>Teknik Informatika</dd>
 <dd>Teknik Lingkungan</dd>
 <dt>Fakultas Ekonomi dan Bisnis</dt>
 <dd>Akuntansi</dd>
 <dd>Manajemen</dd>
 <dd>Bisnis Digital</dd>
 </dl>
 </section>
```
![3](https://user-images.githubusercontent.com/81580084/114475299-2e078d00-9c22-11eb-9012-e96ec8a300a4.png)

Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
```
 <table border="1" cellpadding="4" cellspacing="0">
 <thead>
 <tr>
 <th>No.</th>
 <th>Fakultas</th>
 <th>Program Studi</th>
 </tr>
 </thead>
 <tbody>
 <tr>
 <td>1.</td>
 <td>Teknik</td>
 <td>Teknik Informatika</td>
 </tr>
 <tr>
 <td>2.</td>
 <td>Teknik</td>
 <td>Teknik Industri</td>
 </tr>
 <tr>
 <td>3.</td>
 <td>Teknik</td>
 <td>Teknik Lingkungan</td>
 </tr>
 </tbody>
 </table>
 ```
 ![4](https://user-images.githubusercontent.com/81580084/114475547-b0904c80-9c22-11eb-8458-03d161e2ba69.png)
 
 ***Mengatur Margin dan Padding***
 ```
 <table border="1" cellpadding="4" cellspacing="0">
 ```
 ![5](https://user-images.githubusercontent.com/81580084/114475761-1250b680-9c23-11eb-8dcc-bfeb0ddc07fa.png)
 
***Menggabungkan Sel Data***

Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara horizontal).
```
<table border="1" cellpadding="6" cellspacing="0">
<thead>
<tr>
<th>No.</th>
<th>Fakultas</th>
<th>Program Studi</th>
</tr>
</thead>
<tbody>
<tr>
<td>1.</td>
<td rowspan="3">Teknik</td>
<td>Teknik Informatika</td>
</tr>
<tr>
<td>2.</td>
<td>Teknik Industri</td>
</tr>
<tr>
<td>3.</td>
<td>Teknik Lingkungan</td>
</tr>
</tbody>
</table>
```
![Screenshot (54)](https://user-images.githubusercontent.com/81580084/114475962-8b500e00-9c23-11eb-86ca-04ac31806bdc.png)

***Membuat Form***

Buat file baru dengan nama lab3_form.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>HTML Lanjutan</title>
</head>
<body>
 <header>
 <h1>Membuat Form</h1>
 </header>
</body>
</html>
```
***Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:***
```
<form action="proses.php" method="post">
 <fieldset>
 <legend>Data Pelanggan</legend>
 <p>
 <label for="nama">Nama</label>
 <input type="text" id="nama" name="nama">
 </p>
 <p>
 <label for="alamat">Alamat</label>
 <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
 </p>
 <p>
 <label>Jenis Kelamin</label>
 <input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
 <input id="jk_p" type="radio" name="kelamin" value="P" /><label
 for="jk_p">Perempuan</label>
 </p>
 <p><input type="submit" value="Login"></p>
 </fieldset>
</form>
```
![Screenshot (60)](https://user-images.githubusercontent.com/81580084/114476829-30b7b180-9c25-11eb-8036-6d18bfb23160.png)

***Menabahkan Style pada Form***

Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.
```
<style>
 form p > label {
 display: inline-block;
 width: 100px;
 }
 form input[type="text"], form textarea {
 border: 1px solid #197a43;
 }
 form input[type="submit"] {
 border: 1px solid #197a43;
 background-color: #197a43;
 color: #ffffff;
 font-weight: bold;
 padding: 5px 15px;
 }
</style>
```
![Screenshot (61)](https://user-images.githubusercontent.com/81580084/114477025-af145380-9c25-11eb-9429-52ae8a45aed7.png)





