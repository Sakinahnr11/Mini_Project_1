# Analyzing eCommerce Business Performance with SQL

## **Latar belakang**

Dalam sebuah perusahaan, mengukur kinerja bisnis sangat penting untuk melacak, memantau, dan menilai keberhasilan atau kegagalan berbagai proses bisnis. Oleh karena itu, proyek mini ini akan menganalisis kinerja bisnis untuk perusahaan e-Commerce, dengan mempertimbangkan beberapa metrik bisnis, yaitu pertumbuhan pelanggan, kualitas produk, dan jenis pembayaran.

## **Objektif**

-   Menganalisis beberapa metrik terkait aktivitas pelanggan, seperti jumlah pelanggan aktif, jumlah pelanggan baru, jumlah pelanggan yang melakukan repeat order, dan rata-rata transaksi yang dilakukan pelanggan setiap tahunnya.
-   Menganalisis kualitas produk di eCommerce dapat memberikan keputusan untuk mengembangkan bisnis yang lebih baik. Jelajahi kinerja setiap kategori produk yang ada dan bagaimana hubungannya dengan pendapatan perusahaan.
-   Menganalisis kinerja jenis pembayaran yang ada dapat memberikan wawasan yang lebih baik dalam menciptakan kemitraan strategis dengan penyedia layanan pembayaran. Jelajahi jenis pembayaran yang tersedia dan lihat tren yang berubah selama beberapa tahun terakhir.

## Alat

Saya telah menggunakan berbagai alat pada proyek ini. Karena tujuan proyek ini adalah menganalisis dengan SQL, maka saya menggunakan **postgreSQL**. Kemudian untuk melakukan visualisasi data, saya menggunakan **Google Looker Studio.**

## Isi

## Analisis Data

### Analisis Pertumbuhan Aktivitas Pelanggan Tahunan

Dari tahun 2016 hingga 2018, bisnis mengalami pertumbuhan dalam Monthly Active User (MAU), jumlah pelanggan baru, dan pelanggan yang melakukan repeat order. Namun, ada beberapa perubahan dalam tren tersebut, terutama pada tahun 2018 di mana beberapa metrik mengalami penurunan atau pertumbuhan yang lebih lambat. Analisis ini dapat memberikan wawasan kepada bisnis tentang kinerja dan tren pertumbuhan pelanggan, yang dapat digunakan untuk menginformasikan strategi pemasaran dan upaya mempertahankan pelanggan di masa mendatang.

### Analisis Kualitas Kategori Produk Tahunan

**1. Total Revenue dari Tahun 2016 ke 2018 Mengalami Kenaikan yang Cukup Signifikan Setiap Tahunnya:**

Kenaikan yang terjadi setiap tahun menunjukkan adanya peningkatan penjualan atau mungkin peningkatan harga produk/jasa yang ditawarkan.

**2. Jumlah Cancel Order yang Paling Tinggi Pada Tahun 2018 dan 2017:**

Tingginya jumlah cancel order pada tahun 2018 dan 2017 dapat mengindikasikan adanya masalah dengan kualitas produk, pelayanan pelanggan, atau proses pengiriman yang menyebabkan pelanggan membatalkan pesanan. Hal ini dapat mengindikasikan adanya ketidakpuasan pelanggan terhadap produk atau layanan yang diberikan.

**3. Top Kategori Produk yang Mengalami Cancel Order Terbanyak Per Tahun:**
- Pada tahun 2018, produk kategori Health Beauty memiliki jumlah cancel order terbanyak
- Pada tahun 2017, produk kategori Sport Leisure memiliki jumlah cancel order yang tinggi.

**4. Top Kategori yang Menghasilkan Revenue Terbesar Per Tahun:** 

Pada tahun 2018, produk kategori health beauty menghasilkan revenue terbesar. Hal ini menunjukkan bahwa kategori ini sangat populer dan diminati oleh pelanggan pada tahun tersebut.

### Analisis Penggunaan Jenis Pembayaran Tahunan

**1. Jumlah penggunaan tipe pembayaran paling tinggi pada tahun 2016-2018 adalah Credit Card:**

Tingginya penggunaan credit card sebagai tipe pembayaran utama menunjukkan adanya preferensi pelanggan untuk melakukan pembayaran menggunakan kartu kredit. Penggunaan credit card biasanya dianggap sebagai metode pembayaran yang cepat, mudah, dan aman, dan hal ini bisa menjadi indikasi bahwa banyak pelanggan yang memiliki atau mempercayai kartu kredit.

**2. Tipe pembayaran kedua yang paling banyak digunakan adalah Boleto:**

Boleto adalah metode pembayaran yang dapat mencetak slip pembayaran dan membayar di bank atau gerai tertentu. Tingginya penggunaan boleto menunjukkan bahwa metode ini populer di antara pelanggan, mungkin karena kenyamanan dan fleksibilitasnya.

**3. Tipe pembayaran yang paling tidak diminati adalah “Not Defined”:**

Kategori "not defined" merujuk pada transaksi pembayaran yang tidak jelas atau tidak terdefinisi dengan jelas sebagai salah satu tipe pembayaran yang telah ditentukan. Hal ini bisa terjadi karena data yang kurang lengkap atau kesalahan dalam pelaporan.
