# Ristek CU Front-end Technical Test

## Overview


Ujian ini merupakan ujian berbentuk projek kecil yang dirancang untuk menilai keterampilan praktis calon anggota dalam pengembangan aplikasi front-end. Proyek ini mencakup cara penggunaan HTML, CSS, dan JavaScript oleh para calon anggota untuk membangun aplikasi web, yang mengonsumsi data lewat REST API yang disediakan di [The Movie Database](https://developer.themoviedb.org/docs/getting-started).

## Tech Stack

- **Programming Languages**  
Menggunakan trio maut front-end (HTML, CSS, dan JavaScript) untuk mengembangkan aplikasi web.
- **Front-end Library / Framework**  
Bebas memilih library dan framework untuk pengembangan frontend seperti React, Vue, Svelte, Qwik, ataupun hanya menggunakan Vanilla JavaScript.
- **Styling Library / Framework**  
Diperbolehkan menggunakan framework CSS seperti Tailwind, SASS, Bootstrap, Emotion, dll.
- **No UI / Component Library**  
Tidak diperbolehkan untuk menggunakan component library seperti Material UI, shadcn, Ant Design, dll.
- **Consume REST API TMDb**  
Gunakan [The Movie Database](https://developer.themoviedb.org/docs/getting-started) sebagai RESTful API untuk pengambilan dan pengelolaan data.

## Task

1. **Daftar Film**
    - Tampilkan daftar film yang diambil dari TMDb API.
    - Setiap film harus menampilkan judul, poster, dan tombol untuk melihat detail film.
2. **Detail Film**
    - Ketika pengguna mengklik film, tampilkan detail film yang diambil dari TMDb API.
    - Tampilkan informasi seperti deskripsi, tahun rilis, rating, dan daftar ulasan.
3. **Membuat dan Mengedit Ulasan**
    - Buat formulir untuk menambahkan ulasan baru.
    - Pengguna harus dapat mengedit ulasan yang mereka buat sendiri dengan validasi input.
    - Anda bisa memanfaatkan Web Storage (LocalStorage) yang di sediakan oleh [Web API](https://developer.mozilla.org/en-US/docs/Web/API) untuk menampung data ulasan.
4. **Menghapus Ulasan**
    - Pengguna dapat menghapus ulasan mereka dengan konfirmasi.
    - Penghapusan ulasan harus terefleksi dalam data yang sudah disimpan di Web Storage (LocalStorage) sehingga data akan selalu sinkron.
5. **Desain Responsif:**
    - Pastikan antarmuka pengguna responsif dan dapat digunakan di berbagai perangkat (desktop, tablet, mobile).

## **Note**

- **Dokumentasi Aplikasi**  
Buat dokumentasi tentang cara menjalankan aplikasi frontend dalam file **README.md**.
- **Dokumentasi API**  
Sertakan informasi tentang endpoint TMDb API yang digunakan dalam aplikasi frontend.
- **Struktur Proyek**  
Susun proyek dengan baik agar mudah dipahami oleh pengembang lain.

## **Kriteria Penilaian**

1. **Fungsionalitas**  
Apakah semua fitur berfungsi sesuai dengan spesifikasi / task?
2. **Kualitas Kode**  
Apakah kode terstruktur dengan baik dan mengikuti best practices?
3. **Desain UI/UX**  
Seberapa baik antarmuka pengguna dalam hal estetika dan kegunaan?
4. **Responsivitas**  
Apakah aplikasi berfungsi dengan baik di berbagai perangkat?

## Selamat mengerjakan! :D
