# 📘 Modul 6: Tabel

**🎯 Tujuan Pembelajaran**
Setelah pertemuan ini, peserta mampu:

- Memahami fungsi tabel dalam HTML
- Menggunakan tag `<table>`, `<tr>`, `<th>`, dan `<td>` dengan benar
- Menampilkan data terstruktur dalam bentuk tabel
- Membuat tabel jadwal pelajaran sederhana

## 1️⃣ Fungsi Tabel dalam HTML

Tabel digunakan untuk **menampilkan data terstruktur** (tabular data), seperti:

- Jadwal
- Daftar nilai
- Laporan data
- Rekap informasi

**📌 Catatan penting:**
Tabel **bukan** untuk layout halaman (itu tugas CSS Grid/Flex).

## 2️⃣ Struktur Dasar Tabel HTML

**Tag Utama:**
| Tag | Fungsi |
| --------- | ----------------- |
| `<table>` | Pembungkus tabel |
| `<tr>` | Table row (baris) |
| `<th>` | Header kolom |
| `<td>` | Data tabel |

**Contoh Struktur Dasar:**

```html
<table>
  <tr>
    <th>Hari</th>
    <th>Mata Pelajaran</th>
  </tr>
  <tr>
    <td>Senin</td>
    <td>Matematika</td>
  </tr>
</table>
```

## 3️⃣ Border Tabel

Untuk menampilkan garis tabel secara sederhana, gunakan atribut `border`.

```html
<table border="1"></table>
```

📌 Atribut ini digunakan **untuk pembelajaran dasar**.
Di praktik profesional, border biasanya diatur dengan **CSS**.

## 4️⃣ Contoh Tabel Lengkap

```html
<table border="1">
  <tr>
    <th>Hari</th>
    <th>Jam</th>
    <th>Mata Pelajaran</th>
  </tr>
  <tr>
    <td>Senin</td>
    <td>08.00 - 09.30</td>
    <td>Matematika</td>
  </tr>
  <tr>
    <td>Selasa</td>
    <td>10.00 - 11.30</td>
    <td>Bahasa Inggris</td>
  </tr>
</table>
```

## 5️⃣ Best Practice Dasar Tabel

- Gunakan `<th>` untuk judul kolom
- Jangan gunakan tabel untuk layout
- Pastikan data mudah dibaca
- Susun kolom secara konsisten

## 🧪 Praktik: Membuat Tabel Jadwal Pelajaran

**🎯 Tujuan Praktik**
Menerapkan struktur tabel untuk data jadwal.

**Instruksi:**
Buat file jadwal.html dengan ketentuan:

- Gunakan <table border="1">
- Minimal 5 baris data
- Kolom:
  - Hari
  - Jam
  - Mata Pelajaran

## Contoh Hasil Praktik:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <title>Jadwal Pelajaran</title>
  </head>
  <body>
    <h1>Jadwal Pelajaran</h1>

    <table border="1">
      <tr>
        <th>Hari</th>
        <th>Jam</th>
        <th>Mata Pelajaran</th>
      </tr>
      <tr>
        <td>Senin</td>
        <td>08.00 - 09.30</td>
        <td>Matematika</td>
      </tr>
      <tr>
        <td>Selasa</td>
        <td>09.30 - 11.00</td>
        <td>Fisika</td>
      </tr>
      <tr>
        <td>Rabu</td>
        <td>08.00 - 09.30</td>
        <td>Pemrograman Web</td>
      </tr>
    </table>
  </body>
</html>
```
