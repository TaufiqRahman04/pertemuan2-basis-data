### Membuat Database menggunakan PostgreSQL

1. Buka SQL Shell (psql)

![image](https://github.com/TaufiqRahman04/pertemuan2-basis-data/assets/148308595/6732ef41-8aef-4850-abed-f0bb70bea84c)

3. klik enter sampai diminta untuk menginput password

![image](https://github.com/TaufiqRahman04/pertemuan2-basis-data/assets/148308595/838f4c15-7f86-48a9-adfb-449cac4cb5b7)

4. Ketik command dibawah sesuai perintah yang diinginkan.

`CREATE DATABASE *nama_database*;`
> Untuk membuat sebuah database baru.

`\c *nama_database*`
> Untuk menyambungkan sebuah database untuk di edit

`CREATE TABLE *nama_tabel*;`
> Untuk Membuat sebuah tabel baru di dalam database

`ALTER TABLE table_name ADD column_name datatype;`
> Untuk menambahkan kolom baru di sebuah tabel

`INSERT INTO *nama_tabel* (kolom1,kolom2,...) VALUES (values1,values2,...);`
> Untuk menginputkan sebuah data,dengan berdasarkan kolom yang diinginkan
> Jika ingin menginputkan sebuah data kepada semua kolom,cukup dengan

`INSERT INTO *nama_tabel* VALUES (values1,values2,...);`

`SELECT * FROM *nama_tabel*;`
> Untuk menampilkan sebuah tabel
> Untuk menampilkan sebuah tabel dengan diurutkan tambahkan :
`ORDER BY *nama_kolom* ASC/DESC;`
> ASC untuk secara ascending (Mulai dari terkecil)
> DESC untuk secara descending (Mulai dari terbesar)

`\dt`
> Untuk melihat list tabel yang ada di dalam database

`\d *nama_Tabel*`
> Untuk melihat informasi dari setiap kolom

### Hasil Tabel yang sudah dibuat
* SQL Shell (psql)
  
![image](https://github.com/TaufiqRahman04/pertemuan2-basis-data/assets/148308595/7ea68667-c6e8-460f-94a1-948e2e1a2d46)

* Dbeaver
  
![image](https://github.com/TaufiqRahman04/pertemuan2-basis-data/assets/148308595/39772cd9-5de1-4e5d-bc9d-7e5fa3c1a660)
