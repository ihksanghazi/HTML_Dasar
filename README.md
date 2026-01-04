# 📘 Modul 9: HTML + CSS Dasar (Perkenalan)

**🎯 Tujuan Pembelajaran**
Setelah pertemuan ini, peserta mampu:

- Memahami peran CSS dalam pengembangan web
- Menjelaskan hubungan HTML dan CSS
- Menggunakan Inline CSS
- Mengatur warna, font, dan background pada halaman HTML
- Mempercantik tampilan halaman web sederhana

## 1️⃣ Apa Itu CSS?

**CSS (Cascading Style Sheets)** adalah bahasa yang digunakan untuk:

- Mengatur **tampilan** dan **layout** halaman web
- Memisahkan **struktur (HTML)** dan **desain (CSS)**

📌 Analogi:

- HTML → struktur bangunan
- CSS → desain, warna, dan dekorasi

## 2️⃣ Cara Menggunakan CSS (Pengenalan)

Ada 3 cara menggunakan CSS:

1. Inline CSS
2. Internal CSS
3. External CSS

👉 Pada pertemuan ini, fokus pada **Inline CSS**.

## 3️⃣ Inline CSS

Inline CSS ditulis langsung di dalam tag HTML menggunakan atribut `style`.
**Contoh**

```html
<p style="color:red;">Teks Merah</p>
```

📌 Sintaks:

```html
style="property: value;"
```

## 4️⃣ Properti CSS Dasar

### 🔹 Warna (`color`)

```html
<p style="color: blue;">Teks Biru</p>
```

Bisa menggunakan:

- Nama warna (`red`, `blue`)
- Kode hex (`#ff0000`)

### 🔹 Font (`font-family`, `font-size`)

```html
<p style="font-family: Arial; font-size: 18px;">Teks dengan font Arial</p>
```

### 🔹 Background (`background-color`)

```html
<div style="background-color: lightgray;">Konten dengan background</div>
```

## 5️⃣ Contoh Kombinasi CSS Dasar

```html
<h1 style="color: darkblue;">Judul Website</h1>

<p style="font-size: 16px; color: gray;">
  Ini adalah paragraf dengan style CSS.
</p>
```

📌 Inline CSS cocok untuk:

- Demo cepat
- Pembelajaran awal
  ❌ Tidak disarankan untuk proyek besar

## 🧪 Praktik: Mempercantik Halaman HTML

**🎯 Tujuan Praktik**
Menerapkan CSS dasar untuk memperbaiki tampilan halaman HTML.
**Instruksi:**
Gunakan file HTML sebelumnya (biodata / artikel), lalu:

- Ubah warna judul
- Atur ukuran font paragraf
- Tambahkan background pada bagian tertentu
- Gunakan minimal 3 properti CSS

**Contoh Hasil Praktik:**

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <title>HTML + CSS Dasar</title>
  </head>
  <body>
    <h1 style="color: darkgreen;">Profil Saya</h1>

    <p style="font-size: 18px; color: #333;">
      Saya sedang belajar HTML dan CSS dasar.
    </p>

    <div style="background-color: #f0f0f0; padding: 10px;">
      <p style="color: blue;">CSS membuat tampilan website lebih menarik.</p>
    </div>
  </body>
</html>
```
