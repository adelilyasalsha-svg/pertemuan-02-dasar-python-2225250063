# Pertemuan 02 - Dasar Python

## Identitas

- Nama: Adelilya Salsha
- NIM: 2225250063
- Kelas: 3B
- Mata Kuliah: Algoritma dan Pemrograman

## Tujuan Repository

Repository ini berisi hasil latihan dan tugas pada Pertemuan 02 mata kuliah Algoritma dan Pemrograman.

Pada pertemuan ini dipelajari dasar-dasar Python, yaitu variabel, konstanta, tipe data, input-output, konversi tipe data, operator aritmetika, operator perbandingan, operator logika, serta penggunaan f-string.

Repository ini juga digunakan untuk mendokumentasikan proses pengerjaan, pengujian program, dan pengumpulan tugas melalui GitHub.

## Struktur dan Fungsi Berkas
### Folder Kuis

Folder `Kuis` berisi berkas kuis yang dikerjakan pada Pertemuan 02.

| Berkas | Keterangan |
|---|---|
| `kuis 1.docx` | Berisi hasil pengerjaan Kuis 1 pada Pertemuan 02. |


### Folder Latihan

Folder `latihan` berisi program-program latihan dasar Python.

| Berkas | Keterangan |
|---|---|
| `01_biodata.py` | Program untuk memasukkan dan menampilkan data biodata serta menghitung perkiraan umur. |
| `02_persegi_panjang.py` | Program untuk menghitung luas dan keliling persegi panjang. |
| `03_konversi_suhu.py` | Program untuk mengonversi suhu Celsius ke Fahrenheit dan Kelvin. |
| `04_nilai_akhir.py` | Program untuk menghitung nilai akhir berdasarkan nilai tugas, UTS, dan UAS. |

### Folder Tugas

Folder `tugas` berisi tugas utama pada Pertemuan 02.

| Berkas | Keterangan |
|---|---|
| `kalkulator_koordinat.py` | Program untuk menghitung perubahan koordinat, jarak Euclidean, dan titik tengah dari dua titik. |

### Berkas Lain

| Berkas | Keterangan |
|---|---|
| `.gitignore` | Berisi daftar berkas atau folder yang tidak perlu diunggah ke repository GitHub. |
| `README.md` | Berisi identitas, tujuan repository, struktur berkas, cara menjalankan program, hasil pengujian, refleksi, dan sumber. |

## Cara Menjalankan

Pastikan terminal VS Code berada pada folder utama repository.

### Menjalankan latihan biodata

```bash
python latihan/01_biodata.py
```

### Menjalankan latihan persegi panjang

```bash
python latihan/02_persegi_panjang.py
```

### Menjalankan latihan konversi suhu

```bash
python latihan/03_konversi_suhu.py
```

### Menjalankan latihan nilai akhir

```bash
python latihan/04_nilai_akhir.py
```

### Menjalankan tugas kalkulator koordinat

```bash
python tugas/kalkulator_koordinat.py
```

Jika perintah `python` tidak dapat digunakan, pada sistem tertentu dapat menggunakan:

```bash
python3 tugas/kalkulator_koordinat.py
```

## Hasil Pengujian Tugas Utama

Program `kalkulator_koordinat.py` diuji menggunakan tiga test case yang telah ditentukan pada bahan ajar.

| Kasus | Titik A | Titik B | Jarak | Titik Tengah |
|---|---|---|---:|---|
| 1 | (0, 0) | (3, 4) | 5.00 | (1.50, 2.00) |
| 2 | (-2, 1) | (4, 1) | 6.00 | (1.00, 1.00) |
| 3 | (2.5, -1) | (2.5, 3) | 4.00 | (2.50, 1.00) |

### Kesimpulan Pengujian

Ketiga test case menghasilkan nilai jarak dan titik tengah yang sesuai dengan hasil perhitungan manual, sehingga program dapat menjalankan perhitungan koordinat dengan benar.

## Refleksi

- Konsep yang paling saya pahami adalah penggunaan variabel, input-output, dan operator dalam Python karena dapat langsung dipraktikkan melalui program.
- Kesalahan yang saya temukan adalah kesalahan dalam penulisan kode dan format keluaran. Saya memperbaikinya dengan memeriksa kembali kode dan menjalankan program melalui terminal.
- Pada pertemuan berikutnya saya ingin lebih memahami penggunaan percabangan dan logika dalam Python.

## Sumber

1. Rencana Pembelajaran Semester Algoritma dan Pemrograman OBE Untirta 2026/2027 Ganjil.
2. Python Software Foundation. *The Python Tutorial*.
3. Visual Studio Code. *Getting Started with Python in VS Code*.
4. GitHub Docs. *Creating a New Repository*.
5. GitHub Docs. *Adding Locally Hosted Code to GitHub*.
6. Downey, A. B. (2015). *Think Python: How to Think Like a Computer Scientist* (2nd ed.). Green Tea Press.