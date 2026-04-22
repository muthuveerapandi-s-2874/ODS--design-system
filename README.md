# ODS Design System

Centralized design tokens, components, themes, and accessibility rules for
all ODS (Zoho) web projects. Everything ships as JSON so it can be consumed
by any language or tool.

Extracted from the ODS Figma design system.

---

## Repo Structure

```text
ODS--design-system/
├── DESIGN.md                            # Loader rules and AI behavior
├── README.md                            # This file
├── tokens/
│   ├── color/colors.json                # Full color palette (16 families × 11 shades)
│   ├── typography/typography.json       # Zoho Puvi scale: H1–H6 + paragraphs
│   ├── spacing/spacing.json             # Sizing tokens (Sm/Md/Lg/Xl)
│   ├── radius/elevation-radius.json     # Elevation (shadow) + radius tokens
│   └── layout/grid.json                 # Responsive grid breakpoints
├── components/
│   └── cta.json                         # Call-to-Action button: 5 variants × 4 sizes × 3 states
├── themes/
│   └── shift.json                       # Shift product theme
└── accessibility/
    ├── rules.md                         # WCAG 2.1 AA rules
    ├── examples.md                      # Good/bad code examples
    └── wcag.checklist.json              # Machine-readable checklist
```

---

## Usage

All files are JSON and can be loaded directly.

```javascript
// Node / any JS runtime
const colors = require('./tokens/color/colors.json');
const primaryBlue = colors.colors.blue['500']; // "#0047FF"

const cta = require('./components/cta.json');
const primaryDefault = cta.variants.primary.states.default; // { backgroundColor, color, border }
```

```python
# Python
import json
with open('tokens/color/colors.json') as f:
    colors = json.load(f)
primary_blue = colors['colors']['blue']['500']  # "#0047FF"
```

Consuming projects typically generate CSS custom properties, Tailwind configs,
or Figma token exports from these JSON files at build time.

---

## Figma Source

