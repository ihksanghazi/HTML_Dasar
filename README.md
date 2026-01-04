# 📘 Modul 4: List & Link

**🎯 Tujuan Pembelajaran**

Setelah pertemuan ini, peserta mampu:

- Membuat daftar terurut dan tidak terurut
- Memahami struktur list yang benar dalam HTML
- Membuat hyperlink untuk navigasi halaman
- Menggabungkan list dan link menjadi menu navigasi sederhana

## 1️⃣ Ordered List (`<ol>`)

Ordered List digunakan untuk **daftar yang memiliki urutan atau langkah.**

```html
<ol>
  <li>Install text editor</li>
  <li>Buat file HTML</li>
  <li>Buka di browser</li>
</ol>
```

📌 Contoh penggunaan:

- Langkah tutorial
- Prosedur kerja
- Ranking

## 2️⃣ Unordered List (`<ul>`)

Unordered List digunakan untuk **daftar tanpa urutan khusus.**

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

📌 Contoh penggunaan:

- Menu navigasi
- Daftar fitur
- Kategori

## 3️⃣ List Item (`<li>`)

`<li>` digunakan untuk **setiap item di dalam list** dan **harus berada di dalam** `<ol>` **atau** `<ul>`.
❌ Salah:

```html
<li>Item</li>
```

✅ Benar:

```html
<ul>
  <li>Item</li>
</ul>
```

## 4️⃣ Link (`<a href="">`)

Link digunakan untuk **berpindah halaman atau membuka sumber lain.**
**Struktur Dasar:**

```html
<a href="https://example.com">Kunjungi Website</a>
```

**Jenis Link:**

- **Internal link** (antar halaman)
  ```html
  <a href="about.html">Tentang</a>
  ```
- **External link** (ke website lain)

  ```html
  <a href="https://google.com">Google</a>
  ```

- **Link membuka tab baru**

  ```html
  <a href="https://google.com" target="_blank">Google</a>
  ```

📌 Atribut penting:

- `href` → tujuan link
- `target="\_blank"` → buka tab baru

## 5️⃣ Menggabungkan List & Link (Menu Navigasi)

List sering digunakan sebagai **menu navigasi website.**

```html
<ul>
  <li><a href="index.html">Home</a></li>
  <li><a href="about.html">About</a></li>
  <li><a href="contact.html">Contact</a></li>
</ul>
```

📌 Struktur ini adalah **fondasi navbar** sebelum diberi CSS.

## 🧪 Praktik: Membuat Menu Website Sederhana

**🎯 Tujuan Praktik**
Membuat navigasi website menggunakan list dan link.
**Instruksi:**

1. Buat 3 file HTML:
   - `index.html`
   - `about.html`
   - `contact.html`
2. Di setiap halaman, buat menu navigasi yang sama
3. Gunakan `<ul>`, `<li>`, dan `<a>`

**Contoh** `index.html`:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <title>Home</title>
  </head>
  <body>
    <h1>Website Sederhana</h1>

    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>

    <p>Selamat datang di halaman utama.</p>
  </body>
</html>
```
