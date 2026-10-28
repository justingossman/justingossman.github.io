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
| IMG-02 | index.html    | Diptych — Pair I               | PRODUCT   | 1000 × 1250 px  | `shopify/product-tallow.webp`: Twinkle Whipped Tallow jar | ✓ client photo |
| IMG-03 | index.html    | Diptych — Pair I               | PRODUCT   | 1000 × 1250 px  | `shopify/product-sunbalm.webp`: Solar Shield Sun Balm tins | ✓ client photo |
| IMG-04 | index.html    | Diptych — Pair II              | PRODUCT   | 1000 × 1250 px  | `shopify/product-mucin.webp`: Nebula Mucin Essence tube | ✓ client photo |
| IMG-05 | index.html    | Diptych — Pair II              | PRODUCT   | 1000 × 1250 px  | `shopify/product-bodyoil.webp`: Celestial Silk After Shave Body Oil bottle | ✓ client photo |
| IMG-06 | index.html    | Diptych — Pair III             | PRODUCT   | 1000 × 1250 px  | `shopify/product-deodorant.webp`: Transcendent Tallow Deodorant | ✓ client photo |
| IMG-07 | index.html    | Diptych — Pair III             | PRODUCT   | 1000 × 1250 px  | `shopify/product-set-purity-radiance.webp`: Purity & Radiance Ritual set (Riche Crème + Cleanser) | ✓ client photo |
| IMG-08 | index.html    | Luminous Offerings — Riche Crème | PRODUCT | 900 × 1125 px   | `shopify/product-richecreme.webp`: Rising Star Riche Crème tube | ✓ client photo |
| IMG-09 | index.html    | Luminous Offerings — Eye Serum | PRODUCT   | 900 × 1125 px   | `shopify/product-eyeserum.webp`: Starry Eye Serum tube | ✓ client photo |
| IMG-10 | index.html    | Luminous Offerings — Cleanser  | PRODUCT   | 900 × 1125 px   | `shopify/product-cleanser.webp`: Galactic Oil Cleanser tube | ✓ client photo |
| IMG-11 | index.html    | Starseed Ritual Collection     | PRODUCT   | 2400 × 1000 px  | Section hidden by choice (2026-10-28). Packshots of the three pieces now exist; needs an approved banner composition. The IMG_8124 group render was rejected for misspelled labels ("SOLAR SMELD SUN BALM" et al.) and is kept untracked at `standins/standin-img11-banner.jpg`. | ⊘ hidden |
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
| ✓ client photo      | 13    | IMG-02–10, 13, 14, 15, 17               |
| ⚠ original needed   | 2     | IMG-01, 19                              |
| ◻ placeholder       | 3     | IMG-12, 16, 18                          |
| ⊘ hidden            | 1     | IMG-11                                  |

## Shopify photos (`img/photos/shopify/`)

Downloaded 2026-10-28 from the client's Shopify CDN (`cdn.shopify.com/s/files/1/0912/8391/4936/`).
Only the web JPEGs below are in the repo. The 19 PNG originals are kept outside the repo in
`~/Desktop/kourtneyassets/shopify-originals/`. `img/photos/shopify/ALTERNATES.md`
describes every original.

Packshots come from the products' own Shopify media (product names as in Shopify admin).
Each one is a 4:5 crop framed tightly around the product (10% margin), with the transparency
kept, saved as WebP (1000 × 1250, about 40–75 KB). The slot's dark gradient shows behind the
product, so there's no white box.

