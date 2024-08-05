# Capstone-2

Sebuah perusahaan Software-as-a-Service (SaaS) melakukan pemasaran dan penjualan/penyewaan lisensi *software* ke perusahaan/bisnis lain (*customer*) secara *Business-to-Business* (B2B). Dataset yang dihasilkan berupa pemesanan produk yang dilakukan oleh *customer* di setiap *region* yang berbeda dan *sales*, *quantity*, *discount* dan *profit* dari produk. *Customer* terbagi dalam beberapa pendataan berupa ID, tanggal, negara, kota, *region*, *subregion*, *industry*, *segment*, produk, dan kunci lisensi . 

Dataset asli dapat diakses [di sini](https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales).

Terdapat 19 kolom di dalam dataset SaaS-Sales, yaitu:

|No.|Nama Kolom|Tipe Data|Deskripsi|
|-|-|-|-|
|1.|`Row ID`|object| Identifikasi unik untuk setiap transaksi|
|2.|`Order ID`|object|Identifikasi unik untuk setiap pemesanan|
|3.| `Order Date`|object|Tanggal saat pemesanan dilakukan|
|4.| `Date Key`|object|Representasi numerikal untuk `Order Date` (YYYYMMDD)|
|5.| `Contact Name`|object|Nama pelanggan yang melakukan pemesanan|
|6.| `Country`|object|Negara tempat dilakukan pemesanan|
|7.|`City`|object|Kota tempat dilakukan pemesanan|
|8.|`Region`|object|*Region* tempat dilakukan pemesanan|
|9.|`Subregion`|object|*Subregion* tempat dilakukan pemesanan|
|10.| `Customer`|object|Nama bisnis yang melakukan pemesanan|
|11.| `Customer ID`|object|Identifikasi unik untuk setiap `Customer`|
|12.| `Industry`|object|Industri setiap `Customer`|
|13.| `Segment`|object|Segmen setiap `Customer` (SMB, Strategic, Enterprise, dll.).|
|14.| `Product`|object|Produk yang telah dipesan|
|15.| `License`|object|Kunci lisensi setiap `Product`|
|16.| `Sales`|float|Jumlah total penjualan setiap transaksi|
|17.| `Quantity`|int|Jumlah total `Product` setiap transaksi|
|18.| `Discount`|float|Potongan harga setiap transaksi|
|19.| `Profit`|float|Keuntungan yang didapat setiap transaksi|

