# bookapp
Maysce Christi - 185150701111009


# PENJELASAN 

Pada Praktikum ini kita membuat dan mempersiapkan projek Lumen baru, mengimplementasikan Controller, Migration, Seeder, Model dan kemudian menjalankan Aplikasi Lumen tersebut.
Konsep dasar yang digunakan untuk praktikum kali ini yaitu menggunakan MVC (Model, View, Controller)

# Struktur Laravel
- app/Http
  
  Direktori ini merupakan direktori yang dibuat secara khusus untuk menyimpan seluruh file-file yang berkaitan dengan proses request dan response Http. Dikretori ini memiliki tiga   buah sub direktori yang diantaranya adalah "Controllers", "Middleware" dan "Requests". 
  
- Seeder
  
  Direktori ini berisikan file-file dabase seeds yang digenerate oleh laravel pada saat kita menjalankan perintah php artisan make:seeder. fitur seeding di laravel sendiri sangat   berguna apabila kita ingin melakukan inisialisasi data (data awalan) pada table yang kita buat.
  
- Migration
  
  Direktori ini berisikan file-file migrations yang digenerate oleh laravel pada saat kita menjalankan perintah php artisan make:migration. fitur migration sendiri sangat berguna   untuk melakukan perubahan pada database baik itu penambahan tabel, penambahan kolom, menghapus kolom, menghapus tabel serta melakukan roll-back setiap perubahan database yang     kita buat.
  
- Model
  
  Direktori ini merupakan sebuah penghubung antara controller dengan database yang sudah kita buat.


# CHALLANGE

Pada challange kali ini kita diminta untuk membuat CRUD (Create, Read, Update, dan Delete) pada project bookapp di Modul Praktikum 5.
Fitur CRUD sangat berguna bagi pengguna aplikasi yang dibuat. Dengan adanya CRUD pengguna tidak perlu repot misalkan ingin menambah data atau menghapus data.

Dengan adanya fitur CRUD semuanya menjadi mudah, operasi CRUD adalah manipulasi data dasar untuk database. Berikut penjelasannya :

-Create

  Create diartikan membuat atau menambahkan, membuat atau menambahkan data menggunakan aplikasi yang sudah dibuat, ketika kita menambahkan data diaplikasi nantinya akan otomatis akan masuk kedalam database yang sudah dibuat.
  
-Read

  Read diartikan menampilkan atau membaca, menampilkan atau membaca data kita tidak perlu repot untuk menampilkan data cukup dilihat menggunakan aplikasi data mana yang ingin ditampilkan maka akan tertampil.

-Update

  Update diartikan mengubah, kita tidak perlu repot ketika ingin mengubah data, cukup menggunakan aplikasi maka akan terubah dan database otomatis akan terubah.

-Delete

  Delete diartikan menghapus, fitur ini digunakan untuk menghapus data yang tidak diperlukan. Kita tidak perlu repot ketika ingin menghapus data, tidak perlu menghapus data lewat database.
