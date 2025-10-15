 # 📰 DausFeed - Portal Berita Terbaru

DausFeed adalah aplikasi web portal berita yang menampilkan berbagai informasi terkini dari berbagai kategori seperti **Teknologi**, **Olahraga**, **Bisnis**, **Hiburan**, dan **Kesehatan**.  
Dibangun menggunakan **HTML**, **Bootstrap**, **JavaScript**, dan **jQuery**, aplikasi ini mampu menampilkan berita secara **real-time** menggunakan **NewsAPI**.

---

## 📱 Tampilan Aplikasi
### 🏠 Halaman Home (`home.html`)
- Menampilkan hero section dengan deskripsi situs.  
- Tombol **"Lihat Berita Terbaru"** untuk menuju halaman berita.

### 🗞️ Halaman Berita (`index.html`)
- **Header:** Navigasi utama dengan dropdown kategori berita.  
- **Search Bar:** Cari berita berdasarkan kata kunci.  
- **Card News:**  
  - Gambar berita  
  - Judul  
  - Deskripsi singkat  
  - Tombol **Baca Selengkapnya** yang mengarah ke sumber berita asli  
- **Footer:**  
  - Deskripsi singkat situs  
  - Link kategori cepat  
  - Kontak email & lokasi  
- **Fitur Dark Mode:** Ubah tampilan terang/gelap dengan satu klik.

---

## ⚙️ Teknologi yang Digunakan
| Teknologi | Keterangan |
|------------|-------------|
| **HTML5** | Struktur halaman |
| **CSS3** | Styling dan tema warna |
| **Bootstrap 5.3.2** | Layout responsif & komponen UI |
| **jQuery 3.7.1** | AJAX request & manipulasi DOM |
| **NewsAPI.org** | Sumber data berita |
| **Font Awesome** | Ikon UI |
| **Google Fonts (Poppins)** | Font utama situs |

---

## 🚀 Fitur Utama
- Menampilkan berita **real-time** berdasarkan kategori atau kata kunci.
- Mode **gelap & terang (Dark Mode)**.
- **Responsive design** untuk desktop dan mobile.
- **Loading spinner** saat mengambil data.
- **Error handling** untuk hasil pencarian kosong atau gagal fetch.

---

## 🧩 Cara Menjalankan Proyek
1. **Clone repository:**
   ```bash
   git clone https://github.com/username/dausfeed.git
   cd dausfeed
