# Capstone Project Module 2
Nama   : Rivaldo Nugradwiyanto  
Kelas  : JCDSAH-024
## Latar Belakang
Airbnb menjadi salah satu platform akomodasi terbesar di dunia dengan ribuan listing tersedia di setiap kota besar, termasuk Bangkok. Kota ini memiliki karakteristik yang unik karena:
- pusat kota yang padat,
- jaringan transportasi umum yang sangat berpengaruh pada mobilitas wisatawan (BTS, MRT),
- banyaknya destinasi wisata populer seperti Grand Palace dan Chatuchak Market.

Bagi pemilik properti, lokasi merupakan faktor utama yang dipertimbangkan dalam menentukan harga, potensi booking, dan strategi pemasaran listing. Namun, tidak semua pemilik memiliki pemahaman yang jelas mengenai sejauh mana jarak terhadap pusat kota, transportasi umum, dan tempat wisata benar-benar memengaruhi performa listing mereka.

Dengan memahami pengaruh lokasi terhadap performa listing, pemilik dan calon host dapat:
- menetapkan harga yang lebih kompetitif,
- mengoptimalkan strategi listing,
- meningkatkan tingkat hunian,
- dan memaksimalkan pendapatan.

Dataset Airbnb Listings Bangkok memberikan kesempatan untuk menganalisis faktor lokasi dan melihat apakah benar lokasi memberikan dampak signifikan pada performa listing, yang dapat diukur melalui harga, jumlah review, review per bulan, hingga tingkat ketersediaan.

## Dataset yang digunakan
Dataset ini berisi informasi terkait listing dari akomodasi penginapan di kota Bangkok yang terdaftar di Airbnb.
Terdapat 17 kolom di dalam datases Airbnb Listings Bangkok, yaitu:

- Unnamed:0 : index tambahan dataset
- id : id unik tiap listing
- name : nama dari listing tersebut
- host_id : id unik host listing
- host_name : nama dari listing tersebut
- neighbourhood : nama daerah/distrik listing tersebut berada
- latitude : koordinat lintang lokasi listing
- longitude : koordinat bujur lokasi listing
- room_type : tipe kamar listing
- price : harga listing dalam satuan Baht (THB)
- minimum_nights : jumlah minimum malam untuk booking
- number_of_reviews : jumlah review pada listing
- last_review : tanggal review terakhir
- reviews_per_month : average review pada listing
- calculated_host_listings_count : jumlah listing yang dimiliki host tersebut
- availability_365 : jumlah hari available pada listing dalam satu tahun
- number_of_reviews_ltm : jumlah review dalam 12 bulan terakhir

## Proses Analisis yang dilakukan
1. Load Data
2. Data Cleaning (drop kolom, imputasi missing, perbaikan tipe data, koreksi typo)
3. Data Enrichment (perhitungan jarak ke landmark/transportasi/pusat kota)
4. EDA & Statistik Deskriptif
5. Handling Outlier
6. Visualisasi Data
7. Analisis Inferensial

## Kesimpulan
