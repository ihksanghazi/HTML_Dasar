# 📘 Modul 2: Struktur Dasar HTML

**🎯 Tujuan Pembelajaran**
Setelah pertemuan ini, peserta mampu:

- Memahami kerangka dasar dokumen HTML secara menyeluruh
- Menjelaskan fungsi tag `<html>`, `<head>`, dan `<body>`
- Menggunakan `<title>` dan `<meta>` secara tepat
- Menulis komentar HTML dengan benar
- Membangun halaman biodata sederhana dengan struktur HTML rapi

---

## 1️⃣ Kerangka Dasar Dokumen HTML

HTML memiliki struktur standar yang wajib ada agar browser dapat membaca halaman dengan benar.

Struktur umum:

```html
<!DOCTYPE html>
<html>
  <head> </head>
  <body></body>
</html>
```

📌 Struktur ini menjadi fondasi untuk:

- SEO
- Aksesibilitas
- Pengembangan web modern (framework, library)

---

## 2️⃣ Tag `<html>`, `<head>`, dan `<body>`

### 🔹 `<html>`

- Elemen utama pembungkus seluruh isi dokumen
- Biasanya ditambahkan atribut lang

```html
<html lang="id"></html>
```

📌 Berguna untuk:

- Aksesibilitas
- SEO
- Screen reader

### 🔹 `<head>`

Berisi `informasi metadata`, bukan konten visual.

Digunakan untuk:

- Judul halaman
- Informasi karakter
- SEO
- Link CSS & script

### 🔹 `<body>`

Berisi **konten utama** yang ditampilkan ke pengguna.
Contoh:

- Teks
- Gambar
- Tabel
- Form

---

## 3️⃣ Tag `<title>` dan `<meta>`

### 🔹 `<title>`

Menentukan:

- Judul tab browser
- Nama halaman di hasil pencarian

```html
<title>Biodata Mahasiswa</title>
```

### 🔹 `<meta>`

Digunakan untuk memberikan informasi tambahan tentang halaman.
Contoh penting:

```html
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="description" content="Halaman biodata pribadi" />
```

📌 Fungsi utama:

- Encoding karakter
- Responsive design
- SEO dasar

---

## 4️⃣ Komentar HTML

Komentar digunakan untuk:

- Memberi catatan pada kode
- Membantu kolaborasi tim
- Menonaktifkan sementara kode

Sintaks:

```html
<!-- Ini komentar -->
```

📌 Komentar **tidak ditampilkan** di browser.

---

## 5️⃣ Contoh Struktur HTML Lengkap

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Biodata Saya</title>
  </head>
  <body>
    <!-- Judul Halaman -->
    <h1>Biodata</h1>

    <p>Halo, nama saya Andi.</p>
  </body>
</html>
```

---

## 🧪 Praktik: Membuat Halaman Biodata Sederhana

🎯 **Tujuan Praktik**

Menerapkan struktur dasar HTML dengan benar dan rapi.
**Instruksi:**

Buat file bernama biodata.html yang berisi:

- Struktur HTML lengkap
- Judul halaman menggunakan <title>
- Minimal 1 komentar HTML
- Konten biodata:
  - Nama
  - Umur
  - Hobi
  - Deskripsi singkat

Contoh Hasil Praktik:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <title>Biodata Diri</title>
  </head>
  <body>
    <!-- Informasi pribadi -->
    <h1>Biodata</h1>

    <p>Nama: Raffly</p>
    <p>Umur: 22 Tahun</p>
    <p>Hobi: Coding</p>
  </body>
</html>
```
