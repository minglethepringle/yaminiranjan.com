# yaminiranjan.com

Static rebuild of the former WordPress site, built with [Eleventy](https://www.11ty.dev/).

```
npm install
npm start       # dev server at http://localhost:8080
npm run build   # outputs to _site/
```

Deploy `_site/` to any static host (Netlify, Cloudflare Pages, GitHub Pages, etc.).

- Pages: `src/*.njk`; shared header/footer: `src/_includes/base.njk`
- Styles: `src/assets/css/style.css`
- Images: `src/assets/img/`

## Contact form

The form posts to `contactFormAction` in `src/_data/site.json` (currently blank). Create a form at
[Formspree](https://formspree.io) and paste its endpoint (e.g. `https://formspree.io/f/abc123`) there.
