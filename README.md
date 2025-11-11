# 🏠 Analisis Data Kos-Kosan di Jakarta Pusat  
### *End-to-End Data Analytics Project (Scraping → Cleaning → Visualization → Insight)*

---

## 🧭 Latar Belakang Cerita

Proyek ini berawal dari skenario sederhana namun nyata:  
> *Seseorang baru saja mendapat pekerjaan di wilayah Jakarta Pusat, namun belum memiliki tempat tinggal sementara atau kos yang sesuai.*

Di tengah semangat memulai karier baru, ia dihadapkan pada tantangan klasik di kota besar — **menemukan kos yang strategis, nyaman, dan terjangkau**.  
Informasi tentang kos-kosan tersebar di berbagai situs dengan format yang tidak seragam, harga yang bervariasi, serta sulit dibandingkan antarwilayah.

Dari permasalahan itu, muncul ide untuk melakukan **analisis data kos-kosan di Jakarta Pusat secara end-to-end**, mulai dari pengumpulan data menggunakan teknik *web scraping*, analisis eksploratif dengan Python, hingga visualisasi interaktif menggunakan Tableau.  
Proyek ini bertujuan membantu calon penyewa atau pekerja baru memahami kondisi pasar kos di Jakarta Pusat — berdasarkan **harga, lokasi, dan fasilitas** — secara lebih efisien dan berbasis data.

---

## 🎯 Tujuan Proyek

1. Mengumpulkan data kos-kosan di Jakarta Pusat melalui **web scraping**.  
2. Membersihkan dan menstandarkan data agar siap dianalisis.  
3. Melakukan **Exploratory Data Analysis (EDA)** untuk memahami distribusi harga dan fasilitas.  
4. Membangun **dashboard interaktif Tableau** yang menampilkan:
   - Sebaran harga kos per wilayah.  
   - Perbandingan harga berdasarkan fasilitas utama.  
   - Daftar wilayah dengan harga kos termurah dan termahal.  

---

## 🧩 Alur Pengerjaan (End-to-End)

| Tahap | Deskripsi | Tools / Library |
|--------|------------|----------------|
| 1️⃣ **Data Collection (Scraping)** | Mengambil data kos dari situs properti online menggunakan `requests` dan `BeautifulSoup`. | Python |
| 2️⃣ **Data Cleaning** | Menghapus duplikasi, menangani missing value, konversi kolom harga ke numerik, dan standarisasi teks. | Pandas |
| 3️⃣ **EDA (Exploratory Data Analysis)** | Analisis distribusi harga, lokasi, dan frekuensi fasilitas. Membuat visualisasi awal dengan Matplotlib & Seaborn. | Pandas, Matplotlib, Seaborn |
| 4️⃣ **Data Export** | Menyimpan dataset bersih ke format `.csv` agar bisa diimpor ke Tableau. | Pandas |
| 5️⃣ **Visualization (Tableau)** | Membuat dashboard interaktif menampilkan peta sebaran, distribusi harga, dan proporsi fasilitas. | Tableau Public |
| 6️⃣ **Insight & Recommendation** | Mengambil kesimpulan dan rekomendasi berdasarkan hasil visualisasi. | Tableau, Markdown |

---

## 📊 Visualisasi Dashboard Tableau

**Dashboard Tableau:**  
[🔗 Lihat Dashboard di Tableau Public](#)  
(*Tambahkan link Tableau Public kamu di sini setelah upload*)

**Komponen Dashboard:**
- 🗺️ **Map Chart:** Sebaran harga kos per kelurahan di Jakarta Pusat.  
- 📊 **Bar Chart:** 10 wilayah dengan harga rata-rata tertinggi & terendah.  
- 🍩 **Donut Chart:** Proporsi fasilitas populer (AC, WiFi, Kamar Mandi Dalam, Parkir).  
- 📈 **Histogram:** Distribusi harga kos (kisaran bawah – menengah – premium).  

---

## 💡 Hasil & Insight Utama

- Rata-rata harga kos di Jakarta Pusat berada di kisaran **Rp X – Rp Y per bulan**.  
- Wilayah dengan harga tertinggi: **Menteng dan Tanah Abang**, dengan rata-rata di atas **Rp Z juta/bulan**.  
- Wilayah paling terjangkau: **Cempaka Baru dan Kemayoran**, dengan rata-rata di bawah **Rp A juta/bulan**.  
- Fasilitas seperti **AC** dan **kamar mandi dalam** muncul lebih dari **60%** dari total listing, menjadi indikator utama kos premium.  
- Kos dengan **lokasi dekat area bisnis atau transportasi umum** memiliki harga 25–30% lebih tinggi dibanding daerah residensial.  

(*Isi angka setelah hasil analisis kamu di Pandas/Tableau*)

---

## 🧠 Tools & Teknologi

| Tahap | Teknologi yang Digunakan |
|--------|--------------------------|
| Web Scraping | Python (`requests`, `BeautifulSoup`) |
| Data Cleaning & EDA | Pandas, Matplotlib, Seaborn |
| Visualization | Tableau Public |
| Documentation | Markdown, GitHub |

---

## 📁 Struktur Folder Project
