---
marp: true
title: Product Docs — Overview
author: 24f2005647@ds.study.iitm.ac.in
theme: product-docs
paginate: true
math: katex
footer: '© 2025 — Product Docs | 24f2005647@ds.study.iitm.ac.in'
---

<!-- _class: lead -->
<!-- _backgroundColor: #0e141b -->
<!-- _color: #ffffff -->
# Product Documentation (Marp)

**Author:** 24f2005647@ds.study.iitm.ac.in  
**Goal:** Maintainable docs in version control, exportable to HTML/PDF/PPTX.

---

## Why Marp for Product Docs?

- Markdown-first workflow
- Version-control friendly (Git)
- One source → many formats (HTML/PDF/PPTX)
- Custom themes via CSS
- Page numbers enabled ✅

---

<!-- Background image slide -->
![bg cover](images/hero.jpg)

# Architecture at a Glance

*Use a branded or relevant product image as background (images/hero.jpg).*

---

<!-- _header: **Setup** -->
## Getting Started

1. Install Marp CLI (`npm i -D @marp-team/marp-cli`)
2. Write docs in `slides.md`
3. Export:
   - `marp slides.md -o dist/slides.html`
   - `marp slides.md --pdf --allow-local-files`
   - `marp slides.md --pptx`

> Tip: `marp -s .` for live preview.

---

## Styling with Marp Directives

- `<!-- _class: lead -->` — larger, centered title slide
- `<!-- _backgroundColor: #123456 -->` — custom background
- `<!-- _color: red -->` — text color
- `footer:` & `header:` — per-slide or global
- **Theme:** `theme: product-docs` (our custom theme in `themes/custom.css`)

---

## Code Snippet

```bash
# Export to HTML/PDF/PPTX
marp slides.md -o dist/slides.html
marp slides.md --pdf --allow-local-files
marp slides.md --pptx
