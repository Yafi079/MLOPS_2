# Submission 2: Machine Learning Pipeline Stroke Prediction Model
**Nama:** Muhammad Yafi

**Username dicoding:** muhammad_yafi_079

| | Deskripsi |
| ----------- | ----------- |
| **Dataset** | [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/code) |
| **Masalah** | Memprediksi risiko seseorang mengalami stroke berdasarkan fitur kesehatan dan demografis. Masalah ini penting untuk intervensi dini dan pengambilan keputusan dalam perawatan kesehatan. |
| **Solusi machine learning** | Membuat model machine learning yang dapat memprediksi apakah seseorang berisiko mengalami stroke atau tidak berdasarkan data historis mereka. Solusi ini menggunakan algoritma machine learning untuk menganalisis fitur-fitur pasien dan memberikan prediksi. |
| **Metode pengolahan** | Data diolah dengan menangani nilai yang hilang, mengonversi fitur kategorikal menjadi fitur numerik, dan menormalkan fitur numerik. Transformasi ini dilakukan menggunakan TensorFlow Transform (TFT). |
| **Arsitektur model** | Model menggunakan jaringan saraf tiruan (neural network) dengan beberapa lapisan dense yang dioptimalkan menggunakan hyperparameter tuning. Model ini mencakup input layer untuk setiap fitur, beberapa hidden layer dengan unit dense, dan output layer dengan aktivasi sigmoid untuk prediksi biner. |
| **Metrik evaluasi** | Model dievaluasi menggunakan metrik Binary Accuracy, Precision, Recall, dan AUC (Area Under the Curve) untuk menilai kinerja prediksi model dalam mendeteksi stroke. |
| **Performa model** | Model menunjukkan performa yang baik dengan binary accuracy yang tinggi, menunjukkan kemampuan model untuk memprediksi stroke dengan akurat. Detail metrik performa lainnya seperti Precision, Recall, dan AUC juga dicatat untuk analisis lebih mendalam. |
| **Opsi deployment** | Model di-deploy menggunakan TensorFlow Serving pada platform Railway untuk memberikan prediksi real-time melalui API. |
| **Web app** | [Stroke Prediction Model](https://muhammadyafi079-pipeline-production.up.railway.app/v1/models/stroke-model/metadata) |
| **Monitoring** | Hasil monitoring menunjukkan bahwa model mampu memberikan prediksi dengan latensi rendah dan tingkat keakuratan yang konsisten. Selain itu, log monitoring membantu dalam mengidentifikasi dan memperbaiki anomali dalam prediksi. |
