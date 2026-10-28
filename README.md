<div align="center">
  <a href="https://prayushdesai.com">
    <img src="favicon.svg" alt="pd" width="64" height="64">
  </a>
  <h1>prayushdesai.com</h1>
  <p>
    Source for my personal site. Hand-written HTML and CSS, no framework,<br>
    hosted on <a href="https://pages.github.com">GitHub Pages</a>.
  </p>
  <p>
    <a href="https://prayushdesai.com"><strong>Visit the site →</strong></a>
  </p>
</div>

<br>

<a href="https://prayushdesai.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/preview-dark.png">
    <img alt="Screenshot of prayushdesai.com" src="assets/preview-light.png">
  </picture>
</a>

## Status

The full version — projects, write-ups and a résumé — is in progress. For now the homepage is a single landing page with my links.

## Stack

- **Markup & styles:** plain HTML and CSS in a single file, nothing to build
- **Type:** [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif), [Inter Tight](https://fonts.google.com/specimen/Inter+Tight) and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
- **Hosting:** GitHub Pages
- **Domain & DNS:** Cloudflare

## Structure

```
.
├── index.html      # the whole homepage: markup, styles and the clock script
├── 404.html        # served by GitHub Pages for unknown paths
├── favicon.svg
├── assets/         # social preview image and README screenshots
├── robots.txt
├── sitemap.xml
└── CNAME           # points GitHub Pages at prayushdesai.com
```

## Running locally

There's no build step. Clone it and open the file, or serve the folder so the root-relative paths resolve:

```sh
git clone https://github.com/prayush27/portfolio.git
cd portfolio
python3 -m http.server 8000
```

Then go to [localhost:8000](http://localhost:8000).

## Using this code

You're welcome to borrow from it. The code is MIT-licensed, so take what's useful. If you base your own site on the design, a link back to [prayushdesai.com](https://prayushdesai.com) would be appreciated. Please don't publish my name, photos or writing as your own.

## Contact

[pdesai25@wisc.edu](mailto:pdesai25@wisc.edu) · [LinkedIn](https://linkedin.com/in/prayushdesai)
