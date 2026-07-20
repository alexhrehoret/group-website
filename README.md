# Group website — Nazario Martín research group

Static single-page site (HTML/CSS/JS, everything self-contained) for the
Nazario Martín research group, deployed on GitHub Pages.

> **Live site:** [www.nazariomartingroup.com](https://www.nazariomartingroup.com) — the fully maintained group website.

## Stack

- Single self-contained `index.html` — all CSS and JS are inlined, no build
  step, no framework, no backend
- Hosted free on GitHub Pages (root `index.html` served directly)
- Publication list loaded from `content/publications.json` at runtime —
  updating publications never means touching HTML

## Structure

```
index.html                       full site (HTML + CSS + JS, self-contained)
content/
  publications.example.json      placeholder publication data (structure reference)
  publications.json              real publication list — gitignored, not in repo
```

## Content status

The `index.html` in this repo is a representative demo — it shows the full
site structure and one example of each content type (member card, news item,
publication entry) but does not include the complete real data.
`content/publications.example.json` shows the expected data structure for
the publication list.

## License

The code (HTML structure, CSS, JavaScript) is released under the MIT licence —
meaning anyone can freely use, copy, or modify it. The content (group name,
research descriptions, any real member or publication data) belongs to the
Nazario Martín research group and is not covered by this licence.
