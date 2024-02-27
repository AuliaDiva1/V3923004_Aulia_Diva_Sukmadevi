Latihan Function Menghitung KPK dan FPB Aulia Diva Sukmadevi (V3923004)

Fungsi adalah blok kode terorganisir dan dapat digunakan kembali yang digunakan untuk
melakukan sebuah tindakan/action. Fungsi memberikan modularitas yang lebih baik untuk aplikasi
Anda dan tingkat penggunaan kode yang tinggi Program ini adalah program Python yang mengimplementasikan dua fungsi matematika, yakni mencari Faktor Persekutuan Terbesar (FPB) dan Kelipatan Persekutuan Terkecil (KPK), beserta sebuah loop while yang memberikan opsi kepada pengguna untuk memilih antara kedua fungsi tersebut atau keluar dari program.

Fungsi hitung_fpb(a, b) berfungsi untuk mencari FPB dari dua bilangan bulat a dan b. FPB merupakan bilangan bulat positif terbesar yang dapat membagi habis kedua bilangan input. Fungsi ini menggunakan algoritma Euclidean yang bekerja secara rekursif, dimana prosesnya adalah melakukan pembagian berulang antara bilangan yang lebih besar dengan bilangan yang lebih kecil sampai salah satu bilangan menjadi nol.

Fungsi hitung_kpk(a, b) digunakan untuk mencari KPK dari dua bilangan bulat a dan b. KPK adalah kelipatan terkecil dari kedua bilangan input. Fungsi ini menggunakan pendekatan sederhana dengan menginisialisasi variabel kpk dengan nilai maksimum dari dua bilangan, dan kemudian menambah satu per satu ke kpk hingga ditemukan bilangan yang habis dibagi oleh kedua bilangan input.

Program kemudian memasuki loop while True yang akan berjalan terus menerus. Di dalam loop tersebut, program menampilkan menu pilihan kepada pengguna, yang terdiri dari opsi untuk menghitung FPB, menghitung KPK, atau keluar dari program. Pengguna diminta untuk memasukkan pilihan mereka, dan program akan menanggapi sesuai dengan pilihan yang dimasukkan. Jika pengguna memilih opsi untuk menghitung FPB atau KPK, mereka diminta untuk memasukkan dua bilangan bulat, dan program akan mencetak hasil perhitungan FPB atau KPK sesuai dengan pilihan pengguna. Jika pengguna memilih opsi untuk keluar dari program, pesan "Selesai." akan dicetak, dan loop while akan diakhiri menggunakan pernyataan break, sehingga program berakhir.

Pesan tersebut dicetak menggunakan f-string (formatted string literals), sebuah fitur dalam Python yang memungkinkan penyisipan variabel langsung ke dalam string dengan menggunakan sintaks {}. F-string mempermudah penggunaan variabel dalam string dan membuat kode menjadi lebih bersih dan mudah dibaca.Dengan demikian, program ini memberikan pengguna kemampuan untuk dengan mudah menghitung FPB dan KPK dari dua bilangan bulat apa pun yang mereka masukkan, memberikan alat yang berguna dalam memecahkan masalah matematika atau rekayasa yang melibatkan konsep tersebut.




