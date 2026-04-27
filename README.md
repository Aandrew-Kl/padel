# matchaki-public

Static public landing page for `matchaki.gr`.

This repo is intentionally separate from the main Matchki/Matchaki product codebase. It has no app API, no database connection, no auth, and no environment secrets.

## Local preview

```bash
python3 -m http.server 4173 --bind 127.0.0.1
```

Open:

```text
http://127.0.0.1:4173
```

## Hosting

Any static host can serve this folder directly:

- GitHub Pages
- Cloudflare Pages
- Netlify
- Railway static service
- Any nginx/apache bucket

`CNAME` is included for GitHub Pages custom-domain hosting with `matchaki.gr`.
