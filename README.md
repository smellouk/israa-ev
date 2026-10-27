# Der Algerische Israa-Verein in Deutschland e.V.

Source of the association's website, [israa-ev.org](https://israa-ev.org), in German and Arabic.

Plain HTML and CSS: no JavaScript, no build step, no cookies, no third-party requests.
GitHub Pages serves the `docs/` folder directly.

```
docs/
  index.html         German (default)
  kontakt.html, impressum.html, datenschutz.html
  ar/                Arabic (right-to-left), same file names
  assets/            CSS, fonts, logo
  404.html
brand/               logo masters (1024 px, transparent): colour and white
```

## Preview locally

```
python3 -m http.server -d docs 8000
```

Then open http://localhost:8000.

## Editing

- Every page exists in both languages. Change the German page and its Arabic counterpart
  together, and keep the language links in the header pointing at each other.
- The legal name and address must appear exactly the same everywhere (Impressum,
  Datenschutz, contact page, footer and the structured data in `docs/index.html`).
  The German Impressum and Datenschutzerklärung are the legally binding versions.
- Keep the site free of third-party requests. Embedding Google Maps, YouTube,
  Facebook widgets, Google Fonts or analytics requires updating the
  Datenschutzerklärung and usually a consent banner.
- Only publish photos of people who have agreed to it.

## Contact

[contact@israa-ev.org](mailto:contact@israa-ev.org)

## License

Texts, logo and images © Der Algerische Israa-Verein in Deutschland e.V. All rights reserved.
The font Readex Pro is licensed under the SIL Open Font License 1.1
(see `docs/assets/fonts/OFL.txt`).