- **Design File**: [ODS_Guideline](https://www.figma.com/design/uddrCFCslgueV4AzTXScnP/ODS_Guideline?node-id=201-1450)
- **File Key**: `uddrCFCslgueV4AzTXScnP`

Each JSON file includes a `designSystem` object with the Figma node ID it was
extracted from.

---

## Color Palette — `tokens/color/colors.json`

16 color families, each with 11 shades (50 → 950):

| Family | Role |
|---|---|
| `red` | Error states, destructive actions |
| `orange` | Warnings, attention |
| `deepOrange` | Strong warnings |
| `yellow` | Cautions, highlights |
| `green` | Success states, positive actions |
| `lime` | Light success indicators |
| `lightBlue` | Information, light accents |
| `cyan` | Secondary information |
| `teal` | Tertiary information |
| `purple` | Special accents |
| `pink` | Special accents |
| `blue` | Primary actions, links (`blue-500` = `#0047FF`) |
| `grey` | Neutral tones, text |
| `darkGrey` | Dark-mode backgrounds |
| `white` | Backgrounds, contrast |
| `black` | Text, high contrast |

### Shade Scale

- **50–200** — Light tints, backgrounds
- **300–400** — Lighter accents
- **500** — Base color (most commonly used)
- **600–700** — Darker accents
- **800–950** — Dark shades, text on light backgrounds

All values are uppercase hex (e.g., `#0047FF`).

---

## Typography — `tokens/typography/typography.json`

- **Font Family**: `'Zoho Puvi', sans-serif`
- **Weights**: 400 (regular), 500 (medium), 600 (semibold), 700 (bold)

### Headings

| Level | Size | Line Height |
|---|---|---|
| H1 | 88px | 96px |
| H2 | 80px | 88px |
| H3 | 72px | 80px |
| H4 | 64px | 72px |
| H5 | 56px | 64px |
| H6 | 48px | 56px |

### Paragraphs

| Size | Font Size | Line Height |
|---|---|---|
| Large | 40px | 48px |
| Medium | 32px | 40px |
| Regular | 24px | 32px |
| Small | 20px | 28px |
| X-Small | 16px | 24px |
| Tiny | 12px | 16px |

Each size exposes all four weight variants, each with its own
`letterSpacing` and `tracking` value (expressed as both a percentage and a
resolved pixel value).

---

## Grid — `tokens/layout/grid.json`

Center-aligned grids with 40px margins across all breakpoints.

| Breakpoint | Min Width | Max Width | Columns | Column Width | Gutter |
|---|---|---|---|---|---|
| Desktop | 1720px | — | 12 | 88px | 24px |
| Desktop Medium | 1400px | 1720px | 12 | 88px | 24px |
| Desktop Small | 1200px | 1400px | 12 | 56px | 32px |
| Tablet | 992px | 1200px | 12 | 48px | 16px |
| Tablet Small | 768px | 992px | 8 | 64px | 16px |
| Mobile | 576px | 768px | 4 | 104px | 16px |

---

## Spacing — `tokens/spacing/spacing.json`

Sizing tokens grouped into four categories:

| Category | Range | Count |
|---|---|---|
| Small (`Sm- 1` … `Sm- 5`) | Small spacing / gaps | 5 |
| Medium (`Md- 1` … `Md- 8`) | Standard spacing | 8 |
| Large (`Lg- 1` … `Lg- 10`) | Section spacing | 10 |
| XLarge (`Xl- 1` … `Xl- 10`) | Page-level spacing | 10 |

> **Note:** These tokens currently reference Figma `Space.*` tokens and are
> not all resolved to literal pixel values. Confirmed values so far:
> `Sm- 3` = 12px, `Sm- 4` = 16px, `Sm- 5` = 20px, `Md- 1` = 24px,
> `Md- 2` = 32px, `Md- 5` = 56px. The remaining tokens need to be resolved
> from the Figma Space export.

---

## Elevation & Radius — `tokens/radius/elevation-radius.json`

Contains elevation (box-shadow) definitions at multiple sizes (xs, small,
medium, large, etc.) with raw `shadow` CSS, individual `properties`
(offsetX/Y, blur, spread, color, opacity), and a ready-to-use `css` string.

---

## CTA Component — `components/cta.json`

### Variants

| Variant | Default Background | Default Text |
|---|---|---|
| `primary` | `#0047FF` | `#FFFFFF` |
| `primaryLine` | transparent (outlined) | `#0047FF` |
| `secondary` | `#000000` | `#FFFFFF` |
| `secondaryLine` | transparent (outlined) | `#000000` |
| `tertiary` | `#FFFFFF` | `#000000` |

### Sizes

| Size | Padding | Font | Line Height | Height |
|---|---|---|---|---|
| `xs` | 12px 16px | 16px | 24px | auto |
| `sm` | 16px 24px | 16px | 24px | 56px |
| `md` | 20px 24px | 20px | 28px | auto |
| `lg` | 24px 32px | 24px | 32px | auto |

### States

Each variant exposes `default`, `hover`, and `active` states.

### Other

- Border radius: `4px` (all variants/sizes)
- Font weight: 500 (Medium)
- Icon: 24px, right-aligned, optional

---

## Themes — `themes/{product}.json`

Product themes override only **surface, background, and layout tokens** —
never component styles. See `themes/shift.json` for the reference
implementation.

Theme schema matches the base color schema so it can be substituted
cleanly:

```json
{
  "meta": { "name": "shift", "type": "theme", ... },
  "colors": {
    "primary": { "50": "...", "100": "...", ..., "950": "..." },
    "gray":    { ... },
    ...
  }
}
```

---

## Accessibility — `accessibility/`

- `rules.md` — mandatory WCAG 2.1 AA rules (contrast, semantics, labels,
  keyboard access, focus states)
- `examples.md` — canonical good/bad code pairs
- `wcag.checklist.json` — machine-readable checklist of requirements

---

## Notes

- All colors are stored in uppercase hex (e.g., `#0047FF`)
- Grid containers are always center-aligned with 40px margins
- CTA buttons use Zoho Puvi Medium (500)
- Letter spacing is stored as both a percentage (source) and a resolved
  pixel value (derived)

---

## License

MIT — see [LICENSE](./LICENSE).
