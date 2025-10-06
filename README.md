# Penjelasan setiap langkah praktikum beserta screenshot & PertanyaanTugas

**1.Membuat Dokumen HTML Dasar**

Buat file baru di dalam folder 
Lab3Web dan beri nama lab3_list.html. Seperti berikut.
code:
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
```



**2. Membuat Ordered List**

Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.
code:
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

Output:

<img width="537" height="450" alt="Screenshot 2025-10-06 131339" src="https://github.com/user-attachments/assets/e84a9c3b-2306-4d83-b78b-b54fd44ceaee" />



**3. Membuat Unorderd List**

Tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada
section unordered-list, seperti berikut.
Code:
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

Output:

<img width="640" height="583" alt="Screenshot 2025-10-06 131554" src="https://github.com/user-attachments/assets/a2d88e77-896e-4869-b379-777c256b131a" />



**4. Membuat Description List**

Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.
Code
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

Output:

<img width="674" height="913" alt="Screenshot 2025-10-06 131828" src="https://github.com/user-attachments/assets/605c7b51-e84f-4d1c-80e8-171932bed3b3" />



Selanjutnya lakukan eksperimen lain terkait list dan penggunaan atribut type pada list.



**5. Membuat Tabel**

Buat file baru dengan nama lab3_tabel.html seperti berikut.
Code:
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
<h1>Membuat Table</h1>
</header>
</body>
</html>
```

Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
Code:
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

Output:

<img width="659" height="504" alt="Screenshot 2025-10-06 132033" src="https://github.com/user-attachments/assets/62d51fa5-e392-4107-ab8a-b1260ce22d2f" />



**6. Menggabungkan Sel Data**

Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk
menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara
horizontal).
Code:
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

Output:

<img width="676" height="553" alt="Screenshot 2025-10-06 132423" src="https://github.com/user-attachments/assets/314abe0d-cbca-4331-bf0b-fb3190c374d9" />



**7. Membuat Form**

Buat file baru dengan nama lab3_form.html seperti berikut.
Code:
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

Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
Code:
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

Output:

<img width="952" height="745" alt="Screenshot 2025-10-06 132828" src="https://github.com/user-attachments/assets/40eb255f-6281-43ea-85db-f7fd84aca64f" />



**8. Menabahkan Style pada Form**

Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.
Code:
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

Output:

<img width="941" height="682" alt="Screenshot 2025-10-06 132942" src="https://github.com/user-attachments/assets/44fb6a35-ecfe-4961-a7d9-96ae8753442b" />



# Pertanyaan Dan tugas

**Membuat Form dengan Dropdown Menu dan Listbox Multiple Selection**
**Deskripsi**
Tugas ini bertujuan untuk membuat sebuah form HTML yang memiliki:
- Dropdown menu untuk memilih program studi
- Listbox dengan multiple selection untuk memilih bidang minat
- Tampilan hasil input menggunkan html

  Output:

  <img width="796" height="809" alt="Screenshot 2025-10-06 194855" src="https://github.com/user-attachments/assets/ed9dce22-32d5-418d-b32a-d136a647094d" />



  Hasil Kirim:
  
<img width="778" height="393" alt="Screenshot 2025-10-06 194908" src="https://github.com/user-attachments/assets/3740a833-39b8-4f77-907a-ddb70760a7d9" />

  





