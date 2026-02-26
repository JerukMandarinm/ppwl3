# ppwl3

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.3.8. [Bun](https://bun.com) is a fast all-in-one JavaScript runtime.


# Praktikum Modul 3 – Tailwind CSS

## Praktikum 2 – Perbedaan Tailwind CSS v3 vs v4

1. **Variabel CSS Modern**
   v3 Menggunakan nilai statis yang di-generate ke dalam class.
   v4 Sekarang menjadi CSS-variable-first. Semua tema (warna, spacing, dll) tersedia sebagai variabel CSS asli di browser.

2. **Ukuran Paket (Package Size)**
   Tailwind v4 jauh lebih ringan secara internal:
   Ukuran paket yang diinstal berkurang lebih dari 35%.

## Praktikum 4 – Box Model Tailwind CSS
Jika memberi warna pada latar belakang elemen bg-blue-600, bagian type box yang terpengaruh adalah content box & padding box.
