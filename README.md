# Caristo Mulenga — Portfolio

## Structure
```
/
├── index.html                          # the whole site — single file, no build step
├── splitzk.html                        # standalone SplitZK project demo
├── images/
│   ├── favicon.svg                     # generated brand favicon (ready to use)
│   └── caristo-profile.jpg             # ⚠️ ADD YOUR OWN PHOTO HERE (see below)
├── assets/
│   └── Caristo-Mulenga-Resume.pdf      # generated from your resume — replace if you update it
├── robots.txt
├── sitemap.xml
└── README.md
```

## Before you deploy — replace these placeholders

Search `index.html` for `caristo-dev` (8 occurrences) and replace with your real GitHub
username once you've created the repo. These appear in:
- Canonical URL, Open Graph URL, Twitter card, JSON-LD `url`/`sameAs` (SEO/meta tags)
- Footer GitHub link
- Project card GitHub/demo links (SplitZK, NyumbaNi)

## Add your photo

`images/caristo-profile.jpg` doesn't exist yet — the `<img>` tag has a fallback
(`onerror`) so the page won't break, it'll just hide that photo circle. Drop a square
photo (roughly 400×400px, JPG, under 200KB) at that exact path and it'll appear.

## Updating the resume

If you edit your resume later, regenerate the PDF and overwrite
`assets/Caristo-Mulenga-Resume.pdf` — the download button in the hero already points here.
