```markdown
# Monitor Gempa Indonesia

Dashboard interaktif untuk memvisualisasikan 15 kejadian gempa bumi berkekuatan M5.0 ke atas di Indonesia berdasarkan data resmi BMKG. Project ini dibuat sebagai tugas visualisasi data dengan tujuan menyajikan informasi gempa dalam bentuk grafik yang lebih mudah dipahami dibandingkan data mentah.

🌐 **Live Demo**  
https://dashboard-gempa-indonesia.vercel.app/

---

## Fitur Dashboard

Dashboard menampilkan empat jenis visualisasi yang saling melengkapi, yaitu:

- **Scatter/Bubble Map** untuk menunjukkan persebaran lokasi gempa berdasarkan koordinat lintang dan bujur. Ukuran bubble merepresentasikan besar magnitudo gempa.
- **Line Chart** yang memperlihatkan perubahan magnitudo secara kronologis pada rentang data yang digunakan, sehingga pola maupun kejadian dengan magnitudo tinggi lebih mudah dikenali.
- **Horizontal Bar Chart** yang membandingkan jumlah kejadian gempa pada setiap wilayah pemantauan BMKG.
- **Doughnut Chart** untuk menampilkan proporsi kategori kedalaman gempa, yaitu dangkal, menengah, dan dalam.

Selain visualisasi utama, dashboard juga dilengkapi dengan beberapa fitur pendukung, seperti:

- Tooltip interaktif pada setiap chart untuk menampilkan informasi detail saat kursor diarahkan ke data.
- Tabel data yang dapat diurutkan berdasarkan kolom yang dipilih.
- Animasi pada grafik serta efek *count-up* pada indikator utama (KPI) untuk meningkatkan pengalaman pengguna.

---

## Sumber Data

Dataset yang digunakan berasal dari **Data Gempabumi Terbuka BMKG** dengan kategori **Gempabumi M5.0+**.

- **Penyedia:** Badan Meteorologi, Klimatologi, dan Geofisika (BMKG)
- **Sumber Data:** https://data.bmkg.go.id/DataMKG/TEWS/gempaterkini.xml
- **Jumlah Data:** 15 kejadian gempa
- **Tanggal Akses:** 21 Juni 2026

---

## Menjalankan Project

Project ini merupakan website statis sehingga tidak memerlukan proses instalasi dependency maupun build.

Cukup buka file `index.html` menggunakan browser, atau jalankan melalui **Live Server** di Visual Studio Code.

---

## Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript (Vanilla)
- Chart.js v4.4.4 (dibundle secara lokal)
- Vercel (Deployment)

---

## Anggota Kelompok

| NIM | Nama |
|------|------|
| 103012300455 | Ziyad Fathir Al Biaroza |
| 103012300399 | Muhammad Ridwan Arrayyan |
| 103012300107 | Zweta Lathifah Kus Aliyyah |
| 103012300140 | Farazahwa J Michelle |
```
