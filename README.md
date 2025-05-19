![Screenshot 2025-05-19 121213](https://github.com/user-attachments/assets/4806cfe4-8c63-47a7-93f0-25a0d6438602)

#Penjelasan Aplikasi Manajemen Barang
1. Tampilan
Tampilan UI memiliki elemen-elemen berikut:

Label Judul:

Teks besar “Manajemen Barang” di bagian atas.

Input Form:

Nama Barang: TextBox untuk mengisi nama barang.

Stock Barang: NumericUpDown untuk mengisi jumlah stok barang.

Harga Barang: TextBox untuk harga barang.

Tombol Aksi:

Tambah: Menambahkan barang baru ke database.

Edit: Mengubah data barang yang dipilih.

Hapus: Menghapus barang yang dipilih.

Tabel Data:

DataGridView (berwarna abu-abu) untuk menampilkan daftar barang dari database.

Pencarian:

TextBox untuk input kata kunci pencarian.

Button Cari: Untuk mencari barang berdasarkan nama.

2. Fitur-Fitur Utama
Fitur	Deskripsi
Tambah Data	Menyimpan data baru ke dalam database SQLite.
Tampil Data	Menampilkan seluruh data barang dalam DataGridView.
Cari Data	Mencari barang berdasarkan nama dengan input kata kunci.
Edit Data	(Akan ditambahkan) Mengubah data barang yang dipilih dari DataGridView.
Hapus Data	(Akan ditambahkan) Menghapus data barang berdasarkan pilihan pengguna.
Penyimpanan Lokal	Data disimpan dalam file barang.db yang dibuat otomatis jika belum ada.

3. Teknologi yang Digunakan
Bahasa Pemrograman: C#

Framework: .NET Framework (Windows Forms)

Database: SQLite (local file barang.db)

Komponen UI: TextBox, NumericUpDown, Button, DataGridView, dll.

