# Data-Driven Value Creation: Superstore Sales & Profitability Analysis

Proyek ini adalah analisis data *end-to-end* yang berfokus pada evaluasi kinerja penjualan dan tingkat profitabilitas dari dataset Superstore. Analisis ini disusun menggunakan Python untuk memberikan *actionable insights* yang dapat mendukung keputusan strategis manajemen, khususnya dalam optimasi stok dan kebijakan harga.

## Tujuan Analisis (Business Questions)
Analisis ini dibangun menggunakan pendekatan SMART untuk menjawab dua tantangan bisnis utama:
1. **Evaluasi Tren Musiman:** Bagaimana pergerakan tren *total sales* bulanan selama 4 tahun terakhir, dan apakah terdapat pola lonjakan pesanan yang konsisten pada kuartal tertentu?
2. **Evaluasi Profitabilitas:** Dari seluruh sub-kategori produk, produk mana yang menjadi penyumbang *profit* tertinggi, dan produk mana yang secara konsisten membakar modal perusahaan (*negative profit*)?

## Tech Stack & Pendekatan
* **Bahasa Pemrograman:** Python (via Google Colab)
* **Data Manipulation:** `pandas`, `numpy` (menggunakan metode *Vectorization* untuk efisiensi komputasi).
* **Data Visualization:** `matplotlib`, `seaborn` (menerapkan prinsip *Data-Ink Ratio* untuk visualisasi tingkat eksekutif).

## Temuan Utama (Key Insights)
Berdasarkan *Exploratory Data Analysis* (EDA) yang dilakukan, ditemukan beberapa wawasan menarik:
* **Pola Musiman (Seasonality):** Kinerja *sales* perusahaan memiliki tren pergerakan musiman yang sangat kuat. Puncak pesanan selalu terjadi di **Kuartal 4 (Q4)**, khususnya di bulan November.
* **Paradoks Profitabilitas:** Produk bervolume tinggi tidak selalu menguntungkan. Kategori *Copiers* dan *Phones* terbukti menjadi tulang punggung profitabilitas. Sebaliknya, kategori *Tables* dan *Bookcases* secara konsisten mencatatkan kerugian kumulatif terbesar bagi perusahaan.

## Rekomendasi Tindakan (Action Plan)
1. **Supply Chain:** Manajemen logistik perlu mengamankan alokasi stok maksimal untuk lini *Technology* pada awal Kuartal 3 guna menangkap lonjakan pasar di akhir tahun.
2. **Pricing Strategy:** Disarankan untuk segera melakukan audit biaya dan membekukan program diskon promosi pada lini *Tables* dan *Bookcases* untuk menambal kebocoran *profit*.
