# UAS-Aplikasi-Internet
Pembuatan Website AMR (HTML, CSS)




Dengan 4 Halaman Struktur Utama
Halaman 1: Homepage (Beranda) ---> Pintu masuk utama untuk umum/pengunjung
Halaman 2: Login Page ---> Gerbang masuk untuk penghuni.
Halaman 3: Register Page (Halaman Daftar) ---> Jika belum punya akun, dialihkan ke sini.
Halaman 4: Dashboard/Landing Page Penghuni ---> Halaman khusus setelah sukses login.




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

- Header & Navigation Bar (Menu Atas)
Logo/Nama Asrama di kiri, dan menu navigasi di kanan (Beranda, Fasilitas, Kamar, Kontak).

   = Tambahkan satu tombol mencolok bertuliskan "Area Penghuni" yang akan mengarah ke halaman login.

- Section (Sambutan Utama)
Gambar latar belakang asrama yang diberi overlay gelap agar teks putih di atasnya terlihat kontras dan elegan.

   = Kalimat sambutan yang hangat dan tombol Call to Action (CTA) seperti "Lihat Fasilitas ↓".

- Section Detail Kamar (Menggunakan CSS Grid/Flexbox)
Menampilkan tipe-tipe kamar yang ada (misal: Kamar Reguler, Kamar Pengurus, atau berdasarkan kapasitas orang).

   = Setiap tipe kamar dibuat dalam bentuk Card (Kotak) berisi foto kamar, kapasitas, dan fasilitas dalam kamar (kasur, lemari, meja belajar).

- Section Fasilitas Bersama
Menampilkan fasilitas yang bisa digunakan bersama menggunakan ikon atau foto kecil yang rapi.

   =Contoh: Dapur Bersama, Ruang Tamu/Aula, Ruang Belajar, WiFi Area, dan Tempat Parkir.

- Footer (Bagian Paling Bawah)
Berisi peta lokasi (bisa gunakan teks alamat atau embed sederhana), hak cipta, dan media sosial asrama.




Rancangan Konten untuk Login Page (login.html)

- Kotak Login (Login Card): Berada tepat di tengah-tengah layar (menggunakan efek latar belakang visual asrama yang sedikit buram atau estetik).

- Header Box: Logo asrama atau ikon gembok/user, diikuti judul "Log In Penghuni".

- Form Input:

  = Input untuk Username / Email (menggunakan atribut required).

  = Input untuk Password (menggunakan atribut required).

- Fitur Tambahan (Opsi): Checkbox "Ingat Saya" dan link "Lupa Password?" yang dibuat sejajar (menggunakan Flexbox).

- Tombol Action: Tombol "Masuk" yang didesain mencolok dan interaktif saat di-hover.

- Footer Box (Navigasi Alur): Teks "Belum punya akun? Daftar di sini" yang nantinya akan mengarah ke halaman Register.




Rancangan Konten untuk Register Page (register.html)
- Data Diri: Nama Depan, Nama Belakang, Tempat & Tanggal Lahir, Asal Daerah.

- Data Akademik: Universitas, Fakultas, Jurusan.

- Data Orang Tua: Nama Ayah & Ibu, Pekerjaan, Penghasilan.

- Upload Berkas: KTP, KK, Slip Gaji Orang Tua.

- Keamanan: Buat Password.

- Kotak Peraturan Asrama (Syarat & Ketentuan): Kotak teks panjang yang memiliki scrollbar internal dan wajib dicentang (required) sebelum tombol daftar bisa diklik.




Rancangan Struktur Halaman Penghuni (penghuni.html)
Halaman ini berfungsi sebagai Dashboard Internal Manajemen Asrama dan dibagi menjadi 4 komponen utama:

- Sistem Navigasi & Profil (Sidebar): Menu navigasi khusus internal (Dashboard, Whitelist Tugas, Keuangan) yang dilengkapi dengan kartu profil ringkas penghuni yang sedang login (Nama, Foto/Avatar, Kamar, dan Jabatan).

- Sistem Peringatan Pelanggaran (Alert & Pop-up Modal): Kotak notifikasi bahaya (merah) di bagian atas halaman yang interaktif. Jika tombol diklik, akan memicu jendela pop-up (murni CSS) yang menampilkan detail BAB, Pasal, serta poin peraturan asrama yang dilanggar beserta sanksinya.

- Modul Laporan Keuangan Bulanan (Finance Section):
   = Grafik Lingkaran (Progress Circle): Menampilkan persentase total pengeluaran dibanding pendapatan kas pada bulan berjalan.

   = Diagram Batang (Bar Chart): Menampilkan grafik alokasi anggaran asrama yang dibagi ke dalam 5 pos (Operasional Wajib, Kegiatan & Event, Perbaikan Fasilitas, Dana Darurat, dan Buffer Kas).

- Tabel Whitelist Tugas & Jabatan (Jobdesk Section): Tabel responsif yang menampilkan daftar tugas krusial dari Ketua Asrama. Fitur utamanya adalah Badge Peran (Sekretaris, Bendahara, Divisi) dan Badge Urgensi (Tinggi, Sedang, Rendah) yang memiliki warna penanda berbeda untuk mempermudah monitoring kerja pengurus.