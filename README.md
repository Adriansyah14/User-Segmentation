# USER SEGMENTATION

Variabel pada dataset:
- order_id : kode unik pemesanan
- Product_code : kode pada produk
- product_name : nama produk
- quantity : jumlah produk pada tiap pesanan
- order_date : tanggal pemesanan
- price : harga produk
- customer_id : kode unik pelanggan

## Pre-Processing
Pada tahap ini saya melakukan pembersihan data yaitu penghapusan nilai null, penghapusan outlier, transformasi data, dan pembuatan kolom baru.

## Analisis Hasil
- Segment Hibernating terdapat banyak pengguna yaitu 1066 (27%), diikuti segment Champion 550 (14.1%) dan segment Loyal Customers 546 (14.0%)
- Untuk segment Loyal Customers perlu dibuat program khusus yang fokus pada urgensi bertransaksi agar pengguna pada segment ini kembali bertransaksi dalam waktu dekat sehingga dapat naik ke segment Champion
- Untuk segment Potential Loyalists perlu dibuat program khusus yang fokus pada jumlah transaksi agar pengguna pada segment ini lebih sering melakukan transaksi sehingga dapat naik ke segmen Champion
- Untuk segment Hibernating perlu dibuat program khusus agar pengguna pada segment ini kembali bertransaksi sehingga bisa naik ke segment New Customers atau bahkan Potential Loyalistis
