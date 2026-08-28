# 🌟 Portofolio Pemrograman Web - Vania Veronica (Nia)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

Selamat datang di repositori portofolio dan proyek website **Pemrograman Web** saya!  
Repositori ini dikembangkan oleh **Vania Veronica (Nia)**, mahasiswi **Teknik Komputer (Kelas Tekom C '25)**.

---

## 📌 Daftar Isi
- [Tentang Portofolio](#-tentang-portofolio)
- [Penerapan Konsep CSS Modul Praktikum](#-penerapan-konsep-css-modul-praktikum)
  - [1. Modul 3: CSS Dasar & Selector](#1-modul-3-dasar-css--selector)
  - [2. Modul 4: CSS Image & Background](#2-modul-4-css-image--background)
  - [3. Modul 5: CSS Navigasi & Layout](#3-modul-5-css-navigasi--layout)
  - [4. Modul 6: Dropdown Navigasi, Gradient & Transisi](#4-modul-6-dropdown-navigasi-gradient--transisi)
- [Struktur Halaman Web](#-struktur-halaman-web)
- [Struktur Direktori Repositori](#-struktur-direktori-repositori)
- [Cara Menjalankan Website Secara Lokal](#-cara-menjalankan-website-secara-lokal)
- [Panduan Perintah Git & GitHub](#-panduan-perintah-git--github)
- [Kontak](#-kontak)

---

## 📖 Tentang Portofolio

Website portofolio ini dibangun menggunakan standar **HTML5 semantik** dan **CSS3 eksternal terpadu** (`style.css`) yang menerapkan seluruh kaidah dan konsep praktikum Pemrograman Web Teknik Komputer. Website ini dirancang agar bersih, modern, responsif, dan mencerminkan portofolio nyata seorang mahasiswa Teknik Komputer tanpa menyertakan potongan output modul praktikum mentah.

---

## 🎨 Penerapan Konsep CSS Modul Praktikum

Seluruh konsep teknis CSS dari Modul 3 hingga Modul 6 diintegrasikan secara profesional:

### 1. Modul 3: Dasar CSS & Selector
- **Pemisahan File CSS Eksternal:** Menghubungkan stylesheet menggunakan `<link rel="stylesheet" href="style.css" type="text/css">`.
- **Selector HTML, Class, & ID:** Penggunaan selektor tag standar (`h1`, `h2`, `p`, `table`, `b`, `i`), selektor class (`.headlines`, `.sublines`, `.infotext`, `.card-identitas`), dan selektor ID struktural (`#header-wrapper`, `#menu`, `#hero`, `#leftcolumn`, `#rightcolumn`).
- **Grouping Selector:** Efisiensi kode dengan pengelompokan selektor (misal: `h1, h2, h3, h4, h5, h6 { ... }` dan `.headlines, .sublines, .infotext { ... }`).
- **Elemen Inline & Block (`<span>` dan `<div>`):** Pengelompokan baris teks inline dan blok layer terstruktur.
- **Tugas Mandiri Modul 3:** Format Kartu Identitas Mahasiswa (`.card-identitas`) serta penjabaran rencana target 2-3 tahun ke depan.

### 2. Modul 4: CSS Image & Background
- **Background Styling & Gradients:** Menggunakan `background-color`, `linear-gradient`, `radial-gradient`, dan `background-position`.
- **Standardisasi Dimensi Gambar (Pasfoto):** Pengaturan pasfoto proporsional resmi:
  - **Ukuran 3x4** (`120px` x `160px`)
  - **Ukuran 4x6** (`160px` x `240px`)
  - **Ukuran 10x15** (`200px` x `300px`)
- **Border & Efek Hover Opacity:** Border solid tema `border: 3px solid #1e3c72;` dengan transisi halus saat kursor berada di atas gambar (`img:hover { opacity: 1.0; }`).
- **Text di Box Transparan (Glassmorphism):** Kotak teks semi-transparan menggunakan `background: rgba(...)` dan `backdrop-filter: blur()`.

### 3. Modul 5: CSS Navigasi & Layout
- **Navigasi Berbasis `<ul>` dan `<li>`:** Penghilangan bullet (`list-style-type: none`), margin/padding reset, dan link berbentuk blok (`display: block`).
- **Navigasi Horizontal & Vertikal:** Menu navigasi utama horizontal di header dan navigasi vertikal (`.nav-vertikal`) di area sidebar.
- **Layout 2 Kolom:** Menggunakan float (`#leftcolumn` & `#rightcolumn`) dengan *clearfix*.
- **Layout 3 Kolom:** Menggunakan float tiga kolom (`#sidebar-kiri`, `#sidebar-tengah-atau-badan`, `#sidebar-kanan`).
- **Formulir Interaktif:** Form input pengisian data dan kontak pesan yang rapi.

### 4. Modul 6: Dropdown Navigasi, Gradient & Transisi
- **Multi-Level Dropdown Navbar:** Sub-menu yang muncul otomatis dan elegan saat menu utama di-hover (`#menu li:hover > ul`).
- **CSS Linear Gradient:** Gradasi warna navy modern (`linear-gradient(135deg, #1e3c72 0%, #2a5298 100%)`).
- **Border Radius:** Efek sudut melengkung melingkar pada kartu, gambar, tombol, dan form input (`border-radius: 8px`).
- **CSS Transitions:** Transisi animasi perubahan warna, pergeseran posisi, dan opasitas yang mulus (`transition: all .25s ease-in-out`).

---

## 🌐 Struktur Halaman Web

| Halaman | File | Deskripsi |
| :--- | :--- | :--- |
| **Beranda** | `index.html` | Halaman utama dengan hero banner, ringkasan profil, navigasi vertikal sidebar, dan layout 3 kolom pilar keahlian. |
| **Tentang Saya** | `about.html` | Profil lengkap, galeri pasfoto ukuran standar (3x4 & 4x6), kartu biodata format identitas, dan target 2-3 tahun ke depan. |
| **Portofolio** | `portfolio.html` | Galeri showcase proyek web, eksplorasi desain UI/UX, sistem informasi, dan dokumentasi visual. |
| **Kontak** | `contact.html` | Informasi kontak langsung (Email, WhatsApp, GitHub) dan formulir pengiriman pesan. |
| **Stylesheet** | `style.css` | File CSS utama yang memuat seluruh rancangan desain dan kaidah modul praktikum. |

---

## 📁 Struktur Direktori Repositori

```text
latihan-git/
│
├── assets/
│   └── images/
│       └── profile.jpg      # Foto profil resmi
│
├── index.html               # Halaman Home / Beranda
├── about.html               # Halaman Tentang Saya & Biodata
├── portfolio.html           # Halaman Galeri Portofolio Proyek
├── contact.html             # Halaman Kontak & Formulir
├── style.css                # File CSS Eksternal Utama
├── profile.jpg              # Salinan foto profil
└── Readme.md                # Dokumentasi Repositori GitHub
```

---

## 💻 Cara Menjalankan Website Secara Lokal

1. **Clone repositori ini ke komputer Anda:**
   ```bash
   git clone https://github.com/vaniaveronica0301-bot/vaniaveronica0301-github.io.git
   ```
2. **Buka folder proyek:**
   ```bash
   cd latihan-git
   ```
3. **Buka file `index.html`:**
   - Cukup klik dua kali file `index.html`, atau
   - Klik kanan `index.html` > *Open with* > Pilih web browser favorit Anda (Google Chrome, Firefox, Microsoft Edge).

---

## 🌐 Akses Online (GitHub Pages)

Website portofolio ini dapat diakses secara online melalui link:  
🔗 **[https://vaniaveronica0301-bot.github.io/](https://vaniaveronica0301-bot.github.io/)**

---

## 🛠 Panduan Perintah Git & GitHub

Berikut adalah perintah Git yang digunakan untuk mengelola repositori ini:

```bash
# 1. Cek status perubahan file
git status

# 2. Menambahkan seluruh file ke staging area
git add .

# 3. Melakukan commit perubahan dengan pesan deskriptif
git commit -m "Sesuaikan konsep CSS Modul 3-6 pada portofolio dan bersihkan output modul mentah"

# 4. Mengunggah commit ke GitHub (remote repository)
git push origin master
```

---

## 📬 Kontak

Jika Anda memiliki pertanyaan atau ingin berdiskusi lebih lanjut, silakan hubungi:

- **Nama:** Vania Veronica (Nia)
- **Kelas:** Tekom C 2025 (Teknik Komputer)
- **Email:** [vaniaveronica0301@gmail.com](mailto:vaniaveronica0301@gmail.com)
- **WhatsApp:** [+62 822-6095-0451](https://wa.me/6282260950451)
- **GitHub:** [@vaniaveronica0301-bot](https://github.com/vaniaveronica0301-bot/vaniaveronica0301-github.io)

---
*Dibuat dengan ❤️ untuk Praktikum Pemrograman Web Teknik Komputer.*