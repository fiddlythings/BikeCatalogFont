# Bike Catalog

A heavy, rounded geometric display typeface revived from the vintage **Bike Nashbar / Bike Warehouse** mail-order catalog logotype. Lowercase-only, primarily built for decals and bike-related graphics.

Ships in three spacing cuts drawn from one set of outlines.

---

## The three cuts

| Family | Use | `n` adv | `o` adv | `v` adv | Word space |
|---|---|---:|---:|---:|---:|
| **Bike Catalog** | General use; the comfortable default | 540 | 568 | 502 | 300 |
| **Bike Catalog Tight** | Headlines, decals, signage | 510 | 537 | 470 | 250 |
| **Bike Catalog Poster** | Ultra-tight 90s lockups | 486 | 518 | 458 | 205 |

The glyph shapes are **identical** across all three. Only the optical spacing, word space, and kerning step down. They are three separate font families, so they coexist in the font menu without conflict.

---

## What's in the box

For each cut:

- `*.otf` — desktop install (OpenType/CFF)
- `*.ttf` — web, embedding, and Cricut / sign-cutting / vinyl software
- `*.sfd` — editable [FontForge](https://fontforge.org) source

```
BikeCatalog-Regular.otf / .ttf / .sfd
BikeCatalogTight-Regular.otf / .ttf / .sfd
BikeCatalogPoster-Regular.otf / .ttf / .sfd
BikeCatalog-specimen.png      (all three cuts, full character set)
```

---

## Character set

71 glyphs per cut — **no uppercase**.

- Lowercase `a`–`z`
- Figures `0`–`9` (proportional, lining)
- Currency `$ £ €`
- Full ASCII punctuation & symbols:
  `! " # % & ' ( ) * + , - . / : ; < = > ? @ [ \ ] ^ _ \` { | } ~`
- Space

The authentic logotype letters (`a b e h i k n r s`) are traced from the 1992 catalog logo. The remaining lowercase, figures, and symbols are traced from period specimens of the same face, so traced and authentic glyphs share the same DNA and blend seamlessly.

---

## Installation

**Pick OTF *or* TTF per cut — not both** (installing both creates duplicate menu entries).

- **macOS** — double-click the file → *Install Font* (or drop into Font Book).
- **Windows** — right-click → *Install* (or *Install for all users*).
- **Linux** — copy to `~/.local/share/fonts/` and run `fc-cache -f`.
- **Cricut Design Space / Silhouette / sign software** — install the **TTF** system-wide first; it then appears in the app's font list.

---

## Which cut when

- **Bike Catalog** — anything set at moderate size, mixed words, multi-line.
- **Bike Catalog Tight** — single-line headlines and most decal work; the snug rhythm reads as intentional and punchy at large sizes.
- **Bike Catalog Poster** — short all-out lockups (one or two words) where you want the letters nearly interlocking. The `v`/round pairs deliberately nest tight here.

For decals and cut vinyl, use a TTF and the **Tight** or **Poster** cut.

---

## Technical notes

- **Units per em:** 1000
- **Vertical metrics:** ascent 800 / descent 200; x-height 500; ascenders ≈ 695; figures/symbol cap ≈ 700; descenders ≈ −210
- **Weight class:** Black (900)
- **Kerning:** GPOS `kern` feature, 265 pairs per cut — optical sidebearing pass plus targeted pairs (punctuation tuck, parentheses/braces to bowls, diagonal↔round, stem→ascender, figure/currency). Kerning is clamped per cut so the Poster cut tightens without ink collisions.

### Intentional quirks (authentic to the face)
- **Lowercase only** — by design; this is a display logotype face.
- **Spiral counters** on `6`, `9`, `a`, `e`, `@` — small round counters joined by a thin slit, as in the original.
- **Open counter on `4`** — authentic Bauhaus form.
- **High ASCII tilde `~`** — sits near cap height (spacing tilde), matching the source specimen rather than a centered math tilde.

---

## Editing the source

The `.sfd` files open in FontForge and contain the complete, kerned font. From there you can:

- adjust individual glyphs or sidebearings,
- extend the set (e.g., add an uppercase or small-caps layer — none is present),
- regenerate OTF/TTF via *File → Generate Fonts…*

Outlines were produced by tracing specimen scans with a `potrace → FontForge` pipeline (not lifted from any existing font binary), then optically spaced and kerned.

---

## Provenance & license

Typeface *designs* are not subject to copyright (only the specific font software/binary is). **Bike Catalog** is an independent revival: new outline data traced from owned catalog scans of the historic Bike Nashbar / Bike Warehouse logotype, not extracted from any commercial font.


---

