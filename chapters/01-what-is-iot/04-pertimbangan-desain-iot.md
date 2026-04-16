# Pertimbangan Desain IoT

Banyak pertanyaan perlu diajukan dan beberapa opsi perlu ditinjau saat bekerja dengan klien untuk membantu mereka mengidentifikasi kebutuhan arsitektur IoT mereka. Berikut beberapa pertimbangan tingkat tinggi yang penting untuk membantu Anda mengatur implementasi:

## Fungsionalitas arsitektur IoT

- Apakah arsitektur IoT Anda perlu mengumpulkan data, seperti pada jaringan sensor?
- Apakah perlu memasukkan monitoring dan control, seperti pada jaringan SCADA?
- Seberapa sering data perlu dikirim ke perangkat Anda?
- Berapa jarak antara perangkat dan gateway?
- Seberapa cepat data harus dikirim dari end node ke gateway?
- Apakah Anda memiliki kebutuhan waktu yang ketat yang harus dipenuhi?
- Bagaimana perangkat IoT Anda akan terhubung ke cloud?
- Sebagai contoh, apakah manajemen daya menjadi perhatian pada jaringan yang luas atau terpencil, yang akan mahal atau tidak efisien jika baterai harus sering diganti?

## Pemilihan perangkat IoT: pertimbangan time to market dan “build vs. buy”

- Anda perlu memilih perangkat IoT, seperti radio dan gateway, yang mendukung fungsionalitas yang dibutuhkan proyek Anda.
- Jika waktu bukan hal yang mendesak, Anda dapat membangun solusi dari awal.
- Jika time to market menjadi kunci, pendekatan terbaik adalah memulai dengan modul nirkabel siap pakai dan telah tersertifikasi serta menggunakan layanan dukungan kontrak.

## Manajemen perangkat yang telah di-deploy

- Tentukan apakah Anda memerlukan protokol yang mendukung opsi over-the-air (OTA) untuk memperbarui firmware pada semua perangkat Anda.
- Jika tidak, tentukan apakah Anda mampu menggunakan protokol yang lebih baru yang kemungkinan akan memiliki pembaruan firmware untuk memperbaiki masalah atau meningkatkan fungsionalitas.
- Tanpa pembaruan firmware OTA, penting untuk mempertimbangkan biaya melakukan pembaruan manual satu per satu, atau mengirim “truk” untuk memperbarui unit di lapangan.

Semua keputusan ini akan memengaruhi perencanaan, implementasi, dan pengelolaan proyek Anda secara keseluruhan, dan pada akhirnya memengaruhi total cost of ownership. Mari kita telaah beberapa pertimbangan ini lebih rinci.