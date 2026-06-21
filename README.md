# Monitor Gempa Indonesia

Dashboard interaktif untuk memvisualisasikan 15 kejadian gempa bumi berkekuatan M5.0 ke atas di Indonesia berdasarkan data resmi BMKG. Project ini dibuat sebagai tugas visualisasi data dengan tujuan menyajikan informasi gempa dalam bentuk grafik yang lebih mudah dipahami dibandingkan data mentah.

🌐 **Live Demo:** https://dashboard-gempa-indonesia.vercel.app/

---

## 📊 Fitur Dashboard

Dashboard terdiri dari empat visualisasi utama:

- **Scatter/Bubble Map** untuk menampilkan persebaran lokasi gempa berdasarkan koordinat lintang dan bujur. Ukuran bubble merepresentasikan besar magnitudo gempa.
- **Line Chart** untuk memperlihatkan perubahan magnitudo secara kronologis sehingga tren dan anomali lebih mudah diamati.
- **Horizontal Bar Chart** untuk membandingkan jumlah kejadian gempa pada setiap wilayah pemantauan BMKG.
- **Doughnut Chart** untuk menampilkan proporsi kategori kedalaman gempa, yaitu dangkal, menengah, dan dalam.

Selain visualisasi utama, dashboard juga menyediakan:

- Tooltip interaktif pada setiap chart.
- Tabel data yang dapat diurutkan berdasarkan kolom.
- Animasi grafik serta efek *count-up* pada indikator utama.

---

## Sumber Data

Dataset yang digunakan berasal dari **Data Gempabumi Terbuka BMKG (M5.0+)**.

- **Penyedia:** Badan Meteorologi, Klimatologi, dan Geofisika (BMKG)
- **Sumber:** https://data.bmkg.go.id/DataMKG/TEWS/gempaterkini.xml
- **Jumlah Data:** 15 kejadian gempa
- **Tanggal Akses:** 21 Juni 2026

---

## Menjalankan Project

Project ini merupakan website statis sehingga tidak memerlukan proses instalasi dependency maupun build.

1. Clone repository.
2. Buka folder project menggunakan Visual Studio Code.
3. Jalankan dengan **Live Server**, atau buka file `index.html` langsung melalui browser.

---

## Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript (Vanilla)
- Chart.js v4.4.4
- Vercel

---

## Anggota Kelompok

| NIM | Nama |
|:---|:-----|
| 103012300455 | Ziyad Fathir Al Biaroza |
| 103012300399 | Muhammad Ridwan Arrayyan |
| 103012300107 | Zweta Lathifah Kus Aliyyah |
| 103012300140 | Farazahwa J Michelle |
