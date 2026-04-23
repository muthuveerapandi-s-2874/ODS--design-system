# CLAUDE.md — ODS Design System

## Project Overview

This is the **ODS Design System**, a centralized design token repository extracted from Figma. It contains JSON-based design tokens and component specifications that serve as the single source of truth for colors, typography, grid, elevation, spacing, and accessibility guidelines across web projects.

**This is NOT a code application.** There is no build system, no package manager, no test framework, and no CI/CD pipeline. The repository consists entirely of JSON token files and Markdown documentation.

## Repository Structure

```
ODS--design-system/
├── Button/
│   └── cta-component.json          # CTA button variants, sizes, and states
├── Color tokens/
│   └── color-palette.json           # 16 color families, 11 shades each
├── Grids(web)/
│   └── grid-system.json             # 6 responsive breakpoints, column/margin specs
├── Typo/
│   └── typography.json              # Headings, paragraphs, font weights, spacing
├── wcag/
│   ├── wcag.checklist.json          # Accessibility checklist (images, contrast, forms, nav)
│   ├── wcag.rules.md                # WCAG 2.1 Level AA rules
│   └── wcag.examples.md             # Good/bad accessibility code examples
├── elevation-radius.json            # 5 elevation levels + 5 border radius sizes
├── sizing-tokens.json               # Spacing tokens (Sm/Md/Lg/Xl) referencing Space tokens
├── wcag.rules.md                    # WCAG rules (root copy)
├── wcag.examples.md                 # WCAG examples (root copy)
├── README.md                        # Comprehensive project documentation
└── CLAUDE.md                        # This file
```

Note: Some directories contain spaces or special characters (e.g., `Color tokens/`, `Grids(web)/`). Always quote these paths when referencing them in shell commands.

## Token Categories

### Colors (`Color tokens/color-palette.json`)
- 16 color families: red, orange, deepOrange, yellow, green, lime, lightBlue, cyan, teal, purple, pink, blue, grey, darkGrey, white, black
- Each family has shades 50 (lightest) through 950 (darkest)
- Hex format uses uppercase (e.g., `#0047FF`)
- Semantic mapping: blue = primary, red = error, green = success, orange = warning

### Typography (`Typo/typography.json`)
- Font family: "Zoho Puvi" with sans-serif fallback
- 4 weights: Regular (400), Medium (500), SemiBold (600), Bold (700)
- 6 heading levels (H1-H6) + 6 paragraph sizes (P1-P6)
- Letter spacing defined in both percentage and pixel values

### Grid System (`Grids(web)/grid-system.json`)
- 6 breakpoints: Mobile (576px), Small Tablet (768px), Tablet (1024px), Small Desktop (1280px), Desktop (1440px), Large Desktop (1720px+)
- Columns scale from 4 (mobile) to 12 (desktop)
- Consistent 40px side margins and 40px gutters at most breakpoints

### Elevation & Radius (`elevation-radius.json`)
- 5 shadow levels: xs, small, medium, large, xlarge — with pre-built CSS `box-shadow` strings
- 5 border-radius sizes: xs (2px), small (4px), medium (8px), large (16px), xlarge (160px)

### Sizing/Spacing (`sizing-tokens.json`)
- 4 scale categories: Sm (5 tokens), Md (8 tokens), Lg (10 tokens), Xl (10 tokens)
- Values reference `{Space.*}` tokens from Figma; some known resolved values provided (e.g., `Sm- 3` = 12px, `Md- 1` = 24px)

### CTA Button Component (`Button/cta-component.json`)
- 5 variants: primary, primaryLine, secondary, secondaryLine, tertiary
- 4 sizes: xs, sm, md, lg
- 3 states per variant: default, hover, active
- Optional icon support (24px, right-aligned)
- Border radius: 4px; font: Zoho Puvi Medium (500)

### WCAG Accessibility (`wcag/`)
- Targets WCAG 2.1 Level AA compliance
- Contrast ratios: 4.5:1 for normal text, 3:1 for large text
- Requires: alt text on images, form labels, keyboard navigation, visible focus, semantic HTML with landmarks

## Key Conventions

### JSON Structure
- Every token file includes a top-level `designSystem` metadata object with `name`, `figmaFile`, `nodeId`, and `url` linking back to the Figma source
- Property keys use camelCase (e.g., `fontFamily`, `fontSize`, `letterSpacing`)
- Sizing token names use a `{Category}- {Number}` pattern (e.g., `Sm- 1`, `Md- 5`, `Lg- 10`)
- Color shade keys are numeric strings: `"50"`, `"100"`, ..., `"950"`

### Figma Traceability
- All tokens include direct Figma file references so changes can be traced to the design source
- The Figma file key is `uddrCFCslgueV4AzTXScnP`

### No Build or Runtime Tooling
- No `package.json`, no npm scripts, no bundler, no TypeScript compilation
- Tokens are consumed directly as JSON by downstream projects
- The README provides TypeScript and React usage examples for consumers

## Working With This Repository

### Adding New Tokens
1. Create or update the relevant JSON file following the existing structure
2. Include `designSystem` metadata with the Figma source link
3. Use the established naming conventions (camelCase keys, numeric shade scales)
4. Update `README.md` if adding a new token category

### Adding New Components
1. Create a new directory for the component (prefer lowercase or PascalCase without spaces for new directories)
2. Add a JSON file with variant, size, and state definitions following the pattern in `Button/cta-component.json`
3. Include Figma source metadata
4. Document the component in `README.md`

### Modifying Existing Tokens
1. Ensure changes align with the Figma design source
2. Preserve the existing JSON structure and key naming patterns
3. Update documentation if token semantics change

### Validation Considerations
- JSON files should be valid JSON (no trailing commas, proper quoting)
- Color values should be uppercase hex format (e.g., `#0047FF`, not `#0047ff`)
- Spacing/sizing values should include units (e.g., `"16px"`, not `16`)
- CSS property strings (like `box-shadow`) should be pre-calculated and ready to use

## Common Pitfalls
- Directory names with spaces (`Color tokens/`) and parentheses (`Grids(web)/`) require quoting in shell commands
- Sizing tokens reference `{Space.*}` tokens that are not fully resolved in this repo; only a subset of known values is provided in `sizing-tokens.json` under `knownValues`
- The root-level `wcag.rules.md` and `wcag.examples.md` appear to be duplicates of the files in `wcag/`
