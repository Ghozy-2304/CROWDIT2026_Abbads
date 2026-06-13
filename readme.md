# CultureUp

## Tentang Proyek

CultureUp adalah platform pembelajaran budaya Indonesia berbasis web yang dirancang untuk membantu generasi muda mengenal kembali tradisi, folklore, makanan, tarian, dan sejarah Nusantara melalui pengalaman belajar yang interaktif dan menyenangkan.

## Latar Belakang & Solusi

Banyak generasi muda Indonesia yang semakin jauh dari pengetahuan tentang budaya dan tradisi daerahnya sendiri. Informasi mengenai folklore, rumah adat, tarian tradisional, hingga kuliner khas sering tersebar tidak terstruktur dan kurang menarik untuk dipelajari oleh anak muda.

CulutureUp hadir sebagai solusi dengan menggabungkan konsep **gamifikasi** (XP, streak, leaderboard, challenge harian) dengan **konten edukatif** (quiz, artikel, cerita folklore, kelas budaya) sehingga belajar tentang budaya Indonesia menjadi lebih engaging, terstruktur, dan mudah diakses kapan saja.

## Status Proyek

Proyek ini merupakan **MVP (Minimum Viable Product)**. Artinya:
- Fokus utama saat ini adalah pada **tampilan (UI/UX)** dan **struktur halaman**.
- Sebagian besar konten (gambar, statistik, data pengguna) masih berupa **placeholder/dummy data** untuk keperluan demonstrasi desain.
- Fitur interaktif (tombol, dropdown, modal, filter) sudah berfungsi di sisi front-end menggunakan **vanilla JavaScript**, namun belum terhubung ke backend/database.
- Tujuan MVP ini adalah untuk mendapatkan gambaran alur (flow) dan tampilan produk sebelum dilanjutkan ke pengembangan fitur penuh dan integrasi data nyata.

## Teknologi yang Digunakan

- **HTML5**
- **Tailwind CSS** (via CDN)
- **Vanilla JavaScript** (tanpa framework/library tambahan)
- Font: **Plus Jakarta Sans** (judul/heading) dan **Figtree** (body text)

## Halaman yang Tersedia

- **Home** — Landing page utama dengan ringkasan progres belajar, challenge harian, rekomendasi quiz, folklore, artikel, dan peta budaya.
- **Activity** — Halaman statistik aktivitas pengguna (EXP, streak, quiz selesai, badge) serta daftar aktivitas yang sedang berjalan.
- **Class** — Halaman kelas budaya komunitas, daftar kelas yang diikuti, challenge komunitas, leaderboard, dan forum diskusi.
- **Folklore** — Halaman koleksi cerita rakyat Indonesia dengan kategori dan rekomendasi cerita.
- **Article / Quizzes** — Halaman daftar artikel budaya dan kumpulan quiz berdasarkan kategori.

## Fitur Interaktif (Pop-up / Modal)

Beberapa elemen UI telah dilengkapi dengan interaksi pop-up menggunakan JavaScript murni:

1. **Modal "View All" Quiz per Kategori**
   Saat tombol **View All** pada kategori quiz (misalnya kategori *Houses*) diklik, akan muncul pop-up berisi daftar lengkap quiz pada kategori tersebut dalam bentuk grid card yang dapat di-scroll, lengkap dengan judul kategori dan tombol close (×).

2. **Modal Detail Artikel**
   Saat gambar/card artikel diklik, akan muncul pop-up (modal) yang menampilkan judul artikel, gambar utama, serta isi artikel secara lengkap dalam area yang dapat di-scroll, tanpa perlu pindah halaman.

3. **Dropdown Menu "Save Content / Share"**
   Pada beberapa card (artikel, folklore, aktivitas), tombol titik tiga (⋮) akan menampilkan dropdown menu kecil berisi opsi **Save content** dan **Share**.

4. **Filter Pill Interaktif**
   Pada halaman Article dan Folklore, terdapat filter kategori (All, Foods, Houses, Dance, dll) yang dapat diklik untuk mengubah status aktif secara visual.

Semua interaksi di atas murni berjalan di sisi front-end (client-side) tanpa memerlukan reload halaman.

## Catatan Pengembangan Selanjutnya

- Integrasi dengan backend/database untuk data pengguna, progres, XP, dan leaderboard secara real-time.
- Penambahan sistem autentikasi (login/register).
- Pengisian konten dinamis pada modal artikel dan quiz berdasarkan data sebenarnya (saat ini masih menggunakan data statis/dummy).
- Optimalisasi responsivitas lebih lanjut untuk berbagai ukuran perangkat.