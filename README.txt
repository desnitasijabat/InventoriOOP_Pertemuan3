README TUGAS - MODUL PRAKTIKUM 3

Nama  : Desnita Sijabat
NIM   : 25110212
Kelas : TK A PAGI

Isi proyek:
- Barang.java
- Main.java
- UjiBarang.java

Jawaban singkat:
1. Constructor:
   Constructor adalah method khusus untuk memberi nilai awal pada objek saat dibuat dengan new. Di class Barang, constructor mengisi atribut dan memastikan datanya valid sejak awal.
2. Private (encapsulation):
   private membatasi atribut agar hanya bisa diakses dari dalam class itu sendiri. Data Barang diubah atau dibaca lewat method (getter/setter), sehingga nilainya bisa divalidasi dan tidak bisa diubah sembarangan dari luar.
3. Collection:
   Collection adalah wadah untuk menyimpan banyak objek sekaligus, misalnya ArrayList. Di proyek ini, collection dipakai untuk menampung banyak objek Barang dalam satu daftar yang bisa ditambah, dicari, dan ditelusuri.
4. Pembagian tanggung jawab:
   Setiap class punya tugas sendiri. Barang mengurus data dan aturan validasinya, Main menjalankan alur program dan menampilkan hasil, dan UjiBarang khusus menguji apakah class Barang bekerja dengan benar. Dengan begitu kode lebih rapi, mudah dicari kesalahannya, dan mudah diubah tanpa merusak bagian lain.