# Jasa Suruh Jepara

Static landing page ringan untuk Jasa Suruh Jepara.

## Files

- `index.html` - halaman utama
- `styles.css` - styling responsive
- `favicon.svg` - favicon
- `nginx-jasasuruhjepara.conf` - contoh konfigurasi Nginx untuk VPS

## Deploy VPS

Upload `index.html`, `styles.css`, dan `favicon.svg` ke:

```bash
/var/www/jasasuruhjepara
```

Lalu arahkan Nginx ke folder tersebut. Contoh konfigurasi ada di
`nginx-jasasuruhjepara.conf`.
