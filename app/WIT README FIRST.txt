Using Modular

Design Pattern ayng digunakan : MVP(Model-View-Presenter)


Model-View-Presenter atau yang biasa disingkat menjadi MVP adalah sebuah konsep arsitektur pengembangan aplikasi yang memisahkan antara tampilan aplikasi dengan proses bisnis yang bekerja pada aplikasi. Arsitektur ini akan membuat pengembangan aplikasi kita menjadi lebih terstuktur, mudah di-test dan juga mudah di-maintain.

Berikut penjelasan masing-masing layer pada MVP.
- View, merupakan layer untuk menampilkan data dan interaksi ke user. View biasanya berupa Activity, Fragment atau Dialog di Android. View ini juga yang langsung berkomunikasi dengan user.
- Model, merupakan layer yang menunjuk kepada objek dan data yang ada pada aplikasi.
- Presenter, merupakan layer yang menghubungkan komunikasi antara Model dan View. Setiap interaksi yang dilakukan oleh user akan memanggil Presenter untuk memrosesnya dan mengakses Model lalu mengembalikan responnya kembali kepada View.

Teknologi yang digunakan :
- HIT API 				: Retrofit
- teknologi yang lain ada di gradle(comment)

