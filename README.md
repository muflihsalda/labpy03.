![ft2](https://github.com/user-attachments/assets/435b7319-d8e4-4948-b5dd-a904514aba4c)# labpy03.

Nama : Muflih Salda Maulana <p>
Nim : 312410527 <p>
Kelas : TI.24.A.5 <p>
Mata kuliah : Bahasa pemrograman <p>

## `Latihan1: Angka random`
### Alur Algoritma Latihan1 :
 1. Mulai Program :
    - Import modul random.
    - Minta input dari pengguna untuk nilai n (jumlah bilangan acak yang ingin ditampilkan).
 2. Inisialisasi Variabel :
    - Inisialisasi variabel count dengan nilai 0 untuk menghitung jumlah bilangan acak yang sudah dihasilkan.
 3. Looping:
    - Gunakan loop while untuk terus menghasilkan bilangan acak hingga jumlah yang diinginkan tercapai (i < n).
 4. Menghasilkan Bilangan Acak:
    - Di dalam loop, gunakan random.random() untuk menghasilkan bilangan acak antara 0 dan 1.
 5. Memeriksa Bilangan Acak:
    - Periksa apakah bilangan acak yang dihasilkan kurang dari 0.5.
      > Jika ya, tambahkan nilai i dengan 1 dan cetak bilangan tersebut dengan format “Data Ke {i} = {random_number}”.
 6. Akhir Looping:
    - Ulangi langkah 4 dan 5 hingga count mencapai nilai n.
 7. Selesai:
    - Program selesai setelah menampilkan n bilangan acak yang kurang dari 0.5.
      


### Program python
![gambar1](![ft1](https://github.com/user-attachments/assets/40ab9e2a-3ac0-4aa9-8ede-26d20cbc3acf)

### Hasil eksekusi program 
ini hasil eksekusi program python diatas
![gambar1](![ft2](https://github.com/user-attachments/assets/965be416-eaad-4c19-bf11-1de933845809)

## `Latihan2: Laba`
### Alur Algoritma Latihan2 :
 1. Mulai Program:
    - Inisialisasi modal awal sebesar Rp 100.000.000.
    - Buat daftar keuntungan_bulanan yang berisi persentase keuntungan untuk setiap bulan.
 2. Inisialisasi Variabel:
    - Inisialisasi total_keuntungan dengan nilai 0 untuk menyimpan total keuntungan selama 8 bulan.
 3. Looping:
    - Gunakan loop for untuk iterasi dari bulan 1 hingga bulan 8.
 4. Menghitung Keuntungan Bulanan:
    - Di dalam loop, hitung laba bulan ini dengan mengalikan modal awal dengan persentase keuntungan bulan tersebut.
    - Tambahkan laba bulan ini ke total_keuntungan.
 5. Menampilkan Keuntungan Bulanan:
    - Cetak keuntungan untuk bulan tersebut.
 6. Akhir Looping:
    - Ulangi langkah 4 dan 5 untuk setiap bulan hingga bulan ke-8.
 7. Menampilkan Total Keuntungan:
    - Setelah loop selesai, cetak total keuntungan selama 8 bulan.
 8. Selesai:
    - Program selesai.
      ### Program python
![gambar1](![latihan1](https://github.com/user-attachments/assets/52c9404c-3115-4fdd-8fda-8d0ccd36e2c8)

### Hasil eksekusi program 
ini hasil eksekusi program python diatas
![gambar1](![hasil latihan1](https://github.com/user-attachments/assets/5eb27582-5721-4e2b-b512-05e315a0bf59)
)

## `Latihan3: Mesin atm`
### Flowchart
![gambar1](![latihan3](https://github.com/user-attachments/assets/1a973cfe-6b7c-409f-8330-b603176585d8)

![gambar1]()

### Alur Algoritma Latihan3 :
 1. Mulai Program:
    - Inisialisasi saldo awal sebesar Rp 1.00.000.000.
 2. Tampilkan Menu:
    - Tampilkan menu pilihan kepada pengguna:
      > Cek Saldo <p>
      > Tarik Tunai <p>
      > Keluar <p>
 3. Meminta Input Pengguna:
    - Minta pengguna memilih opsi dari menu.
 4. Proses Pilihan Pengguna:
    - Jika Pilihan 1 (Cek Saldo):
      > Tampilkan saldo saat ini.
    - Jika Pilihan 2 (Tarik Tunai):
      > Minta pengguna memasukkan jumlah uang yang ingin ditarik. <p>
      > Periksa apakah jumlah yang diminta lebih besar dari saldo. <p>
        > Jika ya, tampilkan pesan “Saldo tidak mencukupi.” <p>
        > Jika tidak, kurangi saldo dengan jumlah yang diminta dan tampilkan saldo saat ini. <p>
    - Jika Pilihan 3 (Keluar):
      > Tampilkan pesan “Terima kasih telah menggunakan ATM kami.” dan akhiri program.
    - Jika Pilihan Tidak Valid:
      > Tampilkan pesan “Pilihan tidak valid. Silakan coba lagi.”
 5. Ulangi Proses:
    - Kembali ke langkah 2 hingga pengguna memilih untuk keluar.

### Program python
seperti ini jika algoritma yang dibuat dalam bentuk flowchart di atas, di jadikan sebuah program python
![gambar1](screenshot/ft3.png)

### Hasil eksekusi program 
ini hasil eksekusi program python diatas
![gambar1](screenshot/ft4.png)
    
