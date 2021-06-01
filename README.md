# Praktikum 8 (Pemrograman Web)
## Dimas Reza Nugraha
## 311910431
## TI.19.A.2
## Universitas Pelita Bangsa

## Langkah 1
### Menjalankan MySQL Server
Pastikan  web server  Apache  dan  MySQL  server  sudah  dijalankan. Kemudian buka melalui browser: http://localhost/phpmyadmin/
![SS LANGKAH 1](https://user-images.githubusercontent.com/56240719/120282911-d06bf480-c2e4-11eb-88a8-6f33968e99e6.png)

## Langkah 2
### Membuat Database & Menambahkan Tabel di Query SQL
Membuat Database & menambahkan tabel di Query SQL seperti berikut.
![SS LANGKAH 2](https://user-images.githubusercontent.com/56240719/120284822-dd89e300-c2e6-11eb-840f-153b0f627965.png)

## Langkah 3
### Memasukkan data barang di Query SQL
Memasukkan Data Barang di Query SQL seperti berikut.
![SS LANGKAH 3](https://user-images.githubusercontent.com/56240719/120289049-13c96180-c2eb-11eb-904f-e9e86efc842d.png)
Hasilnya jika Data berhasil di input seperti berikut.
![SS LANGKAH 3 (TAMBAHAN)](https://user-images.githubusercontent.com/56240719/120290189-4c1d6f80-c2ec-11eb-8197-1bb1f9e442b3.png)

## Langkah 4
### Membuat Program CRUD
Membuat folder ```Lab8_php_database``` pada root directory web server (c:\xampp\htdocs) seperti berikut. 
![SS LANGKAH 4](https://user-images.githubusercontent.com/56240719/120291024-17f67e80-c2ed-11eb-8a59-0001794cbc3e.png)

Kemudian untuk mengakses directory tersebut pada web server dengan mengakses URL: http://localhost/Lab8_php_database/ seperti berikut.
![SS LANGKAH 4 (TAMBAHAN)](https://user-images.githubusercontent.com/56240719/120356478-93c4eb00-c32e-11eb-9a7e-fed3fb439806.png)

## Langkah 5
### Membuat File Koneksi Database
Membuat file baru dengan nama ```koneksi.php``` seperti berikut
![SS LANGKAH 5](https://user-images.githubusercontent.com/56240719/120300197-e8983f80-c2f5-11eb-97f5-116af2212474.png)

## Langkah 6
### Membuat File Index Untuk Menampilkan Data (READ)
Membuat file baru dengan nama ```index.php``` seperti berikut.
![SS LANGKAH 6](https://user-images.githubusercontent.com/56240719/120305567-192ea800-c2fb-11eb-98f1-baff675c8046.png)

## Langkah 7
### Menambah Data (Create)
Membuat file baru dengan nama ```tambah.php``` seperti berikut.
![SS LANGKAH 7](https://user-images.githubusercontent.com/56240719/120309075-fe5e3280-c2fe-11eb-9c7c-0f63c565f586.png)
![SS LANGKAH 7 (TAMBAHAN)](https://user-images.githubusercontent.com/56240719/120309135-16ce4d00-c2ff-11eb-9142-552816928715.png)

Form dari Tambah Barang.
![SS LANGKAH 7 (OUTPUT)](https://user-images.githubusercontent.com/56240719/120348768-af78c300-c327-11eb-96ac-135305a1cf4a.png)
Hasilnya ketika kita berhasil untuk menambahkan barang baru.
![SS LANGKAH 7 (OUTPUT 2)](https://user-images.githubusercontent.com/56240719/120349538-65441180-c328-11eb-98ba-24c88d91a176.png)

## Langkah 8
### Mengubah Data (Update)
Membuat file baru dengan nama ```ubah.php``` seperti berikut.
![SS LANGKAH 8](https://user-images.githubusercontent.com/56240719/120350855-8c4f1300-c329-11eb-8f99-a6e99a783dca.png)
![SS LANGKAH 8 (2)](https://user-images.githubusercontent.com/56240719/120350887-93762100-c329-11eb-887f-543d394d7f83.png)
![SS LANGKAH 8 (3)](https://user-images.githubusercontent.com/56240719/120350914-9a049880-c329-11eb-9eae-6e52b94fdd5a.png)

Form dari Ubah Barang
![SS LANGKAH 8 (OUTPUT)](https://user-images.githubusercontent.com/56240719/120353249-befa0b00-c32b-11eb-8bbe-c5d4c8033be1.png)

Sebelum Data Barang Laptop Lenovo diubah.
![SS LANGKAH 8 (OUTPUT 2)](https://user-images.githubusercontent.com/56240719/120353291-c5888280-c32b-11eb-890a-e0cb14b0b4b2.png)

Setelah Data Barang Laptop Lenovo diubah.
![SS LANGKAH 8 (OUTPUT 3)](https://user-images.githubusercontent.com/56240719/120352754-4eeb8500-c32b-11eb-8904-32b0d53e297d.png)

## Langkah 9
### Menghapus Data (Delete)
Membuat file baru dengan nama ```hapus.php``` seperti berikut.
![SS LANGKAH 9](https://user-images.githubusercontent.com/56240719/120354624-c968d480-c32c-11eb-8315-48b6ce085d3b.png)

Sebelum Data Barang Laptop Lenovo dihapus.
![SS LANGKAH 9 (OUTPUT)](https://user-images.githubusercontent.com/56240719/120355057-2e242f00-c32d-11eb-8729-294ea16a1dc5.png)

Setelah Data Barang Laptop Lenovo dihapus.
![SS LANGKAH 9 (OUTPUT 2)](https://user-images.githubusercontent.com/56240719/120355640-a559c300-c32d-11eb-8bfe-cb26b6622e65.png)
