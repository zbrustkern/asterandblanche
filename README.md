# Aster & Blanche Press

> *Boutique stationery atelier & bespoke paper goods — Lake Forest, Illinois*

[![Live Site](https://img.shields.io/badge/atelier-asterandblanche.com-23201D?style=flat-square&labelColor=FCFAF7)](https://asterandblanche.com)
[![Cardstock](https://img.shields.io/badge/cardstock-120%20lb%20Archival-544F48?style=flat-square&labelColor=FCFAF7)](https://asterandblanche.com)

---

## 1. Project Identity & Purpose ("The Brand Shield")

**Aster & Blanche Press** is a heritage letterpress atelier imprint based in Lake Forest, Illinois. The brand serves as the physical imprint and authentic colophon stamped on the reverse of premium handwritten correspondence.

When a recipient receives a handwritten card in the mail, tears open the envelope, and turns the card over, they see the architectural house vignette and the Aster & Blanche colophon. If they look up [asterandblanche.com](https://asterandblanche.com), this site exists to **validate the craftsmanship, protect the brand mystique, and preserve the prestige of the physical artifact**.

### The "Quiet Luxury" Design Canon

This web property is **not** a SaaS marketing funnel, e-commerce storefront, or tech product landing page. It operates under strict editorial restraint:

- **What it is:** A serene, museum-grade digital atelier. An architectural and typographic presence that feels akin to Crane & Co., a historic Savile Row tailor, or a private European printing house.
- **What it strictly is NOT:**
  - ❌ **No software or automation jargon:** Never mention "robots", "plotters", "APIs", "software", "AI", or "tech platforms".
  - ❌ **No commercial noise:** No shopping carts, no checkout popups, no countdown banners, no cookie modals, and no flashing conversion elements.
  - ❌ **No digital shortcuts:** Language always honors the physical reality—*"real ballpoint pen on paper"*, *"curated ink"*, *"tactile indentations"*, and *"first-class postal dispatch"*.
  - ❌ **The Single Bridge:** The digital commissioning desk is subtly linked out to `sendmynotes.com` for patrons seeking private correspondence on demand.

---

## 2. Design System & Aesthetic Specifications

The aesthetic system is calibrated to replicate the look and tactile tooth of archival uncoated paper and genuine pen ink.

### Color Palette

| Swatch | Hex | CSS Variable | Architectural & Editorial Role |
| :--- | :--- | :--- | :--- |
| ![#FCFAF7](https://via.placeholder.com/15/FCFAF7/000000?text=+) | `#FCFAF7` | `--bg-cream` | **Warm Paper:** Archival vellum background, SVG paper fill |
| ![#F6F2EC](https://via.placeholder.com/15/F6F2EC/000000?text=+) | `#F6F2EC` | `--bg-warm` | **Warm Tint:** Inset manifesto card and subtle depth panels |
| ![#23201D](https://via.placeholder.com/15/23201D/000000?text=+) | `#23201D` | `--ink-primary` | **Primary Ink:** Editorial typography & primary architectural outlines (1.8px / 1.2px) |
| ![#544F48](https://via.placeholder.com/15/544F48/000000?text=+) | `#544F48` | `--ink-secondary` | **Midtone Ink:** Secondary body copy, roof slopes, and fine drafting lines (0.75px) |
| ![#878177](https://via.placeholder.com/15/878177/000000?text=+) | `#878177` | `--ink-muted` | **Hairline:** Architectural drafting cross-hatching (0.5px), metadata, footnotes |
| ![#D1CCC4](https://via.placeholder.com/15/D1CCC4/000000?text=+) | `#D1CCC4` | `--rule-accent` | **Rule Accent:** Typographic hairline rules and colophon dividers |
| ![#A58B6F](https://via.placeholder.com/15/A58B6F/000000?text=+) | `#A58B6F` | `--gold-accent` | **Gold Accent:** Section eyebrows, numerals, and colophon flourishes |

### Typography System

| Element | Typeface Stack | Weight | Tracking / Letter-Spacing | Transform |
| :--- | :--- | :--- | :--- | :--- |
| **Brand Masthead** | `Cormorant Garamond`, `Cinzel`, Georgia, serif | 600 (Semibold) | `9px` (`margin-right: -9px`) | Uppercase |
| **Press Label** | `Inter`, system sans-serif | 500 (Medium) | `7px` (`margin-right: -7px`) | Uppercase |
| **Location Subtitle**| `Cormorant Garamond`, `Cinzel`, serif | 500 (Medium) | `5px` (`margin-right: -5px`) | Uppercase |
| **Hero Heading** | `Cormorant Garamond`, Georgia, serif | 500 (Medium) | `-0.01em` | Normal |
| **Body & Prose** | `Inter`, -apple-system, sans-serif | 400 (Regular) | `0` (Line height: 1.7) | Normal |
| **Eyebrows / Badges**| `Inter`, -apple-system, sans-serif | 600 (Semibold) | `0.25em` – `0.28em` | Uppercase |

> **Optical Alignment Rule:** Whenever wide letter-spacing (`letter-spacing: 9px`) is applied to centered text, an equal negative right margin (`margin-right: -9px`) must be applied to prevent the text from optically shifting leftward.

---

## 3. Physical Colophon & Architectural Mark

The architectural house vignette portrays the historic Aster & Blanche estate in Lake Forest, Illinois.

```
       ┌────────────────────────────────────────────────────────┐
       │                                                        │
       │                   [ Roof & Chimneys ]                  │
       │                 ┌─────────────────────┐                │
       │                 │  ARCHITECTURAL MARK │                │
       │                 │    (HOUSE VIGNETTE) │                │
       │                 └─────────────────────┘                │
       │               [ Stone Walkway Foundation ]             │
       │                                                        │
       │                         — • —                          │
       │                   ASTER & BLANCHE                      │
       │                        PRESS                           │
       │                        ─────                           │
       │                LAKE FOREST, ILLINOIS                   │
       │                                                        │
       └────────────────────────────────────────────────────────┘
```

- **Canvas Scale:** A2 Folded Card (`4.25" × 5.5"` at 200 DPI = `850px × 1100px`).
- **Paper Stock:** 120 lb archival uncoated cardstock.
- **Vector Assets:**
  - [`aster-blanche-backplate.svg`](./aster-blanche-backplate.svg): Production-ready vector source for the complete A2 card backplate.
  - [`public/aster-blanche-backplate.svg`](./public/aster-blanche-backplate.svg): Mirror asset for web applications and static builds.
  - [`index.html`](./index.html): Inline vector rendering in the hero (`viewBox="86 38 485 262"`) and interactive card reverse frame.

---

## 4. Repository Structure

```
asterandblanche/
├── .nojekyll                   # Disables Jekyll processing on GitHub Pages
├── CNAME                       # Custom domain routing (asterandblanche.com)
├── favicon.ico                 # Atelier crest browser favicon
├── index.html                  # Single-file, zero-dependency master atelier page
├── aster-blanche-backplate.svg # Master A2 card backplate vector asset
├── og-image.png                # Social preview card metadata asset
├── public/
│   └── aster-blanche-backplate.svg
├── robots.txt                  # Search indexing directives
└── README.md                   # Brand canon & engineering documentation
```

---

## 5. Local Development & Deployment

This project requires **zero build steps, zero node_modules, and zero external compilers**.

### Local Preview

You can preview the site using any static web server:

```bash
# Using Python 3 (standard on macOS)
python3 -m http.server 8000

# Using Node.js npx serve
npx serve .

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

### Production Deployment

- **Hosting:** Static GitHub Pages or any CDN (Cloudflare Pages, Fastly, AWS S3 / CloudFront).
- **Domain:** Configured via `CNAME` pointing to `asterandblanche.com`.
- **Cache-Control:** All HTML and SVG files are lightweight and sub-50KB for sub-millisecond edge delivery.

---

## 6. Guardrails for Future Contributors

When contributing to this repository, please observe the following guardrails:

1. **Protect the Brand Persona:** Under no circumstances should automated robot terminology or corporate SaaS tropes be introduced to this repository.
2. **Preserve Vector Crispness:** Do not substitute low-resolution raster imagery for the vector house vignette. Keep the vector strokes aligned with the four stroke weight tiers (`1.8px`, `1.2px`, `0.75px`, `0.5px`).
3. **Keep It Lightweight:** Maintain zero runtime dependencies. The entire site must load instantly on mobile devices with zero layout shift.
4. **Lock Backplate Artwork:** The backplate artwork in `aster-blanche-backplate.svg` is finalized and centered for the A2 folded cardstock. Do not alter geometry without re-verifying physical print proofs.

---

*Aster & Blanche Press &bull; Lake Forest, Illinois &bull; Est. 2026*
