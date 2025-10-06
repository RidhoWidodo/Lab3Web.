# Lab3Web.
*Nama : Muhammad Ridho Hafiedz*

*Nim :312410195*

*Kelas : TI.24 A2*

# Tahap 1: Persiapan Struktur Dasar HTML
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/1ea578a5-d7c3-4c1c-bd32-65f218760e61" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/2d0408cd-6c0d-4229-84ef-8868bfe28c50" />

**Penjelasannya**
 - `<!DOCTYPE html>`: Deklarasi tipe dokumen HTML5.
 - `<html lang="id">`: Elemen root dengan atribut bahasa Indonesi.
 - `<head>`: Bagian kepala dokumen berisi metadata.
 - `<meta charset="UTF-8">`: Encoding karakter untuk mendukung huruf khusus.
 - `<meta name="viewport">`: Pengaturan responsive design untuk mobile devices.
 - `<title>`: Judul yang muncul di tab browser.
 - `<body>`: Bagian konten yang ditampilkan di browser.
 - `<header>` dan `<h1>`: Header dan judul utama halaman.


# Tahap 2: Membuat Kerangka Form
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/416833bd-16f0-417c-8e5d-5465881ec5a7" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/18c794b8-dbdb-42b2-a763-4ee5557448f0" />

**Penjelasannya**
 - `<form action="proses.php" method="post">:`
    - `action`: Menentukan file yang akan memproses data form (proses.php).
    - `method="post"`: Metode pengiriman data yang lebih aman (tidak terlihat di URL).
 - `<fieldset>`: Mengelompokkan elemen-elemen form yang terkait.
 - `<legend>`: Memberi judul untuk kelompok fieldset.
 

# Tahap 3: Menambahkan Input Dasar
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/b04f1bf9-f729-4df5-a939-281bb9310e3d" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/e4f84e95-542a-4b14-9b2b-eb0b9db640e3" />

**Penjelasannya**
Input Text:
 - `<label for="nama">`: Label yang terhubung dengan input melalui atribut `for`.
 - `<input type="text">`: Input satu baris untuk teks.
 - `required`: Atribut yang membuat field wajib diisi.

Textarea:
 - `<textarea>`: Input multi-baris untuk teks panjang.
 - `cols="30"`: Lebar textarea dalam karakter.
 - `rows="3"`: Tinggi textarea dalam baris.

Radio Button:
 - `<input type="radio">`: Tombol pilihan tunggal.
 - `name="kelamin"`: Nama yang sama membuat radio button dalam grup yang sama.
 - `value="l"`: Nilai yang akan dikirim ketika dipilih.
   

# Tahap 4: Membuat Dropdown Menu (Select)
