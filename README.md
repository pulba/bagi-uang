# Bagi Uang

Aplikasi pembagian pendapatan sederhana untuk membantu mengatur uang setiap kali menerima upah.

Bagi Uang menggunakan sistem pembagian persentase. Setiap pendapatan yang dimasukkan akan otomatis dibagi ke lima kategori:

- 40% Kebutuhan utama
- 22% Makan dan minum
- 20% Investasi
- 11% Dana darurat
- 7% Jajan dan have fun

Total pembagian adalah 100%.

## Konsep

Prinsip aplikasi ini sederhana:

> Setiap uang yang masuk langsung memiliki tujuan.

Pengguna cukup memasukkan jumlah upah yang diterima. Aplikasi kemudian menghitung nominal untuk setiap kategori secara otomatis.

Contoh:

Jika pendapatan hari ini adalah Rp100.000:

| Kategori | Persentase | Alokasi |
|---|---:|---:|
| Kebutuhan utama | 40% | Rp40.000 |
| Makan dan minum | 22% | Rp22.000 |
| Investasi | 20% | Rp20.000 |
| Dana darurat | 11% | Rp11.000 |
| Jajan dan have fun | 7% | Rp7.000 |
| Total | 100% | Rp100.000 |

## Fitur

### 1. Pembagian Pendapatan

Masukkan nominal upah yang diterima.

Aplikasi akan menghitung pembagian secara otomatis berdasarkan persentase yang telah ditentukan.

### 2. Kebutuhan Utama

Sebesar 40% dari pendapatan.

Digunakan untuk kebutuhan seperti:

- Kos
- Tagihan
- Pulsa
- Internet
- Kebutuhan wajib lainnya

### 3. Makan dan Minum

Sebesar 22% dari pendapatan.

Digunakan untuk kebutuhan konsumsi harian.

### 4. Investasi

Sebesar 20% dari pendapatan.

Dana ini dialokasikan untuk tujuan keuangan jangka panjang.

### 5. Dana Darurat

Sebesar 11% dari pendapatan.

Aplikasi menghitung akumulasi dana darurat dari setiap pemasukan yang dicatat.

Pengguna juga dapat menentukan target dana darurat.

### 6. Jajan dan Have Fun

Sebesar 7% dari pendapatan.

Dana ini dapat digunakan untuk hiburan, jajan, hobi, atau aktivitas rekreasi.

### 7. Riwayat Pendapatan

Setiap pemasukan yang dicatat akan disimpan di perangkat.

Riwayat menampilkan:

- Tanggal pemasukan
- Jumlah pendapatan
- Alokasi investasi
- Alokasi dana darurat

### 8. Pengaturan Persentase

Persentase pembagian dapat diubah melalui halaman pengaturan.

Aplikasi memastikan total seluruh persentase harus tepat 100%.

### 9. Penyimpanan Lokal

Data disimpan menggunakan `localStorage`.

Tidak membutuhkan database atau server untuk menjalankan aplikasi versi ini.

## Teknologi

Project ini menggunakan teknologi web dasar:

- HTML5
- CSS3
- JavaScript
- LocalStorage

Tidak menggunakan framework atau library eksternal.

## Struktur Project

Versi saat ini dibuat sebagai single-page application sederhana dalam satu file.

```text
bagi-uang/
│
├── bagi-uang.html
└── README.md
