# UAS-DISKRIT 
### Nama: Mayscela Herliyawati
### Kelas: TI.25.C5
### NIM: 312510371
### Dosen Pengampu:  Dr. Muhamad Fatchan, S.Kom., M.Kom.

## Output Program 
<img width="512" height="233" alt="Screenshot 2026-01-15 111607" src="https://github.com/user-attachments/assets/ef4b0430-f026-46a2-9e41-3fcbda322eb4" />


Program ini dibuat untuk memodelkan sebuah graf serta melakukan penelusuran simpul menggunakan dua algoritma, yaitu Depth First Search (DFS) dan Breadth First Search (BFS).Kedua algoritma ini digunakan untuk mengunjungi setiap simpul dalam graf dengan pola yang berbeda.
## Penjelasan Kode

##### 1. Struktur Dasar Kelas Graph
self.V digunakan untuk menyimpan jumlah simpul dalam graf.
self.graph dibuat sebagai adjacency list berupa list berisi list kosong, yang berfungsi menyimpan hubungan antar simpul.
Struktur ini memudahkan penyimpanan relasi antar simpul dibandingkan dengan matriks, terutama jika graf memiliki banyak simpul.
##### 2. Fungsi add_edge(u, v)
Menambahkan sisi atau hubungan antara simpul u dan v. Karena graf tidak berarah, maka hubungan dibuat dua arah:
**u dimasukkan ke daftar tetangga v**
**v dimasukkan ke daftar tetangga u**
Fungsi ini memastikan bahwa graf dapat dilalui dari kedua arah
##### 5. DFS Rekursif
`Menandai simpul sebagai telah dikunjungi.`
`Menampilkan simpul ke layar.`
`Mengunjungi seluruh tetangga yang belum dikunjungi dengan cara memanggil fungsi DFS kembali.`
Metode ini menelusuri graf sampai ke kedalaman maksimum terlebih dahulu sebelum berpindah ke jalur lain.
##### 6. DFS Iteratif
Menggunakan struktur data stack sebagai pengganti rekursi.
`Simpul awal dimasukkan ke stack.`
`Simpul terakhir dalam stack diambil dan dicetak.`
`Tetangga yang belum dikunjungi dimasukkan kembali ke stack.`
Cara ini memberikan hasil yang mirip dengan DFS rekursif, tetapi lebih aman dari risiko stack overflow.
#####


#####
