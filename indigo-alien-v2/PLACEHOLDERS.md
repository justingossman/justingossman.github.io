# Indigo Alien Beauty — Image Placeholder Inventory

Every image on the site occupies a labeled `.slot`. As of the **hybrid-fill pass**, no
slot renders empty — but **nothing here is final**. Every slot still needs real
photography before any public / marketing use.

Two fill strategies are in place:

- **EDITORIAL (11 slots)** — filled with **CSS-only cosmic/macro textures** (layered
  gradients + grain, no external images). The six diptych textures + the ingredient
  macro are strictly monochrome; the four colour cosmic slots carry a restrained indigo
  undertone. These are decorative stand-ins that read as "art direction," not final art.
- **PRODUCT (3) + MODELING (5)** — filled with **full-colour, full-quality stand-in
  photos**: six pre-cropped from `~/Desktop/kourtneyassets` into `img/standins/`, plus
  two client-supplied web-resolution photos of the founder in `img/photos/` (IMG-01
  hero, IMG-19 founder portrait). No dimming treatment and **no on-page label** — the
  layout reads as a finished design. These 8 are **temporary stand-ins tracked only in
  this file**; every one must be replaced with a licensed full-resolution original.

Types: **PRODUCT** (studio product shot) · **MODELING** (person / on-skin) ·
**EDITORIAL** (macro nature & cosmic imagery, incl. the monochrome diptych).

| ID     | Page          | Section                        | Type      | Rec. dimensions | Current fill                                   | Status        |
|--------|---------------|--------------------------------|-----------|-----------------|------------------------------------------------|---------------|
| IMG-01 | index.html    | Hero                           | MODELING  | 1200 × 1600 px  | Client campaign shot `photos/ia-hero-kourtney.jpg` (web-res) | ⚠ original needed |
| IMG-02 | index.html    | As Above, So Below — Pair I    | EDITORIAL | 1000 × 1250 px  | Shopify crop `shopify/diptych-bodyoil.jpg` (almonds, 944 × 1180) | ✓ client photo |
| IMG-03 | index.html    | As Above, So Below — Pair I    | EDITORIAL | 1000 × 1250 px  | Shopify crop `shopify/diptych-sunbalm.jpg` (raspberry, 800 × 1000) | ✓ client photo |
| IMG-04 | index.html    | As Above, So Below — Pair II   | EDITORIAL | 1000 × 1250 px  | Shopify crop `shopify/diptych-snailmucin.jpg` (bubbles, 896 × 1120) | ✓ client photo |
| IMG-05 | index.html    | As Above, So Below — Pair II   | EDITORIAL | 1000 × 1250 px  | Shopify crop `shopify/diptych-tallow.jpg` (vanilla, 800 × 1000) | ✓ client photo |
| IMG-06 | index.html    | As Above, So Below — Pair III  | EDITORIAL | 1000 × 1250 px  | Shopify crop `shopify/diptych-cleanser.jpg` (aloe, 700 × 875) | ✓ client photo |
| IMG-07 | index.html    | As Above, So Below — Pair III  | EDITORIAL | 1000 × 1250 px  | Shopify `shopify/diptych-swatch.jpg` (Sun Balm swatch, 1000 × 1250) | ✓ client photo |
| IMG-08 | index.html    | Luminous Offerings             | PRODUCT   | 900 × 1125 px   | Stand-in `standin-img08-product.jpg`           | ⚠ needs photo |
| IMG-09 | index.html    | Luminous Offerings             | PRODUCT   | 900 × 1125 px   | Stand-in `standin-img09-product.jpg`           | ⚠ needs photo |
| IMG-10 | index.html    | Luminous Offerings             | PRODUCT   | 900 × 1125 px   | Stand-in `standin-img10-product.jpg`           | ⚠ needs photo |
| IMG-11 | index.html    | Starseed Ritual Collection     | EDITORIAL | 2400 × 1000 px  | CSS texture `.sx-banner` (indigo). IMG_8124 render rejected — misspelled labels ("SOLAR SMELD SUN BALM" et al.) legible at banner size; crop kept unreferenced at `standins/standin-img11-banner.jpg` | ◑ CSS temp    |
| IMG-12 | rituals.html  | Intro row                      | EDITORIAL | 2400 × 1200 px  | CSS texture `.sx-ritual` (indigo)              | ◑ CSS temp    |
| IMG-13 | rituals.html  | The Sequence — Step i          | MODELING  | 900 × 1200 px   | Shopify `shopify/ritual-cleanser.jpg` (Kourtney, 1400 × 1400) | ✓ client photo |
| IMG-14 | rituals.html  | The Sequence — Step ii         | MODELING  | 900 × 1200 px   | Shopify `shopify/ritual-eyeserum.jpg` (Kourtney, 1400 × 1400) | ✓ client photo |
| IMG-15 | rituals.html  | The Sequence — Step iii        | MODELING  | 900 × 1200 px   | Shopify `shopify/ritual-richecreme.jpg` (Kourtney, 1400 × 1400) | ✓ client photo |
| IMG-16 | about.html    | Belief row                     | EDITORIAL | 1600 × 1200 px  | CSS texture `.sx-belief` (indigo)              | ◑ CSS temp    |
| IMG-17 | about.html    | Practice row                   | EDITORIAL | 1000 × 1250 px  | CSS texture `.sx-ingredient` (B&W)             | ◑ CSS temp    |
| IMG-18 | contact.html  | Contact                        | EDITORIAL | 1200 × 1500 px  | CSS texture `.sx-contact` (indigo)             | ◑ CSS temp    |
| IMG-19 | about.html    | Founder row (Meet Kourtney)    | MODELING  | 900 × 1200 px   | Client studio portrait `photos/ia-founder-studio-kourtney.jpg` (web-res) | ⚠ original needed |

