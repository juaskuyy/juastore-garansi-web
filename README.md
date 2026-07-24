# JuaStore Garansi Web v2 Final

Frontend ini langsung terhubung ke:
`https://juastore-garansi-worker.jhonyoga01.workers.dev`

## Cara pasang
1. Hapus file lama di repository `juastore-garansi-web`.
2. Upload semua file dari ZIP ini: `worker.js`, `wrangler.jsonc`, `package.json`, `index.html`, dan `README.md`.
3. Commit changes.
4. Cloudflare akan build otomatis. Jika tidak, tekan Retry build.
5. Build command: `npm install`
6. Deploy command: `npx wrangler deploy`
7. Root directory: `/`

`index.html` disertakan sebagai sumber yang mudah dibaca. Worker menyajikan salinan HTML yang sama secara langsung.
