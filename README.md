# Time Series Forecasting Dengan Framework Modeltime

Projek ini merupakan salah satu project saya sebagai salah satu tim product di Algoritma Data Science Academy. Pada project ini saya ingin mendalami framework modeltime yang dapat membantu saya sebagai seorang Data Scientist untuk melakukan prediksi terhadap data-data deret waktu.

Link publikasi: https://rpubs.com/VicNP/modeltime_TSF

## Tujuan Pembuatan

Salah satu alasan utama kenapa fokus dari artikel ini membahas modeltime karena modeltime adalah sebuah framework yang berisikan beberapa model machine learning time series, dari yang cukup klasik seperti ARIMA dan Exponential Smooting, sampai dengan yang cukup baru seperti Facebook’s Prophet dan parnship. Selain itu, modeltime menyediakan sebuah workflow yang dapat kita manfaatkan sebagai panduan. 

## Input Variable

Projek ini menggunakan sumber data dari [kaggle](https://www.kaggle.com/datasets/djzurawski/us-oil-and-gas-production-june-2008-to-june-2018).

Dari total 36 kolom yang terdapat pada dataframe di atas, kita hanya akan menggunakan 2 kolom saja yaitu kolom Month dan U.S..Crude.Oil. Kolom Month berisikan informasi tanggal setiap awal bulan dari Juni 2008 sampai Juni 2018 dan pada kolom U.S..Crude.Oil berisikan informasi jumlah hasil tambang minyak bumi dari setiap daerah di Amerika Serikat dalam satuan 1000 barel, jumlah hasil tambang minyak bumi pada kolom U.S..Crude.Oil berdasarkan penjumlahan dari 34 kolom lainnya.

| Variable             	| Detail                                                                           	|
|----------------------	|----------------------------------------------------------------------------------	|
| Month | Bulan pengambilan sample |
| U.S. Crude Oil | Jumlah hasil tambang minyak bumi dalam satuan ribuan barel |


