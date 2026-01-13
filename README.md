# ODS--design-system
Centralized design system tokens and components (JSON) for all web projects
This repository contains the color palette, typography, grid system, CTA components, and design tokens from the ODS Design System.

## Color Palette

The color palette has been extracted from the Figma design system and is available in multiple formats:

- **JSON**: `color-palette.json` - Machine-readable format
- **TypeScript**: `color-palette.ts` - Type-safe TypeScript definitions with helper functions

### Figma Source

- **Design File**: [ODS_Guideline](https://www.figma.com/design/uddrCFCslgueV4AzTXScnP/ODS_Guideline?node-id=201-1450)
- **File Key**: `uddrCFCslgueV4AzTXScnP`
- **Node ID**: `201:1450`

## Color Families

The design system includes the following color families, each with shades from 50 (lightest) to 950 (darkest):

1. **Red** - Error states, destructive actions
2. **Orange** - Warnings, attention
3. **Deep Orange** - Strong warnings
4. **Yellow** - Cautions, highlights
5. **Green** - Success states, positive actions
6. **Lime** - Light success indicators
7. **Light Blue** - Information, light accents
8. **Cyan** - Secondary information
9. **Teal** - Tertiary information
10. **Purple** - Special accents
11. **Pink** - Special accents
12. **Blue** - Primary actions, links
13. **Grey** - Neutral tones, text
14. **Dark Grey** - Dark mode backgrounds
15. **White** - Backgrounds, contrast
16. **Black** - Text, high contrast

## Usage

### TypeScript/JavaScript

```typescript
import { colors, getColor } from './color-palette';

// Access specific colors
const primaryBlue = colors.blue[500]; // #0047FF
const errorRed = colors.red[500]; // #FF0405
const successGreen = colors.green[500]; // #03FF17

// Use helper function
const myColor = getColor('blue', 500);
```

### JSON

```javascript
const palette = require('./color-palette.json');
const primaryBlue = palette.colors.blue[500];
```

## Color Shade Scale

Each color family follows a consistent shade scale:
- **50-200**: Light tints, backgrounds
- **300-400**: Lighter accents
- **500**: Base color (most commonly used)
- **600-700**: Darker accents
- **800-950**: Dark shades, text on light backgrounds

## Typography

The typography system has been extracted from the Figma design system and is available in multiple formats:

- **JSON**: `typography.json` - Machine-readable format
- **TypeScript**: `typography.ts` - Type-safe TypeScript definitions with helper functions

### Figma Source

- **Design File**: [ODS_Guideline - Typography](https://www.figma.com/design/uddrCFCslgueV4AzTXScnP/ODS_Guideline?node-id=1942-136)
- **File Key**: `uddrCFCslgueV4AzTXScnP`
- **Node ID**: `1942:136`

### Font Family

- **Name**: Zoho Puvi
- **Fallback**: sans-serif
- **CSS**: `'Zoho Puvi', sans-serif`

### Font Weights

- Regular: 400
- Medium: 500
- Semibold: 600
- Bold: 700

### Heading Styles

| Level | Font Size | Line Height | Use Case |
|-------|-----------|-------------|----------|
| H1    | 88px      | 96px        | Main page titles |
| H2    | 80px      | 88px        | Section headers |
| H3    | 72px      | 80px        | Subsection headers |
| H4    | 64px      | 72px        | Card titles |
| H5    | 56px      | 64px        | Smaller headings |
| H6    | 48px      | 56px        | Smallest headings |

### Paragraph Styles

| Size      | Font Size | Line Height | Use Case |
|-----------|-----------|-------------|----------|
| Large     | 40px      | 48px        | Large body text |
| Medium    | 32px      | 40px        | Medium body text |
| Regular   | 24px      | 32px        | Standard body text |
| Small     | 20px      | 28px        | Small body text |
| X-Small   | 16px      | 24px        | Extra small text |
| Tiny      | 12px      | 16px        | Captions, labels |

### Usage

#### TypeScript/JavaScript

```typescript
import { headings, paragraphs, getTypographyStyle, typographyStyles } from './typography';

// Use helper function
const h1Style = getTypographyStyle('heading', 'h1', 'medium');
// Returns: { fontFamily, fontSize, lineHeight, fontWeight, letterSpacing }

// Use pre-defined styles
const headingStyle = typographyStyles.h1;
const bodyStyle = typographyStyles.bodyRegular;

// Access specific styles
const h2Regular = headings.h2.regular;
const bodyMedium = paragraphs.medium.medium;
```

#### JSON

```javascript
const typography = require('./typography.json');
const h1Size = typography.headings.h1.fontSize; // "88px"
const bodyFont = typography.paragraphs.regular.fontSize; // "24px"
```

## Grid System

The grid system has been extracted from the Figma design system and is available in multiple formats:

- **JSON**: `grid-system.json` - Machine-readable format
- **TypeScript**: `grid-system.ts` - Type-safe TypeScript definitions with helper functions

### Figma Source

- **Design File**: [ODS_Guideline - Grids](https://www.figma.com/design/uddrCFCslgueV4AzTXScnP/ODS_Guideline?node-id=1-2)
- **File Key**: `uddrCFCslgueV4AzTXScnP`
- **Node ID**: `1:2`

### Breakpoints

| Breakpoint | Min Width | Max Width | Columns | Column Width | Gutter | Container Width |
|------------|-----------|-----------|---------|--------------|--------|-----------------|
| Desktop | 1720px | - | 12 | 88px | 24px | 1720px |
| Desktop Medium | 1400px | 1720px | 12 | 88px | 24px | 1400px |
| Desktop Small | 1200px | 1400px | 12 | 56px | 32px | 1200px |
| Tablet | 992px | 1200px | 12 | 48px | 16px | 992px |
| Tablet Small | 768px | 992px | 8 | 64px | 16px | 768px |
| Mobile | 576px | 768px | 4 | 104px | 16px | 576px |

### Grid Properties

- **Type**: All grids are center-aligned
- **Margin**: 40px (consistent across all breakpoints)
- **Default Columns**: 12 (except tablet small: 8, mobile: 4)

### Usage

#### TypeScript/JavaScript

```typescript
import { 
  gridBreakpoints, 
  getColumnWidth, 
  getBreakpoint, 
  mediaQueries,
  gridConfig 
} from './grid-system';

// Get breakpoint for current width
const breakpoint = getBreakpoint(window.innerWidth);

// Calculate column span width (e.g., 6 columns)
const width = getColumnWidth('desktop', 6);

// Use media queries
const desktopQuery = mediaQueries.desktop; // "(min-width: 1720px)"

// Get grid configuration for CSS Grid
const gridStyles = gridConfig.desktop;
```

#### CSS Media Queries

```css
/* Desktop */
@media (min-width: 1720px) {
  .container {
    max-width: 1720px;
    grid-template-columns: repeat(12, 88px);
    gap: 24px;
  }
}

/* Tablet */
@media (min-width: 992px) and (max-width: 1199px) {
  .container {
    max-width: 992px;
    grid-template-columns: repeat(12, 48px);
    gap: 16px;
  }
}

/* Mobile */
@media (min-width: 576px) and (max-width: 767px) {
  .container {
    max-width: 576px;
    grid-template-columns: repeat(4, 104px);
    gap: 16px;
  }
}
```

#### JSON

```javascript
const grid = require('./grid-system.json');
const desktopColumns = grid.breakpoints.desktop.columns; // 12
const tabletGutter = grid.breakpoints.tablet.gutter; // 16
```

## CTA Component

The CTA (Call-to-Action) button component has been extracted from the Figma design system and is available in multiple formats:

- **JSON**: `cta-component.json` - Machine-readable format
- **TypeScript**: `cta-component.ts` - Type-safe TypeScript definitions with helper functions

### Figma Source

- **Design File**: [ODS_Guideline - CTA](https://www.figma.com/design/uddrCFCslgueV4AzTXScnP/ODS_Guideline?node-id=4754-1968)
- **File Key**: `uddrCFCslgueV4AzTXScnP`
- **Node ID**: `4754:1968`

### Variants

| Variant | Description | Default Background | Default Text Color |
|---------|-------------|-------------------|-------------------|
| Primary | Solid blue button for primary actions | #0047FF | #FFFFFF |
| Primary Line | Outlined blue button | Transparent | #0047FF |
| Secondary | Solid black button | #000000 | #FFFFFF |
| Secondary Line | Outlined black button | Transparent | #000000 |
| Tertiary | White button with border | #FFFFFF | #000000 |

### Sizes

| Size | Padding | Font Size | Line Height | Height | Use Case |
|------|---------|-----------|-------------|--------|----------|
| xs | 12px 16px | 16px | 24px | auto | Compact spaces |
| sm | 16px 24px | 16px | 24px | 56px | Standard buttons |
| md | 20px 24px | 20px | 28px | auto | Default size |
| lg | 24px 32px | 24px | 32px | auto | Prominent CTAs |

### States

Each variant has three states:
- **Default**: Base appearance
- **Hover**: Darker background/outline, cursor pointer
- **Active**: Darkest background/outline (pressed state)

### Usage

#### TypeScript/JavaScript

```typescript
import { getCTACSS, getCTAStyles, ctaStyles, CTAVariant, CTASize, CTAState } from './cta-component';

// Get styles dynamically
const buttonStyles = getCTACSS('primary', 'md', 'hover');

// Use pre-defined styles
const primaryButton = ctaStyles.primary.md;

// Get complete style object
const styles = getCTAStyles('secondary', 'lg', 'default');
```

#### React Example

```typescript
import { getCTACSS } from './cta-component';

function Button({ variant = 'primary', size = 'md', children, ...props }) {
  const styles = getCTACSS(variant, size, 'default');
  
  return (
    <button style={styles} {...props}>
      {children}
    </button>
  );
}
```

#### JSON

```javascript
const cta = require('./cta-component.json');
const primaryMd = cta.variants.primary.sizes.md;
const hoverState = cta.variants.primary.states.hover;
```

### Icon Support

- **Size**: 24px
- **Position**: Right side (default)
- **Optional**: Can be disabled or customized

## Sizing Tokens

The sizing tokens have been extracted from the design system tokens and are available in multiple formats:

- **JSON**: `sizing-tokens.json` - Machine-readable format
- **TypeScript**: `sizing-tokens.ts` - Type-safe TypeScript definitions with helper functions

### Source

- **Source File**: `/Users/muthu-2874/Documents/ODS/tokens/Sizing tokens/Sizing tokens.json`
- **Note**: These tokens reference Space tokens. Actual pixel values are resolved from Space token definitions.

### Token Categories

| Category | Tokens | Count |
|----------|--------|-------|
| Small | Sm- 1 to Sm- 5 | 5 |
| Medium | Md- 1 to Md- 8 | 8 |
| Large | Lg- 1 to Lg- 10 | 10 |
| XLarge | Xl- 1 to Xl- 10 | 10 |

### Known Values

These values have been inferred from component usage. Complete values should come from Space tokens:

| Token | Value | Usage |
|-------|-------|-------|
| Sm- 3 | 12px | Small spacing, gaps |
| Sm- 4 | 16px | Standard small spacing |
| Sm- 5 | 20px | Medium-small spacing |
| Md- 1 | 24px | Standard medium spacing |
| Md- 2 | 32px | Large medium spacing |
| Md- 5 | 56px | Extra large medium spacing |

### Usage

#### TypeScript/JavaScript

```typescript
import { 
  getSizingToken, 
  getSizingTokenPx, 
  sizingTokens, 
  sizingCategories,
  knownSizingValues 
} from './sizing-tokens';

// Get token value (returns known value or reference)
const spacing = getSizingToken('Sm- 4'); // "16px" or "{Space.Sm- 4}"

// Get pixel value (throws if not resolved)
const pxValue = getSizingTokenPx('Md- 1'); // "24px"

// Access token directly
const token = sizingTokens['Sm- 3'];

// Use categories
const smallTokens = sizingCategories.small; // ['Sm- 1', 'Sm- 2', ...]
```

#### JSON

```javascript
const sizing = require('./sizing-tokens.json');
const sm3 = sizing.tokens['Sm- 3'];
const knownValues = sizing.knownValues;
```

## Notes

- Colors are stored in uppercase hex format (e.g., `#0047FF`)
- The design system follows Material Design-inspired color scales
- All colors, typography, grid system, and components have been extracted directly from the Figma design files
- Letter spacing is calculated as a percentage of font size and converted to pixels
- Grid containers are always center-aligned with consistent 40px margins
- CTA buttons use Zoho Puvi Medium font (500 weight) with center alignment

