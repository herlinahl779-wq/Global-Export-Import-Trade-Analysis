# 🌍 Global Trade Analytics: Analisis Kinerja Ekspor-Impor Dunia (2010–2021)

**By Herlina** | Data Analyst

[![Tableau Dashboard](https://img.shields.io/badge/Tableau-Dashboard-orange)](https://public.tableau.com/app/profile/herlina.4840/viz/MockupDashboardHerlinaRMT18Millstone2/GlobalTradeAnalyticsStory?publish=yes)

🔗 **Live Dashboard:** [Lihat di Tableau Public](https://public.tableau.com/app/profile/herlina.4840/viz/MockupDashboardHerlinaRMT18Millstone2/GlobalTradeAnalyticsStory?publish=yes)

---

## 📌 Ringkasan Project

Project ini menganalisis data perdagangan internasional (ekspor & impor) dari berbagai negara dan komoditas selama periode **2010–2021**, untuk mengidentifikasi negara dan komoditas dengan kontribusi terbesar terhadap nilai perdagangan global, serta faktor-faktor yang memengaruhi neraca perdagangan (trade balance).

Hasil analisis disajikan dalam bentuk **dashboard interaktif (Tableau)** dan **notebook analisis statistik (Python)**, sehingga dapat digunakan sebagai bahan pertimbangan pengambilan keputusan di bidang perdagangan.

## 🎯 Tujuan Analisis

- Mengidentifikasi komoditas dengan nilai ekspor terbesar
- Mengidentifikasi negara dengan total nilai perdagangan tertinggi
- Mengidentifikasi negara dengan surplus perdagangan terbesar
- Melihat tren nilai perdagangan internasional dari tahun ke tahun
- Menguji perbedaan rata-rata trade balance antar negara secara statistik
- Menguji hubungan antara nilai ekspor dan total perdagangan secara statistik

## 🛠️ Tools & Teknik yang Digunakan

- **Python** (Pandas, NumPy) — data cleaning & preprocessing
- **Matplotlib & Seaborn** — data visualization
- **SciPy** — statistik inferensial (independent t-test / Welch's t-test, Pearson correlation)
- **Tableau** — dashboard visualisasi interaktif

## 🔍 Temuan Utama

- **Batu mulia** menjadi komoditas dengan kontribusi ekspor terbesar.
- **Belgia** merupakan salah satu mitra dagang utama dalam periode analisis.
- **Bangladesh** tercatat sebagai negara dengan surplus perdagangan terbesar.
- Nilai perdagangan global mencapai puncaknya pada **2011**, dan sempat menurun tajam pada **2020** akibat pandemi COVID-19 — menunjukkan sensitivitas perdagangan terhadap guncangan ekonomi global.
- Secara statistik, tidak ditemukan perbedaan rata-rata trade balance yang signifikan antara Bangladesh PR dan Brunei (uji Welch's t-test, p-value = 0.245).
- Terdapat hubungan positif yang kuat dan signifikan secara statistik antara nilai ekspor dan total perdagangan (korelasi Pearson = 0.876, p-value < 0.001).

## 📂 Struktur Project

```
├── P1M2_Herlina.ipynb   # Notebook analisis (data cleaning, statistik, visualisasi)
└── README.md            # Dokumentasi project
```

## 📊 Alur Analisis

1. **Data Loading** — memuat dan eksplorasi data ekspor-impor per negara & komoditas
2. **Data Cleaning** — pembersihan dan penyiapan data untuk analisis
3. **Exploratory & Statistical Analysis** — visualisasi data serta statistik deskriptif dan inferensial
4. **Dashboard Building** — menyusun dashboard interaktif di Tableau
5. **Kesimpulan & Rekomendasi** — insight yang dapat digunakan untuk pengambilan keputusan perdagangan

## 📈 Dashboard Preview

Dashboard interaktif dapat diakses langsung di Tableau Public:
👉 [**Global Trade Analytics Story**](https://public.tableau.com/app/profile/herlina.4840/viz/MockupDashboardHerlinaRMT18Millstone2/GlobalTradeAnalyticsStory?publish=yes)

---

*Project ini merupakan bagian dari program Hacktiv8 Comprehensive Data Analytics — Phase 1.*
