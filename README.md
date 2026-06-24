# $WENFUN site

Static landing page, same concept as stumps-site but themed for Wendy's:
- Hold $WENFUN → receive tokenized $WEN (Wendy's Co., NASDAQ: WEN) every 5 minutes.
- 100% allocation to $WEN (single-stock basket).
- Logo + favicon: `public/logo.png` (green-haired Wendy mascot).

## Local preview

```
cd public
python -m http.server 5577
# open http://localhost:5577
```

## Deploy to Vercel

```
npm i -g vercel
vercel deploy --prod
```

`vercel.json` points the output directory at `public/`.
