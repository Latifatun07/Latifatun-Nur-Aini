Proyek ini memprediksi risiko gagal bayar pinjaman menggunakan data application_train.csv dari Home Credit.

🔍 Tujuan
Membangun model machine learning untuk mengklasifikasi nasabah apakah berisiko gagal bayar atau tidak (TARGET: 0 / 1).

⚙️ Proses
Explorasi data: Cek distribusi TARGET dan missing values.

Pembersihan data: Imputasi nilai kosong dengan median.

Normalisasi: StandardScaler pada fitur numerik.

Modeling: Logistic Regression dengan evaluasi ROC AUC.
