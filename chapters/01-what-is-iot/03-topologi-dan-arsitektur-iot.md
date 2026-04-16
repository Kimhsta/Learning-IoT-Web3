# Topologi dan Arsitektur IoT

## Topologi, Arsitektur, dan Edge Computing pada IoT

Saat ini, topologi IoT sudah lebih terstandarisasi dan seperti yang saya tampilkan pada gambar.

Sebuah perangkat IoT dapat membaca suatu variabel dan menghasilkan frekuensi radio; sinyal frekuensi radio yang mentransmisikan informasi perangkat itu dapat dideteksi oleh concentrator, antena, gateway, atau base station, sesuai istilah yang Anda pilih, yang merupakan titik jaringan yang mengonsentrasikan beberapa perangkat IoT yang terhubung. Tujuan gateway mendeteksi data tersebut adalah untuk mengirimkannya ke cloud di internet, dan kemudian informasi itu dapat mencapai application server. Application server dapat berupa software as a service (SaaS), platform as a service (PaaS), dan sebagainya, yang akan kita bahas lebih mendalam pada topik berikutnya. Desain arsitektur dan cara informasi dari perangkat IoT mencapai application server bergantung pada tujuan yang diinginkan dalam setiap kasus. Mari kita lihat sedikit lebih dalam.

Proyek Internet of Things (IoT) bisa jadi kompleks, karena banyak keputusan yang harus dibuat. Dalam proyek IoT apa pun, Anda harus membeli perangkat komunikasi seperti radio dan gateway, menghubungkan perangkat-perangkat tersebut menggunakan satu atau lebih metode koneksi dan protokol, serta memastikan perangkat bekerja sebagaimana mestinya. Selain itu, banyak keputusan lain juga diperlukan, seperti desain board, penempatan antena, dan interkonektivitas dengan perangkat lain. Arsitektur IoT adalah hasil dari keputusan-keputusan tersebut.

Arsitektur IoT yang umum menggabungkan perangkat nirkabel, intelligent gateway, router, dan cloud computing. Materi ini akan berfokus pada protokol nirkabel dan pilihan konektivitas yang perlu Anda buat saat mendefinisikan strategi, serta sedikit menyentuh komponen fisiknya.

Memilih arsitektur IoT terbaik untuk proyek baru Anda melibatkan penilaian kebutuhan konektivitas, teknologi, dan sumber daya yang diperlukan untuk menyatukannya. Tidak ada jawaban yang sepenuhnya benar atau salah untuk banyak keputusan yang harus dibuat; yang terpenting adalah mengevaluasi dan memilih apa yang paling sesuai dengan use case Anda dan fitur desain produk yang dibutuhkan.

Sebagai contoh, beberapa protokol nirkabel dapat digunakan untuk komunikasi antarperangkat, tetapi masing-masing memiliki keunggulan spesifik dan use case yang ideal. Mana yang paling cocok untuk implementasi Anda akan bergantung pada skenario unik yang Anda miliki. Oleh karena itu, sangat penting untuk memahami proyek Anda dan opsi yang tersedia secara menyeluruh.