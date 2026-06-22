# UAS-Aplikasi-Internet
Pembuatan Website AMR (HTML, CSS)

Dengan 4 Halaman Struktur Utama
Halaman 1: Homepage (Beranda) $\rightarrow$ Pintu masuk utama untuk umum/pengunjung
Halaman 2: Login Page $\rightarrow$ Gerbang masuk untuk penghuni.
Halaman3: Register Page (Halaman Daftar) $\rightarrow$ Jika belum punya akun, dialihkan ke sini.
Halaman 4: Dashboard/Landing Page Penghuni $\rightarrow$ Halaman khusus setelah sukses login.

Plaintext
📂 projek-uas-asrama/
│
├── 📂 css/
│   ├── global.css      <-- (Warna utama, font, reset margin, navbar, footer)
│   ├── homepage.css    <-- (Khusus gaya untuk halaman utama saja)
│   ├── login.css       <-- (Khusus gaya halaman login)
│   ├── register.css    <-- (Khusus gaya pendaftaran)
│   └── dashboard.css   <-- (Khusus gaya landing page penghuni)
│
├── index.html          <-- (Homepage)
├── login.html
├── register.html
└── penghuni.html

Rancangan Konten Utama untuk Homepage (index.html)
Sesuai diskusi kita sebelumnya, kita akan memasukkan Detail Kamar dan Fasilitas langsung di halaman utama ini agar informatif bagi publik. Berikut adalah urutan section yang sangat bagus untuk kamu presentasikan nanti:

1. Header & Navigation Bar (Menu Atas)
Logo/Nama Asrama di kiri, dan menu navigasi di kanan (Beranda, Fasilitas, Kamar, Kontak).

Tambahkan satu tombol mencolok bertuliskan "Area Penghuni" yang akan mengarah ke halaman login.

2. Hero Section (Sambutan Utama)
Gambar latar belakang asrama yang diberi overlay gelap agar teks putih di atasnya terlihat kontras dan elegan.

Kalimat sambutan yang hangat dan tombol Call to Action (CTA) seperti "Lihat Fasilitas ↓".

3. Section Detail Kamar (Menggunakan CSS Grid/Flexbox)
Menampilkan tipe-tipe kamar yang ada (misal: Kamar Reguler, Kamar Pengurus, atau berdasarkan kapasitas orang).

Setiap tipe kamar dibuat dalam bentuk Card (Kotak) berisi foto kamar, kapasitas, dan fasilitas dalam kamar (kasur, lemari, meja belajar).

4. Section Fasilitas Bersama
Menampilkan fasilitas yang bisa digunakan bersama menggunakan ikon atau foto kecil yang rapi.

Contoh: Dapur Bersama, Ruang Tamu/Aula, Ruang Belajar, WiFi Area, dan Tempat Parkir.

5. Footer (Bagian Paling Bawah)
Berisi peta lokasi (bisa gunakan teks alamat atau embed sederhana), hak cipta, dan media sosial asrama.

Rancangan Konten untuk Login Page (login.html)

Kotak Login (Login Card): Berada tepat di tengah-tengah layar (menggunakan efek latar belakang visual asrama yang sedikit buram atau estetik).

Header Box: Logo asrama atau ikon gembok/user, diikuti judul "Log In Penghuni".

Form Input:

Input untuk Username / Email (menggunakan atribut required).

Input untuk Password (menggunakan atribut required).

Fitur Tambahan (Opsi): Checkbox "Ingat Saya" dan link "Lupa Password?" yang dibuat sejajar (menggunakan Flexbox).

Tombol Action: Tombol "Masuk" yang didesain mencolok dan interaktif saat di-hover.

Footer Box (Navigasi Alur): Teks "Belum punya akun? Daftar di sini" yang nantinya akan mengarah ke halaman Register.