# VIATOTO12 — Static SEO Landing Page

Template static HTML yang bisa di-host gratis di Cloudflare Pages, GitHub Pages,
Netlify, atau Vercel.

## 1. Ganti URL tujuan

Cari:

`https://YOUR-TARGET.example/`

di `index.html` dan `viatoto12/index.html`, lalu ganti dengan URL situs tujuan.

## 2. Ganti domain

Cari:

`https://YOUR-DOMAIN.example`

di:
- `index.html`
- `viatoto12/index.html`
- `robots.txt`
- `sitemap.xml`

Ganti dengan domain/subdomain deployment kamu.

## 3. Struktur URL

Halaman target keyword:

`https://DOMAIN-KAMU/viatoto12/`

## 4. Deploy gratis

### Cloudflare Pages
- Push folder ini ke GitHub.
- Cloudflare Dashboard → Workers & Pages → Create application.
- Import repository.
- Framework preset: None.
- Build command: kosong.
- Output directory: `/`
- Deploy.

### GitHub Pages
- Upload repository.
- Settings → Pages.
- Deploy from branch.
- Pilih branch `main` dan folder `/root`.

## 5. Indexing

Setelah domain aktif:
- Verifikasi domain di Google Search Console.
- Submit `https://DOMAIN-KAMU/sitemap.xml`.
- Gunakan URL Inspection untuk meminta crawling halaman `/viatoto12/`.
- Untuk Bing, verifikasi situs di Bing Webmaster Tools dan submit sitemap.
- Indexing tidak bisa dijamin instan atau dijamin ranking tertentu.

## Catatan

Jangan membuat banyak halaman doorway/redirect kosong hanya untuk memanipulasi
hasil pencarian. Gunakan konten yang benar-benar relevan dan bermanfaat.
