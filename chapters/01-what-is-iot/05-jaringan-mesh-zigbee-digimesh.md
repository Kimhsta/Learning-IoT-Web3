# Jaringan Mesh, Zigbee, dan DigiMesh

## Pertimbangan Topologi dan Edge Computing

Banyak insinyur menanyakan satu pertanyaan kunci saat merancang jaringan IoT mereka: “Topologi mana yang paling cocok untuk aplikasi saya?” Beberapa opsi yang tersedia adalah protokol jaringan mesh, seperti Zigbee atau DigiMesh, serta point-to-point atau point-to-multipoint. Dalam beberapa kasus, berdasarkan pertanyaan-pertanyaan di atas, sudah jelas topologi mana yang paling masuk akal. Dalam kasus lain, riset dan pengujian lebih lanjut mungkin diperlukan.

Pada bagian berikut, kita akan meninjau beberapa faktor yang perlu dipertimbangkan saat mengevaluasi mana yang paling sesuai untuk kebutuhan Anda.

## Jaringan mesh

Insinyur jaringan biasanya memiliki pengalaman dengan topologi tertentu dan mungkin berasumsi bahwa topologi tersebut dapat digunakan di lingkungan apa pun. Namun, opsi lain mungkin lebih optimal untuk use case yang berbeda. Memahami kelebihan dan kekurangan topologi jaringan mesh sangat penting untuk menentukan apakah topologi ini merupakan pilihan yang baik untuk aplikasi Anda.

Faktor penting yang harus dianalisis adalah kebutuhan sinkronisasi sistem Anda. Topologi jaringan mesh merutekan data dari node ke node melalui jaringan yang dirancang sebagai mesh. Jadi, Anda harus mempertimbangkan “lompatan” yang menyebabkan latensi tambahan. Apakah Anda membutuhkan data kembali dalam 100 ms, atau Anda bisa menerima satu kali per detik?

Pada akhirnya, pelangganlah yang memutuskan, tetapi memiliki opsi untuk topologi yang berbeda dapat sangat menentukan keberhasilan deployment nirkabel.

## Fitur jaringan mesh

- Jaringan mesh dapat mendukung banyak node, kadang-kadang hingga seribu, tergantung pada arsitekturnya.
- Data secara cerdas menemukan jalannya dari node ke node menuju gateway.
- Jika satu node hilang, jaringan akan menemukan rute baru untuk memastikan data mencapai gateway.
- Setelah sebuah node ditambahkan ke jaringan, jaringan dapat merutekan data melalui node yang baru ditambahkan tersebut setelah terdeteksi.
- Jaringan mesh menyediakan redundansi dengan memungkinkan banyak jalur dari sebuah node atau perangkat ke gateway dan cukup fleksibel untuk menyesuaikan diri saat kondisi berubah.
- Anda juga dapat membangun subnet untuk memisahkan data dari jaringan tetangga. Ini adalah fitur yang sangat baik untuk jaringan padat dengan ribuan node, seperti solar farm atau aplikasi pencahayaan pintar, di mana latensi bukan merupakan masalah.

Jaringan mesh tersedia dalam standar seperti Zigbee dan jaringan peer-to-peer seperti DigiMesh.

## Perbedaan utama antara Zigbee dan DigiMesh

- Zigbee biasanya berada pada frekuensi 2.4 GHz, sedangkan DigiMesh dapat bekerja dengan modul XBee 2.4 GHz maupun modul XBee 900 MHz dan 868 MHz.
- Zigbee memiliki end node, router, dan coordinator yang merepresentasikan end device, repeater, dan gateway.
- DigiMesh adalah jaringan mesh peer-to-peer yang menawarkan self-healing, operasi jaringan padat, daya tahan baterai yang lebih panjang melalui sleep mode, serta instalasi dan konfigurasi yang mudah.

Anda dapat membandingkan kelebihan dan kekurangan Zigbee dan DigiMesh untuk memahami plus-minusnya dan menentukan protokol yang tepat untuk use case Anda.