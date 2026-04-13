# Sports-Footwear-Analysis

## Repository Outline
1. README.md - Penjelasan gambaran umum project
2. notebook.ipynb - Notebook yang berisi pengolahan data dengan python
3. sportswear.csv - Dataset yang digunakan  
4. sportswear_clean.csv - Data clean yang digunakan dalam analisis.


## Problem Background
Akhir-akhir ini berolahraga sedang ramai di kalangan masyarakat, khususnya generasi muda yang semakin sadar pentingnya kesehatan demi masa tua nanti. Saat ini olahrga bukan hanya sekedar sebuah olahraga untuk kesehatan semata, tetapi sudah menjadi bagian dari gaya hidup.  
Fenomena ini membuat permintaan terhadap produk sepatu olahraga menjadi semakin meningkat.  
Hal ini juga menyebabkan brand global seperti Adidas, ASICS, New Balance, Nike, Puma, dan Reebok terus bersaing dalam membuat produk yang terbaik dengan variasi harga dan model. Perubahan perilaku konsumen, peningkatan penjualan dari berbagai channel, serta diskon yang berlaku membuat perusahaan harus mengambil keputusan berdasarkan data yang terjadi di pasar. Oleh karena itu, diperlukan analisa yang lebih spesifik untuk menentukan kombinasi produk, channel, dan segmentasi pelanggan yang paling optimal dalam meningkatkan revenue.

## Project Output
Output dari project ini berupa dashboard pada Tableau.

## Data
Sumber data : https://www.kaggle.com/datasets/aliiihussain/sports-footwear-sales-and-consumer-behavior

- order_id – ID unik untuk setiap transaksi penjualan 
- order_date – Tanggal terjadinya penjualan 
- brand – Merek sepatu 
- model_name – Nama/model spesifik sepatu 
- category – Kategori sepatu (Running, Training, Basketball, Lifestyle, Gym) 
- gender – Jenis kelamin target (Pria, Wanita, Unisex) 
- size – Ukuran sepatu 
- color – Warna sepatu 
- base_price_usd – Harga asli sebelum diskon 
- discount_percent – Persentase diskon yang diberikan (%) 
- final_price_usd – Harga setelah diskon 
- units_sold – Jumlah unit yang terjual 
- revenue_usd – Total pendapatan dari transaksi 
- payment_method – Metode pembayaran (Card, Cash, Wallet, Bank Transfer) 
- sales_channel – Saluran penjualan (Online / Retail Store) 
- country – Negara tempat penjualan 
- customer_income_level – Tingkat pendapatan pelanggan (Low / Medium / High) 
- customer_rating – Rata-rata penilaian pelanggan (3.0 hingga 5.0) 

## Method
- Turkey's Rule / IQR -> Menghapus outlier, hal ini dikarenakan ketika nilai skewness > 0.5.  
- Visualisasi Barchart -> Untuk membandingkan besarnya jumlah masing-masing produk.  
- Visualisasi Pie Chart -> Untuk mengetahui perbandingan dalam bentuk persen antar kategori/grup dengan syarat kategori yang dibandingkan tidak banyak.  
- Visualisasi Line Chart -> Untuk mengetahui tren penjualan dalam kurun waktu tertentu.  
- Central Tendency -> Untuk mengetahui persebaran harga produk yang dijual.  
- ANOVA Test -> Untuk menguji hipotesis pengaruh diskon terhadap revenue penjualan.

## Stacks
Programming Language:
- Python

Libraries:
- pandas
- matplotlib
- seaborn
- scipy

Tools:
- Visual Studio Code
- Tableau
- Git & GitHub

## Reference
https://public.tableau.com/app/profile/abdul.hakim.zelfi/viz/Milestone_17726114429960/Dashboard1?publish=yes
