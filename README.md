# Marciacq Travel Studio — Landing

Editorial landing page for Marciacq Travel Studio. Built strictly against the brand guide (Raleway + Cormorant italic accents, Perla/Linen/Verde Selva/Terracota palette, sober editorial tone).

## ⚠️ MOCKUP NOTICE

This is an **internal preview**. All photographs in `/images/` are placeholders sourced from third parties (ogayatravel.com, es.tourismpanama.com) for presentation purposes only.

**Before any public launch:**

1. Replace every photograph in `/images/`
2. Search `index.html` for `MOCKUP-IMG` to locate every slot
3. Use one of:
   - Marciacq's own production photography (recommended)
   - Licensed stock (Unsplash with attribution / Adobe Stock)
   - ATP press-kit imagery cleared for commercial use

The wordmark also uses **Cormorant Garamond italic** as a free-Google-Fonts substitute for the brand's **Mango Display**. Swap when Mango Display web license is acquired.

## Edit and deploy

```bash
cd ~/Projects/marciacq-landing
# edit index.html
./deploy.sh "describe the change"
```

Live URL appears in the deploy output. Currently:
**https://spiderguard.github.io/marciacq-landing/**

## Structure

```
marciacq-landing/
├── index.html       ← the page
├── images/          ← MOCKUP placeholders — replace before launch
│   ├── hero-jungle.jpg
│   ├── guna-yala-aerial.jpg
│   ├── baru-summit.jpg
│   └── boquete-cloudforest.jpg
├── deploy.sh
├── .nojekyll
└── README.md
```

## Brand fidelity

| Element | Source |
|---|---|
| Palette | Brand guide § 03 — Perla `#F5EFE9` / Linen `#E9DFD3` / Verde Selva `#2F4A3F` / Terracota `#A65A38` / Arena `#31251F` |
| Typography | Raleway 200–500 for everything · Cormorant italic (substitute for Mango Display) for signature moments |
| Voice | Strategist, not content creator. No "amazing", no "magical", no emoji, no "leave it to us" |
| Image direction | Atmospheric, natural light, single subject, never posed |

## Programs included (mock copy)

- ⭐ Featured: **The Adriatic Architecture** (Italy/Croatia · 12 nights · from USD 145,000)
- 01 — **Guna Yala · Open Water** (Panama Caribbean · from USD 58,000)
- 02 — **The Highland Threshold** (Boquete/Volcán Barú · from USD 42,000)
- 03 — **The Azuero Sequence** (Las Tablas/Pedasí · from USD 38,000)
- 04 — **The Atelier Route** (Paris/Geneva/Florence/Milan · from USD 128,000)
- 05 — **The Family Concession** (Andalusia · from USD 92,000)
- 06 — **The Offsite Mainframe** (Corporate / MICE · by brief)

All program names, descriptions, and prices are **mockup proposals** to demonstrate brand voice and pricing range. Confirm with Nicole before publishing.
