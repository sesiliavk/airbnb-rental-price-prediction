# Airbnb Rental Price Prediction in Amsterdam 

## Repository Outline
1. README.md: Berisi gambaran umum dan penjelasan proyek.
2. Sesilia_Virdha.ipynb: Notebook utama yang berisi seluruh kode untuk tahapan machine learning, mulai dari pra-pemrosesan data, eksplorasi data, pelatihan model, evaluasi, hingga hyperparameter tuning.
3. Sesilia_Virdha_inf.ipynb: File notebook untuk menjalankan inference atau prediksi menggunakan model terbaik yang telah dilatih.
4. model_best.pkl: File yang menyimpan model machine learning terbaik dalam format pickle, siap untuk digunakan dalam inference atau deployment.
5. Deployment/: Folder yang berisi semua file yang diperlukan untuk proses deployment model (misalnya app.py untuk aplikasi web, requirements.txt untuk dependensi, dll.).
6. amsterdam_airbnb.csv: File dataset yang digunakan dalam proyek machine learning ini.

## Problem Background
Airbnb telah menjadi salah satu platform penyewaan akomodasi paling populer di dunia, termasuk di kota-kota besar seperti Amsterdam. Dengan banyaknya pilihan listing yang tersedia dari segi lokasi, tipe kamar, kapasitas tamu, hingga kualitas pelayanan dan penentuan harga sewa yang tepat menjadi hal yang krusial baik bagi pemilik properti maupun calon penyewa.

Namun, dalam praktiknya, banyak pemilik kesulitan menentukan harga yang optimal. Harga terlalu tinggi dapat membuat listing tidak kompetitif, sementara harga terlalu rendah dapat menyebabkan kerugian. Oleh karena itu, dibutuhkan pendekatan berbasis data untuk memprediksi harga sewa secara akurat dengan mempertimbangkan berbagai faktor seperti tipe kamar, jarak dari pusat kota, rating kebersihan, dan kepuasan tamu.

Proyek ini tidak hanya bermanfaat untuk membantu pemilik menetapkan harga sewa yang tepat, tetapi juga dapat digunakan sebagai dasar pengambilan keputusan strategis oleh investor, analis pasar properti, dan pengelola platform.

## Project Output
Proyek ini bertujuan untuk memprediksi harga Airbnb di Amsterdam menggunakan machine learning regresi, dengan mengembangkan dan memilih model terbaik dari lima algoritma yang diuji. Hasil prediksi ini diharapkan dapat membantu pemilik properti dalam menetapkan harga sewa yang tepat, serta menjadi dasar pengambilan keputusan strategis bagi investor, analis pasar properti, dan pengelola platform.

## Data
Data yang digunakan dalam proyek ini memiliki 1103 baris dan 20 kolom, tanpa nilai yang hilang (missing value), dengan persentase outlier yang sangat kecil (tertinggi hanya sekitar 1%), dan memiliki cardinality yang rendah.

## Method
Proyek ini akan menerapkan model machine learning regresi menggunakan lima algoritma berbeda: SVR, Random Forest Regressor, K-Nearest Neighbors Regressor, Decision Tree Regressor, dan XGBoost Regressor, semuanya dengan parameter default. Selanjutnya, model terbaik akan dipilih untuk dilakukan hyperparameter tuning menggunakan random search untuk mengoptimalkan prediksinya terhadap harga Airbnb.

## Stacks
1. bahasa pemrograman: python
2. tools: visual studio code, hugging face, kaggle
3. library: pandas, numpy, matplotlib, seaborn, scipy.stats, sklearn.preprocessing, sklearn.pipeline, sklearn.model_selection, sklearn.metrics, sklearn.svm, sklearn.ensemble, sklearn.neighbors, sklearn.tree, xgboost, pickle

## Reference
dataset = https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities/data

deployment = https://huggingface.co/spaces/sesiliavk/Milestone2
