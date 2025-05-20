# SOAL NOMOR 4 MENENTUKAN NILAI TERTINGGI
## Studi Kasus: Menentukan Nilai Tertinggi dari 5 Siswa
### Deskripsi
Setelah semua nilai siswa dimasukkan kedalam list nilai_siswa, 
program mencari nilai tertinggi dan menentukan siswa ke berapa yang 
mendapat nilai tersebut menggunakan dua fungsi utama
# FUNGSI MAX ()
nilai_tertinggi = max(nilai_siswa)
- Fungsi max() digunakan untuk mencari nilai 
terbesar dari semua nilai yang sudah dimasukkan ke dalam list.
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