| File                                | Slot   | Shopify source                                          |
|-------------------------------------|--------|---------------------------------------------------------|
| product-tallow.webp                 | IMG-02 | `WhippedTallow_….png` (4000²)                           |
| product-sunbalm.webp                | IMG-03 | `EdibleSunBalm_….png` (4000²)                           |
| product-mucin.webp                  | IMG-04 | `SnailMucinEssence_….png` (4422²)                       |
| product-bodyoil.webp                | IMG-05 | `50mlSeamossOil.png` (4000²)                            |
| product-deodorant.webp              | IMG-06 | `2ozTallowDeodorant.png` (4000²)                        |
| product-set-purity-radiance.webp    | IMG-07 | `Clean_HydrateFaceDuo.png` (4000²)                      |
| product-richecreme.webp             | IMG-08 | `RicheCreme_….png` (4422²)                              |
| product-eyeserum.webp               | IMG-09 | `EyeSerum_….png` (4422²)                                |
| product-cleanser.webp               | IMG-10 | `FoamingOilCleanser_….png` (4422²)                      |
| ritual-cleanser.jpg                 | IMG-13 | `lifestyle-cleanser.png`, scaled to 1400 × 1400         |
| ritual-eyeserum.jpg                 | IMG-14 | `lifestyle-eyeserum.png`, scaled to 1400 × 1400         |
| ritual-richecreme.jpg               | IMG-15 | `lifestyle-richecreme.png`, scaled to 1400 × 1400       |
| about-ingredient-vanilla-bw.jpg     | IMG-17 | `ingredient-tallow.png`: a crop of the vanilla bean with no text, converted to grayscale, 800 × 1000 |

**Names to confirm with the client:** the Shopify product is titled "Celestical Silk After
Shave Body Oil" (typo); the site uses "Celestial". The tube and the Shopify title say
"Nebula Mucin Essence", while the CDN files say "SnailMucinEssence".

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

1. **Starseed banner (IMG-11):** hidden by choice. Packshots of all three collection tubes now
   exist (`product-richecreme/eyeserum/cleanser.webp`), so it can come back when a banner
   composition is approved. Remove `hidden` on the section to restore it.
2. **Modeling (IMG-01/19):** full-res originals of the two client shots.
3. **Editorial (IMG-12, 16, 18):** colour cosmic features, or keep the CSS textures if approved.

### Breakdown by page
- **index.html** — 11 (IMG-01 … IMG-11)
- **rituals.html** — 4 (IMG-12 … IMG-15)
- **about.html** — 3 (IMG-16, IMG-17, IMG-19)
- **contact.html** — 1 (IMG-18)

## Product pages (`products/<slug>.html`)

Nine pages, one per product shown on index.html. The text was copied read-only from each
product's Shopify admin page on 2026-10-28:

| On the page        | Shopify admin field                                              |
|--------------------|------------------------------------------------------------------|
| Name, price        | Title, Price                                                     |
| Description        | Description (rich text)                                          |
| Why you’ll love it | **Key Ingredient** metafield. There's no "Why you'll love it" text field; the "…Why_you_will_love_it.png" cards in Files paraphrase Key Ingredient. |
| How to use         | **Ritual** metafield. The "How to use" metafield is empty on every product. |
| Full ingredients   | Full Ingredients metafield                                       |
| Buy button         | `https://indigoalienbeauty.com/products/<Shopify handle>`        |

Shopify has **no Ritual / how-to text** for Twinkle Whipped Tallow, Solar Shield Sun Balm,
Celestial Silk After Shave Body Oil, Transcendent Tallow Deodorant or The Purity & Radiance
Ritual, so those pages have no "How to use" section.

Lifestyle shots: only files whose Shopify name credits Kourtney are used: Riche Crème, Eye
Serum and Cleanser (`ritual-*.jpg`), and Nebula Mucin, Twinkle Tallow and Deodorant
(`lifestyle-*.jpg`). Sun Balm and Body Oil have lifestyle images that aren't credited to her,
and the bundle has none, so those three pages have no lifestyle shot.

Data issues to raise with the client: the Body Oil's Shopify title and handle say "Celestical"
(the site shows "Celestial"; the buy link has to use the real handle). The Purity & Radiance
Ritual's one-liner is copied from Starry Eye Serum ("Awaken the Starlight Within Your Gaze."),
so it isn't used on the site.
