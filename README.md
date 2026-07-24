# JuaStore Garansi Web

Frontend final untuk domain `https://juastore.biz.id`.

API sudah diarahkan ke:
`https://juastore-garansi-worker.jhonyoga01.workers.dev`

## Deploy Cloudflare Pages
1. Buat repository GitHub baru: `juastore-garansi-web`.
2. Upload `index.html` dan `README.md`.
3. Di Cloudflare: Workers & Pages → Create → Pages → Connect to Git.
4. Pilih repo `juastore-garansi-web`.
5. Framework preset: None.
6. Build command: kosong.
7. Build output directory: `/`.
8. Deploy.
9. Tambahkan custom domain `juastore.biz.id`.

Catatan: Worker membatasi akses CORS ke `https://juastore.biz.id`, jadi pengiriman form diuji setelah custom domain aktif.
