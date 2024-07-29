# Wilwa-Tikta Rent Frontend

Wilwa-Tikta Rent Frontend adalah antarmuka pengguna untuk aplikasi penyewaan online Wilwa-Tikta Rent.

## Fitur Utama

- **Halaman Beranda**: Menampilkan item yang tersedia untuk disewa.
- **Pencarian dan Filter**: Mencari dan menyaring item berdasarkan kategori dan kriteria lainnya.
- **Detail Item**: Menampilkan detail item dan opsi untuk melakukan reservasi.
- **Manajemen Pesanan**: Melihat dan mengelola pesanan pengguna.
- **Profil Pengguna**: Mengelola informasi profil dan pengaturan akun.
- **Sistem Ulasan**: Menulis dan membaca ulasan untuk item yang disewa.
- **Integrasi API**: Menghubungkan dengan backend Wilwa-Tikta Rent untuk mengambil data dan melakukan tindakan.

## Persyaratan

- Node.js (versi terbaru disarankan)
- NPM (Node Package Manager)

## Instalasi dan Menjalankan Proyek

1. **Clone Repository**

   ```bash
   git clone https://github.com/ebetap/wilwa-tikta-frontend.git
   cd wilwa-tikta-frontend
   ```

2. **Install Dependensi**

   ```bash
   npm install
   ```

3. **Konfigurasi**

   Buat file `.env` di root proyek dan tambahkan konfigurasi berikut:

   ```
   REACT_APP_API_BASE_URL=https://api.wilwatikta.com/api/v1
   ```

   Sesuaikan `REACT_APP_API_BASE_URL` dengan URL API backend Anda.

4. **Menjalankan Aplikasi**

   Jalankan aplikasi untuk pengembangan:

   ```bash
   npm start
   ```

   Aplikasi akan berjalan di `http://localhost:3000`.

5. **Membangun Aplikasi**

   Untuk membangun aplikasi untuk produksi, jalankan:

   ```bash
   npm run build
   ```

   Hasil build akan berada di folder `build/`.

## Struktur Proyek

```bash
src/
├── components/      # Komponen UI untuk halaman aplikasi
├── pages/           # Halaman aplikasi seperti Home, Item Detail, User Profile
├── styles/          # Berkas gaya (CSS/SCSS)
├── utils/           # Fungsi utilitas dan API helper
└── App.js           # Entry point untuk aplikasi
public/
├── index.html       # Template HTML
└── favicon.ico      # Ikon aplikasi
```

## Kontribusi

Kami menerima kontribusi dari siapa pun yang ingin meningkatkan antarmuka pengguna ini. Untuk kontribusi, silakan buat pull request atau buka isu baru di repository ini.

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

## Kontak

Jika Anda memiliki pertanyaan atau membutuhkan bantuan, jangan ragu untuk menghubungi kami di [beta.priyoko@students.amikom.ac.id](mailto:beta.priyoko@students.amikom.ac.id).
