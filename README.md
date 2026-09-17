# Pertemuan 03 Seleksi Python

Nama: Mutiara Sari  
NIM: 2225250071  
Kelas: 3A  

## Tujuan

Mempelajari dan menerapkan struktur seleksi `if`, `if-else`, kondisi majemuk, dan nested `if` dalam Python untuk membuat program yang dapat mengambil keputusan berdasarkan kondisi tertentu.

## Cara Menjalankan

Program dapat dijalankan melalui terminal VS Code dengan perintah:

python tugas/analisis_persamaan_kuadrat.py

## Algoritma Tugas

1. Memasukkan koefisien a, b, dan c sebagai bilangan bertipe float.
2. Memeriksa apakah nilai a sama dengan 0.
3. Jika a = 0, menampilkan bahwa input bukan persamaan kuadrat.
4. Jika a ≠ 0, menghitung diskriminan dengan rumus D = b² - 4ac.
5. Jika D > 0, menghitung dan menampilkan dua akar real yang berbeda.
6. Jika D = 0, menghitung dan menampilkan satu akar real kembar.
7. Jika D < 0, menampilkan bahwa tidak ada akar real.
8. Menampilkan nilai numerik dengan dua angka di belakang koma.

## Hasil Pengujian

### Test Case 1
- Input: a = 1, b = -5, c = 6
- Hasil yang diharapkan: Dua akar real, x1 = 3.00 dan x2 = 2.00
- Hasil aktual: Dua akar real, x1 = 3.00 dan x2 = 2.00
- Status: Berhasil

### Test Case 2
- Input: a = 1, b = 2, c = 1
- Hasil yang diharapkan: Akar real kembar, x = -1.00
- Hasil aktual: Akar real kembar, x = -1.00
- Status: Berhasil

### Test Case 3
- Input: a = 1, b = 0, c = 1
- Hasil yang diharapkan: Tidak ada akar real
- Hasil aktual: Tidak ada akar real
- Status: Berhasil

### Test Case 4
- Input: a = 0, b = 2, c = 3
- Hasil yang diharapkan: Bukan persamaan kuadrat
- Hasil aktual: Bukan persamaan kuadrat
- Status: Berhasil

## Refleksi

Pada latihan ini saya mempelajari penggunaan struktur seleksi dalam Python, terutama nested if. Saya memahami bahwa kondisi a = 0 harus diperiksa terlebih dahulu sebelum menghitung diskriminan dan akar persamaan kuadrat. Saya juga memahami bahwa nilai diskriminan menentukan jenis akar, yaitu dua akar real berbeda jika D > 0, satu akar real kembar jika D = 0, dan tidak ada akar real jika D < 0. Dari pengujian yang dilakukan, seluruh test case dapat berjalan sesuai dengan hasil yang diharapkan.