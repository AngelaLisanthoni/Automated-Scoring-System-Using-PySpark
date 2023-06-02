# Automated Scoring System Using PySpark

Tujuan pembuatan code ini adalah melakukan automasi sistem nilai pada jawaban essay menggunakan pyspark. Algoritma yang digunakan dalam studi kasus ini adalah ALS. Adapun tahapan - tahapan yang dilakukan dalam proses ini, diantaranya:
1. Membuat Session pyspark terlebih dahulu
2. Import beserta melakukan pre-processing dataset
3. Melakukan proses hash untuk mengubah jawaban essay menjadi nilai numerik
4. Splitting dataset dan pembuatan model
5. Menyiapkan data baru yang dilakukan proses hash kembali
6. Melakukan prediksi score terhadap data baru berbasis model ALS yang didefinisikan sebelumnya
7. Melakukan evaluasi model dengan RMSE
