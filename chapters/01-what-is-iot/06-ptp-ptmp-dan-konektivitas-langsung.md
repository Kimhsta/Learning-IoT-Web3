# PTP, PTMP, dan Konektivitas Langsung

## Point to point atau point to multipoint

Protokol nirkabel point-to-point (PTP) dan point-to-multipoint (PTMP) adalah topologi yang digunakan untuk konektivitas dalam banyak aplikasi, seperti use case ketika Anda ingin mengganti kabel dengan komunikasi nirkabel. Protokol ini berkomunikasi antara dua perangkat (point-to-point) atau dari satu perangkat ke beberapa perangkat lain (point-to-multipoint).

Beberapa faktor, seperti jarak, timing, dan daya baterai, dapat menunjukkan apakah PTP atau jaringan mesh yang dibutuhkan.

Berikut beberapa poin penting dari protokol PTP dan PTMP:

- Jika Anda membutuhkan link nirkabel untuk beberapa perangkat yang berjarak satu atau dua mil dan memiliki line of sight yang baik, PTP mungkin merupakan solusi yang paling mudah.
- PTP atau PTMP dapat efisien untuk aplikasi berbasis baterai. Data dapat dikirim saat diperlukan, dan sleep mode dapat diaktifkan sesuai kebutuhan komunikasi Anda. Bukan hal yang aneh jika baterai bertahan beberapa tahun pada aplikasi tipe PTP/PTMP.
- Di sisi lain, jaringan mesh menambah latensi dan mengonsumsi lebih banyak energi karena diperlukan router atau repeater yang diberi daya oleh jaringan.

Karena itu, jika jaringannya kecil dan cakupannya jelas, PTP/PTMP memiliki banyak keunggulan dibandingkan jaringan mesh.

## Konektivitas langsung dengan seluler, Wi-Fi, dan Bluetooth

Selain arsitektur IoT yang telah kita bahas, Anda juga dapat langsung menghubungkan perangkat ke cloud melalui Wi-Fi dan seluler ketika kondisi memerlukannya. Setiap strategi memiliki kelebihan dan kekurangannya masing-masing.

Wi-Fi mungkin merupakan protokol yang paling umum. Namun, penting untuk mempertimbangkan ketersediaan internet di lokasi klien dan kebijakan keamanannya. Mendapatkan izin agar perangkat IoT Anda dapat terhubung ke jaringan Wi-Fi seseorang tidak selalu cepat. Tinjauan keamanan tambahan mungkin diperlukan tergantung pada kebijakan perusahaan klien; dalam beberapa kasus, hal ini bahkan tidak memungkinkan.

Bekerja dengan ratusan wireless access point dan tingkat pengetahuan pelanggan yang berbeda-beda tentang Wi-Fi juga dapat menjadi tantangan pada aplikasi residensial.

## Pertimbangan penting untuk aplikasi seluler

- Dengan konektivitas menggunakan radio seluler, Anda perlu memastikan bahwa Anda memiliki akses ke jaringan seluler, yang biasanya tersedia di sebagian besar lingkungan perkotaan tetapi bisa menjadi tantangan di daerah yang lebih pedesaan.
- Anda perlu mempertimbangkan kecepatan data dan memastikan bahwa Anda mengirim data ke cloud pada kecepatan yang dibutuhkan aplikasi Anda. Protokol LTE-M dan LTE Cat-1 sangat cocok untuk sebagian besar aplikasi IoT yang mengirim data sensor ke cloud.
- Aktivasi, data plan, manajemen SIM, dan manajemen perangkat jarak jauh juga harus dipertimbangkan, karena mempertahankan koneksi seluler untuk perangkat IoT melibatkan lebih banyak komponen yang harus dikelola.

Sebagai contoh, bekerja dengan operator seperti Verizon atau AT&T. Jika Anda adalah startup atau baru memulai proyek IoT seluler pertama Anda, bekerja langsung dengan operator seperti Verizon atau AT&T terkadang bisa membuat frustrasi. Bekerja dengan MVNO (Mobile Virtual Operator) bisa lebih efisien dan membantu proyek IoT Anda berjalan tepat waktu.

Tren IoT lainnya adalah dukungan dual radio dalam satu modul. Modul tersebut memiliki protokol nirkabel utama, seperti LTE-M, Cat-1, Zigbee, atau 802.15.4, dan link Bluetooth bawaan untuk konfigurasi dan manajemen.

Bayangkan Anda mendatangi sebuah perangkat di lapangan, dan alih-alih menghubungkan kabel untuk mengonfigurasi atau melakukan troubleshooting, Anda menggunakan link Bluetooth dengan aplikasi di ponsel Anda. Ini juga membuat proses menyalakan dan menjalankan perangkat menjadi jauh lebih mudah dibandingkan harus membawa komputer dan kabel untuk setup.