# Tugas_2

- **Nama**: Rahman Azkarafi Prasetya  
- **NRP**: 5025231044
## Getting Started

This project is a starting point for a Flutter application.

<img width="1699" height="1074" alt="image" src="https://github.com/user-attachments/assets/68ad34fc-0e49-49c2-a972-af9d2d49136e" />

## Penjelasan Struktur UI Flutter

Gambar diatas mnnunjukkan hierarki widget pada aplikasi Flutter.

### Root
- `MaterialApp` sebagai pembungkus utama aplikasi
- `Scaffold` sebagai kerangka layout

### Bagian Utama
- `AppBar` berisi judul aplikasi
- `Body` menggunakan `Column` untuk menyusun elemen secara vertikal
- `FloatingActionButton` sebagai tombol aksi

### Isi Body (Column)
1. `Container` berisi `Image` untuk menampilkan gambar
2. `Container` berisi `Text` sebagai deskripsi
3. `Container` berisi `Row` yang menampilkan beberapa menu secara horizontal  
   - Setiap menu menggunakan `Column` yang terdiri dari `Icon` dan `Text`
4. `Container` berisi teks counter dan tombol untuk menambah nilai

### core
- `Column` digunakan untuk susunan vertikal
- `Row` digunakan untuk susunan horizontal
- `Container` digunakan sebagai pembungkus untuk pengaturan tampilan
