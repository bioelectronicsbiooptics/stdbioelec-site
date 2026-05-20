# STD Bioelectronics site

GitHub Pages site for `stdbioelec.com`.

## Main files

- `index.html`: research homepage
- `publications.html`: year-grouped Google Scholar publication list
- `papers/electric-field-guided-dna-storage.html`: visual explainer copied from the local Science Advance folder
- `assets/STDbio.png`, `assets/BEBO.png`: original lab logos
- `assets/STDbio-web.png`, `assets/BEBO-web.png`: web-sized logo assets
- `SOCIAL_SETUP.md`: X / social account setup notes

## Publication source

The publication list was built from:

```text
https://scholar.google.com/citations?hl=en&user=NqwCwVcAAAAJ&view_op=list_works&sortby=pubdate
```

Snapshot date: 2026-05-20 KST.

## Update workflow

```bash
cd /Users/young/Desktop/stdbioelec-site
git status
git add index.html publications.html papers assets README.md SOCIAL_SETUP.md
git commit -m "Update research homepage and publication archive"
git push origin main
```

GitHub Pages publishes from the `main` branch.
