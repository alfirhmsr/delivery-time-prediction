# Prediksi Waktu Pengiriman Makanan

Final project ini bertujuan untuk memprediksi waktu pengiriman makanan berdasarkan data logistik seperti kondisi cuaca, lalu lintas, tipe kendaraan, dan jarak.

## 📊 Deskripsi Proyek
- Tipe: Klasifikasi
- Target: `Time_taken (min)`
- Fitur: Weather, Traffic, Type_of_vehicle, Distance, dll.
- Model yang digunakan: Decision Tree, Random Forest, XGBoost

## 📁 Struktur
- `notebooks/`: Notebook utama
- `README.md`: Penjelasan proyek
- `requirements.txt`: Library yang digunakan
- `.gitignore`: File yang diabaikan oleh Git

## 🧪 Instalasi
```
pip install -r requirements.txt
```

## 🚀 Cara Menjalankan
1. Buka `notebooks/delivery_time_prediction.ipynb`
2. Jalankan secara berurutan untuk melihat proses preprocessing, modeling, dan evaluasi

## ✅ Hasil
Model terbaik mencapai akurasi hingga 89% menggunakan Random Forest.
