# Home Credit Default Risk Classification![image](https://user-images.githubusercontent.com/56854278/193455679-af49b847-b9ed-432c-aedf-291bd977eac7.png)

## Define Problem

Dalam pemberian layanan terhadap customer home credit, perlu adanya analisis mengenai skor kredit melalui prediksi skor kredit. Hasil dari analisis skor kredit digunakan untuk memastikan bahwa pelanggan yang mempunyai potensi melakukan penulanasan tidak ditolak saat mengajukan kredit. Analisa skor kredit secara manual akan membutuhkan waktu yang lama dan tenaga yang besar apalagi jika data yang masuk cukup banyak. Maka dari itu, dibutuhkan solusi agar pemberian skor kredit lebih efisien. Solusi untuk mengatasi hal tersebut, prediksi skor kredit dapat diselesaikan menggunakan machine learning.

Pada kasus ini akan dilakukan 
* Analisa mengenai pelanggan yang bisa melakukan pelunasan dan yang tidak. Analisa meliputi jumlah pelanggan yang melakukan pelunansan atau tidak, faktor yang mempengaruhi dalam melakukan pelunasan, dan solusi bagaimana sebaiknya home credit memberikan pinjaman kepada pelanggan berdasarkan visualisasi data.

* Pembuatan model prediktif berupa klasifikasi sehingga home credit dapat memprediksi skor kredit customer. Algoritma yang digunakan adalah algoritma yang termasuk dalam supervised learning dimana terdapat label pada data training. Skor kredit terdiri atas 1 dan 0. Skor kredit 1 menunjukkan bahwa customer memiliki kesulitan dalam pelunasan. Sedangkat 0 menunjukkan bahwa customer tidak memililki kesulitan dalam pelunasan.

## Dataset

Data terdiri dari 7 tabel dimana data utama berada pada tabel application_{train|test}. 

* **Tabel application_{train|test}** berisi tentang pinjaman saat waktu pengajuan
* **Tabel previous_application** berisi tentang informasi peminjaman sebelumnya
* **Tabel POS_CASH_balance** berisi tentang informasi saldo bulanan pinjaman sebelumnya 
* **Tabel instalments_payments** berisi tentang transaksi berkaitan dengan peminjaman sebelumnya 
* **Tabel credit_card_balance** berisi tentang informasi saldo bulanan kartu kredit pada peminjaman sebelumnya
* **Tabel bureau** berisi tentang data peminjaman dari institusi lain
* **Tabel bureau_balance** berisi tentang saldo bulanan pada kredit sebelumnya di institusi lain 

![index](https://user-images.githubusercontent.com/56854278/193455948-4234aefa-1c82-4c7e-afb5-2edfbcbcbd50.png)
