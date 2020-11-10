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
