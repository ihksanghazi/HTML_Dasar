# 📘 Modul 5: Gambar & Media

**🎯 Tujuan Pembelajaran**
Setelah pertemuan ini, peserta mampu:

- Menampilkan gambar menggunakan tag `<img>`
- Memahami dan menggunakan atribut `src`, `alt`, `width`, dan `height`
- Mengelola folder gambar dengan struktur yang rapi
- Membuat galeri foto sederhana menggunakan HTML

## 1️⃣ Tag `<img>`

Tag `<img>` digunakan untuk menampilkan gambar pada halaman web.
📌 Karakteristik penting:

- Tidak memiliki tag penutup
- Bersifat inline element
- Wajib memiliki atribut `src`

**Contoh Dasar:**

```html
<img src="foto.jpg" />
```

## 2️⃣ Atribut Penting pada `<img>`

### 🔹 `src` (source)

```html
<img src="images/foto1.jpg" />
```

📌 Bisa berupa:

- Path lokal (folder proyek)
- URL online

### 🔹 `alt` (alternative text)

Digunakan untuk:

- Aksesibilitas (screen reader)
- Ditampilkan jika gambar gagal dimuat
- SEO

```html
<img src="images/foto1.jpg" alt="Foto pemandangan gunung" />
```

📌 **Best practice**: selalu gunakan alt.

### 🔹 width dan height

Digunakan untuk mengatur ukuran gambar.

```html
<img src="images/foto1.jpg" width="300" height="200" />
```

📌 Satuan default adalah **pixel.**

## 3️⃣ Struktur Folder Gambar

Pengelolaan folder yang rapi memudahkan pengembangan.

📁 Contoh struktur proyek:
project-html/
├── index.html
├── gallery.html
└── images/
├── foto1.jpg
├── foto2.jpg
└── foto3.jpg

📌 Praktik ini digunakan di proyek web profesional.

## 4️⃣ Menampilkan Banyak Gambar

```html
<img src="images/foto1.jpg" alt="Foto 1" width="200" />
<img src="images/foto2.jpg" alt="Foto 2" width="200" />
<img src="images/foto3.jpg" alt="Foto 3" width="200" />
```

## 5️⃣ Contoh Galeri Foto Sederhana

```html
<h2>Galeri Foto</h2>

<img src="images/foto1.jpg" alt="Foto pantai" width="200" />
<img src="images/foto2.jpg" alt="Foto gunung" width="200" />
<img src="images/foto3.jpg" alt="Foto kota" width="200" />
```

📌 Pada tahap ini, galeri masih **tanpa CSS.**

## 🧪 Praktik: Membuat Galeri Foto Sederhana

**🎯 Tujuan Praktik**
Menerapkan penggunaan gambar dan folder media secara benar.

**Instruksi:**

1. Buat folder `images`
2. Masukkan minimal 3 gambar
3. Buat file `gallery.html`
4. Tampilkan semua gambar dalam satu halaman
5. Gunakan atribut `alt` dan `width`

**Contoh** `gallery.html`:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <title>Galeri Foto</title>
  </head>
  <body>
    <h1>Galeri Foto</h1>

    <img src="images/foto1.jpg" alt="Foto pertama" width="250" />
    <img src="images/foto2.jpg" alt="Foto kedua" width="250" />
    <img src="images/foto3.jpg" alt="Foto ketiga" width="250" />
  </body>
</html>
```
