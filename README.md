# Praktikum 8 - Pemrograman Web (PHP dan Database MySQL)

### Sigit Ardiansyah - 311910627

### TI.19.A.2

## Menjalankan server MySQL
Pastikan server telah berjalan dan akses http://localhost/phpmyadmin/ untuk membuat database.
![SS1](https://user-images.githubusercontent.com/56240078/120264210-7a3c8880-c2c7-11eb-8929-daadb3295617.jpg)

## Membuat Database
Membuat database dan kemudian membuat tabel sebagai berikut.
![7 1](https://user-images.githubusercontent.com/56240134/120320848-da095280-c30c-11eb-9537-e5b60d030c0c.png)

## Menambah data
Memasukkan data ke dalam tabel.
![7 2](https://user-images.githubusercontent.com/56240134/120320858-db3a7f80-c30c-11eb-9df7-7661ea6f69bf.png)

# Membuat Program CRUD
## Langkah 1
Buat folder lab8_php_database di directory web server (\xampp\htdocs). Kemudian buka http://localhost/lab8_php_database/ untuk mengakses folder/directory tersebut.
![7 3](https://user-images.githubusercontent.com/56240134/120320860-dc6bac80-c30c-11eb-86a0-f344ff8925dc.png)
![7 4](https://user-images.githubusercontent.com/56240134/120320862-dc6bac80-c30c-11eb-9377-6f6ff1d35436.png)

## Langkah 2
Membuat sebuah file <b>koneksi.php</b> untuk koneksi ke database.
![7 5](https://user-images.githubusercontent.com/56240134/120320868-dd044300-c30c-11eb-99fa-a75fcd4b58aa.png)

## Langkah 3
Membuat file <b>index.php</b> untuk menampilkan data. <b>(Read)</b>
![7 6](https://user-images.githubusercontent.com/56240134/120320872-dd9cd980-c30c-11eb-8909-499e1ac60848.png)

### Berikut tampilan data yang sudah diinput ke database
![7 7](https://user-images.githubusercontent.com/56240134/120320873-de357000-c30c-11eb-819d-07c151ffe640.png)

## Langkah 4
Membuat file <b>tambah.php</b> untuk opsi menambahkan data. <b>(Create)</b>
![7 9](https://user-images.githubusercontent.com/56240134/120320876-dece0680-c30c-11eb-9c5b-c25b9a6b4d9a.png)
![7 10](https://user-images.githubusercontent.com/56240134/120320878-df669d00-c30c-11eb-9aff-d8283d8455fc.png)

Hasilnya akan seperti ini.
![7 11](https://user-images.githubusercontent.com/56240134/120320882-dfff3380-c30c-11eb-83e3-57053cdfb5f6.png)
![7 12](https://user-images.githubusercontent.com/56240134/120320886-e097ca00-c30c-11eb-8c5d-a44023232fc9.png)

## Langkah 5
Membuat file <b>ubah.php</b> untuk mengubah data yang ada. <b>(Update)</b>
![7 15](https://user-images.githubusercontent.com/56240134/120320900-e1c8f700-c30c-11eb-86cf-93ce2d0e5b57.png)
![7 16](https://user-images.githubusercontent.com/56240134/120320903-e2618d80-c30c-11eb-826b-e7c1e2a385f4.png)

### Hasilnya sebagai berikut.
![7 13](https://user-images.githubusercontent.com/56240134/120320895-e1306080-c30c-11eb-8c52-221750983e04.png)
### Sebelum data diubah:
![7 12](https://user-images.githubusercontent.com/56240134/120320886-e097ca00-c30c-11eb-8c5d-a44023232fc9.png)
### Sesudah data diubah:
![7 14](https://user-images.githubusercontent.com/56240134/120320898-e1306080-c30c-11eb-8ce6-c85702af5343.png)

## Langkah 6
Membuat file baru <b>hapus.php</b> untuk menghapus data yang ada. <b>(Delete)</b>
![7 17](https://user-images.githubusercontent.com/56240134/120320906-e2fa2400-c30c-11eb-9e4e-1c27813a4136.png)
![7 18](https://user-images.githubusercontent.com/56240134/120320910-e392ba80-c30c-11eb-8edc-8e64deea0c3b.png)
