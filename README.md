📊 Beijing PM2.5 Air Quality Analysis
📌 Deskripsi Proyek

Proyek ini berfokus pada Exploratory Data Analysis (EDA) dan feature engineering terhadap data kualitas udara PM2.5 di Beijing.
Analisis dilakukan untuk memahami pola temporal, pengaruh kondisi cuaca, serta hubungan antara arah dan kecepatan angin terhadap konsentrasi partikel PM2.5.

📊 Dataset

Nama dataset: PRSA Air Quality Dataset (Beijing)

Sumber: UCI Machine Learning Repository / publik dataset

Periode data: Time series (jam)

Target utama: Konsentrasi PM2.5

Variabel Utama:

pm25 : Konsentrasi PM2.5 (µg/m³)

suhu : Temperatur

embun : Dew point

pres : Tekanan udara

cws : Cumulative wind speed

cbwd : Arah angin (kategori)

Variabel kalender: jam, hari, bulan, akhir pekan, lunar event

🔎 Metodologi Analisis

Tahapan analisis yang dilakukan:

Data Cleaning

Konversi waktu ke DatetimeIndex

Penanganan missing values

Subsetting data berdasarkan kondisi waktu dan cuaca

Exploratory Data Analysis (EDA)

Analisis tren PM2.5 secara temporal

Perbandingan akhir pekan vs hari kerja

Analisis distribusi dan statistik deskriptif

Visualisasi korelasi antar variabel numerik

Feature Engineering

Ekstraksi fitur waktu (bulan, jam)

One-hot encoding variabel kategorikal

Interaction term antara arah angin dan kecepatan angin

Seleksi dan penghapusan fitur yang redundan

Statistical Analysis

Uji korelasi

Interpretasi statistik pada variabel hasil encoding

📈 Visualisasi

Beberapa visualisasi utama dalam notebook:

Time series plot PM2.5

Heatmap korelasi variabel numerik

Analisis korelasi berdasarkan arah angin

Distribusi PM2.5 berdasarkan kondisi waktu
