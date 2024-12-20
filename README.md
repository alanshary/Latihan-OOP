NAMA  : ZAID AL ANSHARY

Kelas : TI.24.A4

NIM   : 312410315

Matkul: Bahasa Pemrograman

# Latihan OOP

![gambar](https://github.com/andreanbadeh/Latihan-OOP/blob/d0d378be0428cf95cec28d28e1b5ee234729d04c/Images/Screenshot%202024-12-10%20075305.png)

# Penjelasan Code

# data -> mahasiswa.py

Mahasiswa: Class yang mewakili entitas mahasiswa. Memiliki atribut: `nim, nama, dan jurusan`. 

Fungsi utama:
`tambah_mahasiswa(nim, nama, jurusan)`: Menambah data mahasiswa baru.

`hapus_mahasiswa(nim)`: Menghapus mahasiswa berdasarkan NIM.

`ubah_mahasiswa(nim, nama_baru, jurusan)`: Memperbarui data mahasiswa tertentu.

`cari_mahasiswa(nim)`: Mencari mahasiswa berdasarkan NIM.

`semua_mahasiswa()`: Mengembalikan seluruh data mahasiswa.

# view -> input_form.py

Berisi class InputForm untuk menangani input dari pengguna.

`input_mahasiswa()`: Fungsi untuk meminta pengguna memasukkan data mahasiswa berupa NIM, Nama, dan Jurusan.

# view/mahasiswa.py

Berisi class `ViewMahasiswa` untuk menampilkan data mahasiswa ke layar.

Fungsi utama:

`tampilkan_semua_mahasiswa(data)`: Menampilkan semua data mahasiswa dalam bentuk daftar.

`tampilkan_mahasiswa(mahasiswa)`: Menampilkan detail satu mahasiswa tertentu.

# main.py

File utama program yang berisi menu untuk berinteraksi dengan pengguna.

Cara kerjanya:

- Tampilkan menu pilihan kepada pengguna.
- Pengguna memasukkan opsi, seperti:

1. `Tambah mahasiswa`: Memasukkan NIM, Nama, dan Jurusan untuk disimpan.

2. `Lihat semua mahasiswa`: Menampilkan seluruh data mahasiswa yang sudah tersimpan.

3. `Cari mahasiswa`: Mencari mahasiswa berdasarkan NIM.

4. `Ubah mahasiswa`: Memperbarui data mahasiswa tertentu.

5. `Hapus mahasiswa`: Menghapus data mahasiswa berdasarkan NIM.

6. `Keluar`: Mengakhiri program.

- Setiap pilihan akan memanggil fungsi yang relevan dari modul di folder `data` atau `view`.

Code Program Tersebut:

![gambar](https://github.com/andreanbadeh/Latihan-OOP/blob/1143d6fa951b5abb514b802727d827813f8f4ea8/Images/data.png)

Hasil Program Tersebut:

![Screenshot (46)](https://github.com/user-attachments/assets/9e126a98-fb1a-4a67-8530-205fc4b33cf6)
