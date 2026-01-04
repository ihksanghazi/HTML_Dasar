# 📘 Pertemuan 8: Semantic HTML

**🎯 Tujuan Pembelajaran**
Setelah pertemuan ini, peserta mampu:

- Memahami konsep Semantic HTML
- Menggunakan elemen semantic untuk membangun struktur website modern
- Menjelaskan manfaat semantic HTML terhadap SEO dan aksesibilitas
- Membuat layout website sederhana dengan struktur semantic

## 1️⃣ Apa Itu Semantic HTML?

**Semantic HTML** adalah penggunaan tag HTML yang **memiliki makna jelas** sesuai fungsinya.
📌 Contoh:

- `<header>` → bagian kepala halaman
- `<footer>` → bagian penutup halaman

❌ Non-semantic:

```html
<div></div>
```

✅ Semantic:

```html
<header></header>
```

## 2️⃣ Elemen Semantic Utama

### 🔹 `<header>`

Digunakan untuk:

- Judul halaman
- Logo
- Informasi pembuka

```html
<header>
  <h1>Website Saya</h1>
</header>
```

### 🔹 `<nav>`

Digunakan untuk **navigasi utama**.

```html
<nav>
  <a href="#">Home</a> | <a href="#">About</a> |
  <a href="#">Contact</a>
</nav>
```

📌 Biasanya berisi menu.

### 🔹 `<main>`

Menampung **konten utama** halaman.

```html
<main>
  <p>Konten utama website</p>
</main>
```

📌 Hanya **1** `<main>` **per halaman**.

### 🔹 `<section>`

Digunakan untuk **mengelompokkan konten** berdasarkan topik.

```html
<section>
  <h2>Tentang Kami</h2>
  <p>Deskripsi singkat.</p>
</section>
```

### 🔹 `<article>`

Digunakan untuk konten **mandiri** dan bisa berdiri sendiri.

```html
<article>
  <h3>Artikel Pertama</h3>
  <p>Isi artikel.</p>
</article>
```

📌 Cocok untuk:

- Artikel blog
- Berita
- Postingan

### 🔹 `<footer>`

Bagian penutup halaman.

```html
<footer>
  <p>&copy; 2026 Website Saya</p>
</footer>
```

## 3️⃣ Struktur Semantic HTML Lengkap

```html
<header>
  <h1>Website Saya</h1>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>

<main>
  <section>
    <h2>Artikel Terbaru</h2>
    <article>
      <h3>Belajar HTML</h3>
      <p>HTML adalah dasar web.</p>
    </article>
  </section>
</main>

<footer>
  <p>&copy; 2026 Website Saya</p>
</footer>
```

## 4️⃣ Manfaat Semantic HTML

**✅ SEO (Search Engine Optimization)**

- Mesin pencari lebih mudah memahami konten

**✅ Aksesibilitas**

- Screen reader lebih ramah bagi pengguna difabel

**✅ Kode Lebih Rapi**

- Mudah dibaca dan dikelola
- Standar industri web modern

## 🧪 Praktik: Membuat Layout Website Sederhana

**🎯 Tujuan Praktik**
Membuat layout website menggunakan struktur semantic HTML.

**Instruksi:**
Buat file `layout.html` dengan ketentuan:

- Gunakan `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- Minimal 1 `<article>`
- Menu navigasi sederhana
- Konten bebas (profil / artikel)

**Contoh Hasil Praktik:**

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <title>Website Semantic</title>
  </head>
  <body>
    <header>
      <h1>Website Pribadi</h1>
    </header>

    <nav>
      <a href="#">Home</a> | <a href="#">Profil</a> |
      <a href="#">Kontak</a>
    </nav>

    <main>
      <section>
        <h2>Tentang Saya</h2>
        <article>
          <p>Saya sedang belajar web development.</p>
        </article>
      </section>
    </main>

    <footer>
      <p>&copy; 2026 Website Saya</p>
    </footer>
  </body>
</html>
```
