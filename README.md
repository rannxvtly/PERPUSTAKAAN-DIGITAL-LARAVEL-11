
# 📚 Sistem Perpustakaan Digital Berbasis Laravel

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-11-red?style=for-the-badge&logo=laravel">
  <img src="https://img.shields.io/badge/PHP-8-blue?style=for-the-badge&logo=php">
  <img src="https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql">
  <img src="https://img.shields.io/badge/Bootstrap-5-purple?style=for-the-badge&logo=bootstrap">
</p>

---

# 📖 Deskripsi Project

Sistem Perpustakaan Digital adalah aplikasi berbasis web yang dibuat menggunakan framework Laravel untuk membantu proses pengelolaan perpustakaan secara digital.

Aplikasi ini menyediakan fitur pengelolaan data buku, anggota, peminjaman, pengembalian buku, dashboard statistik, serta sistem login berdasarkan role pengguna.

---

# ✨ Fitur Utama

## 🔐 Autentikasi
- Login Admin
- Login Anggota
- Logout Sistem
- Middleware Role

---

## 📚 Manajemen Buku
- Tambah Buku
- Edit Buku
- Hapus Buku
- Pencarian Buku
- Manajemen Stok Buku

---

## 👥 Manajemen Anggota
- Tambah Anggota
- Edit Anggota
- Hapus Anggota
- Sinkronisasi Data User Login

---

## 🔄 Peminjaman Buku
- Tambah Data Peminjaman
- Status Peminjaman
- Pengurangan Stok Otomatis

---

## ✅ Pengembalian Buku
- Pengembalian Buku
- Penambahan Stok Otomatis
- Update Status Buku

---

## 📊 Dashboard
- Total Buku
- Total Anggota
- Total Peminjaman
- Pencarian Buku Cepat

---

# 🛠️ Teknologi Yang Digunakan

| Teknologi | Keterangan |
|---|---|
| Laravel 11 | Framework PHP |
| PHP 8+ | Bahasa Pemrograman |
| MySQL | Database |
| Bootstrap 5 | UI Framework |
| Blade Template | Template Engine Laravel |
| Laragon | Local Server |
| Navicat | Database Management |

---

# 📂 Struktur Folder

```bash
app/
 ├── Http/
 │    ├── Controllers/
 │    └── Middleware/
 ├── Models/

resources/
 └── views/
      ├── auth/
      ├── buku/
      ├── anggota/
      ├── peminjaman/
      └── dashboard/

routes/
 └── web.php

database/
 └── migrations/



```

---

## Konfigurasi Database

Buka file `.env`

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=perpustakaan-digital
DB_USERNAME=root
DB_PASSWORD=
```

---

## Jalankan Migration

```bash
php artisan migrate
```

---

## Jalankan Laravel

```bash
php artisan serve
```

---

# 🌐 Akses Aplikasi

```bash
http://127.0.0.1:8000/perpustakaan
```

---

# 👤 Role Pengguna

| Role | Hak Akses |
|---|---|
| Admin | Mengelola seluruh data buku, anggota, dan peminjaman |
| Anggota | Melihat daftar buku |

---

# 🗄️ Struktur Database

Tabel utama pada database:

- users
- bukus
- anggotas
- peminjamen
- sessions
- cache
- jobs

---

# 📸 Output Project

✅ Database `.sql`  
✅ Source Code Laravel  
✅ Screenshot Aplikasi  
✅ Laporan Singkat  
✅ Presentasi / Demo Aplikasi  

---

# 👩‍💻 Developer

Project dibuat untuk memenuhi tugas mata kuliah Pemrograman Web menggunakan Framework Laravel.

---

# 📄 License

Project ini digunakan untuk kebutuhan pembelajaran dan pengembangan aplikasi perpustakaan digital.
