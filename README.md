**Analisis Sentimen dengan Seleksi Fitur Information Gain**

Repositori ini berisi implementasi analisis sentimen pada data ulasan dengan menggunakan algoritma Naïve Bayes dan metode seleksi fitur Information Gain.
Alur pengerjaan dimulai dari proses scraping data hingga pembuatan model klasifikasi.

📌 Alur Proses
**Scraping Data Ulasan**
Dilakukan menggunakan file main.py
Mengambil data ulasan pengguna dari sumber tertentu disini data diambil dari Google Play Store

Labeling Otomatis
Memberikan label sentimen pada data ulasan (positif/negatif/neutral) secara otomatis berdasarkan kata kunci atau aturan tertentu.

**Preprocessing Data**
Tahapan pembersihan teks yang meliputi:
Case folding
Tokenizing
Stopword removal
Stemming

Seleksi Fitur dengan Information Gain
Menghitung bobot setiap fitur/term
Memilih fitur terbaik yang berkontribusi pada klasifikasi

**Pemodelan dengan Naïve Bayes**
Data hasil seleksi fitur digunakan untuk membangun model klasifikasi
Evaluasi dilakukan menggunakan metrik: akurasi, precision, recall, dan f1-score

⚙️ Teknologi yang Digunakan

Python 3.12.0

Library:
pandas
scikit-learn
nltk
sastrawi
google-play-scraper (opsional, jika scraping dari Play Store)
