# Proyek Excel Laporan Tahunan Toko Vrinda 2022

Selamat datang di Proyek Excel Menarik! Proyek ini dirancang untuk memberikan pengalaman belajar yang menarik tentang Excel dan penggunaannya.

## Daftar Isi

- [Tujuan Pengerjaan](#tujuan-pengerjaan)
- [Pertanyaan Bagian 1](#pertanyaan-bagian-1)
- [Kesimpulan](#kesimpulan)
- [Kontribusi](#kontribusi)

## Tujuan Pengerjaan

Vrinda store ingin membuat laporan penjualan untuk tahun 2022, jadi vrinda store ingin memahami pelanggan dan meningkatkan penjualan di tahun 2023

## Pertanyaan Beserta Jawaban

### 1. Bulan apa yang mendapatkan penjualan dan pemesanan yang tinggi ? 
      Maret karena total penjualan sekitar 1.928.066 dengan total order 2819

### 2. Siapa pembeli yang paling banyak diantara pria atau wanita pada tahun 2022 ? 
      pembeli paling banyak wanita dengan rasio 64% sedangkan pria 36%

### 3. Daftar 3 negara bagian teratas yang berkontribusi dalam penjualan ? 
      Negara teratas maharashtra, karnataka, dan uttar pradesh 

### 4. Hubungan antara umur dan jenis kelamin berdasarkan jumlah penjualan ? 
      yaitu kategori adult rasio 50 % penjualan dengan rentang umur 30-49 yang paling tinggi 

### 5. Saluran mana yang berkontribusi maxsimum dalam penjualan ? 
      Yaitu channel amazon, myntra dan flipkart dengan kontribusi sebanyak 80% 

### 6. Kategori apa yang penjualanya tinggi ? 
      Yaitu kategori set dengan jumlah penjualan 10.507.546

## Data Cleansing

### 1. Melakukan replace terhadap data yang tidak sesuai pada tabel : Gender dan QTY 

## Data Prosesing

### 1. Membuat age grup untuk tingkatan umur
       Dengan rumus : =IF(E2>=50;"Senior";IF(E2>=30;"Adult";"Teenager"))

### 2. Membuat kolom month
      Dengan rumus : =TEXT(G2;"mmmm")

## Kesimpulan

kesimpulan akhir untuk meningkatkan penjualan toko vrinda
target pelanggan wanita kelompok usia 30-49 tahun yang tinggal di maharashtra, karnataka dan uttar pradesh dengan menampilkan iklan/penawaran/kupon yang tersedia di amazon, flipkart dan myntra

## Kontribusi

Kontribusi selalu sangat dihargai! Jika Anda ingin menambahkan contoh atau latihan baru, memperbaiki kesalahan, atau meningkatkan proyek ini secara keseluruhan, silakan ikuti langkah-langkah berikut:
1. Fork repositori ini.
2. Buat branch baru untuk fitur atau perbaikan Anda: `git checkout -b fitur-baru`.
3. Lakukan perubahan yang diinginkan.
4. Commit perubahan Anda: `git commit -m 'Menambahkan contoh query SQL baru'`.
5. Push ke branch Anda: `git push origin fitur-baru`.
6. Buat pull request ke branch `main` repositori ini.

Kami akan melihat kontribusi Anda dengan senang hati dan merespons secepat mungkin!
- SQL Client yang di pakai DBeaver untuk berinteraksi dengan database.
- Pembelajaran dari Youtube [Rishabh Mishra] - https://www.youtube.com/@RishabhMishraOfficial

Terima kasih telah mengeksplorasi Proyek SQL Menarik ini! Semoga proyek ini membantu Anda meningkatkan pemahaman tentang SQL
***
© 2023 - Royjihan Maulana
