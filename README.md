OUTPUT # Jawaban-Latihan-Modul-13

#Nomor 1
masukkan:
31 13 25 43 1 7 19 37 -5
keluaran:
1 7 13 19 25 31 37 43
Data berjarak 6

masukkan:
4 40 14 8 26 1 38 2 32 -31
keluaran:
1 2 4 8 14 26 32 38 40
Data berjarak tidak tetap

penjelasan:
Membaca input sampai menemukan bilangan negatif
Mengurutkan data menggunakan insertion sort
Mencetak data yang sudah terurut
Memeriksa jarak antar data:
Jika semua data memiliki jarak yang sama, cetak "Data berjarak x"
Jika tidak, cetak "Data berjarak tidak tetap"


#Nomor 2
Masukkan dan keluaran program:
=== PROGRAM MANAJEMEN PERPUSTAKAAN ===
Masukkan jumlah buku yang akan didaftarkan: 6

=== PENDAFTARAN BUKU ===
Silahkan masukkan data 6 buku:

Buku ke-1:
Masukkan ID Buku (contoh: B001): B001
Masukkan Judul Buku (gunakan underscore untuk spasi): Harry_Potter
Masukkan Nama Penulis (gunakan underscore untuk spasi): JK_Rowling
Masukkan Nama Penerbit (gunakan underscore untuk spasi): Gramedia
Masukkan Jumlah Eksemplar: 5
Masukkan Tahun Terbit: 2001
Masukkan Rating (0-100): 95

Buku ke-2:
Masukkan ID Buku (contoh: B001): B002
Masukkan Judul Buku (gunakan underscore untuk spasi): Lord_of_Rings
Masukkan Nama Penulis (gunakan underscore untuk spasi): Tolkien
Masukkan Nama Penerbit (gunakan underscore untuk spasi): Gramedia
Masukkan Jumlah Eksemplar: 3
Masukkan Tahun Terbit: 1954
Masukkan Rating (0-100): 90

Buku ke-3:
Masukkan ID Buku (contoh: B001): B003 
Masukkan Judul Buku (gunakan underscore untuk spasi): Da_Vinci_Code
Masukkan Nama Penulis (gunakan underscore untuk spasi): Dan_Brown
Masukkan Nama Penerbit (gunakan underscore untuk spasi): Gramedia
Masukkan Jumlah Eksemplar: 4
Masukkan Tahun Terbit: 2003
Masukkan Rating (0-100): 80

Buku ke-4:
Masukkan ID Buku (contoh: B001): B004
Masukkan Judul Buku (gunakan underscore untuk spasi): Laskar_Pelangi
Masukkan Nama Penulis (gunakan underscore untuk spasi): Andrea_Hirata
Masukkan Nama Penerbit (gunakan underscore untuk spasi): Gramedia
Masukkan Jumlah Eksemplar: 6
Masukkan Tahun Terbit: 2005
Masukkan Rating (0-100): 92

Buku ke-5:
Masukkan ID Buku (contoh: B001): Game_of_Thrones
Masukkan Judul Buku (gunakan underscore untuk spasi): George_RR_Martin
Masukkan Nama Penulis (gunakan underscore untuk spasi): Gramedia         
Masukkan Nama Penerbit (gunakan underscore untuk spasi): 2
Masukkan Jumlah Eksemplar: 1996
Masukkan Tahun Terbit: 94
Masukkan Rating (0-100): 94

Buku ke-6:
Masukkan ID Buku (contoh: B001): B005             
Masukkan Judul Buku (gunakan underscore untuk spasi): Hunger_Games
Masukkan Nama Penulis (gunakan underscore untuk spasi): Suzanne_Collins
Masukkan Nama Penerbit (gunakan underscore untuk spasi): Gramedia
Masukkan Jumlah Eksemplar: 4
Masukkan Tahun Terbit: 2008
Masukkan Rating (0-100): 88

Pendaftaran buku selesai!

=== BUKU TERFAVORIT ===
Buku terfavorit adalah: Harry_Potter JK_Rowling Gramedia 2001

=== PENGURUTAN BUKU ===
Mengurutkan buku berdasarkan rating...
Pengurutan selesai!

=== 5 BUKU RATING TERTINGGI ===
Menampilkan 5 buku dengan rating tertinggi:
1. Harry_Potter
2. George_RR_Martin
3. Laskar_Pelangi
4. Lord_of_Rings
5. Hunger_Games

Masukkan rating buku yang ingin dicari: 92

=== PENCARIAN BUKU DENGAN RATING 92 ===
Buku ditemukan:
Judul: Laskar_Pelangi
Penulis: Andrea_Hirata
Penerbit: Gramedia
Tahun: 2005
Eksemplar: 6
Rating: 92

=== PROGRAM SELESAI ===


Penjelasan:
mengimplementasikan semua subprogram pada modul

DaftarkanBuku:
Membaca n data buku dari input
Menyimpan ke dalam array pustaka

CetakTerfavorit:
Mencari buku dengan rating tertinggi
Mencetak judul, penulis, penerbit, tahun

UrutBuku:
Menggunakan insertion sort
Mengurutkan berdasarkan rating secara menurun

Cetak5Terbaru:
Mencetak 5 judul buku rating tertinggi
Menangani kasus jika buku kurang dari 5

CariBuku:
Menggunakan binary search
Mencari buku dengan rating yang diminta
Mencetak pesan error jika tidak ditemukan
