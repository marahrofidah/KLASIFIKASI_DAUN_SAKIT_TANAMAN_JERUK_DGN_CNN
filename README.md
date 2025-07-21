# KLASIFIKASI DAUN SAKIT PADA TANAMAN JERUK
## RINGKASAN PROYEK
Proyek ini bertujuan untuk mengklasifikasikan kondisi daun tanaman jeruk, apakah sehat atau terinfeksi penyakit, menggunakan pendekatan Convolutional Neural Network (CNN). Dengan memanfaatkan dataset gambar daun, model CNN dilatih untuk mengenali pola visual penyakit pada daun secara otomatis.

## FITUR UTAMA
- Klasifikasi gambar daun jeruk: sehat vs sakit
- Penggunaan augmentasi data untuk meningkatkan performa model
- Visualisasi metrik: akurasi dan loss selama pelatihan
- Evaluasi model pada data uji
- Prediksi terhadap gambar daun baru

## STRUKTUR DATASET

citrus-leaf-disease-image/

└── Citrus Leaf Disease Image/

    ├── Black spot/
    ├── Canker/
    ├── Greening/
    ├── Healthy/
    └── Melanose/

## CARA MENJALANKAN PROYEK
KLONING ATAU UNDUH PROYEK

https://github.com/marahrofidah/KLASIFIKASI_DAUN_SAKIT_TANAMAN_JERUK_DGN_CNN.git

MEMPERSIAPKAN DATASET

citrus-leaf-disease-image/

└── Citrus Leaf Disease Image/

    ├── Black spot/
    ├── Canker/
    ├── Greening/
    ├── Healthy/
    └── Melanose/

JALANKAN NOTEBOOK
Buka file klasifikasi-daun-sakit-pada-tanaman-jeruk-dgn-cnn.ipynb menggunakan:

 - Google Colab (rekomendasi)
 - Jupyter Notebook (lokal)

INSTALASI LIBRARY 

pip install tensorflow matplotlib numpy


## HASIL DAN ANALISIS
model CNN sederhana ini telah berhasil menunjukkan potensi dalam mengklasifikasikan citra daun jeruk dengan akurasi 65% pada data pengujian, mengindikasikan kemampuannya untuk mengenali pola visual. Meskipun demikian, performanya belum optimal karena adanya indikasi overfitting, yang menunjukkan model masih perlu perbaikan signifikan agar dapat menggeneralisasi data baru dengan lebih baik. Dengan strategi pengembangan yang tepat seperti transfer learning dan penyesuaian arsitektur, model ini memiliki potensi besar untuk mencapai akurasi yang jauh lebih tinggi dan menjadi alat yang efektif dalam sistem pertanian cerdas.

## TOOLS YANG DIGUNAKAN
- Python 3.x

- TensorFlow / Keras

- NumPy

- Matplotlib

- Jupyter Notebook / Google Colab

