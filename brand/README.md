# Evergreen Consulting business card

- `business-card.pdf` — print-ready, 2 pages (page 1 = front, page 2 = back).
- `business-card.html` — the source. Logos are inlined, so the file works anywhere.
- `preview.png` — what it looks like.

## For the printer
- Trim size **3.5 × 2 in**; file is **3.75 × 2.25 in** with **0.125 in bleed** on all four edges.
- Double-sided, full colour. Colours: evergreen `#1F4A3C`, paper `#FAFAF7`, brass rule `#B8935A`.
- Suggested stock: 16pt matte or soft-touch. A matte finish suits the palette; avoid high gloss.
- Fonts are Fraunces and Albert Sans (Google Fonts), embedded in the PDF.

## To change it
Edit `business-card.html`, then:

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --disable-gpu \
  --no-pdf-header-footer --print-to-pdf=business-card.pdf --virtual-time-budget=8000 business-card.html
```
