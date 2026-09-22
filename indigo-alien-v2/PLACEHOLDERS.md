# Indigo Alien Beauty — Image Placeholder Inventory

Every image on the site occupies a labeled `.slot`. As of the **hybrid-fill pass**, no
slot renders empty — but **nothing here is final**. Every slot still needs real
photography before any public / marketing use.

Two fill strategies are in place:

- **EDITORIAL (11 slots)** — filled with **CSS-only cosmic/macro textures** (layered
  gradients + grain, no external images). The six diptych textures + the ingredient
  macro are strictly monochrome; the four colour cosmic slots carry a restrained indigo
  undertone. These are decorative stand-ins that read as "art direction," not final art.
- **PRODUCT (3) + MODELING (4)** — filled with **full-colour, full-quality stand-in
  photos** from `~/Desktop/kourtneyassets`, copied (pre-cropped to push any baked-in
  text / watermark out of frame) into `img/standins/`. No dimming treatment and **no
  on-page label** — the layout reads as a finished design. These 7 are **temporary
  stand-ins tracked only in this file**; every one must be replaced with a licensed
  original.

Types: **PRODUCT** (studio product shot) · **MODELING** (person / on-skin) ·
**EDITORIAL** (macro nature & cosmic imagery, incl. the monochrome diptych).

| ID     | Page          | Section                        | Type      | Rec. dimensions | Current fill                                   | Status        |
|--------|---------------|--------------------------------|-----------|-----------------|------------------------------------------------|---------------|
| IMG-01 | index.html    | Hero                           | MODELING  | 1200 × 1600 px  | Stand-in `standin-img01-modeling.jpg`          | ⚠ needs photo |
| IMG-02 | index.html    | As Above, So Below — Pair I    | EDITORIAL | 1000 × 1250 px  | CSS texture `.sx-neuron` (B&W)                 | ◑ CSS temp    |
| IMG-03 | index.html    | As Above, So Below — Pair I    | EDITORIAL | 1000 × 1250 px  | CSS texture `.sx-galaxy` (B&W, mirrors 02)     | ◑ CSS temp    |
| IMG-04 | index.html    | As Above, So Below — Pair II   | EDITORIAL | 1000 × 1250 px  | CSS texture `.sx-iris` (B&W)                    | ◑ CSS temp    |
| IMG-05 | index.html    | As Above, So Below — Pair II   | EDITORIAL | 1000 × 1250 px  | CSS texture `.sx-nebula` (B&W, mirrors 04)     | ◑ CSS temp    |
| IMG-06 | index.html    | As Above, So Below — Pair III  | EDITORIAL | 1000 × 1250 px  | CSS texture `.sx-roots` (B&W)                   | ◑ CSS temp    |
| IMG-07 | index.html    | As Above, So Below — Pair III  | EDITORIAL | 1000 × 1250 px  | CSS texture `.sx-vessels` (B&W, mirrors 06)    | ◑ CSS temp    |
| IMG-08 | index.html    | Luminous Offerings             | PRODUCT   | 900 × 1125 px   | Stand-in `standin-img08-product.jpg`           | ⚠ needs photo |
| IMG-09 | index.html    | Luminous Offerings             | PRODUCT   | 900 × 1125 px   | Stand-in `standin-img09-product.jpg`           | ⚠ needs photo |
| IMG-10 | index.html    | Luminous Offerings             | PRODUCT   | 900 × 1125 px   | Stand-in `standin-img10-product.jpg`           | ⚠ needs photo |
| IMG-11 | index.html    | Starseed Ritual Collection     | EDITORIAL | 2400 × 1000 px  | CSS texture `.sx-banner` (indigo)              | ◑ CSS temp    |
| IMG-12 | rituals.html  | Intro row                      | EDITORIAL | 2400 × 1200 px  | CSS texture `.sx-ritual` (indigo)              | ◑ CSS temp    |
| IMG-13 | rituals.html  | The Sequence — Step i          | MODELING  | 900 × 1200 px   | Stand-in `standin-img13-modeling.jpg`          | ⚠ needs photo |
| IMG-14 | rituals.html  | The Sequence — Step ii         | MODELING  | 900 × 1200 px   | Stand-in `standin-img14-modeling.jpg`          | ⚠ needs photo |
| IMG-15 | rituals.html  | The Sequence — Step iii        | MODELING  | 900 × 1200 px   | Stand-in `standin-img15-modeling.jpg`          | ⚠ needs photo |
| IMG-16 | about.html    | Belief row                     | EDITORIAL | 1600 × 1200 px  | CSS texture `.sx-belief` (indigo)              | ◑ CSS temp    |
| IMG-17 | about.html    | Practice row                   | EDITORIAL | 1000 × 1250 px  | CSS texture `.sx-ingredient` (B&W)             | ◑ CSS temp    |
| IMG-18 | contact.html  | Contact                        | EDITORIAL | 1200 × 1500 px  | CSS texture `.sx-contact` (indigo)             | ◑ CSS temp    |

