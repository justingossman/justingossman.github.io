# Indigo Alien Beauty — Image Placeholder Inventory

Every image on the site sits in a `.slot`. Each slot is in one of these states:

- **✓ client photo**: a real client photo is in place.
- **⚠ original needed**: a client photo is in place, but only at web resolution. The full-resolution original is needed.
- **◻ placeholder**: no photo yet. The frame shows a plain dark gradient (or an indigo
  texture on the cosmic slots), with **no visible label**. It is waiting for real photography.
- **⊘ hidden**: the whole section is hidden (`hidden` attribute) until photos exist.

**Rule (2026-10-28):** the diptych and product slots take only **true product shots**
(a jar, bottle, tin or tube on a clean background). Ingredient cards and styled renders
are not used there. If there is no product shot, the slot stays a placeholder.

Types: **PRODUCT** (product on a clean background) · **MODELING** (person / on-skin) ·
**EDITORIAL** (cosmic or ingredient imagery).

| ID     | Page          | Section                        | Type      | Rec. dimensions | Current fill                                   | Status        |
|--------|---------------|--------------------------------|-----------|-----------------|------------------------------------------------|---------------|
| IMG-01 | index.html    | Hero                           | MODELING  | 1200 × 1600 px  | Client campaign shot `photos/ia-hero-kourtney.jpg` (web-res) | ⚠ original needed |
| IMG-02 | index.html    | Diptych — Pair I               | PRODUCT   | 1000 × 1250 px  | `shopify/product-tallow.jpg`: Twinkle Whipped Tallow jar on white | ✓ client photo |
| IMG-03 | index.html    | Diptych — Pair I               | PRODUCT   | 1000 × 1250 px  | `shopify/product-sunbalm.jpg`: Solar Shield Sun Balm tins on white | ✓ client photo |
| IMG-04 | index.html    | Diptych — Pair II              | PRODUCT   | 1000 × 1250 px  | none                                           | ◻ placeholder |
| IMG-05 | index.html    | Diptych — Pair II              | PRODUCT   | 1000 × 1250 px  | none                                           | ◻ placeholder |
| IMG-06 | index.html    | Diptych — Pair III             | PRODUCT   | 1000 × 1250 px  | none                                           | ◻ placeholder |
| IMG-07 | index.html    | Diptych — Pair III             | PRODUCT   | 1000 × 1250 px  | none                                           | ◻ placeholder |
| IMG-08 | index.html    | Luminous Offerings — Riche Crème | PRODUCT | 900 × 1125 px   | none (the old styled render `standin-img08` is no longer used) | ◻ placeholder |
| IMG-09 | index.html    | Luminous Offerings — Eye Serum | PRODUCT   | 900 × 1125 px   | none (old render `standin-img09` had garbled labels)  | ◻ placeholder |
| IMG-10 | index.html    | Luminous Offerings — Cleanser  | PRODUCT   | 900 × 1125 px   | none (old render `standin-img10` was 300 px wide with a misspelled label) | ◻ placeholder |
| IMG-11 | index.html    | Starseed Ritual Collection     | PRODUCT   | 2400 × 1000 px  | Section hidden. Needs product shots of Galactic Oil Cleanser, Starry Eye Serum and Rising Star Riche Crème. The IMG_8124 group render was rejected for misspelled labels ("SOLAR SMELD SUN BALM" et al.) and is kept untracked at `standins/standin-img11-banner.jpg`. | ⊘ hidden |
| IMG-12 | rituals.html  | Intro row                      | EDITORIAL | 2400 × 1200 px  | CSS texture `.sx-ritual` (indigo), unlabelled  | ◻ placeholder |
| IMG-13 | rituals.html  | The Sequence — Step i          | MODELING  | 900 × 1200 px   | `shopify/ritual-cleanser.jpg` (Kourtney, 1400 × 1400) | ✓ client photo |
| IMG-14 | rituals.html  | The Sequence — Step ii         | MODELING  | 900 × 1200 px   | `shopify/ritual-eyeserum.jpg` (Kourtney, 1400 × 1400) | ✓ client photo |
| IMG-15 | rituals.html  | The Sequence — Step iii        | MODELING  | 900 × 1200 px   | `shopify/ritual-richecreme.jpg` (Kourtney, 1400 × 1400) | ✓ client photo |
| IMG-16 | about.html    | Belief row                     | EDITORIAL | 1600 × 1200 px  | CSS texture `.sx-belief` (indigo), unlabelled. None of the Shopify images fit. | ◻ placeholder |
| IMG-17 | about.html    | Practice row (ingredient origin) | EDITORIAL | 1000 × 1250 px | `shopify/about-ingredient-vanilla-bw.jpg`: black-and-white vanilla bean macro, 800 × 1000 | ✓ client photo |
| IMG-18 | contact.html  | Contact                        | EDITORIAL | 1200 × 1500 px  | CSS texture `.sx-contact` (indigo), unlabelled | ◻ placeholder |
| IMG-19 | about.html    | Founder row (Meet Kourtney)    | MODELING  | 900 × 1200 px   | Client studio portrait `photos/ia-founder-studio-kourtney.jpg` (web-res) | ⚠ original needed |

