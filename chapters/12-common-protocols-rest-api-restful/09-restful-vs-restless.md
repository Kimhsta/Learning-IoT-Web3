# RESTful vs RESTless

Tidak semua API yang terlihat modern otomatis RESTful. Ada API yang tampak seperti REST, tetapi tidak benar-benar mengikuti prinsip-prinsip REST. Ini kadang disebut **RESTless**.

## Contoh RESTless

Misalnya semua operasi API dibuat seperti ini:

```bash
POST /getUser
POST /createUser
POST /deleteUser
POST /updateUser
```

Secara teknis ini bisa bekerja, tetapi desainnya tidak RESTful karena semua aksi dipaksa memakai `POST`.

Desain RESTful biasanya lebih seperti ini:

```bash
GET    /users/1
POST   /users
PUT    /users/1
PATCH  /users/1
DELETE /users/1
```

Desain seperti ini lebih konsisten, mudah dibaca, dan sesuai dengan prinsip REST.