Legend — **✓ client photo**: real client photo from the Shopify CDN (see below). **⚠ needs photo**: full-colour temporary stand-in in place (no on-page label),
must be replaced with a licensed original. **◑ CSS temp**: CSS texture in place; replace
with final editorial imagery (or keep as intentional texture if art direction approves).

## Totals

| Type      | Count | Fill                                  |
|-----------|-------|---------------------------------------|
| PRODUCT   | 3     | full-colour stand-ins (temporary)     |
| MODELING  | 5     | 3 Shopify photos + 2 client web-res   |
| EDITORIAL | 11    | 6 Shopify photos + 5 CSS textures     |
| **Total** | **19**| 0 empty                               |

## Stand-in provenance (`img/standins/`)

All sourced from `~/Desktop/kourtneyassets`, pre-cropped to remove baked-in text /
watermarks, rendered at full colour and quality with no overlay. **These are temporary
placeholders, not licensed final assets — every one must be replaced with a licensed
original.**

| Stand-in file                | Slot   | Source (kourtneyassets)                         |
|------------------------------|--------|-------------------------------------------------|
| standin-img08-product.jpg    | IMG-08 | 70f5fe60… (bottle on amethyst, upper crop)      |
| standin-img09-product.jpg    | IMG-09 | 70f5fe60… (hexagon product array, lower crop)   |
| standin-img10-product.jpg    | IMG-10 | 1bdcab39… (dark jar tile, cropped)              |
| standin-img13-modeling.jpg   | IMG-13 | e03719e2… (serum/dropper panel, cropped)        |
| standin-img14-modeling.jpg   | IMG-14 | e03719e2… (portrait panel, cropped below text)  |
| standin-img15-modeling.jpg   | IMG-15 | b878be50… (bio-alchemy still-life panel, cropped)|

## Shopify photos (`img/photos/shopify/`)

Downloaded 2026-10-28 from the client's Shopify CDN (`cdn.shopify.com/s/files/1/0912/8391/4936/`).
Only the web JPEGs listed below (quality 85) are in the repo. The 19 PNG originals
(2000 × 2000; the two packshots are 4000 × 4000) are kept outside the repo in
`~/Desktop/kourtneyassets/shopify-originals/` and can also be re-downloaded from the CDN.
Unused images are listed in `img/photos/shopify/ALTERNATES.md`.

The Ingredient PNGs are infographic cards with a headline and benefit copy printed over the
photo, so each diptych JPEG is a 4:5 crop of an area with no text. Eye Serum and Riche Crème
have text across the middle and could not be cropped clean. **Client copy error:** the
Body Oil card (almonds) is captioned "Snail Secretion Filtrate (Mucin)" — flag for the client.

