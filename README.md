# 📚 Rak Buku Alief - Landing Page Komunitas & Peminjaman Buku

Selamat datang di repositori **Rak Buku Alief**! Website ini merupakan *Landing Page* modern yang dirancang untuk platform ruang baca, rekomendasi buku, jasa peminjaman buku, dan komunitas literasi. 

Project ini dibuat untuk memenuhi **Tugas Praktikum 3 - Framework CSS (Tailwind CSS)** pada mata kuliah Pemrograman Web / Praktikum Sistem Informasi.

---

## 🌟 Fitur & Komponen Utama

Website ini dibangun sesuai dengan kriteria dan ketentuan struktur *landing page*, mencakup:

1. **Navbar (Responsive Navigation)**: Navigasi utama dengan *sticky effect*, *glassmorphism*, serta *hamburger menu* untuk tampilan seluler (*mobile view*).
2. **Hero Section**: Tampilan utama yang menarik dengan foto latar belakang, lencana komunitas, tajuk inspiratif, serta tombol *Call to Action* (CTA).
3. **Tentang (About Section)**: Penjelasan mengenai visi dan tujuan utama dari Rak Buku Alief.
4. **Fitur / Keunggulan (Grid System)**: Memuat 3 poin keunggulan utama dalam bentuk *card* interaktif.
5. **Layanan**: Menampilkan 4 jenis layanan yang ditawarkan (Katalog Buku, Ruang Diskusi, Peminjaman Buku, dan Rekomendasi Personal).
6. **Katalog Buku (Grid System)**: Showcase koleksi buku populer lengkap dengan gambar sampul, penulis, genre, dan deskripsi singkat.
7. **Testimoni Anggota**: Kesaksian dan ulasan dari pengguna/anggota komunitas.
8. **Form Pendaftaran / Kontak**: Formulir pendaftaran anggota baru atau pengajuan peminjaman buku.
9. **Footer**: Informasi kontak lengkap, tautan navigasi, dan media sosial.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5**: Struktur semantic halaman web.
* **[Tailwind CSS (v4)](https://tailwindcss.com/)**: Murni 100% menggunakan *utility classes* bawaan tanpa CSS manual tambahan.
* **JavaScript (DOM Manipulation)**: Digunakan untuk fungsi *toggle menu* pada navigasi seluler.

---

## 📐 Fitur Desain & Teknikal

* **100% Responsive Design**: Tampilan otomatis menyesuaikan berbagai ukuran layar (Desktop, Tablet, dan Mobile).
* **Multi-Grid System**: Menerapkan sistem *Grid* bawaan Tailwind CSS pada bagian Fitur, Layanan, Katalog, dan Form Kontak.
* **Zero Custom CSS**: Seluruh penataan gaya, transisi, warna, dan tata letak dikelola sepenuhnya menggunakan *class* Tailwind.

---

## 📁 Struktur Direktori

```text
.
├── assets/                  # Gambar latar belakang dan sampul buku
│   ├── filosofiTeras.jpg
│   ├── hujanTereLiye.jpg
│   ├── laskarpelangi.jpg
│   ├── lautBercerita.jpg
│   ├── pareidoliaTereLiye.jpg
│   ├── perpusBackground.jpg
│   ├── rdpd.png
│   └── sisiTergelapSurga.jpg
├── index.html               # File utama HTML & Tailwind CSS
└── README.md                # Dokumentasi proyek