## Totals

| Status              | Count | Slots                                   |
|---------------------|-------|-----------------------------------------|
| ✓ client photo      | 6     | IMG-02, 03, 13, 14, 15, 17              |
| ⚠ original needed   | 2     | IMG-01, 19                              |
| ◻ placeholder       | 10    | IMG-04–10, 12, 16, 18                   |
| ⊘ hidden            | 1     | IMG-11                                  |

## Shopify photos (`img/photos/shopify/`)

Downloaded 2026-10-28 from the client's Shopify CDN (`cdn.shopify.com/s/files/1/0912/8391/4936/`).
Only the web JPEGs below are in the repo. The 19 PNG originals are kept outside the repo in
`~/Desktop/kourtneyassets/shopify-originals/`. `img/photos/shopify/ALTERNATES.md`
describes every original.

| File                            | Slot   | Source / treatment                                          |
|---------------------------------|--------|-------------------------------------------------------------|
| product-tallow.jpg              | IMG-02 | `product-tallow.png` (4000², transparent background) on white, padded to 1000 × 1250 |
| product-sunbalm.jpg             | IMG-03 | `product-sunbalm.png` (4000², transparent background) on white, padded to 1000 × 1250 |
| ritual-cleanser.jpg             | IMG-13 | `lifestyle-cleanser.png`, scaled to 1400 × 1400             |
| ritual-eyeserum.jpg             | IMG-14 | `lifestyle-eyeserum.png`, scaled to 1400 × 1400             |
| ritual-richecreme.jpg           | IMG-15 | `lifestyle-richecreme.png`, scaled to 1400 × 1400           |
| about-ingredient-vanilla-bw.jpg | IMG-17 | `ingredient-tallow.png`: a crop of the vanilla bean with no text, converted to grayscale, 800 × 1000 |

**Ingredient cards are not used in the product slots.** Each one has a headline and benefit
copy printed over the photo. The benefit copy would be unreadable in a small "What's inside"
strip, so there is no such strip. **Client copy error:** the Body Oil card (almonds) is
captioned "Snail Secretion Filtrate (Mucin)". Flag it for the client.

The old stand-ins in `img/standins/` (img08/09/10/13/14/15) are no longer referenced. They are kept on disk.

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

1. **Product shots needed:** Rising Star Riche Crème (IMG-08), Starry Eye Serum (IMG-09) and Galactic
   Oil Cleanser (IMG-10), each on a clean background. These three also unlock the hidden
   Starseed banner (IMG-11). The diptych needs four more product shots (IMG-04–07). Snail Mucin
   Essence and Manuka Honey & Sea Moss Body Oil are the obvious next pair. To fill a placeholder,
   add `<img class="slot-img" …>` inside the slot and the `slot--standin` class.
2. **Modeling (IMG-01/19):** full-res originals of the two client shots.
3. **Editorial (IMG-12, 16, 18):** colour cosmic features, or keep the CSS textures if approved.

### Breakdown by page
- **index.html** — 11 (IMG-01 … IMG-11)
- **rituals.html** — 4 (IMG-12 … IMG-15)
- **about.html** — 3 (IMG-16, IMG-17, IMG-19)
- **contact.html** — 1 (IMG-18)
