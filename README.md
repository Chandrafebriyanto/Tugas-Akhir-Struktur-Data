# **Tugas Akhir - Implementasi Struktur Data dalam C++**

Repositori ini berisi kode sumber untuk proyek Tugas Akhir mata kuliah Struktur Data. Proyek ini adalah sebuah aplikasi konsol sederhana yang mengimplementasikan konsep-konsep dasar struktur data untuk mengelola sebuah data.

<!-- Ganti baris di bawah ini dengan tangkapan layar program Anda -->
[Tangkapan Layar Aplikasi Anda]

## **Deskripsi Proyek** 📖

Program ini merupakan aplikasi *command-line interface* (CLI) yang dibangun menggunakan bahasa C++. Tujuannya adalah untuk mendemonstrasikan penerapan praktis dari struktur data fundamental seperti `struct` dan `array` dalam sebuah kasus penggunaan sederhana, yaitu manajemen data. Pengguna dapat melakukan operasi dasar **CRUD** (*Create, Read, Update, Delete*) pada data yang disimpan sementara selama program berjalan.

---
## **Fitur Utama** ✨

* **Tambah Data**: Menambahkan entitas data baru ke dalam sistem.
* **Tampilkan Data**: Menampilkan seluruh data yang telah tersimpan dalam format tabel yang rapi.
* **Ubah Data**: Mengedit atau memperbarui informasi dari data yang sudah ada.
* **Hapus Data**: Menghapus data dari daftar berdasarkan kriteria tertentu.
* **Pencarian Data**: Mencari data spesifik dalam daftar.
* **Pengurutan Data**: Mengurutkan data berdasarkan kriteria tertentu (misalnya, nama atau nomor induk).

---
## **Struktur Data & Algoritma** 🏗️

* **`struct`**: Digunakan untuk merepresentasikan model data (misalnya, data mahasiswa) secara terstruktur, menggabungkan beberapa tipe data menjadi satu unit.
* **`array`**: Digunakan sebagai wadah utama untuk menyimpan kumpulan `struct` data tersebut.
* **Algoritma Pencarian Linear**: Diimplementasikan untuk fitur pencarian data.
* **Algoritma Pengurutan (contoh: Bubble Sort)**: Diimplementasikan untuk mengurutkan data yang ditampilkan.

---
## **Teknologi yang Digunakan** 💻

* **Bahasa Pemrograman**: C++
* **Compiler**: g++ (direkomendasikan menggunakan MinGW-w64 untuk Windows)
* **Lingkungan Pengembangan**: Visual Studio Code, Dev-C++, atau IDE C++ lainnya.

---
## **Instalasi dan Cara Menjalankan** 🚀

Pastikan Anda telah menginstal C++ compiler (seperti **g++** dari MinGW) di sistem Anda.

1.  **Clone Repositori**
    Buka terminal atau Git Bash, lalu jalankan perintah berikut:
    ```bash
    git clone [https://github.com/Chandrafebriyanto/Tugas-Akhir-Struktur-Data.git](https://github.com/Chandrafebriyanto/Tugas-Akhir-Struktur-Data.git)
    ```

2.  **Masuk ke Direktori Proyek**
    ```bash
    cd Tugas-Akhir-Struktur-Data
    ```

3.  **Kompilasi Kode**
    Gunakan compiler g++ untuk mengompilasi semua file `.cpp` menjadi sebuah file *executable*. Beri nama `program.exe` (untuk Windows) atau `program` (untuk Linux/macOS).
    ```bash
    g++ main.cpp -o program
    ```
    *Catatan: Jika Anda memiliki beberapa file sumber, tambahkan semuanya dalam perintah kompilasi (`g++ main.cpp fungsi.cpp -o program`).*

4.  **Jalankan Program**
    Setelah kompilasi berhasil, jalankan program dari terminal:
    ```bash
    ./program
    ```
    Atau di Command Prompt Windows:
    ```bash
    program.exe
    ```

---
## **Kontributor** 👥

* **Nama**: Chandra Febriyanto
* **GitHub**: [@Chandrafebriyanto](https://github.com/Chandrafebriyanto)
