# Praktikum 8: PHP dan Database MySQL

## Nama: Syafarudiansya
## NIM: 312410381
## Kelas: TI 24 A6

### 1. Membuat Database
<img src="gambar/3.png" width="300"/>

### 2. Membuat Tabel
<img src="gambar/4.png" width="300"/>

### 3. Menambahkan Data
<img src="gambar/5.png" width="500"/>

### Hasil:
<img src="gambar/6 (2).png" width="500"/>

### Membuat Program CRUD

#### 1. Membuat file koneksi.php
```php
<?php
$host = "localhost";
$user = "root";
$pass = "";
$db = "latihan1";

$conn = mysqli_connect($host, $user, $pass, $db);
if ($conn == false)
{
    echo "Koneksi ke server gagal.";
    die();
} #else echo "Koneksi berhasil";
?>
```
Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan
koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”;

<img src="gambar/7.png" width="300"/>
