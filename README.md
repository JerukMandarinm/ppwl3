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

## Praktikum 2 – Perbedaan Tailwind CSS v3 dan v4

1. **Konfigurasi**
   Tailwind v3 bergantung pada file tailwind.config.js untuk tema dan utilities kustom, sementara v4 menggunakan directive @theme dan CSS variables langsung di CSS untuk kemudahan integrasi.

2. **Performa**
   v4 memiliki engine lebih kecil dan build time lebih cepat berkat optimasi CSS variables serta incremental builds, dibandingkan v3 yang lebih lambat pada proyek besar.

## Praktikum 4 – Box Model Tailwind CSS

Jika memberi warna pada latar belakang elemen bg-blue-600, komponen model box yang terpengaruh adalah content box dan padding box.
