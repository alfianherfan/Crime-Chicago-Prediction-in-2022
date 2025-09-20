# Time Series Forecasting for Crime Chicago Prediction in 2022

data = https://www.kaggle.com/datasets/georgehanyfouad/crime-prediction-in-chicago-in-2022

Data yang digunakan adalah data dummy yang berasal dari Kaggle. Data yang digunakan adalah Crime Prediction in Chicago 2022. 
Dataset ini berisi mengenai catatan kejahatan atau kriminal yang terjadi di kota Chicago pada tahun 2022. 
Data ini mencakup seperti id nomor laporan, tanggal kejadian, tipe jenis kriminal, deskripsi kriminal, status penangkapan, dan lainnya.

Background: 
Kota Chicago mengalami fluktuasi jumlah kejahatan sepanjang tahun. Pemangku kebijakan ingin menyusun strategi pencegahan yang berbasis data, bukan sekadar reaktif.
Diperlukan analisis tren dan pola musiman agar penempatan patroli, kampanye keamanan, serta alokasi anggaran dapat dilakukan lebih efektif dan tepat waktu. Data ini memiliki rentang waktu pada tahun 2022.

Apa saja yang dilakukan?
- Memahami background data
- Melakukan data understanding
- Data manipulation
- Melakukan Exploratory Data Analysis dan membuat visualisasi
- Feature engineering seperti Calendar Features, Cyclical Encoding, Lag & Rolling Target, dan Split Data untuk model machine learning
- Modelling
- Insight & Rekomendasi

Machine learning yang digunakan ada 3 yaitu Holt-Winters, Random Forest Regressor, dan ARIMA.
Matriks yang digunakan adalah matriks regresi seperti MAE, RMSE, MAPE, dan R-square

Hasil:

<img width="1356" height="622" alt="image" src="https://github.com/user-attachments/assets/0dba7779-ab0c-44f3-af5f-3c06f373788f" />


Random Forest Regressor memberikan hasil yang terbaik karena matrik yang didapatkan lebih baik diantara model lainnya.

Rekomendasi:
- Pemasangan CCTV & Penerangan Tambahan: Identifikasi dan pasang lebih banyak kamera pengawas atau tingkatkan penerangan jalan di lokasi yang rawan.
- Optimalisasi Patroli Berbasis Prediksi: Alokasikan lebih banyak personel patroli ke area yang memiliki risiko kejahatan lebih tinggi.
- Peningkatan Keamanan Diri: Mendorong masyarakat untuk lebih waspada, terutama di bulan-bulan yang teridentifikasi rawan, seperti yang terlihat pada grafik.