| File                     | Slot   | Source / treatment                                              |
|--------------------------|--------|-----------------------------------------------------------------|
| diptych-bodyoil.jpg      | IMG-02 | `ingredient-bodyoil.png`, text-free crop 944 × 1180             |
| diptych-sunbalm.jpg      | IMG-03 | `ingredient-sunbalm.png`, text-free crop 800 × 1000             |
| diptych-snailmucin.jpg   | IMG-04 | `ingredient-snailmucin.png`, text-free crop 896 × 1120          |
| diptych-tallow.jpg       | IMG-05 | `ingredient-tallow.png`, text-free crop 800 × 1000              |
| diptych-cleanser.jpg     | IMG-06 | `ingredient-cleanser.png`, text-free crop 700 × 875             |
| diptych-swatch.jpg       | IMG-07 | `swatch-sunbalm.png`, 4:5 crop scaled to 1000 × 1250            |
| ritual-cleanser.jpg      | IMG-13 | `lifestyle-cleanser.png`, scaled to 1400 × 1400                 |
| ritual-eyeserum.jpg      | IMG-14 | `lifestyle-eyeserum.png`, scaled to 1400 × 1400                 |
| ritual-richecreme.jpg    | IMG-15 | `lifestyle-richecreme.png`, scaled to 1400 × 1400               |

The old stand-ins `standins/standin-img13/14/15-modeling.jpg` are no longer referenced; they are kept on disk.

## Client-supplied photos (`img/photos/`)

Sent by the client on 2026-09-22 as web-resolution files (Instagram / screenshot
quality). Fine for this private mockup; **not** store-grade — the full-resolution
originals are needed before Shopify.

| File                     | Slot   | Source / treatment                                                        |
|--------------------------|--------|---------------------------------------------------------------------------|
| ia-hero-kourtney.jpg     | IMG-01 | Campaign shot with jar (1170 × 2532 phone screenshot). Rounded corners and the baked-in "Indigo Alien Beauty" title removed; cropped to 1154 × 2106. |
| ia-founder-studio-kourtney.jpg | IMG-19 | White-bg studio shot, 1121 × 1403, used as-is (replaces ia-founder-kourtney.jpg, retained on disk). |
| ia-about-header-kourtney.jpg | —  | White-bg studio shot, 1122 × 1402 — About header figure.                  |
| ia-look-01.jpg           | —      | Holographic campaign (logo printed), 1122 × 1402 — index lookbook strip.  |
| ia-look-02.jpg           | —      | Holographic campaign (logo printed), 1122 × 1402 — index lookbook strip.  |
| ia-look-03.jpg           | —      | Holographic campaign (logo printed), 1122 × 1402 — index lookbook strip.  |
| ia-dropper-kourtney.jpg  | —      | Dropper close-up, 1100 × 1430 — index serum band.                         |

## Brand assets (`img/brand/`)

`ia-logo-lockup.png` (wordmark + "BEAUTY FROM BEYOND") and `ia-logo-wordmark.png`
(wordmark only) are white-on-transparent knockouts rebuilt from the client's Instagram
cover screenshot (three stitched grid tiles). Clean at nav and masthead sizes; **replace
with the designer's original vector / transparent PNG** for print and Shopify.

## Background (`img/bg/`)

`stars-far.svg` / `stars-near.svg` — generated star-field tiles behind every page
(see STAR FIELD in styles.css). Final; no swap needed.

## To reach final

1. **Product (IMG-08/09/10):** shoot the three SKUs (Rising Star Riche Crème, Starry Eye
   Serum, Galactic Oil Cleanser) at 900 × 1125, then drop into `img/products/` and swap
   the `<img src>` + remove the `slot--standin` class.
2. **Modeling (IMG-01/13/14/15/19):** hero, three on-skin ritual gestures, founder portrait — full-res originals of the two client shots, plus real photography for the ritual steps.
3. **Editorial (IMG-02–07, 11, 12, 16, 17, 18):** real B&W macro pairs (neuron/galaxy,
   iris/nebula, roots/vessels), ingredient macro, and the colour cosmic features — or
   keep the CSS textures if approved. To swap: remove the `.sx-*` class and add an `<img>`.

### Breakdown by page
- **index.html** — 11 (IMG-01 … IMG-11)
- **rituals.html** — 4 (IMG-12 … IMG-15)
- **about.html** — 3 (IMG-16, IMG-17, IMG-19)
- **contact.html** — 1 (IMG-18)
