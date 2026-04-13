# Karakteristik API agar dianggap REST

Agar sebuah API benar-benar dapat disebut REST, ada beberapa prinsip penting yang perlu dipenuhi.

## 1. Stateless

Setiap request harus membawa semua informasi yang dibutuhkan server.

Artinya server tidak perlu mengingat request sebelumnya untuk memahami request saat ini.

### Contoh
Jika request membutuhkan token login, maka token itu harus ikut dikirim pada request tersebut, bukan mengandalkan ingatan server dari request sebelumnya.

## 2. Client-Server

Ada pemisahan yang jelas antara sisi client dan sisi server.

- Client fokus pada tampilan dan interaksi pengguna.
- Server fokus pada data, logika bisnis, dan pemrosesan.

Keuntungan utamanya adalah keduanya bisa dikembangkan secara terpisah.

## 3. Cacheable

Response tertentu boleh disimpan sementara agar tidak selalu meminta ulang ke server.

Manfaatnya:

- lebih cepat,
- mengurangi beban server,
- menghemat bandwidth.

## 4. Uniform Interface

REST menekankan antarmuka yang seragam. Ini adalah salah satu ciri paling penting.

Artinya:

- resource dikenali dengan URI,
- aksi dilakukan dengan method standar,
- pesan request dan response harus jelas,
- struktur komunikasi dibuat konsisten.

Prinsip ini membuat API lebih mudah dipelajari dan dipakai.

## 5. Layered System

Sistem REST dapat terdiri dari beberapa lapisan, misalnya:

- client,
- gateway,
- proxy,
- load balancer,
- server utama,
- database.

Client tidak harus tahu apakah ia terhubung langsung ke server utama atau melalui lapisan lain.

## 6. Code on Demand

Dalam kondisi tertentu, server bisa mengirim kode yang dijalankan di client.

Namun, prinsip ini bersifat opsional dan jarang menjadi fokus utama pada REST API modern.