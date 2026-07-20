# Group website — Nazario Martín research group

Static single-page site (HTML/CSS/JS, everything self-contained) for the
Nazario Martín research group, deployed on GitHub Pages.

> **Live site:** [www.nazariomartingroup.com](https://www.nazariomartingroup.com) — the fully maintained group website.

## ⚠️ Repository visibility

**Keep this repository PRIVATE until explicit sign-off from the group /
Nazario Martín.** This is institutional content, not a personal project —
authorization covers the code, not necessarily the real content (member
names, photos, publication data).

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

`content/publications.example.json` shows the expected data structure.
The real content (`publications.json`, member photos, etc.) is gitignored and
gets added once the repo's use is confirmed with the group.

## License

Code: MIT (see LICENSE). Content (once real) is not covered by this license
and belongs to the research group.
