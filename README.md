# Projek-Semester-1
- Nama: Athayya El Maury Awanputri
- NIM: 552012610005
## Deskripsi Projek
Projek yang akan saya kerjakan adalah membangun pipeline ETL menggunakan dataset coffe sales dari kaggle. Projek ini bertujuan untuk mengubah data penjualan mentah coffe sales menjadi data bersih yang siap dianalisis lebih lanjut. Data penjualan akan diekstrak dari file, dibersihkan, dan ditransformasikan menggunakan phyton, kemudian dimuat ke PostGreSQL untuk dianalisis lebih lanjut menggunakan SQL.
## Tujuan Projek
1. Menganalisis Total Penjualan per Bulan
2. Jenis Kopi Terlaris
3. Metode Transaksi
4. Jam Penjualan paling ramai
5. Hari Penjualan paling ramai 
## Tools yang akan digunakan
-Phyton
-PostGreSQL
-DBeaver
-Git
-Github
## Langkah-Langkah
1. Membuat repository baru dengan nama coffe sales dataset.
2. Mengunduh dataset dari kaggle.
3. Membuat struktur folder proyek (data, scripts, sql, diagrams).
4. Menyimpan dataset CSV ke folder `data/raw'.
5. Membuat database PostGreSQL.
6. Membuat tabel coffe_sales untuk data yang telah dibersihkan.
7. Membuat script extract.py untuk membaca file CSV.
8. Membuat script transform.py untuk membersihkan data, menghapus duplikat, memperbaiki format tanggal, dan memvalidasi nilai transaksi.
9. Membuat script load.py untuk memuat data yang sudah bersih ke PostGreSQL.
10. Membuat file SQL untuk melakukan analisis data.
11. Membuat diagram arsitektur pipeline.
12. Mengunggah seluruh file proyek ke GitHub.
## Alur Pipeline
Coffe Sales ==> Phyton Extract ==> Phyton Transform ==> PostGreSQL Load ==> SQL Analysis
## Sumber Dataset
https://www.kaggle.com/datasets/anassarfraz13/coffee-sales-dataset?resource=download
