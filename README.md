# JudolDetector
Task Seleksi IRK Created by Haikal

## 💡 Latar Belakang
Saat ini, judi online menjadi masalah di Indonesia, bahkan cara promosinya beragam, dimulai dari donate streamer, backlink dari website ilegal, hingga kolom komentar youtube, kali ini kita akan mendeteksi kolom komentar video Youtube yang terdeteksi judi online menggunakan Youtube API algoritma string matching yang sudah dipelajari.

## Spesifikasi
### Fitur Wajib
1. Program merupakan web-based application, penggunaan bahasa pemrograman dibebaskan.
2. Program dapat menerima link video youtube atau id video yang akan ditelusuri.
3. Pengguna dapat mengubah algoritma string matching yang digunakan (Regex, KMP, BM, dan Rabin-Karp).
4. Untuk algoritma selain regex, pengguna dapat menambahkan file dengan format .txt untuk melakukan string matching, untuk pencarian dengan regex, format pencarian yaitu 2 atau 3 angka di belakang kata tanpa spasi. Contoh: Danantara77, Gacor88.
5. Seiring berkembangnya teknik pengiriman komentar judi online di Youtube, banyak situs yang menggunakan unicode letter untuk mengelabui kreator, gunakan regex untuk melakukan normalisasi, agar memudahkan, yang perlu dinormalisasi hanya font Mathematical Italic, Mathematical Sans-Serif Bold, Mathematical Sans-Serif Bold Italic, Fullwidth, dan Monospace.
6.  List komentar harus didapatkan menggunakan Youtube API.
