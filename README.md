# Endor

A one-page static marketing-agency website based in Pauri Garhwal, Uttarakhand.

**Live site:** https://rageyfrodo.github.io/endor/

The site uses plain HTML, CSS, and original SVG artwork. There are no dependencies, trackers, forms, or external asset requests.

## Preview locally

```sh
python3 -m http.server 8175 --bind 127.0.0.1 --directory site
```

Open http://127.0.0.1:8175. Edit `site/index.html` for content and `site/styles.css` for presentation.

## Deploy

Push to `main` or run the **Deploy Endor** workflow manually. GitHub Pages must use GitHub Actions as its publishing source. Only `site/` is uploaded to Pages.
