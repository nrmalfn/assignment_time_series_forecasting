# Time Series Forecasting Assignment

## Deskripsi

Tugas ini adalah tentang menerapkan metode peramalan time series pada kasus bisnis. Anda akan menganalisis data transaksi e-commerce harian dan membuat peramalan untuk menyusun strategi bisnis di masa depan.

## Tujuan

1.  Mampu melakukan pengolahan dan analisis data untuk keperluan forecasting menggunakan model time series.
2.  Mampu membuat dan menyeleksi model terbaik untuk melakukan forecasting.

## Data

Data yang digunakan untuk analisis dapat diakses melalui [link](link). Dataset ini memiliki metadata sebagai berikut:

*   **'Row ID'**: Nomor Urut.
*   **'Order ID'**: ID pesanan.
*   **'Order Date'**: Tanggal pesanan dibuat.
*   **'Ship Date'**: Tanggal pesanan dikirim.
*   **'Ship Mode'**: Moda pengiriman.
*   **'Customer ID'**: ID pelanggan.
*   **'Customer Name'**: Nama Pelanggan.
*   **'Segment'**: Segmen pelanggan.
*   **'Country'**: Negara (hanya data AS).
*   **'City'**: Kota di AS.
*   **'State'**: Negara bagian di AS.
*   **'Postal Code'**: Kode pos.
*   **'Region'**: Wilayah.
*   **'Product ID'**: ID Produk.
*   **'Category'**: Kategori produk.
*   **'Sub-Category'**: Sub-Kategori produk.
*   **'Product Name'**: Nama produk.
*   **'Sales'**: Harga Jual produk.
*   **'Quantity'**: Jumlah produk yang tersedia.
*   **'Discount'**: Diskon produk.
*   **'Profit'**: Keuntungan produk.

## Soal

1.  Hitung total *revenue*, jumlah *order*, dan jumlah barang yang terjual sepanjang tahun 2019. Hitung juga rata-rata jumlah barang yang dibeli per transaksi dan rata-rata *spending* per transaksi.

2.  Hitung jumlah *order* dan GMV (*Gross Merchandise Value*) dengan rentang waktu berikut:

    *   Harian
    *   Mingguan
    *   Bulanan

    Catatan: GMV dihitung berdasarkan total *spending* yang dilakukan *customer* dengan memperhitungkan semua biaya dan diskon yang dibayarkan *customer*.

3.  Identifikasi top 10 produk yang membawa *revenue* terbesar dalam 3 bulan terakhir dan produk apa saja yang bisa di-*bundling* berdasarkan hasil analisis untuk meningkatkan penjualan.

4.  Identifikasi top 5 kota yang memiliki *order* terbanyak dan 5 kota yang memiliki total dan rata-rata *spending* terbesar.

5.  Analisa pada rentang jam berapa penjualan terjadi secara aktif (*rush hour*) untuk membantu tim *marketing* merancang strategi.

6.  Buatlah model *forecasting* untuk memprediksi jumlah *visitor* dan jumlah transaksi untuk 1 bulan kedepan dengan data harian. Anda diharuskan membuat setidaknya 2 model untuk selanjutnya diambil model terbaik berdasarkan MAPE terkecil. Berikan rekomendasi apa yang perlu dilakukan tim bisnis berdasarkan hasil *forecasting* dan analisis Anda.

## Tools

*   Google Colab
*   Github

## Pengumpulan

*   Dikumpulkan dalam bentuk *link* Google Colab dan *link* Github secara individu di LMS.
*   Deadline: Maksimal H+7 Kelas (Pukul 23.30 WIB)

## Indikator Penilaian

| No. | Aspek Penilaian | Parameter | Bobot Maksimal |
| --- | --------------- | --------- | -------------- |
| 1   | Soal 1          |           | 10             |
| 2   | Soal 2          |           | 10             |
| 3   | Soal 3          |           | 10             |
| 4   | Soal 4          |           | 15             |
| 5   | Soal 5          |           | 15             |
| 6   | Soal 6          |           | 40             |