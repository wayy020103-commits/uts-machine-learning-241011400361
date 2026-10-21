# UTS Machine Learning

## Identitas Mahasiswa
- **Nama:** Wahyu Damai Saputra
- **NIM:** 241011400361
- **Kelas:** Reg C

## Ringkasan Hasil

### A. Linear Regression — Biaya Iklan dan Penjualan
- **Jumlah data:** 40 baris
- **Persamaan regresi:** ŷ = 27.8952 + 9.0943X
- **MAE training:** 4.6054
- **MSE training:** 38.0581
- **RMSE training:** 6.1691
- **R² training:** 0.9437
- **MAE testing:** 4.3607
- **MSE testing:** 28.7447
- **RMSE testing:** 5.3614
- **R² testing:** 0.9383

Interpretasi singkat: koefisien positif menunjukkan bahwa biaya iklan yang lebih tinggi cenderung berkaitan dengan penjualan yang lebih tinggi pada dataset ini.

### B. Logistic Regression — Klasifikasi Email Spam
- **Jumlah data:** 60 email
- **Intercept:** -8.6579
- **Koefisien JumlahLink:** 0.7371
- **Koefisien KataPromo:** 0.7673
- **Log loss akhir training:** 0.3023
- **Accuracy testing:** 0.9333 (93.33%)
- **Precision testing:** 0.6667
- **Recall testing:** 1.0000
- **F1-score testing:** 0.8000
- **Confusion matrix:** TN = 12, FP = 1, FN = 0, TP = 2

Persamaan probabilitas:
`P(Spam) = sigmoid(-8.6579 + 0.7371*JumlahLink + 0.7673*KataPromo)`

## Isi Repositori
- `README.md` — identitas dan ringkasan hasil
- `tugas_UTS.ipynb` — notebook yang telah dijalankan dengan output
- `Ads_Data.csv` — dataset biaya iklan dan penjualan
- `Email_Data.csv` — dataset email spam

## Catatan
Hasil metrik berasal dari pembagian data dengan `RANDOM_STATE = 61` (dua digit terakhir NIM). Pastikan kembali identitas dan kelas sesuai data akademik sebelum mengumpulkan.
