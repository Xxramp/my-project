📌 Deskripsi Proyek
Proyek ini merupakan implementasi alur kerja seorang Data Engineer dalam mengumpulkan, membersihkan, dan menganalisis data mobil 
bekas dari situs Mudi.co.id melalui teknik web scraping. Tujuannya adalah membangun pipeline data yang dapat digunakan untuk 
analisis harga, tren mobil populer, dan distribusi mobil berdasarkan lokasi atau merek.
Teknologi yang Digunakan
Python 3.x

requests, BeautifulSoup – Web Scraping

pandas, numpy – Data Cleaning & Processing

matplotlib, seaborn – Visualisasi Data

Jupyter Notebook – Eksplorasi & dokumentasi

📥 Data Collection (Scraping)
Data dikumpulkan dari website Mudi menggunakan BeautifulSoup dan disimpan dalam format CSV (raw_data.csv). Informasi yang diambil meliputi:

Nama mobil

Tahun

Harga

Kilometer

Lokasi

Transmisi

🧹 Data Cleaning
Langkah-langkah yang dilakukan untuk membersihkan data:

Menghapus duplikasi

Menghilangkan simbol/karakter tidak perlu (Rp, km, dll)

Konversi tipe data (str → int/float)

Menangani missing values

Output akhir: cleaned_data.csv

📊 Data Visualization
Setelah data bersih, dilakukan analisis visual untuk menjawab pertanyaan seperti:

Distribusi harga mobil

Brand paling populer

Kota dengan listing terbanyak

Hubungan tahun dengan harga
