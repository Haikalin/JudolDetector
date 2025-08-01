# 🎰 Judol Detector
Task Seleksi IRK Created by Haikal

## 💡 Latar Belakang
Saat ini, judi online menjadi masalah di Indonesia, bahkan cara promosinya beragam, dimulai dari donate streamer, backlink dari website ilegal, hingga kolom komentar youtube, kali ini kita akan mendeteksi kolom komentar video Youtube yang terdeteksi judi online menggunakan Youtube API dan algoritma string matching yang sudah dipelajari.

<div align="center">
  <img src="img/ketua.jpg" alt="Ketua" style="height: 200px; margin: 10px; object-fit: cover;">
  <img src="img/wakil.jpg" alt="Wakil" style="height: 200px; margin: 10px; object-fit: cover;">
</div>
<div align="center">
  <strong>Note: </strong>Gambar di atas hanya pemanis
</div>


## 🎯 Spesifikasi
### Fitur Wajib (1500 poin)
1. Program merupakan web-based application, penggunaan bahasa pemrograman dibebaskan.
2. Program dapat menerima link video youtube atau id video yang akan ditelusuri.
3. Pengguna dapat mengubah algoritma string matching yang digunakan (Regex, KMP, BM, dan Rabin-Karp).
4. Untuk algoritma selain regex, pengguna dapat menambahkan file dengan format .txt yang dipisahkan dengan endline untuk melakukan string matching, untuk pencarian dengan regex, format pencarian yaitu 2 atau 3 angka di belakang kata tanpa spasi. Contoh: Danantara77, Gacor88.
5. Seiring berkembangnya teknik pengiriman komentar judi online di Youtube, banyak situs yang menggunakan unicode letter untuk mengelabui kreator, gunakan regex untuk melakukan normalisasi, agar memudahkan, yang perlu dinormalisasi hanya font Mathematical Italic, Mathematical Sans-Serif Bold, Mathematical Sans-Serif Bold Italic, Fullwidth, dan Monospace.
6.  List komentar harus didapatkan menggunakan Youtube API. [Youtube API](https://developers.google.com/youtube/v3)

### Fitur Bonus (1000 poin)
1. Insert dan delete komentar di channel youtube sendiri, pengguna dapat menambahkan banyak komentar dalam bentuk file txt yang dipisahkan oleh semicolon (;), dan untuk delete komentar, hanya komentar mengandung judi online saja yang dihapus,  <strong>Note: </strong>Delete hanya bisa digunakan di akun sendiri, jadi upload video terlebih dahulu.
2. Normalisasi font selain 5 font yang telah menjadi fitur wajib, gunakan [Referensi font unicode](https://www.textconverter.net/).
3. Melakukan deployment pada frontend dan backend.

## 📂 Pengerjaan dan Pengumpulan
1. Buatlah repositori **private** pada github masing-masing dan invite `Haikalin` dalam repositori tersebut.
2. Berkas yang dikumpulkan berupa **link rilis tag ke repositori github** yang telah dibuat dengan ketentuan sebagai berikut.
    - Memberikan tag `vn` pada commit terakhir Anda setiap kali ingin melakukan submisi dengan `n` adalah jumlah submisi yang telah dilakukan. (contoh: `v1` untuk submisi pertama).
    - **Tidak menggunakan *url shortener*** (bit.ly, shortlink, atau yang lain) saat melakukan pengumpulan *task*.
    - Anda dapat melakukan rilis dengan panduan [berikut](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).
3. **Lakukan submisi** pada website seleksi IRK dengan menggunakan akun std.stei.itb.ac.id, **lakukan konfirmasi** ke LINE `haikal11082017`, dan **jadwalkan demo** dengan cara yang sama. Lakukan hal yang sama jika membuat rilis yang baru. *Tidak kontak untuk demo == Tidak dapet nilai*
4. Jika terdapat pertanyaan dapat menghubungi LINE `haikal11082017`.
