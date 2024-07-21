# Overview

Dalam suatu perusahaan mengukur performa bisnis sangatlah penting untuk melacak, memantau, dan menilai keberhasilan atau kegagalan dari berbagai proses bisnis. Oleh karena itu, dalam paper ini akan menganalisa performa bisnis untuk sebuah perusahan eCommerce,  dengan memperhitungkan beberapa metrik bisnis yaitu pertumbuhan pelanggan, kualitas produk, dan tipe pembayaran.

# Insights

## ERD Diagram

![EDR Diagram](https://github.com/M-Fatoni/Mini-Project---Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/img/ecommerceDB.png)

## 1. Annual Customer Activity Growth Analysis

![Total_New_Cust](https://github.com/M-Fatoni/Mini-Project---Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/img/total_new_cust.JPG)

![MAU](https://github.com/M-Fatoni/Mini-Project---Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/img/MAU.JPG)

Secara keseluruhan, data ini menunjukkan bahwa platform eCommerce tersebut berkembang dengan baik dan berhasil meningkatkan basis pengguna aktif bulanan dan menarik customer baru, dengan peningkatan yang signifikan setiap tahunnya.

![num_repeat_cust](https://github.com/M-Fatoni/Mini-Project---Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/img/num_repeat_cust.JPG)

Secara keseluruhan, data ini menunjukkan keberhasilan platform dalam meningkatkan retensi pelanggan dari tahun 2016 ke 2017, meskipun ada sedikit tantangan di tahun 2018 yang perlu diatasi.

![num_orders](https://github.com/M-Fatoni/Mini-Project---Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/img/avg_num_of_orders_per_cust.JPG)

Secara keseluruhan, rata-rata jumlah pesanan per pelanggan cenderung stabil dalam tiga tahun terakhir, dengan fluktuasi kecil antara tahun-tahun tersebut.

## 2. Annual Product Category Quality Analysis

![total_rev_per_year](https://github.com/M-Fatoni/Mini-Project---Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/img/total_reven_per_year.JPG)

Tren ini menunjukkan pertumbuhan yang positif dari tahun ke tahun, yang dapat mengindikasikan peningkatan aktivitas penjualan dan potensi pertumbuhan perusahaan di masa mendatang.

![total_cancel_order_per_year](https://github.com/M-Fatoni/Mini-Project---Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/img/total_cancel_orders_per_year.JPG)

Tren ini menunjukkan adanya peningkatan yang signifikan dalam jumlah pesanan yang dibatalkan dari tahun ke tahun, yang dapat menjadi perhatian bagi perusahaan untuk memahami alasan di balik pembatalan pesanan dan mencari solusi untuk mengurangi jumlah pembatalan di masa depan.

![total_cancel_order_per_year_by_cat](https://github.com/M-Fatoni/Mini-Project---Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/img/total_cancel_orders_by_category.JPG)

- Dari tahun 2016 ke 2018, terlihat ada peningkatan dalam jumlah total pembatalan pesanan, dari 3 pembatalan pada 2016 hingga 27 pembatalan pada 2018. 

- Setiap tahun, kategori produk yang paling banyak dibatalkan berubah, menunjukkan bahwa masalah yang menyebabkan pembatalan tidak terbatas pada satu kategori produk saja tetapi menyebar ke berbagai kategori.

## 3. Analysis of Annual Payment Type Usage

![payment_type_usage](https://github.com/M-Fatoni/Mini-Project---Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/img/payment_type.JPG)

Kartu kredit (credit_card) menonjol sebagai tipe pembayaran yang paling umum digunakan, dengan jumlah penggunaan mencapai 76.795 pada periode seluruhnya. Sementara itu, boleto dan voucher merupakan alternatif lain yang cukup populer dengan jumlah penggunaan berturut-turut sebesar 19.784 dan 5.775.

