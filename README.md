# wearethewatchers-site

Public static site bundle for CUSTOS at `https://wearethewatchers.com/`.

## Source of Truth

The private/source launch package lives in `CODEX_CUSTOSGEAR/custos-launch`. Export a fresh public bundle with:

```bash
cd /Users/ninjatom/Documents/CODEX_CUSTOSGEAR/custos-launch
npm run export:site
```

Copy the contents of `/tmp/wearethewatchers-site` into this public repo, then run the manual GitHub Pages workflow when ready.

## GitHub Pages Domain

- Custom domain: `wearethewatchers.com`
- CNAME file: `CNAME`
- Enforce HTTPS after Pages certificate is available.
- Do not add wildcard DNS records.
