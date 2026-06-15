<div align="center">

<img src=".github/banner.jpg" alt="Japanese Color Atlas" width="100%" />

# Japanese Color Atlas · 日本の伝統色

**Free traditional Japanese color tokens — CSS, Tailwind, and design tokens.**

A source-aware color reference for designers and developers working with Japanese-inspired visual systems.

[![Website](https://img.shields.io/badge/Website-japanesecoloratlas.com-1A1A1A?style=flat-square)](https://japanesecoloratlas.com)
[![Free samples](https://img.shields.io/badge/Free%20samples-Download-2E7D5B?style=flat-square)](https://japanesecoloratlas.com/resources/free)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Chroma Cathay](https://img.shields.io/badge/Studio-Chroma%20Cathay-9E2916?style=flat-square)](https://chromacathay.com)

[**Website**](https://japanesecoloratlas.com) · [**Free samples**](https://japanesecoloratlas.com/resources/free) · [**Methodology**](https://japanesecoloratlas.com/methodology) · [**Chroma Cathay**](https://chromacathay.com)

</div>

---

Free traditional Japanese color samples and workflow resources from **Japanese Color Atlas**, a [Chroma Cathay](https://chromacathay.com) project.

Use this repository when you want to test traditional Japanese colors in real design and development workflows before using the complete atlas. It includes sample CSS variables, Tailwind colors, and design tokens.

Japanese Color Atlas is a source-aware color reference for designers, developers, and creative teams working with Japanese-inspired visual systems. The complete atlas covers 144 colors with seasonal palettes, kasane (襲の色目) layered pairings, and a 72-season koyomi calendar; this public repository intentionally publishes a representative free sample set only.

## Start Here

- **Developers:** try `free/japanese-colors.css`, `free/japanese-colors-tailwind.cjs`, or `free/japanese-colors-tokens.json`.
- **Designers & design-system teams:** read the source-status methodology at <https://japanesecoloratlas.com/methodology>.
- **Need context?** read the free resource page at <https://japanesecoloratlas.com/resources/free>.

## What's Included

This public repository contains free distribution assets only. The product website and complete resource packs live separately.

The complete 144-color workflow packs are available on the main site at <https://japanesecoloratlas.com/resources>; this repository only provides representative samples.

| File | Use |
|---|---|
| `free/japanese-colors.css` | CSS custom properties sample for representative traditional Japanese colors |
| `free/japanese-colors-tailwind.cjs` | Tailwind theme color token sample |
| `free/japanese-colors-tokens.json` | W3C DTCG-style design token sample |

## Quick Use

### CSS

```css
@import "./free/japanese-colors.css";

.card {
  background: var(--jp-ai-iro);
  color: var(--jp-shironeri);
}
```

### Tailwind

```js
const japaneseColors = require('./free/japanese-colors-tailwind.cjs')

module.exports = {
  theme: {
    extend: {
      colors: japaneseColors.colors,
    },
  },
}
```

## Full Resource Packs

The complete design resource packs include all 144 colors as CSS, Tailwind, W3C DTCG tokens, Figma Variables, Adobe ASE, Procreate swatches, AI prompts, seasonal palettes, and full JSON datasets.

- Website: https://japanesecoloratlas.com
- Free samples: https://japanesecoloratlas.com/resources/free
- Paid packs: https://japanesecoloratlas.com/resources
- Methodology and data sources: https://japanesecoloratlas.com/methodology

## Free vs Paid Boundary

This repository is intentionally small and public. It is meant for discovery, demos, tutorials, attribution, and workflow testing.

It does not include the complete 144-color Figma Variables file, full Adobe ASE palette, full Procreate sets, complete AI prompt pack, kasane/koyomi research JSON, or full production handoff files. Those complete workflow files are delivered through the resource packs on the Japanese Color Atlas site.

## Who This Is For

- UI and brand designers building Japanese-inspired visual systems
- Frontend developers who need CSS / Tailwind / token exports
- Illustrators and AI image creators working with Japanese aesthetics
- Researchers and cultural projects that need careful source attribution

## Attribution

Japanese Color Atlas is a Chroma Cathay project. Attribution is appreciated when you use these assets in public resources, documentation, tutorials, or derivative datasets.

Suggested attribution:

> Traditional Japanese color samples from Japanese Color Atlas by Chroma Cathay: https://japanesecoloratlas.com

See `ATTRIBUTION.md` for data-source notes.

## License

Code and sample export files in this repository are released under the MIT License, except where source attribution notes specify otherwise. See `LICENSE` and `ATTRIBUTION.md`.
