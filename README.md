# Analisis Data K-Pop dengan Neo4j AuraDB

## 📘 Deskripsi  
Proyek ini menggunakan **Neo4j AuraDB** untuk menganalisis data artis/grup K-Pop (sample dari `kpop.csv`). Tujuannya mengeksplorasi relasi antar artis, agensi, genre, dan tren debut, serta menghasilkan insight berbasis graph database.

---

## 🗂 Dataset  
File utama: **`kpop.csv`**  
Kolom data:  
- **Tipe** (Group / Soloist)  
- **Nama Group / Artis**  
- **Agensi**  
- **Album_Title / Album_Year**  
- **Lagu_Title / Lagu_Year**  
- **Genre**  
- **Tahun Debut**  
- **Fandom**  

---

## ⚙️ Cara Menjalankan

1. Pastikan database **Neo4j / AuraDB** sudah aktif & terkoneksi.  
2. Upload `kpop.csv` ke folder `import/` (atau gunakan URL publik jika di AuraDB).  
3. Jalankan query **DDL** terlebih dahulu untuk membuat struktur (constraint & label).  
4. Jalankan query **DML** untuk memasukkan data artis, agensi, album, genre, dan fandom.  
5. Jalankan query **DML Relationship** untuk menghubungkan antar node.  
6. Jalankan **query analisis** (tersimpan di `analysis.txt`) untuk mendapatkan insight.  
7. Lihat hasil visualisasi di Neo4j Browser, ambil screenshot untuk laporan/presentasi.  

---

📖 Analisis & Fakta Pendukung

Industri K-Pop terus berkembang pesat sejak awal 2000-an. Pada periode 2012–2015 terjadi lonjakan debut artis yang menandai masuknya Generasi 3 K-Pop. Fenomena ini sejalan dengan temuan Nakamura, Lee, & Park (2025) yang menunjukkan adanya lonjakan pendengar global dan ekspansi K-Pop dari genre lokal ke fenomena internasional. Setelah 2019, muncul gelombang debut baru yang menandai Generasi 4, meskipun setelah pandemi 2020 jumlah debut relatif menurun.

Dominasi pasar tetap dikuasai oleh Big 3 agensi, yaitu SM Entertainment, YG Entertainment, dan JYP Entertainment. Laporan industri (PGP Capital, 2023) menegaskan bahwa label besar ini memainkan peran utama dalam mengelola artis dan menentukan arah pasar, sementara studi Cornell University (2025) menambahkan bahwa ketiga agensi ini masih berfungsi sebagai “trendsetter” dalam inovasi konsep K-Pop.

Dari sisi genre, pop, R&B, dan dance-pop muncul sebagai yang paling banyak digunakan oleh artis. Hal ini konsisten dengan laporan Chartmetric (2024) yang menyoroti faktor genre, digital fandom, dan distribusi global sebagai alasan utama popularitas K-Pop. Luminate Data (2024) juga menunjukkan bahwa dominasi streaming global K-Pop terus meningkat, memperkuat posisi genre tersebut di pasar musik internasional.
