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
   - Fitur pencarian instan dan pengurutan (harga terendah, harga tertinggi, performa terbaik)[cite: 1].
   - CRUD (Tambah, Edit, Hapus) data smartphone langsung melalui antarmuka[cite: 1].
3. **Pengaturan Kriteria & Bobot Penilaian**:
   - Menyesuaikan tingkat kepentingan (bobot %) untuk berbagai aspek seperti Harga, RAM, Kamera, Baterai, Penyimpanan, dan Performa[cite: 1].
   - Mendukung opsi kriteria *benefit* (semakin tinggi semakin baik) dan *cost* (semakin rendah semakin baik)[cite: 1].
4. **Mesin Rekomendasi Pintar**:
   - Filter berdasarkan *budget* minimal dan maksimal[cite: 1].
   - Pilihan profil cepat (*Preset*): **Gaming**, **Fotografi**, **Produktivitas**, dan **Sehari-hari**[cite: 1].
   - Menampilkan peringkat 3 teratas smartphone terbaik lengkap dengan skor kecocokan persentase[cite: 1].
5. **Perbandingan & Hasil Perhitungan**:
   - Tabel perbandingan berdampingan (*side-by-side*) untuk produk rekomendasi teratas[cite: 1].
   - Rincian skor transparan di halaman Hasil Perhitungan[cite: 1].
   - Fitur cetak/ekspor hasil rekomendasi secara langsung[cite: 1].

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibuat menggunakan pendekatan *frontend-only* yang ringan tanpa memerlukan instalasi *backend* yang rumit:
- **HTML5 & CSS3**[cite: 1]
- **Tailwind CSS** (via CDN untuk styling responsif modern)[cite: 1]
- **JavaScript (ES6+)** (Logika aplikasi, manipulasi DOM, dan sistem perankingan)[cite: 1]
- **Lucide Icons** (Ikon UI modern)[cite: 1]
- **Chart.js** (Visualisasi data dan grafik statistik)[cite: 1]
- **Google Fonts (Plus Jakarta Sans)** (Tipografi utama)[cite: 1]

---

## 🚀 Cara Menjalankan Proyek

Karena proyek ini berbasis web statis, Anda tidak memerlukan server khusus atau instalasi Node.js yang rumit. Ikuti langkah-langkah berikut:

1. **Clone repositori ini** atau unduh file proyek (`index.html` dan aset terkait):
   ```bash
   git clone [https://github.com/username/smartpick.git](https://github.com/username/smartpick.git)
