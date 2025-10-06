# Lab3Web.
*Nama : Muhammad Ridho Hafiedz*

*Nim :312410195*

*Kelas : TI.24 A2*

# Tahap 1: Persiapan Struktur Dasar HTML
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/1ea578a5-d7c3-4c1c-bd32-65f218760e61" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/2d0408cd-6c0d-4229-84ef-8868bfe28c50" />

**Penjelasannya:**
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

**Penjelasannya:**
 - `<form action="proses.php" method="post">:`
    - `action`: Menentukan file yang akan memproses data form (proses.php).
    - `method="post"`: Metode pengiriman data yang lebih aman (tidak terlihat di URL).
 - `<fieldset>`: Mengelompokkan elemen-elemen form yang terkait.
 - `<legend>`: Memberi judul untuk kelompok fieldset.
 
# Tahap 3: Menambahkan Input Dasar
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/b04f1bf9-f729-4df5-a939-281bb9310e3d" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/e4f84e95-542a-4b14-9b2b-eb0b9db640e3" />

**Penjelasannya:**
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
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4fe21378-18ba-46cd-8d3b-39176cb43d14" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/65fc3d48-6eda-4e56-a8b2-5cae77bf95f7" />

**Penjelasannya:**
Dropdown Menu:
 - `<select>`: Membuat dropdown menu.
 - `name="negara"`: Nama variabel yang akan dikirim ke server.
 - `<option>`: Opsi-opsi yang dapat dipilih.
 - `value=""`: Nilai yang dikosongkan untuk opsi placeholder.
 - `value="id"`: Nilai yang akan dikirim ketika opsi dipilih

# Tahap 5: Membuat Listbox dengan Multiple Selection
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/ab5720f5-6e83-437c-ae08-a34de983e503" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/999b6c84-c0f1-4014-a45d-e651d9832064" />

**Penjelasannya:**
Listbox Multiple:
 - `multiple`: Atribut yang memungkinkan pemilihan multiple opsi.
 - `size="4"`: Menampilkan 4 opsi sekaligus (membuat listbox).
 - `name="hobi[]"`: Notasi array untuk menerima multiple values di PHP.
 - `<small>`: Teks petunjuk untuk pengguna
   
Cara Penggunaan:
 - Windows/Linux: Tahan `Ctrl` + Klik opsi.
 - Mac: Tahan `Command` + Klik opsi

# Tahap 6: Menambahkan Tombol Submit
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/da4a678f-0777-453b-b050-7b62912e7833" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/947df6a1-637c-415f-acde-79941a5f26db" />

**Penjelasannya:**
 - `<input type="submit">`: Tombol untuk mengirim form
 - `value="Kirim Data"`: Teks yang ditampilkan pada tombol

# Tahap 7: Menambahkan CSS untuk Styling
