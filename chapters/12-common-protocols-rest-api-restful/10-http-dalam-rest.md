# HTTP dalam REST

REST sangat erat dengan HTTP. Karena itu, REST memanfaatkan method HTTP untuk menyatakan aksi terhadap resource.

## Method HTTP yang umum dipakai

- `GET` → mengambil data.
- `POST` → menambahkan data baru.
- `PUT` → memperbarui seluruh data resource.
- `PATCH` → memperbarui sebagian data resource.
- `DELETE` → menghapus data.

## Selain method, REST juga memanfaatkan

- **URI** untuk alamat resource,
- **header** untuk metadata,
- **status code** untuk hasil request,
- **query parameter** untuk filter atau pencarian,
- **authentication/authorization** untuk keamanan,
- **cache** untuk efisiensi.

## Contoh

```bash
GET /products
GET /products/10
POST /products
DELETE /products/10
```

Dari URI dan method saja, kita sudah bisa menebak fungsi endpoint tersebut.