Legend — **⚠ needs photo**: full-colour temporary stand-in in place (no on-page label),
must be replaced with a licensed original. **◑ CSS temp**: CSS texture in place; replace
with final editorial imagery (or keep as intentional texture if art direction approves).

## Totals

| Type      | Count | Fill                                  |
|-----------|-------|---------------------------------------|
| PRODUCT   | 3     | full-colour stand-ins (temporary)     |
| MODELING  | 4     | full-colour stand-ins (temporary)     |
| EDITORIAL | 11    | CSS textures                          |
| **Total** | **18**| 0 empty                               |

## Stand-in provenance (`img/standins/`)

All sourced from `~/Desktop/kourtneyassets`, pre-cropped to remove baked-in text /
watermarks, rendered at full colour and quality with no overlay. **These are temporary
placeholders, not licensed final assets — every one must be replaced with a licensed
original.**

| Stand-in file                | Slot   | Source (kourtneyassets)                         |
|------------------------------|--------|-------------------------------------------------|
| standin-img01-modeling.jpg   | IMG-01 | b878be50… (iridescent figure, cropped)          |
| standin-img08-product.jpg    | IMG-08 | 70f5fe60… (bottle on amethyst, upper crop)      |
| standin-img09-product.jpg    | IMG-09 | 70f5fe60… (hexagon product array, lower crop)   |
| standin-img10-product.jpg    | IMG-10 | 1bdcab39… (dark jar tile, cropped)              |
| standin-img13-modeling.jpg   | IMG-13 | e03719e2… (serum/dropper panel, cropped)        |
| standin-img14-modeling.jpg   | IMG-14 | e03719e2… (portrait panel, cropped below text)  |
| standin-img15-modeling.jpg   | IMG-15 | b878be50… (bio-alchemy still-life panel, cropped)|

## To reach final

1. **Product (IMG-08/09/10):** shoot the three SKUs (Rising Star Riche Crème, Starry Eye
   Serum, Galactic Oil Cleanser) at 900 × 1125, then drop into `img/products/` and swap
   the `<img src>` + remove the `slot--standin` class.
2. **Modeling (IMG-01/13/14/15):** hero portrait + three on-skin ritual gestures.
3. **Editorial (IMG-02–07, 11, 12, 16, 17, 18):** real B&W macro pairs (neuron/galaxy,
   iris/nebula, roots/vessels), ingredient macro, and the colour cosmic features — or
   keep the CSS textures if approved. To swap: remove the `.sx-*` class and add an `<img>`.

### Breakdown by page
- **index.html** — 11 (IMG-01 … IMG-11)
- **rituals.html** — 4 (IMG-12 … IMG-15)
- **about.html** — 2 (IMG-16, IMG-17)
- **contact.html** — 1 (IMG-18)
