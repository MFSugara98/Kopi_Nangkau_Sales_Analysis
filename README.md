#  Coffee Shop Sales Performance Analysis & Product Bundling Strategy (2021–2023)

##  Project Overview
Proyek ini bertujuan untuk menganalisis kinerja penjualan harian toko **Kopi Nangkau** selama periode 3 tahun (2021–2023) berdasarkan 6.041 transaksi harian. Analisis difokuskan pada pembersihan data (*duplicate handling & missing value imputation*), pemetaan performa produk berbasis volume dan pendapatan (*revenue*), serta perumusan strategi bisnis untuk mendorong pertumbuhan produk *pastry* dan ekspansi pelanggan.

---

##  Tech Stack & Tools
* **Programming Language:** Python 3.14
* **Data Processing & Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Development Environment:** Visual Studio Code / Jupyter Notebooks

---

##  Data Cleaning & Preprocessing
Sebelum analisis dilakukan, data mentah (*dummy CSV*) diproses untuk menjaga integritas hasil analisis:
1. **Handling Duplicates:** Mengidentifikasi dan menghapus data ganda (*duplicate rows*) transaksi harian.
2. **Missing Value Treatment:** Penanganan nilai kosong (*missing values*) pada catatan penjualan produk dan atribut transaksi agar perhitungan agregasi presisi.

---

##  Key Findings & Business Insights

### 1. Main Revenue Engine (Milk-Based Coffee)
* **Penyumbang Omset Tertinggi:** Kategori minuman berbasis susu (*milk-based coffee*) menjadi mesin penggerak utama ekonomi Kopi Nangkau.
  * **Latte:** Menyumbang pendapatan tertinggi sebesar **Rp 1.128.724.240**.
  * **Cappuccino:** Menyumbang pendapatan sebesar **Rp 1.016.256.000**.

### 2. High & Consistent Product Volume
* Kategori kopi (*Americano, Cappuccino, Espresso, Latte*) memiliki tingkat permintaan harian yang sangat konsisten, dengan akumulasi volume penjualan masing-masing mencapai kisaran **~39.000 unit** dalam kurun waktu 3 tahun.

### 3. Pastry Performance vs. Coffee Demand
* Produk pendamping (*pastry*) seperti **Donat** (22.379 unit) dan **Croissant** (21.360 unit) mencatatkan volume penjualan hampir separuh dari total volume kopi.
* *Insight:* Mayoritas pelanggan datang ke toko khusus untuk membeli kopi, sementara sebagian kecil menambah pesanan dengan makanan ringan.

### 4. Pricing & Customer Base Elasticity
* Kebijakan kenaikan harga sebesar **2% setiap tahun** terbukti membantu menjaga margin dari dampak inflasi tanpa menyebabkan pelanggan (*existing base*) kabur.
* Namun, volume penjualan harian cenderung stagnan di angka rata-rata **39 unit/hari**, mengindikasikan belum adanya pertumbuhan signifikan pada basis pelanggan baru.

---

##  Actionable Business Recommendations

1. **Strategi Cross-Selling & Breakfast/Tea-Time Bundling:**
   * Buat paket hemat bundling (misalnya *"Americano + Croissant"*) dengan harga sedikit lebih murah dibanding pembelian terpisah.
   * Strategi ini dirancang untuk mendongkrak penjualan *pastry* yang saat ini rata-rata terjual 21 unit/hari agar mendekati volume penjualan kopi (39 unit/hari).
2. **Optimalisasi Margin & Kebijakan Harga:**
   * Pertahankan kebijakan penyesuaian harga tahunan sebesar 2% karena elastisitas harga pelanggan tergolong baik (*low churn*).
3. **Pemasaran Digital & Akuisisi Pelanggan Baru:**
   * Gencarkan kampanye pemasaran di media sosial (*brand awareness & local promo*) untuk menembus batas penyerapan harian (*breakthrough*) dari 39 unit menjadi di atas 40 unit kopi per hari.

---

##  How to Run the Project

1. Clone repositori ini:
   ```bash
   https://github.com/MFSugara98/Kopi_Nangkau_Sales_Analysis.git
