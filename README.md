# Practical Lab: Simple Web Layout (HTML & CSS)

Project ini merupakan tugas praktikum pemrograman web untuk membangun layout web dasar yang responsif menggunakan **HTML5** dan **CSS3**. Struktur tata letak memanfaatkan teknik *CSS Floating*, *Flexbox*, serta pemanfaatan Google Fonts eksternal.

---

## truktur File & Folder

```text
Lab4Web/
│
├── Home.html        # Halaman Utama (Hero, 3 Kolom Fitur, Artikel)
├── About.html       # Halaman Profil & Daftar Portofolio
├── kontak.html      # Halaman Formulir Kontak
├── lab4_box.html    # Eksperimen Dasar CSS Box Model & Float Clear
├── Home.css         # Stylesheet Utama (Layout, Typography, Components)
└── README.md        # Dokumentasi Project
```

---

##  Fitur & Komponen Utama

1. **Top Navigation Bar:**
   - Navigasi utama dengan status aktif (`class="active"`).
   - Tautan navigasi internal (Anchor Link `#artikel`) untuk bergulir ke bagian artikel di halaman yang sama.

2. **Hero Section:**
   - Bagian *banner* ucapan selamat datang menggunakan tombol pemicu tindakan (*Call-To-Action*).

3. **3-Column Feature Boxes:**
   - Tampilan 3 kolom berjejer berisi gambar melingkar (`.image-circle`) dan deskripsi singkat.

4. **Article Section (`.entry`):**
   - Artikel dengan penataan gambar bergantian di sebelah **kiri** (`.left-img`) dan **kanan** (`.right-img`) menggunakan *CSS Float*.
   - Dilengkapi *clearfix* (`::after`) agar tinggi elemen pembungkus tidak rusak.

5. **Right Sidebar Widget:**
   - Widget diletakkan secara presisi di bagian kanan menggunakan *layout wrapper* (`#main` dan `#sidebar`).

6. **Interactive Contact Form & Portfolio:**
   - Formulir input nama, email, subjek, dan pesan pada `kontak.html`.
   - List portofolio berbasis kartu di halaman `About.html`.

---

##  Impor Font Eksternal

Stylesheet menggunakan font Google Fonts yang diimpor pada baris paling atas `Home.css`:

```css
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&display=swap');
```

---

##  Cara Menjalankan Project

1. *Clone* atau unduh seluruh file project ke komputer Anda.
2. Pastikan semua file `.html` dan `.css` berada di dalam direktori/folder yang sama.
3. Buka file `Home.html` menggunakan *web browser* pilihan Anda (Google Chrome, Firefox, Edge) atau jalankan melalui ektensi **Live Server** di VS Code.

---

##  Keterangan
* **Mata Kuliah:** Pemrograman Web
* **Institusi:** Universitas Pelita Bangsa