# AsjaiRobi-PBO2-Tugas6
# Aplikasi Cek Cuaca Sederhana

Aplikasi ini adalah aplikasi desktop berbasis Java yang memungkinkan pengguna untuk memeriksa informasi cuaca berdasarkan kota. Aplikasi ini menggunakan API OpenWeatherMap untuk mengambil data cuaca secara real-time dan menampilkan hasilnya dalam antarmuka grafis.
Fitur

    Menampilkan cuaca real-time untuk kota yang dipilih atau dimasukkan.
    Menambahkan kota ke dalam daftar favorit.
    Menyimpan data cuaca ke file CSV (data_cuaca.csv).
    Menampilkan daftar cuaca yang telah disimpan dalam bentuk tabel.
    Mendukung ikon cuaca berdasarkan kondisi cuaca (cerah, hujan, berawan, dll.).

Struktur Proyek

src/
├── data_cuaca.csv       # File CSV untuk menyimpan data cuaca.
├── favorit_kota.txt     # File teks untuk menyimpan daftar kota favorit.
├── images/              # Folder berisi ikon cuaca.
│   ├── sunny.png
│   ├── cloudy.png
│   ├── rain.png
│   ├── thunderstorm.png
└── CekCuaca.java        # File utama aplikasi.

# Fitur Antarmuka
Menu Input

    Input Kota: Pilih kota dari dropdown atau masukkan secara manual.
    Cek Cuaca: Ambil data cuaca dari API berdasarkan kota.
    Ulang: Reset semua input dan tampilan cuaca.

Tabel Cuaca

    Tampilkan data cuaca yang telah disimpan.
    Gunakan tombol "Muat Data" untuk membaca file data_cuaca.csv.

Fungsi Tambahan

    Tambah ke Favorit: Tambahkan kota ke daftar favorit.
    Simpan File: Simpan data cuaca kota yang sedang ditampilkan ke file CSV.
