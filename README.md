# 📘 Modul 7: Formulir (Form)

**🎯 Tujuan Pembelajaran**
Setelah pertemuan ini, peserta mampu:

- Memahami fungsi form dalam website
- Menggunakan tag `<form>` sebagai pembungkus input
- Membuat berbagai jenis input data
- Membangun form pendaftaran sederhana

## 1️⃣ Fungsi Form dalam Website

Form digunakan untuk **mengambil data dari pengguna**, seperti:

- Login
- Registrasi
- Pencarian
- Feedback

📌 Data dari form biasanya diproses oleh:

- Backend (PHP, Node.js, Python)
- JavaScript

## 2️⃣ Tag `<form>`

`<form>` adalah elemen utama yang membungkus semua input.

```html
<form>
  <!-- input di sini -->
</form>
```

📌 Atribut penting (akan dipelajari lanjut):

- `action` → tujuan pengiriman data
- `method` → metode pengiriman (`GET`, `POST`)

## 3️⃣ Input (`<input>`)

Tag `<input>` digunakan untuk memasukkan data dari pengguna.

### 🔹 Input Text

```html
<input type="text" placeholder="Nama Lengkap" />
```

### 🔹 Input Password

```html
<input type="password" placeholder="Password" />
```

### 🔹 Input Email

```html
<input type="email" placeholder="Email" />
```

📌 `placeholder` membantu pengguna memahami input.

## 4️⃣ Textarea (`<textarea>`)

Digunakan untuk **teks panjang**.

```html
<textarea rows="4" cols="30" placeholder="Alamat"></textarea>
```

📌 Cocok untuk:

- Alamat
- Deskripsi
- Pesan

## 5️⃣ Button (`<button>`)

Digunakan untuk **mengirim atau menjalankan aksi**.

```html
<button type="submit">Daftar</button>
```

Jenis button:

- `submit` → mengirim form
- `button` → tombol biasa (untuk JavaScript)

## 6️⃣ Contoh Form Sederhana

```html
<form>
  <input type="text" placeholder="Nama" /><br /><br />
  <input type="email" placeholder="Email" /><br /><br />
  <input type="password" placeholder="Password" /><br /><br />
  <textarea placeholder="Alamat"></textarea><br /><br />
  <button type="submit">Kirim</button>
</form>
```

## 🧪 Praktik: Form Pendaftaran Siswa

**🎯 Tujuan Praktik**
Membuat form pendaftaran menggunakan berbagai input dasar.
**Instruksi:**
Buat file `form-pendaftaran.html` dengan ketentuan:

- Menggunakan `<form>`
- Minimal 3 input:
- 1 `<textarea>` untuk alamat
- 1 `<button>` untuk submit

**Contoh Hasil Praktik:**

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <title>Form Pendaftaran</title>
  </head>
  <body>
    <h1>Form Pendaftaran Siswa</h1>

    <form>
      <p>
        <input type="text" placeholder="Nama Lengkap" />
      </p>
      <p>
        <input type="email" placeholder="Email" />
      </p>
      <p>
        <input type="password" placeholder="Password" />
      </p>
      <p>
        <textarea placeholder="Alamat Lengkap"></textarea>
      </p>
      <button type="submit">Daftar</button>
    </form>
  </body>
</html>
```
