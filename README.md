# SOAL NOMOR 4 MENENTUKAN NILAI TERTINGGI
## Studi Kasus: Menentukan Nilai Tertinggi dari 5 Siswa
### Deskripsi
Setelah semua nilai-nilai siswa dimasukkan kedalam list (nilai_siswa), 
program mencari nilai tertinggi dan menentukan siswa ke berapa yang 
mendapat nilai tersebut menggunakan dua fungsi utama, yaitu 
# FUNGSI MAX ()
nilai_tertinggi = max(nilai_siswa)
- Fungsi max() berguna buat mencari nilai 
terbesar dari semua nilai yang udah dimasukkan ke dalam listnya.
- Contoh: Jika nilai_siswa = [70, 85, 90, 88, 75],
maka max(nilai_siswa) akan menghasilkan 90.
# FUNGSI INDEX ()
siswa_tertinggi = nilai_siswa.index(nilai_tertinggi) + 1
- Fungsi index() digunakan untuk mencari 
posisi (indeks) dari nilai tertinggi di dalam list.
- Karena Python menghitung indeks mulai dari 0,
kita tambahkan 1 agar sesuai dengan urutan siswa (siswa ke-1, ke-2, dst).
- Misalnya, nilai 90 ada di indeks ke-2 
(elemen ketiga), maka 2 + 1 = 3. Artinya, siswa ke-3 yang mendapat
# CONTOH HASIL AKHIR
nilai_siswa = [80, 76, 92, 85, 70]
-  nilai_tertinggi = max(nilai_siswa) → 92
- siswa_tertinggi = nilai_siswa.index(92) + 1 → 2 + 1 = 3

# SOAL NOMOR 1
## Studi Kasus Pemberian Diskon
### Deskripsi
pelanggan mendapoatkan diskon 10% jika total belanja lebih dari Rp 500.000.
Tujuan adalah menghitung total bayar akhir, untuk harga apakah kena diskon atau tidak?

### Menentukan input dan output
- Input:Total belanja
- Total bayar setelah diskon

## menentukan struktur kontrol 
Gunakan percabangan if-else untuk mengecek apakah total belanja melebihi Rp500.000 atau tidak.
Gunakan operator aritmatika (* dan -) untuk menghitung diskon dan total akhir.
Tipe data menggunakan tipe data (float) untuk menangani nilai desimal.
alasannya:
(if-else) dipakai untuk membuat program bisa mengambil keputusan.
(float) dipakai agar bisa menerima input desimal (misalnya Rp500.500).

# SOAL NOMOR 2
## Studi kasus menentukan kelulusan berdasrkan nilai rata-rata
### Deskripsi
Seorang siswa ingin mengetahui apakah ia lulus ujian berdasarkan rata-rata dari 3 mata pelajaran.
Kriteria kelulusan:
Lulus jika rata-rata nilai > 75.

### peran tipe data 
Program menggunakan tipe data numerik (float) agar dapat menghitung rata-rata dengan nilai desimal.
Input dari pengguna dikonversi dari string ke float menggunakan float().
Gunakan if-else untuk menentukan apakah rata-rata ≥ 75.

### peran opertator
Operator aritmatika + dan / digunakan untuk menghitung rata-rata:
rata_rata = (nilai1 + nilai2 + nilai3) / 3
Operator pembanding digunakan untuk menentukan status kelulusan:
if rata_rata >= 75:

### contoh output
1. Lulus
Masukkan nilai pelajaran 1: 80  
Masukkan nilai pelajaran 2: 85  
Masukkan nilai pelajaran 3: 78  
Rata-rata nilai: 81.00  
Status: LULUS

2. Tidak Lulus
Masukkan nilai pelajaran 1: 70  
Masukkan nilai pelajaran 2: 65  
Masukkan nilai pelajaran 3: 72  
Rata-rata nilai: 69.00  
Status: TIDAK LULUS

# SOAL NOMOR 3
## Studi kasus menghitung faktorial dengan rekursi
### Deskripsi
membuat program Python yang menghitung faktorial dari suatu bilangan bulat 
menggunakan fungsi rekursif.
Faktorial dari sebuah bilangan n (ditulis n!)
adalah hasil perkalian dari n × (n-1) × (n-2) × ... × 1.
Contoh: 5! = 5 × 4 × 3 × 2 × 1 = 120

### Cara kerja rekursi 
Rekursi adalah suatu teknik di mana fungsi memanggil dirinya sendiri untuk menyelesaikan masalah yang lebih kecil.
Dalam kasus faktorial:
faktorial(n) = n × faktorial(n-1)
Proses berulang hingga mencapai base case (kondisi berhenti), yaitu:
faktorial(0) = 1
1. Buat fungsi faktorial(n) yang memanggil dirinya sendiri jika n > 0.
2. Base case: jika n == 0, kembalikan nilai 1.
### contoh output
- Input: 5
Masukkan bilangan bulat non-negatif: 5  
Faktorial dari 5 adalah 120
- Input: 0
Masukkan bilangan bulat non-negatif: 0  
Faktorial dari 0 adalah 1
- Input: -3
Masukkan bilangan bulat non-negatif: -3  
Faktorial tidak terdefinisi untuk bilangan negatif.

Rekursi menyederhanakan proses pengulangan dengan memanggil fungsi itu sendiri.
Base case (n == 0) penting agar rekursi tidak berjalan tanpa henti.

# SOAL NOMOR 5 
## Studi kasus menghitung total harga pembelian 3 barang
### Deskripsi
kasir toko ingin sistem sederhana untuk menghitung total harga dari 3 barang yang dibeli, lalu menampilkan total pembayaran ke pelanggan.
### Penjelasan program 
Program ini menggunakan tipe data (float) agar dapat menghitung harga desimal (misalnya Rp10.500).
Tidak menggunakan struktur kontrol karena hanya menjumlahkan data langsung dan linier.
Program sangat dasar, cocok untuk memahami input-output dan aritmatika sederhana di Python.

### Mengapa memakai kode\program ini?
Menggunakan float() saat input karena harga bisa berupa desimal, misalnya 25000.50.
Variabel barang1, barang2, dan barang3 digunakan untuk menyimpan harga masing-masing barang agar lebih jelas dan mudah digunakan dalam perhitungan.
Penjumlahan sederhana digunakan karena hanya ada 3 barang.
Menggunakan try-except untuk menangani kesalahan input (misalnya jika pengguna tidak mengetik angka
Program ini membantu kasir menghitung total belanja dengan cepat dan efisien.

### Contoh Output
Masukkan harga barang ke-1: Rp25000  
Masukkan harga barang ke-2: Rp15000  
Masukkan harga barang ke-3: Rp10000  
Total yang harus dibayar: Rp50000.00
