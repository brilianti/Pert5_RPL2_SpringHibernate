# Data Mahasiswa menggunakan Konsep Framework Spring dan Hibernate

Proyek ini membuat aplikasi **CRUD sederhana** berbasis **Spring Boot**, **JPA**, dan **MySQL** dengan menu console.

## Struktur Proyek
- **Model**
  - `ModelMahasiswa` : Entity JPA yang merepresentasikan tabel mahasiswa.
- **Repository**
  - `MahasiswaRepository` : Akses data menggunakan JpaRepository (CRUD otomatis).
- **Controller**
  - `MahasiswaController` : Menu console: tambah data, tampilkan semua data, cek koneksi.
- **Main App**
  - `Pertemuan5SpringBootApplication` : Kelas utama yang menjalankan aplikasi dan memanggil menu.

## Fitur
- Menampilkan seluruh data mahasiswa  
- Menambah data mahasiswa baru  
- Mengecek koneksi ke database  
- CRUD dilakukan otomatis melalui JpaRepository

## Cara Menjalankan
1. Start **Apache & MySQL** melalui XAMPP.  
2. Buat database `pert5_50422341`.  
3. Build project melalui **Maven** (pom.xml sudah berisi Spring Boot + MySQL driver).  
4. Jalankan `Pertemuan5SpringBootApplication.java`.  
5. Gunakan menu console untuk menjalankan fitur (tambah data, cek koneksi, tampilkan data).

