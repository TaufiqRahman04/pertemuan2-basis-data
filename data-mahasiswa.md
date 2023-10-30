### Membuat Database menggunakan PostgreSQL

1. Buka SQL Shell (psql)

![image](https://github.com/TaufiqRahman04/pertemuan2-basis-data/assets/148308595/6732ef41-8aef-4850-abed-f0bb70bea84c)

2. klik enter sampai diminta untuk menginput password

![image](https://github.com/TaufiqRahman04/pertemuan2-basis-data/assets/148308595/838f4c15-7f86-48a9-adfb-449cac4cb5b7)

3. Input password yang sudah di masukkan pada saat proses penginstallan
4. Ketik command dibawah sesuai perintah yang diinginkan.


* `CREATE DATABASE nama_database;`
> Untuk membuat sebuah database baru.


* `\c nama_database`
> Untuk menyambungkan sebuah database untuk di edit


* `CREATE TABLE nama_tabel (kolom1 tipedata,kolom2 tipedata,...);`
> Untuk Membuat sebuah tabel baru di dalam database beserta kolomnya.


* `ALTER TABLE nama_tabel ADD nama_kolom datatype;`
> Untuk menambahkan kolom baru di sebuah tabel


* `INSERT INTO nama_tabel (kolom1,kolom2,...) VALUES (values1,values2,...);`
> Untuk menginputkan sebuah data,dengan berdasarkan kolom yang diinginkan
> Jika ingin menginputkan sebuah data kepada semua kolom,cukup dengan

`INSERT INTO nama_tabel VALUES (values1,values2,...);`


* `SELECT * FROM nama_tabel;`
> Untuk menampilkan sebuah tabel
> Untuk menampilkan sebuah tabel dengan diurutkan tambahkan :

`ORDER BY nama_kolom ASC/DESC;`

> ASC untuk secara ascending (Mulai dari terkecil)

> DESC untuk secara descending (Mulai dari terbesar)


* `\dt`
> Untuk melihat list tabel yang ada di dalam database


* `\d nama_Tabel`
> Untuk melihat informasi dari setiap kolom


### Hasil Tabel yang sudah dibuat
* SQL Shell (psql)
  
![image](https://github.com/TaufiqRahman04/pertemuan2-basis-data/assets/148308595/0815de38-17b3-4742-9bbf-ebeacc7657e7)


* Dbeaver
  
![image](https://github.com/TaufiqRahman04/pertemuan2-basis-data/assets/148308595/672a8225-7fee-406b-b35c-220007267b12)

