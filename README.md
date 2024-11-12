# Weather Data Analysis

## Deskripsi Project
Project ini bertujuan untuk memenuhi tugas infinite learning dengan mengambil, menyimpan, dan menganalisis data cuaca dari beberapa kota di Indonesia menggunakan API dari OpenWeatherMap. Data cuaca yang dianalisis meliputi suhu, kelembaban, dan kondisi cuaca. Analisis dilakukan menggunakan Python, dengan hasil disimpan dalam format CSV dan divisualisasikan dengan matplotlib dan seaborn.

## Persyaratan
- Python 3.x
- Paket yang dibutuhkan:
  - `requests`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  
## Penggunaan API
Proyek ini menggunakan OpenWeatherMap API untuk mengambil data cuaca dari lima kota: Jakarta, Bogor, Pamulang, Ciamis, dan Bandung. Pastikan Anda memiliki API key dari OpenWeatherMap dan ganti `api_key` dengan API key Anda.

## Cara Menjalankan Kode
1. Clone atau unduh kode ini ke komputer Anda.
2. Pastikan semua paket yang dibutuhkan telah terinstal.
3. Jalankan skrip Python.

```python
python weather_analysis.py

# Analisis Data Cuaca dengan Python

Proyek ini menggunakan data cuaca dari beberapa kota di dunia, yang diambil melalui API OpenWeatherMap. Proyek bertujuan untuk melakukan analisis data cuaca menggunakan Python dan menghasilkan berbagai visualisasi untuk membantu memahami pola cuaca.

## Tahapan Analisis

### 1. Pengambilan Data Cuaca dari API
- Kode mengakses API untuk mendapatkan data cuaca dari lima kota yang ditentukan.
- Data yang dikumpulkan mencakup:
  - **Suhu** (dalam °C)
  - **Kelembaban** (%)
  - **Deskripsi kondisi cuaca**

### 2. Penyimpanan Data ke CSV
- Data cuaca yang telah diambil disimpan dalam file CSV bernama `weather_data.csv`.

### 3. Analisis Data Cuaca
- **Rata-rata Suhu**: Menghitung rata-rata suhu dari semua kota.
- **Standar Deviasi Suhu**: Menghitung standar deviasi dari distribusi suhu.
- **Median Suhu**: Menentukan nilai tengah dari suhu yang diperoleh.
- **Suhu Tertinggi dan Terendah**: Menemukan nilai maksimum dan minimum suhu.
- **Kondisi Cuaca Paling Umum**: Menemukan kondisi cuaca yang paling sering muncul di antara kota-kota yang dianalisis.

### 4. Visualisasi Data
- **Distribusi Suhu** di setiap kota menggunakan *barplot*.
- **Frekuensi Kondisi Cuaca** dengan *countplot*.
- **Histogram Distribusi Suhu** untuk melihat persebaran suhu.

---

## Contoh Hasil Analisis

- **Rata-rata Suhu**: 27.49°C  
- **Standar Deviasi Suhu**: 1.72°C  
- **Median Suhu**: 28.12°C  
- **Suhu Tertinggi**: 29.2°C  
- **Suhu Terendah**: 24.94°C  
- **Kondisi Cuaca Paling Umum**: Moderate rain  

---

## Visualisasi

### 1. Distribusi Suhu di Berbagai Kota
- Menampilkan perbedaan suhu rata-rata dari setiap kota.

### 2. Frekuensi Kondisi Cuaca
- Menampilkan jumlah kemunculan setiap kondisi cuaca di lima kota.

### 3. Distribusi Suhu
- Histogram untuk melihat distribusi suhu dalam rentang yang lebih kecil.

---