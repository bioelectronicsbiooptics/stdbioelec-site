# STD Bioelectronics site

GitHub Pages site for `stdbioelec.com`.

## Main files

- `index.html`: Korean default research homepage served at `stdbioelec.com`
- `index-en.html`: English research homepage
- `index-ko.html`: Korean alias page kept for older links
- `publications.html`, `publications-ko.html`: English and Korean year-grouped Google Scholar publication lists
- `class.html`, `class-ko.html`: LLM from Scratch class entry pages
- `assets/site.css`: shared homepage, publication, and class page styles
- `papers/electric-field-guided-dna-storage.html`: visual explainer copied from the local Science Advance folder
- `assets/STDbio.png`, `assets/BEBO.png`: original lab logos
- `assets/STDbio-web.png`, `assets/BEBO-web.png`: web-sized logo assets
- `SOCIAL_SETUP.md`: X / social account setup notes

## Local class source

The public class pages summarize the course structure without publishing copyrighted
book content. Local teaching materials are organized here:

```text
/Users/young/Desktop/Deep_Learning_from_Scratch/LLM_scratch
```

That folder contains English notes, Korean notes, linked notes, HTML pages, and
PPTX material. Public links should point to official repositories:

```text
https://github.com/rasbt/LLMs-from-scratch
https://github.com/rasbt/reasoning-from-scratch
```

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
git add index.html index-en.html index-ko.html publications.html publications-ko.html class.html class-ko.html papers assets README.md SOCIAL_SETUP.md
git commit -m "Update research homepage and publication archive"
git push origin main
```

GitHub Pages publishes from the `main` branch.
