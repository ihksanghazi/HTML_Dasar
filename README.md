# 📘 Modul 3: Teks & Heading

🎯 **Tujuan Pembelajaran**

Setelah pertemuan ini, peserta mampu:

- Menggunakan heading secara hierarkis dan terstruktur
- Menampilkan teks paragraf dengan rapi
- Memberi penekanan teks sesuai kebutuhan
- Mengatur pemisahan baris teks
- Membuat halaman artikel sederhana dengan struktur yang baik

## 1️⃣ Heading (`<h1>` – `<h6>`)

Heading digunakan untuk `menyusun hierarki konten`, bukan sekadar memperbesar teks.
**Tingkatan Heading:**
| Tag | Fungsi |
| --------------- | ---------------------------------------- |
| `<h1>` | Judul utama halaman (1 saja per halaman) |
| `<h2>` | Subjudul |
| `<h3>` | Sub-subjudul |
| `<h4>` – `<h6>` | Detail lanjutan |

**Contoh:**

```html
<h1>Belajar HTML Dasar</h1>
<h2>Pengenalan</h2>
<h3>Apa itu HTML?</h3>
```

**📌 Best Practice:**

- Gunakan `<h1>` hanya satu kali
- Jangan lompat level (misalnya dari `<h1>` langsung ke `<h4>`)

## 2️⃣ Paragraf (`<p>`)

Paragraf digunakan untuk **teks utama** atau penjelasan konten.

```html
<p>
  HTML adalah bahasa markup yang digunakan untuk membangun struktur halaman web.
</p>
```

📌 Browser otomatis memberi jarak antar paragraf.

## 3️⃣ Penekanan Teks (Bold, Italic, Underline)

### 🔹 Bold (`<b>`)

Digunakan untuk menebalkan teks, tanpa makna khusus.

```html
<b>Teks Tebal</b>
```

### 🔹 Italic (`<i>`)

Digunakan untuk:

- Istilah asing
- Penekanan ringan

```html
<i>HyperText Markup Language</i>
```

### 🔹 Underline (`<u>`)

Digunakan untuk:

- Menandai teks tertentu
- Catatan atau penekanan visual

```html
<u>Teks Garis Bawah</u>
```

## 4️⃣ Line Break (`<br>`)

Digunakan untuk **pindah baris tanpa membuat paragraf baru.**

```html
<p>
  Alamat:<br />
  Jl. Merdeka No. 10<br />
  Jakarta
</p>
```

📌 Cocok untuk alamat, puisi, atau teks pendek bertingkat.

## 5️⃣ Contoh Kombinasi Teks & Heading

```html
<h1>Teknologi Web</h1>

<p>Teknologi web berkembang sangat pesat.</p>

<h2>HTML</h2>
<p>
  <b>HTML</b> adalah dasar dari semua website modern. Bahasa ini digunakan untuk
  <i>struktur konten</i>.
</p>
```

## 🧪 Praktik: Membuat Halaman Artikel Pendek

**🎯 Tujuan Praktik**
Menerapkan teks dan heading secara terstruktur seperti artikel online.

**Instruksi:**
Buat file `artikel.html` dengan ketentuan:

- 1 `<h1>` sebagai judul artikel
- Minimal 2 `<h2>` sebagai subjudul
- Paragraf penjelasan di setiap bagian
- Gunakan `<b>`, `<i>`, atau `<u>` minimal 2 kali
- Gunakan `<br>` jika diperlukan

Contoh Hasil Praktik:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <title>Belajar Web Development</title>
  </head>
  <body>
    <h1>Belajar Web Development</h1>

    <h2>Apa itu Web Development?</h2>
    <p>
      Web development adalah proses pembuatan website. Bidang ini sangat
      <b>dibutuhkan</b> di era digital.
    </p>

    <h2>Teknologi yang Digunakan</h2>
    <p>Teknologi utama dalam web adalah <i>HTML</i>, CSS, dan JavaScript.</p>

    <p>
      Ditulis oleh:<br />
      <u>Ihksan</u>
    </p>
  </body>
</html>
```
