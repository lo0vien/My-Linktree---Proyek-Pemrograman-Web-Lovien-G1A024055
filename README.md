# Website Linktree Pribadi – Proyek Pemrograman Web

Halo! Saya Lovien Najla Dhafiyah, mahasiswi Universitas Bengkulu Program Studi Informatika Angkatan 2024 dengan NPM G1A024055. Website ini dibuat sebagai bagian dari pemenuhan tugas mata kuliah Proyek Pemrograman Web. Website ini merupakan halaman Linktree sederhana, yang berfungsi sebagai media untuk menampilkan profil singkat serta tautan menuju akun media sosial dan dokumen CV saya.

Website ini memuat:
* Foto profil dan identitas singkat
* Link Instagram
* Link WhatsApp
* Link GitHub
* Link Download Curriculum Vitae (CV) dalam format PDF

---

## Struktur Folder dan File

Berikut adalah susunan direktori dalam proyek ini:

```text
├── index.html  
├── style.css  
├── CV-Lovien.pdf  
└── img  
    ├── profile.JPG  
    └── logo.jpg  
```

---

## Penjelasan Struktur

1. **Folder img**
   Folder ini berisi gambar yang digunakan pada website, yaitu foto profil serta logo yang digunakan sebagai favicon pada tab browser.

2. **File CV**
   File `CV-Lovien.pdf` merupakan Curriculum Vitae yang dapat diakses dan diunduh melalui tombol *Download CV* pada halaman utama.

3. **File HTML**
   File `index.html` merupakan halaman utama yang berisi struktur tampilan Linktree, termasuk bagian profil dan tombol tautan sosial media.

4. **File CSS**
   File `style.css` digunakan untuk mengatur desain website agar terlihat lebih modern, menarik, responsif, serta memiliki tema warna pastel yang lembut.

---

## Kode yang Dihighlight

Berikut beberapa bagian kode penting yang digunakan dalam website ini:


### 1. Menampilkan Ikon (Favicon) pada Tab Browser

```html
<link rel="icon" type="img/jpg" sizes="16x16" href="img/logo.jpg">
<link rel="manifest" href="/site.webmanifest">
```

Kode ini digunakan untuk menampilkan logo website sebagai ikon pada tab browser.

---

### 2. Menggunakan Google Font dan FontAwesome Icon

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<script src="https://kit.fontawesome.com/7f4731297f.js" crossorigin="anonymous"></script>
```

Kode ini digunakan untuk menambahkan font **Poppins** serta ikon sosial media agar tampilan lebih menarik.

---

### 3. Menampilkan Foto Profil dan Identitas Singkat

```html
<div class="profil">
    <img src="img/profile.JPG" alt="profile">
    <h1>Hi, I'm Lovien Najla Dhafiyah</h1>
    <p>Informatics Student | University of Bengkulu</p>
</div>
```

Kode ini digunakan untuk menampilkan komponen profil berupa foto, nama, dan deskripsi singkat.

---

### 4. Membuat Tombol Tautan Media Sosial

```html
<a href="https://instagram.com/loviennajla" target="_blank">
    <div class="sosmed">
        <i class="fa-brands fa-instagram"></i>
        Instagram
    </div>
</a>
```

Kode ini digunakan untuk membuat tombol tautan menuju akun media sosial dengan ikon di sebelah kiri.

---

### 5. Mengatur Tampilan Tombol dengan CSS dan Hover Effect

```css
.sosmed {
    background: white;
    color: #ff6fae;
    padding: 15px;
    border-radius: 20px;
    box-shadow: 0 5px 12px rgba(255, 182, 193, 0.35);
    transition: all 0.3s ease;
}

.sosmed:hover {
    background: #ffb6d9;
    color: white;
    transform: scale(1.05);
}
```

Kode ini digunakan untuk membuat tombol sosial media terlihat seperti kartu modern dengan efek hover saat disentuh.

---

## Tujuan Pembuatan Website
Website Linktree ini dibuat sebagai sarana untuk memperkenalkan profil pribadi secara digital sekaligus melatih kemampuan dasar dalam pengembangan web menggunakan HTML dan CSS. Melalui proyek ini, saya mempelajari Struktur dasar HTML, Penggunaan file eksternal CSS, Pengelolaan folder gambar dan dokumen, Pemanfaatan ikon FontAwesome, Pembuatan tampilan modern dan responsif

Terima kasih telah mengunjungi dan membaca README ini
