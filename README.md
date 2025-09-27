# Laporan Praktikum  
**Pembuatan Website Curriculum Vitae dengan HTML dan CSS**

**Dosen Pengampu:**  
Ir. Gede Humaswara Prathama, S.T., M.T.  

**Oleh:**  
Ni Komang Ria Asrini — 42430014  

**Program Studi Teknologi Informasi**  
Fakultas Teknik dan Informatika  
Universitas Pendidikan Nasional  
2025  

---

## 1. Penjelasan Kode

### a) Deklarasi dan Elemen Dasar
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Curriculum Vitae</title>
</head>
<body>
</body>
</html>
```

- `<!DOCTYPE html>` → mendefinisikan jenis dokumen sebagai HTML5.  
- `<html lang="id">` → menyatakan bahasa utama halaman adalah Bahasa Indonesia.  
- `<head>` → menyimpan metadata dokumen.  
- `<meta charset="UTF-8">` → set karakter UTF-8.  
- `<meta name="viewport"...>` → menyesuaikan tampilan dengan perangkat.  
- `<title>` → judul halaman di tab browser.  

---

### b) Bagian Body
```html
<body>
</body>
```
- `<body>` menampung seluruh konten web.  

---

### c) Header
```html
<header>
  <h1>Nama Lengkap</h1>
  <p>Developer | Graphic Designer</p>
</header>
```
- `<header>` untuk bagian kepala halaman.  
- `<h1>` judul utama.  
- `<p>` tagline atau deskripsi singkat.  

---

### d) Navigasi
```html
<nav>
  <ul>
    <li><a href="#biodata">Biodata</a></li>
    <li><a href="#pendidikan">Pendidikan</a></li>
    <li><a href="#skill">Skill</a></li>
  </ul>
</nav>
```
- `<nav>` → bagian navigasi.  
- `<ul>` → daftar tidak berurutan.  
- `<li>` → item daftar.  
- `<a href="#...">` → tautan internal ke id yang sesuai.  

---

### e) Bagian Utama
```html
<section id="biodata">
  <h2>Biodata Diri</h2>
  <p>Nama: Nama Lengkap</p>
  <p>Email: email@contoh.com</p>
</section>

<section id="pendidikan">
  <h2>Pendidikan</h2>
  <ul>
    <li>Sekolah Dasar XYZ</li>
    <li>Sekolah Menengah Pertama ABC</li>
  </ul>
</section>

<section id="skill">
  <h2>Skill</h2>
  <p>HTML, CSS, JavaScript, Photoshop</p>
</section>

<footer>
  <p>Ikuti saya di social media: 
    <a href="https://twitter.com/">Twitter</a>, 
    <a href="https://linkedin.com/">LinkedIn</a>
  </p>
</footer>
```
- `<section>` → membuat bagian konten.  
- `<footer>` → informasi sosial media.  

---

## 2. CSS Selectors

### a) Selektor Kelas
```css
.judul-utama {
  color: darkblue;
  text-align: center;
}
```

### b) Selektor ID
```css
#paragraf-satu {
  font-size: 1.2em;
  font-style: italic;
  background-color: #f0f0f0;
  padding: 10px;
}
```

### c) Selektor Atribut
```css
a[target="_blank"] {
  color: green;
  text-decoration: none;
  font-weight: bold;
}
```

### d) Pseudo-class
```css
a[target="_blank"]:hover {
  color: orange;
  text-decoration: underline;
}
```

### e) Pseudo-element
```css
.intro::first-line {
  font-weight: bold;
  font-size: 1.1em;
}
```

### f) Style Section
```css
section {
  border: 1px solid #ddd;
  padding: 15px;
  margin: 20px 0;
  box-shadow: 0 0 5px #aaa;
}
```

---

## 3. Menghubungkan CSS
```html
<link rel="stylesheet" href="style.css">
```
- `rel="stylesheet"` → memberi tahu browser bahwa ini file CSS.  
- `href="style.css"` → menunjuk ke file eksternal CSS.  

---
