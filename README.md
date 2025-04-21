# Soal Tes Pemrograman dan Machine Learning

## 1. Inference Video Menggunakan Model YOLO

Buatlah program sederhana yang melakukan inference terhadap video yang terdapat di dalam folder `video`, menggunakan model YOLO yang disimpan dalam folder `model`. Program harus memenuhi ketentuan sebagai berikut:

- Melakukan inference setiap 30 frame (1 frame per detik jika video 30 FPS).
- Mengganti label hasil inference dengan klasifikasi kualitas buah sebagai berikut:  
  `['Ripe', 'Unripe', 'OverRipe', 'Rotten', 'EmptyBunch']`
- Objek yang terdeteksi harus tetap dilacak (tracking) hingga melewati garis penghitung (counting line).

## 2. Analisis Grafik Hasil Training

Berikan penjelasan terhadap grafik hasil training yang terdapat pada masing-masing file gambar dalam folder `train_result`.  
Penjelasan harus mencakup:

- Loss (Training dan Validation)
- Metrik evaluasi seperti mAP, Precision, dan Recall
- Interpretasi terhadap performa model berdasarkan grafik

## 3. Perancangan Algoritma Tracking Kendaraan

Rancanglah algoritma atau pendekatan berbasis Machine Learning atau Deep Learning yang paling sesuai untuk melakukan pelacakan (tracking) kendaraan berdasarkan data yang tersimpan pada database berikut:

- **Host**      : `https://hb01677.ap-southeast-3.aws.snowflakecomputing.com/`
- **User**      : `TES_USR_LACAK`
- **Password**  : `TES_USR_LACAK`

Pendekatan yang dibuat harus mencakup:

- Desain arsitektur model atau framework yang digunakan
- Alur pemrosesan data (data pipeline)
- Mekanisme tracking antar titik koordinat (misalnya GPS atau sensor lainnya)
- Cara mengintegrasikan dengan database Snowflake
