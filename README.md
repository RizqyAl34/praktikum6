# praktikum6

## Fungsi hitung_nilai_akhir
![Gambar](./foto/1.png)
-Mendifinisikan Fungsi bernama hitung_nilai_akhir yang menerima tiga parameter: tugas, uts, dan uas.
![Gambar](./foto/2.png)
-Menghitung nilai akhir berdasarkan bobot yang telah ditentukan: tugas 30%, UTS 35%, dan UAS 35%. Hasil perhitungan dikembalikan (return).

## Fungsi tampilkan_data
![Gambar](./foto/3.png)
-Mendefinisikan fungsi tampilkan_data untuk menampilkan semua data mahasiswa.
![Gambar](./foto/4.png)
-Mengecek apakah dictionary data_mahasiswa kosong. Jika kosong, cetak pesan "Daftar Nilai Mahasiswa Kosong" dan keluar dari fungsi.
![Gambar](./foto/5.png)
-Mencetak judul tabel dan garis pemisah sepanjang 86 karakter.
![Gambar](./foto/6.png)
-Mencetak header kolom tabel dengan lebar kolom yang telah diatur agar rapi. Simbol ^ menandakan bahwa teks akan diratakan ke tengah.
![Gambar](./foto/7.png)
-Mencetak data mahasiswa untuk setiap baris, termasuk nomor urut (i), NIM, nama, nilai tugas, UTS, UAS, dan nilai akhir. Nilai akhir diformat menjadi dua angka desimal (.2f).
![Gambar](./foto/8.png)
-Mencetak garis pemisah di akhir tabel.

## Inisialisasi data_mahasiswa
![Gambar](./foto/9.png)
-Membuat dictionary kosong data_mahasiswa untuk menyimpan data mahasiswa.
![Gambar](./foto/10.png)
-Mencetak menu opsi dan meminta input dari pengguna. Input kemudian diubah menjadi huruf kecil (lower()) agar bisa diterima dalam bentuk huruf besar atau kecil.

# Tambah data
![Gambar](./foto/11.png)
-Jika pengguna memilih opsi 'T', program meminta input NIM dari pengguna.
![Gambar](./foto/12.png)
-Mengecek apakah NIM yang dimasukkan sudah ada di data_mahasiswa. Jika ya, tampilkan pesan bahwa NIM sudah terdaftar dan lanjutkan ke iterasi berikutnya dari loop (continue).
![Gambar](./foto/13.png)
-Meminta input nama, nilai tugas, UTS, dan UAS. Nilai tugas, UTS, dan UAS dikonversi menjadi tipe data float karena mereka adalah angka desimal.
![Gambar](./foto/14.png)
-Menyimpan data mahasiswa ke dalam dictionary data_mahasiswa dengan NIM sebagai kunci dan informasi lainnya sebagai nilai.
![Gambar](./foto/15.png)
-Menampilkan pesan konfirmasi bahwa data berhasil ditambahkan.

# Ubah data
![Gambar](./foto/16.png)
-Jika pengguna memilih opsi 'U', program meminta input NIM mahasiswa yang datanya ingin diubah.
![Gambar](./foto/17.png)
-Mengecek apakah NIM tersebut ada dalam data_mahasiswa. Jika ada, tampilkan pesan bahwa data ditemukan dan meminta input data baru.
![Gambar](./foto/18.png)
-Menghitung nilai akhir baru dan memperbarui data mahasiswa di dictionary data_mahasiswa.
![Gambar](./foto/19.png)
-Menampilkan pesan konfirmasi bahwa data berhasil diperbarui.

# Hapus data
![Gambar](./foto/20.png)
-Jika pengguna memilih opsi 'H', program meminta input NIM mahasiswa yang datanya ingin dihapus.
![Gambar](./foto/21.png)
-Mengecek apakah NIM tersebut ada dalam data_mahasiswa. Jika ada, data dihapus menggunakan perintah del dan menampilkan pesan konfirmasi.

# Lihat data
![Gambar](./foto/22.png)
-Jika pengguna memilih opsi 'L', program memanggil fungsi tampilkan_data untuk menampilkan seluruh data mahasiswa.

# Cari data
![Gambar](./foto/23.png)
-Jika pengguna memilih opsi 'C', program meminta input NIM mahasiswa yang ingin dicari.
![Gambar](./foto/24.png)
-Mengecek apakah NIM tersebut ada dalam data_mahasiswa. Jika ada, data mahasiswa tersebut disimpan dalam variabel mahasiswa.
![Gambar](./foto/25.png)
-Mencetak data mahasiswa tersebut dengan format tabel yang rapi, serupa dengan fungsi tampilkan_data.

# Keluar program
![Gambar](./foto/26.png)
Jika pengguna memilih opsi 'K', program mencetak pesan perpisahan dan menghentikan loop dengan break, sehingga program berhenti.

# Pilihan tidak valid
![Gambar](./foto/27.png)
Jika input dari pengguna tidak cocok dengan salah satu opsi yang tersedia, tampilkan pesan kesalahan dan program kembali ke menu.

# Hasil
![Gambar](./foto/28.png)
