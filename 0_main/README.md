# NihonTravel Website

[Fahima DayCare](https://www.fahimadaycare.site/)

<a href="https://www.fahimadaycare.site/" target="_blank">
<img src="../images/readme_picture/fahimadaycare_log.jpeg" alt="add relative path to image" 
width="200" height='250'/>
</a>

Website [**NihonTravel**](https://www.fahimadaycare.site/) adalah situs web yang menyediakan informasi tentang berbagai layanan dan produk yang terkait dengan perjalanan ke Jepang. Panduan ini menjelaskan langkah-langkah untuk membuat dan menjalankan website ini.

## Struktur Proyek

NihonTravel/
├── index.html
├── CSS/
│ └── style.css
└── README.md

## Langkah-langkah Membuat Website

### 1. Persiapan

Pastikan Anda memiliki struktur proyek seperti yang dijelaskan di atas. Buat folder utama bernama `NihonTravel`, di dalamnya buat folder `CSS` dan file `index.html` serta `style.css`.

### 2. HTML

File `index.html` berfungsi sebagai halaman utama dari website NihonTravel. Berikut adalah struktur utama dari file `index.html`:

- Bagian `<head>`: Mengandung metadata, judul halaman, dan link ke stylesheet serta font dari Google Fonts.
- Bagian `<body>`: Terdiri dari header, main content, dan footer.

#### Header

Header berisi navigasi dengan logo situs dan tombol "Sign In". Berikut adalah kode untuk header:

```html
<header class="navbar-container">
  <nav class="navbar">
    <h1 class="logo"><a href="./index.html">NihonTravel</a></h1>
    <ul class="nav-links">
      <li>Join now for an extra 10% Cash Back on purchases made in your first 7 days.*</li>
    </ul>
    <a href="#SignIn" class="header-btn">Sign In</a>
  </nav>
</header>
```

Main Content
Bagian utama berisi grid yang menampilkan berbagai kategori seperti "About Us", "Products", "Services", "Gallery", dan "Contact". Setiap item dalam grid ini adalah tautan ke halaman terkait.

```<main class="grid-container">
  <!-- Contoh item dalam grid -->
  <div id="items-1" class="grid-item">
    <a href="../1_about_us/index.html">
      <img src="about_us_image_url" alt="About Us" />
    </a>
    <p class="text-overlay">About Us</p>
  </div>
  <!-- Item lainnya mengikuti struktur yang sama -->
</main>
```

Footer
Footer tidak memiliki konten spesifik dan dapat diperluas sesuai kebutuhan
`<footer></footer>`
