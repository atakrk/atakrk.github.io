# atakuruk.com

Source for my personal site, served by GitHub Pages at
[atakuruk.com](https://atakuruk.com).

One self-contained `index.html` — no build step, no framework, no runtime
dependencies beyond a webfont. A personal site should still load on a bad
connection in five years.

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## Deployment

Pushing to `main` publishes. `CNAME` holds the custom domain; DNS points at
GitHub Pages with four A and four AAAA records on the apex and a CNAME on
`www`.
