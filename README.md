# 📱 SmartPick - Temukan Smartphone Terbaik

**SmartPick** adalah aplikasi web interaktif berbasis *Single Page Application* (SPA) yang dirancang untuk membantu pengguna dalam menemukan smartphone ideal berdasarkan rentang *budget*, kebutuhan penggunaan (seperti gaming, fotografi, produktivitas, atau harian), serta prioritas kriteria spesifik yang dapat diatur sendiri.

Aplikasi ini menggunakan pendekatan sistem pendukung keputusan untuk merangking dan merekomendasikan pilihan smartphone terbaik secara objektif dan transparan.

---

## ✨ Fitur Utama

1. **Dashboard & Ringkasan Interaktif**: 
   - Menyediakan statistik ringkas terkait ketersediaan smartphone, aspek penilaian, dan daftar ponsel terpopuler.
   - Grafik interaktif menggunakan **Chart.js** untuk melihat sebaran kategori smartphone (Entry-Level, Mid-Range, Flagship).
2. **Katalog & Manajemen Data Smartphone**:
   - Filter lengkap berdasarkan nama, brand, dan rentang harga.
   - Fitur pencarian instan dan pengurutan (harga terendah, harga tertinggi, performa terbaik).
   - CRUD (Tambah, Edit, Hapus) data smartphone langsung melalui antarmuka.
3. **Pengaturan Kriteria & Bobot Penilaian**:
   - Menyesuaikan tingkat kepentingan (bobot %) untuk berbagai aspek seperti Harga, RAM, Kamera, Baterai, Penyimpanan, dan Performa.
   - Mendukung opsi kriteria *benefit* (semakin tinggi semakin baik) dan *cost* (semakin rendah semakin baik).
4. **Mesin Rekomendasi Pintar**:
   - Filter berdasarkan *budget* minimal dan maksimal.
   - Pilihan profil cepat (*Preset*): **Gaming**, **Fotografi**, **Produktivitas**, dan **Sehari-hari**.
   - Menampilkan peringkat 3 teratas smartphone terbaik lengkap dengan skor kecocokan persentase.
5. **Perbandingan & Hasil Perhitungan**:
   - Tabel perbandingan berdampingan (*side-by-side*) untuk produk rekomendasi teratas.
   - Rincian skor transparan di halaman Hasil Perhitungan.
   - Fitur cetak/ekspor hasil rekomendasi secara langsung.

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibuat menggunakan pendekatan *frontend-only* yang ringan tanpa memerlukan instalasi *backend* yang rumit:
- **HTML5 & CSS3**
- **Tailwind CSS** (via CDN untuk styling responsif modern)
- **JavaScript (ES6+)** (Logika aplikasi, manipulasi DOM, dan sistem perankingan)
- **Lucide Icons** (Ikon UI modern)
- **Chart.js** (Visualisasi data dan grafik statistik)
- **Google Fonts (Plus Jakarta Sans)** (Tipografi utama)

---

## 🚀 Cara Menjalankan Proyek

Karena proyek ini berbasis web statis, Anda tidak memerlukan server khusus atau instalasi Node.js yang rumit. Ikuti langkah-langkah berikut:

1. **Clone repositori ini** atau unduh file proyek (`index.html` dan aset terkait):
   ```bash
   git clone [https://github.com/username/smartpick.git](https://github.com/username/smartpick.git)
