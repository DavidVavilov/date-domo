# date-domo 🍣❤️

הזמנה אינטראקטיבית לדייט ב-[Domo Sushi](https://domo-sushi.co.il/) — יום חמישי 3.9.2026 בשעה 20:30.

A tiny static web app (single `index.html`, no build step) with a few Hebrew slides
and a "yes / no" question where the **no** button runs away from the cursor/finger.

## Run locally

Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Share the resulting URL.

## Customize

Edit the text in `index.html`. Date/time and place are in the `Config` block at the top of the `<script>`.
