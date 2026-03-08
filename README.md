# Style Selector — Claude Code Skill

Deploy 5 radically different visual direction demos for any Next.js + Tailwind CSS project. Compare side-by-side and choose your aesthetic before committing.

## What it does

When invoked, this skill generates 5 self-contained demo pages under `/demo/` in your Next.js project. Each page is a complete landing page with a distinct visual identity:

| Direction | Reference | Mood |
|-----------|-----------|------|
| **Editorial Serif** | The Economist, Monocle | Intellectual authority, printed-page sophistication |
| **Swiss Minimal** | Dieter Rams, Braun | Radical reduction, functional clarity |
| **Luxury Dark Warm** | Aesop, Byredo | Intimate warmth, quiet confidence |
| **Corporate Bold** | Accenture, McKinsey | Structured professionalism, data-driven |
| **Understated Elegance** | Kinfolk, Cereal | Editorial calm, deliberate whitespace |

Each demo includes: navigation, hero section, storytelling, stats, services, CTA, and footer — all styled with unique typography, color palette, and layout patterns.

## Installation

```bash
npx skills add Luispitik/style-selector-skill@style-selector
```

Or install globally:

```bash
npx skills add Luispitik/style-selector-skill@style-selector -g -y
```

## Usage

In Claude Code, say any of:
- "style selector"
- "choose styles"
- "visual alternatives"
- "pick a design direction"
- "compare different aesthetics"

The skill will automatically:
1. Gather your project context (business type, name, services, CTA)
2. Generate 5 demo pages with your real content adapted to each style
3. Build and verify all routes compile
4. Present a summary with the demo URL (`/demo`)

## Requirements

- Next.js App Router project
- Tailwind CSS configured
- `src/app/` directory structure

## The 5 Directions at a Glance

### A — Editorial Serif
Cream background, gold accents, Playfair Display + Source Serif 4. Think printed magazine.

### B — Swiss Minimal
Pure white, red CTAs only, Space Grotesk + Inter. Maximum restraint, functional clarity.

### C — Luxury Dark Warm
Charcoal background, copper accents, Cormorant Garamond + Outfit. Intimate and refined.

### D — Corporate Bold
White/navy alternating sections, purple accents, Plus Jakarta Sans. Confident authority.

### E — Understated Elegance
Bone background, olive accents, Libre Baskerville + Karla. Quiet sophistication.

## Author

Created by [Luis Salgado](https://salgadoia.com) — AI consultant helping businesses adopt AI with strategy, not hype.

## License

MIT
