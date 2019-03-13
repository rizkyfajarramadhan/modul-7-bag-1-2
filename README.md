# modul-7-bag-1-2
SOAL
1. Berikan contoh kode keneksi untuk ke database pd php?

2. Bagaimana cara anda membuat database pada phpMySQl!

3. Berikan code query untuk menampilkan sebuah data yang ada pada ke database?

4. Berikan code query untuk mengupdate sebuah data yang ada pada ke database?

5. Berikan code query untuk menghapus sebuah data yang ada pada ke database?

JAWABAN
1.[$connect = mysqli_connect($host,$uname,$pass,$db);]

2.-Install aplikasi XAMPP
  -Buka XAMPP Control Panel
  -Jalankan Apache dan MySQL
  -Lalu buka browser(bisa di browser mana saja) dan ketik http://localhost/phpmyadmin
  -Setelah ada tampilan menu database, masukkan nama database yang diinginkan lalu klik tombol Create di pojok kanan bawah
  -Setelah itu akan muncul halaman untuk membuat tabel. Masukkan nama tabel dan jumlah kolom yang diinginkan, lalu klik tombol GO
  -Setelah itu masuk ke halaman untuk membuat kolom database. Masukkan nama kolom kemudian tentukan type data dan panjang karakter dan tentukan primary key nya juga
  -Jika sudah klik tombol Save, database yang kita buat akan tersimpan.
  
 3.[$query = "SELECT * FROM (nama_tabel)";]
 
 4.[$query = "UPDATE nama_tabel SET nama_kolom = 'data_baru' WHERE nama_primary_key = primary_key";]
 
 5.[$query = "DELETE FROM nama_tabel WHERE nama_primary_key = primary_key";]
 
 HASIL
 
 ![alt text](https://github.com/rizkyfajarramadhan/modul-7-bag-1-2/blob/master/1.png)
 ![alt text](https://github.com/rizkyfajarramadhan/modul-7-bag-1-2/blob/master/2.png)
 ![alt text](https://github.com/rizkyfajarramadhan/modul-7-bag-1-2/blob/master/3.png)
 ![alt text](https://github.com/rizkyfajarramadhan/modul-7-bag-1-2/blob/master/4.png)
 ![alt text](https://github.com/rizkyfajarramadhan/modul-7-bag-1-2/blob/master/5.png)
 ![alt text](https://github.com/rizkyfajarramadhan/modul-7-bag-1-2/blob/master/6.png)
 ![alt text](https://github.com/rizkyfajarramadhan/modul-7-bag-1-2/blob/master/7.png)
 ![alt text](https://github.com/rizkyfajarramadhan/modul-7-bag-1-2/blob/master/8.png)
 ![alt text](https://github.com/rizkyfajarramadhan/modul-7-bag-1-2/blob/master/9.png)
