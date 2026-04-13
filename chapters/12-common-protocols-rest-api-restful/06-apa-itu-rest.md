# Apa itu REST?

**REST (Representational State Transfer)** adalah gaya arsitektur untuk membangun layanan web. REST bukan protokol dan bukan standar resmi yang kaku, tetapi kumpulan prinsip yang membantu kita merancang API dengan cara yang rapi, ringan, dan mudah dikembangkan.

REST umumnya berjalan di atas **HTTP**, yaitu protokol yang juga dipakai saat kita membuka website.

## Ide utama REST

Dalam REST, data dipandang sebagai **resource**. Setiap resource punya alamat yang jelas, lalu diakses dengan method HTTP tertentu.

Contoh resource:

```bash
/users/1
```

Artinya: resource user dengan ID `1`.

Jadi, REST fokus pada:

- **resource** apa yang diakses,
- **alamat resource** di mana,
- **aksi** apa yang ingin dilakukan terhadap resource tersebut.