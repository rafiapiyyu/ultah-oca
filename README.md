# Web Ulang Tahun untuk Selvi

## Cara pakai
1. Buka `index.html`, edit blok `CONFIG` di bagian atas script:
   - `from` -> namamu
   - `letter` -> isi surat
   - `photos` -> daftar nama file foto + caption
   - `wishes` -> kartu doa
2. Taruh foto di folder `photos/` (nama file harus sama dengan di CONFIG).
3. (Opsional) Taruh lagu bernama `music.mp3` di folder yang sama dengan index.html.
4. Jika semua foto sudah terpasang, ubah `hideMissingPhotos` menjadi `true`.

## Cara hosting gratis
- Netlify Drop: buka https://app.netlify.com/drop lalu seret seluruh folder ini.
- GitHub Pages: upload ke repo, Settings -> Pages -> pilih branch main.
- Vercel / Cloudflare Pages: import folder atau repo ini.

Tip: kompres foto dulu (maks ~300 KB per foto) supaya cepat dibuka di HP.
