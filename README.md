# Jasa Suruh Jepara

Landing page statis untuk layanan bantuan harian lokal di Jepara.

**Apa pun urusannya, tinggal suruh.**

[![Website](https://img.shields.io/badge/Live%20Website-jasasuruhjepara.isacool.my.id-d7fb4f?style=for-the-badge&labelColor=111827)](https://jasasuruhjepara.isacool.my.id/)
[![Static](https://img.shields.io/badge/Static-HTML%20%2B%20CSS-38bdf8?style=for-the-badge&labelColor=111827)](#tech-stack)

## Website Preview

![Screenshot Website Jasa Suruh Jepara](screenshot-website.png)

## Poster Preview

![Poster Jasa Suruh Jepara](poster-jasa-suruh-jepara-v2.png)

## Overview

Jasa Suruh Jepara adalah konsep **personal errand service** untuk membantu kebutuhan harian seperti mengambil barang, mengantar dokumen, membeli kebutuhan, antre, mencari barang, dan permintaan khusus yang aman serta legal.

Repo ini berisi versi landing page yang dibuat **super ringan**: hanya HTML, CSS, dan SVG. Tidak ada framework, build step, database, atau runtime Node.js di server.

## Live Site

Website aktif:

[https://jasasuruhjepara.isacool.my.id/](https://jasasuruhjepara.isacool.my.id/)

## Tech Stack

- HTML statis
- CSS responsif
- SVG favicon
- Apache virtual host untuk VPS produksi
- Nginx config contoh jika ingin migrasi ke Nginx

## Project Structure

```text
.
├── index.html
├── styles.css
├── favicon.svg
├── screenshot-website.png
├── poster-jasa-suruh-jepara-v2.png
├── apache-jasasuruhjepara.conf
├── nginx-jasasuruhjepara.conf
└── README.md
```

## Local Preview

Jalankan server statis sederhana dari root project:

```bash
python -m http.server 8080
```

Lalu buka:

```text
http://localhost:8080
```
