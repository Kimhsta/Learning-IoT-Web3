# Resource dan URI

Dalam REST, semua hal yang dikelola dianggap sebagai **resource**. Resource itu bisa berupa:

- user,
- produk,
- artikel,
- transaksi,
- komentar,
- file,
- dan sebagainya.

Setiap resource sebaiknya punya URI yang jelas dan konsisten.

## Contoh URI

```bash
/users
/users/1
/products
/products/10
/orders/99
```

## Kenapa penting?

Karena URI yang baik membuat API:

- lebih mudah dipahami,
- lebih mudah didokumentasikan,
- lebih mudah digunakan developer lain,
- lebih konsisten saat project membesar.