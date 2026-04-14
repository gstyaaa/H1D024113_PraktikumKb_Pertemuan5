# Sistem Pakar Diagnosa Penyakit THT

Aplikasi sistem pakar sederhana berbasis console yang dirancang untuk mendiagnosa penyakit Telinga, Hidung, dan Tenggorokan (THT) berdasarkan pola gejala yang dialami pengguna.

## Deskripsi Data
Program ini menggunakan dataset yang mencakup:
- **37 Jenis Gejala (G1 - G37)**: Mulai dari nafas abnormal hingga demam.
- **23 Jenis Penyakit**: Termasuk berbagai jenis Sinusitis, Kanker, dan infeksi telinga.

## Logika Program
Sistem bekerja menggunakan metode **Forward Chaining** sederhana:
1. Program menampilkan daftar gejala secara berurutan.
2. Pengguna memberikan input konfirmasi (ya/tidak).
3. Program mengumpulkan gejala yang dikonfirmasi.
4. Program mencocokkan kumpulan gejala tersebut dengan basis aturan (rule-base) penyakit yang ada di dataset.
5. Jika gejala yang diinput memenuhi kriteria minimal suatu penyakit, hasil diagnosa akan ditampilkan.

## Cara Penggunaan
1. gunakan perintah python penyakit_THT.py.
2. pilih opsi yang tersedia untuk mendeteksi penyakit anda.