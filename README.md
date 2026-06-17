# Manipulasi Citra Digital Menggunakan OpenCV

## Nama Mahasiswa

* Nama : Assyifa Nailah Abdullah
* NIM : 452024618077
* Program Studi : Teknik Informatika

## Deskripsi Singkat Project

Project ini merupakan implementasi manipulasi dasar citra digital menggunakan Python dan OpenCV pada mata kuliah Pengolahan Sinyal Digital. Eksperimen yang dilakukan meliputi pembacaan citra, konversi warna BGR ke RGB, resize citra, image blending, image negative, transformasi logaritmik, dan transformasi gamma.

## Citra yang Digunakan

* image1.jpg : Citra pertama
* image2.jpg : Citra kedua

## Library yang Digunakan

* OpenCV (cv2)
* NumPy
* Matplotlib

## Cara Menjalankan Notebook

1. Buka Google Colab atau Jupyter Notebook.
2. Upload file `image1.jpg` dan `image2.jpg`.
3. Jalankan file `image_manipulation.ipynb`.
4. Eksekusi setiap cell secara berurutan.
5. Amati hasil visualisasi dan analisis yang dihasilkan.

## Struktur Folder Project

```
manipulasi-citra-digital/
│
├── notebook/
│   └── image_manipulation.ipynb
│
├── images/
│   ├── IMG_4951.jpg
│   └── IMG_4502.jpg
│
├── report/
│   └── laporan.pdf
│
├── README.md
└── requirements.txt
```

## Ringkasan Hasil Eksperimen

* Konversi BGR ke RGB menghasilkan tampilan warna yang sesuai.
* Resize citra memungkinkan dua gambar memiliki ukuran yang sama sebelum dilakukan image blending.
* Image blending menghasilkan kombinasi dua citra dengan tingkat dominasi sesuai bobot yang diberikan.
* Image negative membalik intensitas piksel sehingga area terang menjadi gelap dan sebaliknya.
* Transformasi logaritmik meningkatkan detail pada area gelap.
* Transformasi gamma digunakan untuk mengatur tingkat kecerahan citra melalui variasi nilai gamma.

## Kesimpulan Singkat

Setiap teknik manipulasi citra memiliki fungsi yang berbeda sesuai dengan tujuan pengolahan citra. Pemilihan metode yang tepat sangat memengaruhi kualitas hasil akhir dan dapat digunakan untuk meningkatkan brightness, contrast, serta detail pada citra digital.
