# TechnicalTest-Dreamus-Edutaiment

Task 2 - Database Design
- ERD
Pembuatan ERD berawal dari Master Item dan hubungan antara Master Item, Lokasi Item, Letak tiap Stock, Pergerakan Stock dan Sinkronisasi tiap item
Untuk ERD berada di file ERD.
Hal utama yang perlu dibuat adalah Master Item dengan mengikuti informasi yang diberikan pada soal. lalu karena terdapat penjelasan pembagian Item ke 150 toko dan 2 warehouse, berarti kita perlu membuat database location untuk mengetahui lokasi mana saja yang dimiliki oleh tim. Setelah itu, dapat diproses untuk melihat stock adalah dengan menggabungkan antara master item dengan location dengan melihat primary keynya yaitu ID dari Item dan Location. Dari penggabungan ini, akan terlihat antara seluruh list item dari semua tempat yang ada. Selanjutnya adalah pembuatan database Pergerakan stock, yang mana karena item selalu berputar (terjual dan diperbaharui) maka perlu ada pemcatatan flow dari item secara langsung sehingga dapat terlihat secara keseluruhan di semua lokasi untuk semua item. Karena flow item selalu berputar, maka perlu dilakukan sikronisasi saat item baru diinput dan baru dikeluarkan yaitu dengan membuat database sync logs. sync log berguna untuk melihat sikronisasi perputaran item berhasil dilakukan atau tidak dan dapat terlihat tiap perpindahan dilakukan oleh siapa dan kapan terjadi.

- Script SQL
Pembuatan Script dapat dilakukan setelah menemukan hubungan antara Master Item, Lokasi Item, letak stok, pergerakan stock dan sinkronisasi tiap item.

- Index yang diperlukan
Untuk index yang digunakan dapat fokus pada Primary Key dan Foreign Key karena beberapa table saling berhubungan untuk dapat mengetahui jumlah stock secara langsung. Primary Key dipilih karena menjadi acuan untuk mencari setiap data dan bersifat unik dan mencegah duplikat.

- Alasan Design
Alasan membuat desain seperti ini sudah dijelaskan pada ERD dan Master item menjadi primary table yang digunakan karena fokus pada isi stock barang di table tersebut

- Trade-off
untuk trade - off bagian size dan color cukup berada di bagian table karena setiap item memiliki tipe, jenis dan warna yang acak dan tidak terlalu sama. ketika kita terlalu fokus untuk mengelompokkan sesuatu, maka akan memakan waktu malah tidak rapi.

Task 3 - REST API Development
Untuk API Development, saya belum memiliki pengalaman begitu banyak terkait pembuatan API dan dikarenakan kekurangan tools yang dimiliki dari perangkat saya membuat proses technical test ini menjadi kurang lancar dan saya sangat menghindari penggunaan AI ketika saya masih perlu belajar banyak terkait hal yang ingin saya tulis.
Tetapi sejauh yang saya paham terkait API.
Pembuatan API ini memerlukan tools menggunakan bahasa pemrograman dan saya sudah mencoba menggunakan python tetapi hal tersebut belum bisa menemukan cara terbaik dengan cepat.

Task 4 - Inventory Transaction
Untuk API Development, saya belum memiliki pengalaman begitu banyak terkait pembuatan API dan dikarenakan kekurangan tools yang dimiliki dari perangkat saya membuat proses technical test ini menjadi kurang lancar dan saya sangat menghindari penggunaan AI ketika saya masih perlu belajar banyak terkait hal yang ingin saya tulis.
Tetapi sejauh yang saya paham terkait API.
Pembuatan API ini memerlukan tools menggunakan bahasa pemrograman dan saya sudah mencoba menggunakan python tetapi hal tersebut belum bisa menemukan cara terbaik dengan cepat.

Task 5 - Integration API
Dikarenakan belum berhasil membuat API maka pada integrasi ini belum bisa dilakukan. Biasanya untuk API, saya dibantu oleh tim Developer untuk dibuatkan API yang sesuai. Saya akan coba pelajari lagi lebih lanjut terkait proses API ini.

Task 6 - Query
Dikarenakan tidak memiliki aplikasi MySQL atau sejenisnya, saya hanya membuat query sesuai dengan pengalaman saya dalam membuat query dan disesuaikan dengan soal yang ada
