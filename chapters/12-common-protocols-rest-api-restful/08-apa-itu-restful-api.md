# Apa itu RESTful API?

**RESTful API** adalah API yang dirancang berdasarkan prinsip REST. Biasanya API ini memakai HTTP sebagai media komunikasi dan sering menggunakan **JSON** sebagai format data utama.

Saat client mengirim request, server akan mengembalikan **representasi** dari resource yang diminta. Representasi ini bisa berupa:

- JSON,
- XML,
- HTML,
- plain text,
- atau format lain sesuai kebutuhan.

## Contoh sederhana

Misalnya ada endpoint:

```bash
GET /users/1
```

Server bisa mengembalikan response seperti ini:

```json
{
  "id": 1,
  "name": "Budi",
  "email": "budi@mail.com"
}
```

Artinya client meminta data user dengan ID `1`, lalu server mengirim representasi data user tersebut.