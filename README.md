# Lab8Web.

## Langkah-langkah Praktikum
## Persiapan
Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah
database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan
melalui XAMPP.

## Menjalankan MySQL Server
Untuk menjalankan MySQL Server dari menu XAMPP Contol. 

<img width="530" alt="Screenshot 2023-11-21 075246" src="https://github.com/Agussetiaa/Lab8Web./assets/115542822/0a059588-c856-46cf-bcdd-6d74cf972a64">

## Membuat Database: Studi Kasus Data Barang

<img width="724" alt="image" src="https://github.com/Agussetiaa/Lab8Web./assets/115542822/2fcfa5aa-29f2-4fb5-b9e4-a9ae5619120f">

## Membuat Database
```
CREATE DATABASE latihan1;
```
### Membuat Tabel
```
CREATE TABLE data_barang (
id_barang int(10) auto_increment Primary Key,
kategori varchar(30),
nama varchar(30),
gambar varchar(100),
harga_beli decimal(10,0),
harga_jual decimal(10,0),
stok int(4)
);
```
### Menambahkan Data
```
INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual, stok)
VALUES ('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000, 2400000, 5),
('Elektronik', 'HP Xiaomi Android', 'hp_xiaomi.jpg', 1000000, 1400000, 5),
('Elektronik', 'HP OPPO Android', 'hp_oppo.jpg', 1800000, 2300000, 5);
```

<img width="858" alt="image" src="https://github.com/Agussetiaa/Lab8Web./assets/115542822/509c31bc-3d05-4fda-80dd-772772b73010">


