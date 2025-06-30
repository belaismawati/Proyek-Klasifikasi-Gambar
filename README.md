# Klasifikasi Gambar pada Makanan

Proyek ini merupakan proyek klasifikasi gambar berbasis citra menggunakan deep learning, dimana datasetnya terdiri dari 7 kategori makanan, yaitu Baked Potato, Crispy Chicken, Donut, Fries, Hot Dog, Sandwich, dan Taquito.

---

## Struktur Folder

```
Submission
├───tfjs_model
| ├───group1-shard1of4.bin
| ├───group1-shard2of4.bin
| ├───group1-shard3of4.bin
| ├───group1-shard4of4.bin
| └───model.json
├───tflite
| ├───model.tflite
| └───klasifikasiGambar.txt
├───my_model
| ├───saved_model.pb
| └───variables
├───Proyek_Klasifikasi_Gambar.ipynb
├───proyek_klasifikasi_gambar.py
├───model_food_classification.h5
├───hasil_prediksi.csv
├───README.md
└───requirements.txt
```

---

## Fitur Utama

- Deteksi makanan menggunakan gambar.
- Format model: `.h5`, SavedModel, TFJS, dan `.tflite`.
- Preprocessing gambar otomatis dan inference dari gambar lokal.
- Dukungan konversi model lintas platform.

---

## Evaluasi dan Akurasi

- Akurasi data test: 86%
- Dataset: Food Image Classification Dataset
- Arsitektur model: MobileNetV2

---

## Penulis

- **Nama**: [Bela Ismawati Nuraisa]  
- **GitHub**: [https://github.com/belaismawati]  

---
>>>>>>> 6c32bb6 (Initial commit)
