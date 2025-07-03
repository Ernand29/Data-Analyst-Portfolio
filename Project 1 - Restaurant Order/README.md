# SQL-Portofolio

[Read this in English](./README_ENG.md)

---

## 📝 Ringkasan Proyek

Proyek ini bertujuan untuk menganalisis data operasional sebuah restoran menggunakan SQL. Analisis mencakup eksplorasi menu, pola pemesanan pelanggan, dan performa penjualan secara keseluruhan. Dengan menggunakan serangkaian query SQL, saya menggali data untuk menjawab pertanyaan-pertanyaan bisnis kunci dan memberikan wawasan yang dapat ditindaklanjuti untuk meningkatkan strategi menu dan operasional restoran.

---

## Data Source

The dataset consists of two main tables:
* **`menu_items`**: Berisi informasi tentang setiap item menu, termasuk nama, kategori, dan harganya.
* **`order_details`**: Berisi data transaksional, termasuk ID pesanan, waktu pemesanan, dan item menu spesifik yang termasuk dalam setiap pesanan.

### Entity Relationship Diagram (ERD)
![ERD](https://github.com/user-attachments/assets/112eac84-7f03-4d06-a074-ced6c70f6561)

---

## Tools yang Digunakan
* **SQL (MySQL Workbench)**: Untuk kueri, analisis, dan manipulasi data.

---

## ⚙️ Proses Analisis

Analisis dilakukan dengan menulis serangkaian kueri SQL untuk menjawab pertanyaan bisnis yang spesifik. Proses ini disusun menjadi tiga bagian utama:

* **Analisis Menu**: Memahami komposisi, harga, dan kategori dari semua item yang ada di menu.
* **Analisis Pesanan**: Menganalisis volume dan tren pesanan dari waktu ke waktu untuk mengidentifikasi periode puncak.
* **Analisis Performa Penjualan**: Menggabungkan data menu dan pesanan untuk mengidentifikasi item terlaris dan perilaku pembelian pelanggan secara keseluruhan.

---

## ❓ Pertanyaan Utama yang Dijawab

* Berapa jumlah total item yang tersedia di menu?
* Apa item termurah dan termahal yang ada di menu?
* Berapa total pesanan yang telah dilakukan?
* Item menu manakah yang paling sering dan paling jarang dipesan?
* Berapa total pesanan yang dilakukan untuk setiap kategori?
* Kapan jam makan puncak (peak hours) di restoran?
* Berapa jumlah item rata-rata per pesanan?

---

## 📊 Temuan Utama

* Menu restoran terdiri dari **122 item unik**.
* Rentang harga item menu adalah dari **$1.99 hingga $29.99**.
* Sebanyak **12.234 pesanan** telah dianalisis.
* Item yang paling sering dipesan adalah **'edamame'**, sedangkan item yang paling jarang dipesan adalah **'house salad'** dan **'french fries'**.
* Kategori **'Italian'** memiliki jumlah pesanan tertinggi.
* Jam makan puncak terjadi antara pukul **12:00 - 13:00** dan **17:00 - 19:00**.
* Rata-rata, setiap pesanan berisi **2.7 item**.

---

## 💡 Rekomendasi

Berdasarkan analisis, berikut adalah rekomendasi yang diberikan:

* **Optimasi Menu**: Tonjolkan dan promosikan item populer dari kategori 'Italian'. Pertimbangkan untuk mengevaluasi ulang atau membuat promosi khusus untuk item yang kurang populer seperti 'house salad' dan 'french fries' untuk meningkatkan penjualan.
* **Staf dan Operasional**: Sesuaikan jadwal staf untuk memastikan cakupan yang memadai selama jam puncak yang telah diidentifikasi (12:00-13:00 dan 17:00-19:00) untuk meningkatkan kecepatan layanan dan kepuasan pelanggan.
* **Strategi Pemasaran**: Buat kampanye pemasaran yang ditargetkan, seperti 'paket makan siang spesial', untuk memanfaatkan lebih lanjut volume pesanan yang tinggi selama puncak jam makan siang.
```

---

## 📬 Hubungi Saya

Jika Anda memiliki pertanyaan atau ingin berdiskusi mengenai proyek ini, jangan ragu untuk menghubungi saya.

* **LinkedIn:** https://www.linkedin.com/in/ernando-taufiq-nur-hidayat/
* **Email:** ernando.taufiq29@gmail.com
