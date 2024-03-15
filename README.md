# LP5DPBO2024C2

Saya Daffa Fakhry Anshori dengan NIM 2200337 mengerjakan soal Latihan 5 dalam Praktikum mata kuliah Desain dan Pemrograman Berbasis Objek, 
untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamin. 

# Desain Program
Program yang sudah saya buat adalah sebuah aplikasi Java GUI untuk manajemen data mahasiswa. Desain program ini menggunakan konsep objek dan GUI Swing dari Java untuk memungkinkan pengguna untuk menambahkan, mengubah, dan menghapus entri data mahasiswa. Berikut adalah desain GUI untuk program manajemen data mahasiswa:
1. Panel Utama:
   - Panel utama akan menampung semua komponen GUI, seperti formulir, tabel, dan tombol.
   - Warna latar belakang panel utama adalah putih.
2. Judul Label:
   - Label "Data Mahasiswa" akan digunakan sebagai judul utama program.
   - Judul akan memiliki ukuran teks yang lebih besar dan ditebalkan.
3. Formulir Mahasiswa:
   - Formulir akan memiliki Label dan (Field untuk memasukkan NIM dan Nama mahasiswa, ComboBox untuk memilih Jenis kelamin mahasiswa, RadioButton untuk memilih Kelas mahasiswa).
   - Label, Field, ComboBox, dan RadioButton akan disusun secara vertikal.
4. Tabel Mahasiswa:
   - Tabel akan menampilkan data mahasiswa dalam format yang terstruktur, termasuk kolom untuk NIM, nama, jenis kelamin, dan kelas.
   - Data mahasiswa dibuat dummy dalam program.
   - Pengguna dapat memilih baris tabel untuk memperbarui atau menghapus data.
5. Tombol Aksi:
   - Terdapat tombol "Add" untuk menambahkan data baru dan "Update" untuk memperbarui data yang dipilih.
   - Tombol "Delete" akan muncul saat pengguna memilih baris pada tabel untuk menghapus data.
   - Tombol "Cancel" akan menghapus semua input di formulir tanpa membuat perubahan pada tabel.

# Alur Program
1. Program dimulai dengan menampilkan sebuah window berukuran 480x560 piksel yang berisi form untuk memasukkan data mahasiswa.
2. Pengguna dapat mengisi form dengan memasukkan NIM, nama, jenis kelamin, dan kelas mahasiswa.
3. Setelah pengguna mengisi form, klik tombol "Add" untuk memasukkan data mahasiswa baru ke dalam tabel dan form akan dikosongkan kembali. Kemudian menampilkan feedback berisi "Data berhasil ditambahkan!".
4. Jika pengguna mengklik salah satu baris di tabel, informasi dari baris tersebut akan dimuat ke dalam form. Setelah itu tombol "Update" akan muncul menggantikan tombol "Add".
5. Jika pengguna mengklik tombol "Update", data mahasiswa yang ada di tabel akan diperbarui sesuai dengan informasi yang dimasukkan ke dalam form. Kemudian menampilkan feedback berisi "Data berhasil diubah!".
6. Jika pengguna mengklik tombol "Cancel", semua input di form akan dihapus.
7. Jika pengguna mengklik tombol "Delete", akan muncul jendela konfirmasi dengan pesan "Hapus data?". Pengguna akan diberikan opsi untuk memilih "Yes" atau "No". Jika pengguna memilih "Yes", data mahasiswa yang terkait akan dihapus dari tabel. Kemudian menampilkan feedback berisi "Data berhasil dihapus!". Jika pengguna memilih "No", tidak akan dilakukan tindakan apa pun dan jendela konfirmasi akan ditutup.
   
