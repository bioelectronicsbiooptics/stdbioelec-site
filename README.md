# STD Bioelectronics site

GitHub Pages site for `stdbioelec.com`.

## Main files

- `index.html`: Korean default research homepage served at `stdbioelec.com`
- `index-en.html`: English research homepage
- `index-ko.html`: Korean alias page kept for older links
- `publications.html`, `publications-ko.html`: English and Korean year-grouped Google Scholar publication lists
- `class.html`, `class-ko.html`: LLM from Scratch class entry pages
- `classes/llm-from-scratch/`: public HTML copy of the LLM from Scratch study notes
- `assets/site.css`: shared homepage, publication, and class page styles
- `papers/electric-field-guided-dna-storage.html`: visual explainer copied from the local Science Advance folder
- `papers/dna-data-ink-digital-preservation.html`: ACS Nano DNA data ink visual explainer
- `papers/enzyme-free-dna-ligation-mirna.html`: Cell Reports Physical Science miRNA ligation visual explainer
- `assets/STDbio.png`, `assets/BEBO.png`: original lab logos
- `assets/STDbio-web.png`, `assets/BEBO-web.png`: web-sized logo assets
- `SOCIAL_SETUP.md`: X / social account setup notes

## Local class source

The public class pages now link a generated HTML copy of the LLM from Scratch
study notes:

```text
classes/llm-from-scratch/
```

That public copy was copied from:

```text
/Users/young/Desktop/Deep_Learning_from_Scratch/LLM_scratch_v2/html
```

Local teaching materials, including English notes, Korean notes, linked notes,
HTML pages, and PPTX material, are organized under:

```text
/Users/young/Desktop/Deep_Learning_from_Scratch/LLM_scratch_v2
```

Before publishing refreshed textbook-derived notes or figures, confirm that the
lab has the right to make that material public.

Official source-code links should still point to the upstream repositories:

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
git add index.html index-en.html index-ko.html publications.html publications-ko.html class.html class-ko.html classes papers assets README.md SOCIAL_SETUP.md
git commit -m "Update research homepage and publication archive"
git push origin main
```

GitHub Pages publishes from the `main` branch.
