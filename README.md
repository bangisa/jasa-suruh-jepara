# Jasa Suruh Jepara

Landing page statis untuk layanan bantuan harian lokal di Jepara.

**Apa pun urusannya, tinggal suruh.**

[![Website](https://img.shields.io/badge/Live%20Website-jasasuruhjepara.isacool.my.id-d7fb4f?style=for-the-badge&labelColor=111827)](https://jasasuruhjepara.isacool.my.id/)
[![Static](https://img.shields.io/badge/Static-HTML%20%2B%20CSS-38bdf8?style=for-the-badge&labelColor=111827)](#tech-stack)

![Poster Jasa Suruh Jepara](poster-jasa-suruh-jepara-v2.png)

## Overview

Jasa Suruh Jepara adalah konsep **personal errand service** untuk membantu kebutuhan harian seperti mengambil barang, mengantar dokumen, membeli kebutuhan, antre, mencari barang, dan permintaan khusus yang aman serta legal.

Repo ini berisi versi landing page yang dibuat **super ringan**: hanya HTML, CSS, dan SVG. Tidak ada framework, build step, database, atau runtime Node.js di server.

## Live Site

Website aktif:

[https://jasasuruhjepara.isacool.my.id/](https://jasasuruhjepara.isacool.my.id/)

## Services

| Layanan | Harga Mulai | Contoh |
|---|---:|---|
| Suruh Antar | Rp10.000 | Dokumen, barang kecil, titipan ringan |
| Suruh Ambil | Rp10.000 | Paket, laundry, barang tertinggal |
| Suruh Beli | Rp12.000 | Makanan, ATK, obat bebas, kebutuhan rumah |
| Suruh Antre | Rp15.000 | Antre makanan, ambil nomor, menunggu pesanan |
| Suruh Cari | Rp15.000 | Cari barang, cek toko, survei lokasi ringan |
| Suruh Apa Aja | Rp15.000 | Permintaan khusus yang aman dan legal |

## Pricing Rules

Struktur tarif dibuat sederhana:

```text
Harga = biaya dasar + jarak + waktu tunggu + tambahan aktual
```

Komponen tambahan:

- Tambahan jarak: `Rp3.000/km`
- Menunggu: `Rp5.000/20 menit`
- Lokasi tambahan: `Rp3.000/titik`
- Biaya aktual: sesuai struk atau kesepakatan

Harga final tetap dikonfirmasi melalui WhatsApp sebelum pekerjaan dilakukan.

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
