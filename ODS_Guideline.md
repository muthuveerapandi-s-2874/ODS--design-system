---
title: "ODS_Guideline.md — ODS_Guideline"
---

# DESIGN.md — ODS_Guideline

> **AI AGENT INSTRUCTIONS — READ FIRST, APPLY TO ALL OUTPUT**
>
> This file is the complete visual specification for **"ODS_Guideline"**.
> Apply every rule below to every line of UI, HTML, CSS, JSX, or component code you generate.
>
> 1. **Colours** — Use only exact hex values or `var(--token)` names from this file. No substitutions.
> 2. **Typography** — Match font family, weight, size, line-height exactly.
> 3. **Spacing** — Use only values from the spacing/sizing token tables.
> 4. **Border radius** — Use only the defined radius tokens.
> 5. **Components** — Mirror defined structures. Honour variant property names exactly.
> 6. **Shadows** — Apply defined elevation styles. Do not invent shadows.
> 7. **Unknowns** — If a visual decision is not defined here, ask before inventing it.

## How to Use

| Platform | Instructions |
|----------|-------------|
| **Google Stitch** | Upload via *Design System → DESIGN.md* |
| **Claude Code** | Place in project root, reference as `@DESIGN.md` |
| **Cursor / Windsurf** | Add to context, prompt: *"Follow @DESIGN.md for all visual decisions"* |
| **Antigravity** | Import via *Design System settings* |
| **OpenAI Codex** | Paste as system context before UI tasks |
| **Any LLM** | Paste at top of session as system context |

```
You have the design system for "ODS_Guideline" in DESIGN.md. Follow it precisely for ALL visual decisions. No deviations.
```

## Design System Summary

- **Source**: ODS_Guideline · Generated: 2026-04-19
- **Color tokens**: 528
- **Spacing / size tokens**: 128
- **Border radius tokens**: 6
- **Typography tokens**: 80
- **Text styles**: 48
- **Effect styles**: 5
- **Paint styles**: 151
- **Component sets**: 19

## Color Tokens

> Use only these values. Reference as CSS custom properties (`var(--token-name)`).

### Primitives

| Token | Value | Alias source |
|-------|-------|-------------|
| `Blue/950` | `#000719` | — |
| `Blue/900` | `#000e33` | — |
| `Blue/800` | `#001d66` | — |
| `Blue/700` | `#012b99` | — |
| `Blue/600` | `#003acc` | — |
| `Blue/500` | `#0047ff` | — |
| `Blue/400` | `#336dff` | — |
| `Blue/300` | `#6691ff` | — |
| `Blue/200` | `#9ab6ff` | — |
| `Blue/100` | `#ccdaff` | — |
| `Blue/50` | `#e4edff` | — |
| `Teal/950` | `#015d54` | — |
| `Teal/900` | `#008075` | — |
| `Teal/800` | `#05a79a` | — |
| `Teal/700` | `#00ccbb` | — |
| `Teal/600` | `#01e6d2` | — |
| `Teal/500` | `#0fffeb` | — |
| `Teal/400` | `#75fff4` | — |
| `Teal/300` | `#adfff9` | — |
| `Teal/200` | `#ccfffb` | — |
| `Teal/100` | `#ebfffd` | — |
| `Teal/50` | `#f5fffe` | — |
| `Grey/950` | `#1a1a1a` | — |
| `Grey/900` | `#262626` | — |
| `Grey/800` | `#383838` | — |
| `Grey/700` | `#454545` | — |
| `Grey/600` | `#4f4f4f` | — |
| `Grey/500` | `#595959` | — |
| `Grey/400` | `#919191` | — |
| `Grey/300` | `#b5b5b5` | — |
| `Grey/200` | `#d1d1d1` | — |
| `Grey/100` | `#ebebeb` | — |
| `Grey/50` | `#f5f5f5` | — |
| `Cyan/950` | `#011619` | — |
| `Cyan/900` | `#012c32` | — |
| `Cyan/800` | `#035e69` | — |
| `Cyan/700` | `#03899c` | — |
| `Cyan/600` | `#07bad2` | — |
| `Cyan/500` | `#10dffa` | — |
| `Cyan/400` | `#40e5fb` | — |
| `Cyan/300` | `#6eebfc` | — |
| `Cyan/200` | `#9ff2fd` | — |
| `Cyan/100` | `#ccf8fe` | — |
| `Cyan/50` | `#e6fcff` | — |
| `DeepOrange/950` | `#190900` | — |
| `DeepOrange/900` | `#331300` | — |
| `DeepOrange/800` | `#662500` | — |
| `DeepOrange/700` | `#9e3a01` | — |
| `DeepOrange/600` | `#d14d00` | — |
| `DeepOrange/500` | `#ff6105` | — |
| `DeepOrange/400` | `#ff8138` | — |
| `DeepOrange/300` | `#ffa16b` | — |
| `DeepOrange/200` | `#ffbe9a` | — |
| `DeepOrange/100` | `#ffdfcb` | — |
| `DeepOrange/50` | `#ffeee5` | — |
| `Lime/950` | `#171900` | — |
| `Lime/900` | `#2e3300` | — |
| `Lime/800` | `#606b01` | — |
| `Lime/700` | `#8e9f00` | — |
| `Lime/600` | `#c1d601` | — |
| `Lime/500` | `#e6ff0a` | — |
| `Lime/400` | `#ebff3e` | — |
| `Lime/300` | `#f0ff6a` | — |
| `Lime/200` | `#f5ff9d` | — |
| `Lime/100` | `#faffcc` | — |
| `Lime/50` | `#fdffe4` | — |
| `Pink/950` | `#180109` | — |
| `Pink/900` | `#310212` | — |
| `Pink/800` | `#620423` | — |
| `Pink/700` | `#970736` | — |
| `Pink/600` | `#c80b49` | — |
| `Pink/500` | `#f4115d` | — |
| `Pink/400` | `#f6417d` | — |
| `Pink/300` | `#f8729f` | — |
| `Pink/200` | `#fb9dbc` | — |
| `Pink/100` | `#fecedf` | — |
| `Pink/50` | `#fee7ee` | — |
| `Purple/950` | `#090019` | — |
| `Purple/900` | `#130033` | — |
| `Purple/800` | `#240066` | — |
| `Purple/700` | `#37009f` | — |
| `Purple/600` | `#4900d1` | — |
| `Purple/500` | `#5e05ff` | — |
| `Purple/400` | `#7e38ff` | — |
| `Purple/300` | `#9f6bff` | — |
| `Purple/200` | `#bd99ff` | — |
| `Purple/100` | `#deccff` | — |
| `Purple/50` | `#eee5ff` | — |
| `Lightblue/950` | `#001119` | — |
| `Lightblue/900` | `#002232` | — |
| `Lightblue/800` | `#004466` | — |
| `Lightblue/700` | `#01699e` | — |
| `Lightblue/600` | `#008bd1` | — |
| `Lightblue/500` | `#09abff` | — |
| `Lightblue/400` | `#38bdff` | — |
| `Lightblue/300` | `#6bceff` | — |
| `Lightblue/200` | `#99ddff` | — |
| `Lightblue/100` | `#cdeeff` | — |
| `Lightblue/50` | `#e5f7ff` | — |
| `Green/950` | `#011902` | — |
| `Green/900` | `#003203` | — |
| `Green/800` | `#00660a` | — |
| `Green/700` | `#019e0d` | — |
| `Green/600` | `#04d111` | — |
| `Green/500` | `#03ff17` | — |
| `Green/400` | `#37ff49` | — |
| `Green/300` | `#6cff77` | — |
| `Green/200` | `#99ffa2` | — |
| `Green/100` | `#ccffd0` | — |
| `Green/50` | `#e5ffe8` | — |
| `Yellow/950` | `#564800` | — |
| `Yellow/900` | `#7a6600` | — |
| `Yellow/800` | `#ad9001` | — |
| `Yellow/700` | `#cba901` | — |
| `Yellow/600` | `#eac301` | — |
| `Yellow/500` | `#fed70b` | — |
| `Yellow/400` | `#fee253` | — |
| `Yellow/300` | `#feea85` | — |
| `Yellow/200` | `#fff3b3` | — |
| `Yellow/100` | `#fff9db` | — |
| `Yellow/50` | `#fffceb` | — |
| `Orange/950` | `#180f00` | — |
| `Orange/900` | `#331f00` | — |
| `Orange/800` | `#6b4000` | — |
| `Orange/700` | `#9e5f01` | — |
| `Orange/600` | `#d68100` | — |
| `Orange/500` | `#ff9e08` | — |
| `Orange/400` | `#ffb13d` | — |
| `Orange/300` | `#ffc46b` | — |
| `Orange/200` | `#ffd99e` | — |
| `Orange/100` | `#ffebcb` | — |
| `Orange/50` | `#fff5e5` | — |
| `Red/950` | `#190001` | — |
| `Red/900` | `#330000` | — |
| `Red/800` | `#660000` | — |
| `Red/700` | `#9f0101` | — |
| `Red/600` | `#d10000` | — |
| `Red/500` | `#ff0405` | — |
| `Red/400` | `#ff3938` | — |
| `Red/300` | `#ff6b6b` | — |
| `Red/200` | `#ff999a` | — |
| `Red/100` | `#ffcccc` | — |
| `Red/50` | `#ffe5e4` | — |
| `Blue/Color` | `#ffffff` | — |
| `White & black/White` | `#ffffff` | — |
| `White & black/Black` | `#000000` | — |
| `Dark Grey/950` | `#030303` | — |
| `Dark Grey/900` | `#050505` | — |
| `Dark Grey/800` | `#080808` | — |
| `Dark Grey/700` | `#0a0a0a` | — |
| `Dark Grey/600` | `#0d0d0d` | — |
| `Dark Grey/500` | `#0f0f0f` | — |
| `Dark Grey/400` | `#121212` | — |
| `Dark Grey/300` | `#141414` | — |
| `Dark Grey/200` | `#171717` | — |
| `Dark Grey/100` | `#1a1a1a` | — |
| `Dark Grey/50` | `#1a1a1a` | — |
| `Beige/50` | `#fdf8f0` | — |
| `Beige/100` | `#faf0e1` | — |
| `Beige/200` | `#f5e1c3` | — |
| `Beige/300` | `#efcfa0` | — |
| `Beige/400` | `#e8bc7d` | — |
| `Beige/500` | `#e0a85a` | — |
| `Beige/600` | `#c48e3e` | — |
| `Beige/700` | `#a0722e` | — |
| `Beige/800` | `#7a5721` | — |
| `Beige/900` | `#543c17` | — |
| `Beige/950` | `#2e200c` | — |
| `WarmGray/50` | `#faf8f6` | — |
| `WarmGray/100` | `#f0edea` | — |
| `WarmGray/200` | `#e0dbd5` | — |
| `WarmGray/300` | `#c8c0b8` | — |
| `WarmGray/400` | `#ada39a` | — |
| `WarmGray/500` | `#93877c` | — |
| `WarmGray/600` | `#796d62` | — |
| `WarmGray/700` | `#5f544b` | — |
| `WarmGray/800` | `#463d35` | — |
| `WarmGray/900` | `#2e2721` | — |
| `WarmGray/950` | `#1a1512` | — |
| `CoolGray/50` | `#f5f7fa` | — |
| `CoolGray/100` | `#ebeef3` | — |
| `CoolGray/200` | `#d5dbe5` | — |
| `CoolGray/300` | `#b8c1d1` | — |
| `CoolGray/400` | `#9aa7bd` | — |
| `CoolGray/500` | `#7c8da8` | — |
| `CoolGray/600` | `#627390` | — |
| `CoolGray/700` | `#4b5a74` | — |
| `CoolGray/800` | `#354158` | — |
| `CoolGray/900` | `#212b3d` | — |
| `CoolGray/950` | `#121822` | — |
| `Dark/50` | `#e8e8ee` | — |
| `Dark/100` | `#c4c4d4` | — |
| `Dark/200` | `#9696b0` | — |
| `Dark/300` | `#6a6a8c` | — |
| `Dark/400` | `#464668` | — |
| `Dark/500` | `#2a2a4a` | — |
| `Dark/600` | `#22223c` | — |
| `Dark/700` | `#1a1a2e` | — |
| `Dark/800` | `#121222` | — |
| `Dark/900` | `#0a0a18` | — |
| `Dark/950` | `#05050c` | — |

### Semantic colors

| Token | Value | Alias source |
|-------|-------|-------------|
| `Semantic/Success/Subtle` | `#ccffd0` | ← `Green/100` |
| `Semantic/Success/Bold` | `#03ff17` | ← `Green/500` |
| `Semantic/Error/Subtle` | `#ffe5e4` | ← `Red/50` |
| `Semantic/Error/Bold` | `#ff0405` | ← `Red/500` |
| `Semantic/Warning/Subtle` | `#ffdfcb` | ← `DeepOrange/100` |
| `Semantic/Warning/Bold` | `#ff6105` | ← `DeepOrange/500` |
| `Semantic/button-primary-bg/Subtle` | `#ffdfcb` | ← `DeepOrange/100` |
| `Semantic/button-primary-bg/Bold` | `#ff6105` | ← `DeepOrange/500` |

### Primitives/Mode 1

| Token | Value | Alias source |
|-------|-------|-------------|
| `Blue/950` | `#000719` | — |
| `Blue/900` | `#000e33` | — |
| `Blue/800` | `#001d66` | — |
| `Blue/700` | `#012b99` | — |
| `Blue/600` | `#003acc` | — |
| `Blue/500` | `#0047ff` | — |
| `Blue/400` | `#336dff` | — |
| `Blue/300` | `#6691ff` | — |
| `Blue/200` | `#9ab6ff` | — |
| `Blue/100` | `#ccdaff` | — |
| `Blue/50` | `#e4edff` | — |
| `Teal/950` | `#015d54` | — |
| `Teal/900` | `#008075` | — |
| `Teal/800` | `#05a79a` | — |
| `Teal/700` | `#00ccbb` | — |
| `Teal/600` | `#01e6d2` | — |
| `Teal/500` | `#0fffeb` | — |
| `Teal/400` | `#75fff4` | — |
| `Teal/300` | `#adfff9` | — |
| `Teal/200` | `#ccfffb` | — |
| `Teal/100` | `#ebfffd` | — |
| `Teal/50` | `#f5fffe` | — |
| `Gray/950` | `#1a1a1a` | — |
| `Gray/900` | `#262626` | — |
| `Gray/800` | `#383838` | — |
| `Gray/700` | `#454545` | — |
| `Gray/600` | `#4f4f4f` | — |
| `Gray/500` | `#595959` | — |
| `Gray/400` | `#919191` | — |
| `Gray/300` | `#b5b5b5` | — |
| `Gray/200` | `#d1d1d1` | — |
| `Gray/100` | `#ebebeb` | — |
| `Gray/50` | `#f5f5f5` | — |
| `Cyan/950` | `#011619` | — |
| `Cyan/900` | `#012c32` | — |
| `Cyan/800` | `#035e69` | — |
| `Cyan/700` | `#03899c` | — |
| `Cyan/600` | `#07bad2` | — |
| `Cyan/500` | `#10dffa` | — |
| `Cyan/400` | `#40e5fb` | — |
| `Cyan/300` | `#6eebfc` | — |
| `Cyan/200` | `#9ff2fd` | — |
| `Cyan/100` | `#ccf8fe` | — |
| `Cyan/50` | `#e6fcff` | — |
| `DeepOrange/950` | `#190900` | — |
| `DeepOrange/900` | `#331300` | — |
| `DeepOrange/800` | `#662500` | — |
| `DeepOrange/700` | `#9e3a01` | — |
| `DeepOrange/600` | `#d14d00` | — |
| `DeepOrange/500` | `#ff6105` | — |
| `DeepOrange/400` | `#ff8138` | — |
| `DeepOrange/300` | `#ffa16b` | — |
| `DeepOrange/200` | `#ffbe9a` | — |
| `DeepOrange/100` | `#ffdfcb` | — |
| `DeepOrange/50` | `#ffeee5` | — |
| `Lime/950` | `#171900` | — |
| `Lime/900` | `#2e3300` | — |
| `Lime/800` | `#606b01` | — |
| `Lime/700` | `#8e9f00` | — |
| `Lime/600` | `#c1d601` | — |
| `Lime/500` | `#e6ff0a` | — |
| `Lime/400` | `#ebff3e` | — |
| `Lime/300` | `#f0ff6a` | — |
| `Lime/200` | `#f5ff9d` | — |
| `Lime/100` | `#faffcc` | — |
| `Lime/50` | `#fdffe4` | — |
| `Pink/950` | `#180109` | — |
| `Pink/900` | `#310212` | — |
| `Pink/800` | `#620423` | — |
| `Pink/700` | `#970736` | — |
| `Pink/600` | `#c80b49` | — |
| `Pink/500` | `#f4115d` | — |
| `Pink/400` | `#f6417d` | — |
| `Pink/300` | `#f8729f` | — |
| `Pink/200` | `#fb9dbc` | — |
| `Pink/100` | `#fecedf` | — |
| `Pink/50` | `#fee7ee` | — |
| `Purple/950` | `#090019` | — |
| `Purple/900` | `#130033` | — |
| `Purple/800` | `#240066` | — |
| `Purple/700` | `#37009f` | — |
| `Purple/600` | `#4900d1` | — |
| `Purple/500` | `#5e05ff` | — |
| `Purple/400` | `#7e38ff` | — |
| `Purple/300` | `#9f6bff` | — |
| `Purple/200` | `#bd99ff` | — |
| `Purple/100` | `#deccff` | — |
| `Purple/50` | `#eee5ff` | — |
| `Lightblue/950` | `#001119` | — |
| `Lightblue/900` | `#002232` | — |
| `Lightblue/800` | `#004466` | — |
| `Lightblue/700` | `#01699e` | — |
| `Lightblue/600` | `#008bd1` | — |
| `Lightblue/500` | `#09abff` | — |
| `Lightblue/400` | `#38bdff` | — |
| `Lightblue/300` | `#6bceff` | — |
| `Lightblue/200` | `#99ddff` | — |
| `Lightblue/100` | `#cdeeff` | — |
| `Lightblue/50` | `#e5f7ff` | — |
| `Green/950` | `#011902` | — |
| `Green/900` | `#003203` | — |
| `Green/800` | `#00660a` | — |
| `Green/700` | `#019e0d` | — |
| `Green/600` | `#04d111` | — |
| `Green/500` | `#03ff17` | — |
| `Green/400` | `#37ff49` | — |
| `Green/300` | `#6cff77` | — |
| `Green/200` | `#99ffa2` | — |
| `Green/100` | `#ccffd0` | — |
| `Green/50` | `#e5ffe8` | — |
| `Yellow/950` | `#564800` | — |
| `Yellow/900` | `#7a6600` | — |
| `Yellow/800` | `#ad9001` | — |
| `Yellow/700` | `#cba901` | — |
| `Yellow/600` | `#eac301` | — |
| `Yellow/500` | `#fed70b` | — |
| `Yellow/400` | `#fee253` | — |
| `Yellow/300` | `#feea85` | — |
| `Yellow/200` | `#fff3b3` | — |
| `Yellow/100` | `#fff9db` | — |
| `Yellow/50` | `#fffceb` | — |
| `Orange/950` | `#180f00` | — |
| `Orange/900` | `#331f00` | — |
| `Orange/800` | `#6b4000` | — |
| `Orange/700` | `#9e5f01` | — |
| `Orange/600` | `#d68100` | — |
| `Orange/500` | `#ff9e08` | — |
| `Orange/400` | `#ffb13d` | — |
| `Orange/300` | `#ffc46b` | — |
| `Orange/200` | `#ffd99e` | — |
| `Orange/100` | `#ffebcb` | — |
| `Orange/50` | `#fff5e5` | — |
| `Red/950` | `#190001` | — |
| `Red/900` | `#330000` | — |
| `Red/800` | `#660000` | — |
| `Red/700` | `#9f0101` | — |
| `Red/600` | `#d10000` | — |
| `Red/500` | `#ff0405` | — |
| `Red/400` | `#ff3938` | — |
| `Red/300` | `#ff6b6b` | — |
| `Red/200` | `#ff999a` | — |
| `Red/100` | `#ffcccc` | — |
| `Red/50` | `#ffe5e4` | — |
| `Blue/Color` | `#ffffff` | — |
| `White & black/White` | `#ffffff` | — |
| `White & black/Black` | `#000000` | — |
| `Dark Gray/950` | `#030303` | — |
| `Dark Gray/900` | `#050505` | — |
| `Dark Gray/800` | `#080808` | — |
| `Dark Gray/700` | `#0a0a0a` | — |
| `Dark Gray/600` | `#0d0d0d` | — |
| `Dark Gray/500` | `#0f0f0f` | — |
| `Dark Gray/400` | `#121212` | — |
| `Dark Gray/300` | `#141414` | — |
| `Dark Gray/200` | `#171717` | — |
| `Dark Gray/100` | `#1a1a1a` | — |
| `Dark Gray/50` | `#1a1a1a` | — |

### Light Shades

| Token | Value | Alias source |
|-------|-------|-------------|
| `bg/page` | `#ffffff` | ← `White & black/White` |
| `bg/subtle` | `#f5f5f5` | ← `Grey/50` |
| `bg/muted` | `#ebebeb` | ← `Grey/100` |
| `bg/emphasized` | `#d1d1d1` | ← `Grey/200` |
| `surface/default` | `#ffffff` | ← `White & black/White` |
| `surface/raised` | `#f5f5f5` | ← `Grey/50` |
| `surface/overlay` | `#ebebeb` | ← `Grey/100` |
| `state/error/bg` | `#ffe5e4` | ← `Red/50` |
| `state/error/bg-hover` | `#ffcccc` | ← `Red/100` |
| `state/error/bg-active` | `#ff999a` | ← `Red/200` |
| `state/warning/bg` | `#fff5e5` | ← `Orange/50` |
| `state/warning/bg-hover` | `#ffebcb` | ← `Orange/100` |
| `state/warning/bg-active` | `#ffd99e` | ← `Orange/200` |
| `state/success/bg` | `#e5ffe8` | ← `Green/50` |
| `state/success/bg-hover` | `#ccffd0` | ← `Green/100` |
| `state/success/bg-active` | `#99ffa2` | ← `Green/200` |
| `state/info/bg` | `#e4edff` | ← `Blue/50` |
| `state/info/bg-hover` | `#ccdaff` | ← `Blue/100` |
| `state/info/bg-active` | `#9ab6ff` | ← `Blue/200` |
| `state/notice/bg` | `#fffceb` | ← `Yellow/50` |
| `state/notice/bg-hover` | `#fff9db` | ← `Yellow/100` |
| `state/notice/bg-active` | `#fff3b3` | ← `Yellow/200` |
| `state/critical/bg` | `#ffe5e4` | ← `Red/50` |
| `state/critical/bg-hover` | `#ffcccc` | ← `Red/100` |
| `state/pink/bg` | `#fee7ee` | ← `Pink/50` |
| `state/pink/bg-hover` | `#fecedf` | ← `Pink/100` |
| `state/purple/bg` | `#eee5ff` | ← `Purple/50` |
| `state/purple/bg-hover` | `#deccff` | ← `Purple/100` |
| `state/teal/bg` | `#f5fffe` | ← `Teal/50` |
| `state/teal/bg-hover` | `#ebfffd` | ← `Teal/100` |
| `state/cyan/bg` | `#e6fcff` | ← `Cyan/50` |
| `state/cyan/bg-hover` | `#ccf8fe` | ← `Cyan/100` |
| `state/lightblue/bg` | `#e5f7ff` | ← `Lightblue/50` |
| `state/lightblue/bg-hover` | `#cdeeff` | ← `Lightblue/100` |
| `state/lime/bg` | `#fdffe4` | ← `Lime/50` |
| `state/lime/bg-hover` | `#faffcc` | ← `Lime/100` |
| `state/deeporange/bg` | `#ffeee5` | ← `DeepOrange/50` |
| `state/deeporange/bg-hover` | `#ffdfcb` | ← `DeepOrange/100` |
| `light-shade/Red/1` | `#ffe5e4` | ← `Red/50` |
| `light-shade/Red/2` | `#ffcccc` | ← `Red/100` |
| `light-shade/Red/3` | `#ff999a` | ← `Red/200` |
| `light-shade/Orange/1` | `#fff5e5` | ← `Orange/50` |
| `light-shade/Orange/2` | `#ffebcb` | ← `Orange/100` |
| `light-shade/Orange/3` | `#ffd99e` | ← `Orange/200` |
| `light-shade/DeepOrange/1` | `#ffeee5` | ← `DeepOrange/50` |
| `light-shade/DeepOrange/2` | `#ffdfcb` | ← `DeepOrange/100` |
| `light-shade/DeepOrange/3` | `#ffbe9a` | ← `DeepOrange/200` |
| `light-shade/Yellow/1` | `#fffceb` | ← `Yellow/50` |
| `light-shade/Yellow/2` | `#fff9db` | ← `Yellow/100` |
| `light-shade/Yellow/3` | `#fff3b3` | ← `Yellow/200` |
| `light-shade/Green/1` | `#e5ffe8` | ← `Green/50` |
| `light-shade/Green/2` | `#ccffd0` | ← `Green/100` |
| `light-shade/Green/3` | `#99ffa2` | ← `Green/200` |
| `light-shade/Lime/1` | `#fdffe4` | ← `Lime/50` |
| `light-shade/Lime/2` | `#faffcc` | ← `Lime/100` |
| `light-shade/Lime/3` | `#f5ff9d` | ← `Lime/200` |
| `light-shade/Blue/1` | `#e4edff` | ← `Blue/50` |
| `light-shade/Blue/2` | `#ccdaff` | ← `Blue/100` |
| `light-shade/Blue/3` | `#9ab6ff` | ← `Blue/200` |
| `light-shade/Lightblue/1` | `#e5f7ff` | ← `Lightblue/50` |
| `light-shade/Lightblue/2` | `#cdeeff` | ← `Lightblue/100` |
| `light-shade/Lightblue/3` | `#99ddff` | ← `Lightblue/200` |
| `light-shade/Cyan/1` | `#e6fcff` | ← `Cyan/50` |
| `light-shade/Cyan/2` | `#ccf8fe` | ← `Cyan/100` |
| `light-shade/Cyan/3` | `#9ff2fd` | ← `Cyan/200` |
| `light-shade/Teal/1` | `#f5fffe` | ← `Teal/50` |
| `light-shade/Teal/2` | `#ebfffd` | ← `Teal/100` |
| `light-shade/Teal/3` | `#ccfffb` | ← `Teal/200` |
| `light-shade/Purple/1` | `#eee5ff` | ← `Purple/50` |
| `light-shade/Purple/2` | `#deccff` | ← `Purple/100` |
| `light-shade/Purple/3` | `#bd99ff` | ← `Purple/200` |
| `light-shade/Pink/1` | `#fee7ee` | ← `Pink/50` |
| `light-shade/Pink/2` | `#fecedf` | ← `Pink/100` |
| `light-shade/Pink/3` | `#fb9dbc` | ← `Pink/200` |

### Workplace Primitives

| Token | Value | Alias source |
|-------|-------|-------------|
| `Primary/50` | `#fbffe8` | — |
| `Primary/100` | `#f5ffcc` | — |
| `Primary/200` | `#eeff99` | — |
| `Primary/300` | `#e3ff77` | — |
| `Primary/400` | `#cfff55` | — |
| `Primary/500` | `#b8e64d` | — |
| `Primary/600` | `#9abf3d` | — |
| `Primary/700` | `#7a992f` | — |
| `Primary/800` | `#5c7322` | — |
| `Primary/900` | `#3d4d17` | — |
| `Primary/950` | `#1f260c` | — |
| `Secondary/50` | `#f0f2f7` | — |
| `Secondary/100` | `#dde1ec` | — |
| `Secondary/200` | `#bcc3d9` | — |
| `Secondary/300` | `#95a0bf` | — |
| `Secondary/400` | `#6e7da5` | — |
| `Secondary/500` | `#4d5d8a` | — |
| `Secondary/600` | `#3d4a6e` | — |
| `Secondary/700` | `#2f3953` | — |
| `Secondary/800` | `#232a3d` | — |
| `Secondary/900` | `#181c29` | — |
| `Secondary/950` | `#0c0e14` | — |
| `Accent/50` | `#fff3ee` | — |
| `Accent/100` | `#ffe2d4` | — |
| `Accent/200` | `#ffc4a8` | — |
| `Accent/300` | `#ffa070` | — |
| `Accent/400` | `#ff7a45` | — |
| `Accent/500` | `#e8632e` | — |
| `Accent/600` | `#c04f22` | — |
| `Accent/700` | `#983d1a` | — |
| `Accent/800` | `#702d13` | — |
| `Accent/900` | `#4a1e0d` | — |
| `Accent/950` | `#250f06` | — |
| `Neutral/50` | `#f8f9f5` | — |
| `Neutral/100` | `#f0f1ec` | — |
| `Neutral/200` | `#e0e2da` | — |
| `Neutral/300` | `#c8cbc0` | — |
| `Neutral/400` | `#a8aca0` | — |
| `Neutral/500` | `#888c80` | — |
| `Neutral/600` | `#6c7065` | — |
| `Neutral/700` | `#52554d` | — |
| `Neutral/800` | `#3a3c36` | — |
| `Neutral/900` | `#242521` | — |
| `Neutral/950` | `#121310` | — |
| `Success/50` | `#ecfdf5` | — |
| `Success/100` | `#d1fae5` | — |
| `Success/200` | `#a7f3d0` | — |
| `Success/300` | `#6ee7b7` | — |
| `Success/400` | `#34d399` | — |
| `Success/500` | `#10b981` | — |
| `Success/600` | `#059669` | — |
| `Success/700` | `#047857` | — |
| `Success/800` | `#065f46` | — |
| `Success/900` | `#064e3b` | — |
| `Success/950` | `#022c22` | — |
| `Warning/50` | `#fffbeb` | — |
| `Warning/100` | `#fef3c7` | — |
| `Warning/200` | `#fde68a` | — |
| `Warning/300` | `#fcd34d` | — |
| `Warning/400` | `#fbbf24` | — |
| `Warning/500` | `#f59e0b` | — |
| `Warning/600` | `#d97706` | — |
| `Warning/700` | `#b45309` | — |
| `Warning/800` | `#92400e` | — |
| `Warning/900` | `#78350f` | — |
| `Warning/950` | `#451a03` | — |
| `Error/50` | `#fef2f2` | — |
| `Error/100` | `#fee2e2` | — |
| `Error/200` | `#fecaca` | — |
| `Error/300` | `#fca5a5` | — |
| `Error/400` | `#f87171` | — |
| `Error/500` | `#ef4444` | — |
| `Error/600` | `#dc2626` | — |
| `Error/700` | `#b91c1c` | — |
| `Error/800` | `#991b1b` | — |
| `Error/900` | `#7f1d1d` | — |
| `Error/950` | `#450a0a` | — |
| `Info/50` | `#eff6ff` | — |
| `Info/100` | `#dbeafe` | — |
| `Info/200` | `#bfdbfe` | — |
| `Info/300` | `#93c5fd` | — |
| `Info/400` | `#60a5fa` | — |
| `Info/500` | `#3b82f6` | — |
| `Info/600` | `#2563eb` | — |
| `Info/700` | `#1d4ed8` | — |
| `Info/800` | `#1e40af` | — |
| `Info/900` | `#1e3a8a` | — |
| `Info/950` | `#172554` | — |

## Spacing Tokens

> Apply these values for all margins, padding, and gaps.

### Brand

| Token | Value |
|-------|-------|
| `Space/Sm- 1` | `4px` |
| `Space/Md-1` | `24px` |
| `Space/Md- 2` | `32px` |
| `Space/Md- 3` | `40px` |
| `Space/Md- 4` | `48px` |
| `Space/Md- 5` | `56px` |
| `Space/Md- 6` | `64px` |
| `Space/Md- 7` | `72px` |
| `Space/Md- 8` | `80px` |
| `Space/Lg- 1` | `88px` |
| `Space/Lg- 2` | `96px` |
| `Space/Lg- 3` | `104px` |
| `Space/Lg- 4` | `112px` |
| `Space/Lg- 5` | `120px` |
| `Space/Lg- 6` | `128px` |
| `Space/Lg- 7` | `136px` |
| `Space/Lg- 8` | `144px` |
| `Space/Lg- 9` | `152px` |
| `Space/Lg- 10` | `160px` |
| `Space/Xl- 1` | `168px` |
| `Space/Xl- 2` | `176px` |
| `Space/Xl- 3` | `184px` |
| `Space/Xl- 4` | `192px` |
| `Space/Xl- 5` | `200px` |
| `Space/Xl- 6` | `208px` |
| `Space/Xl- 7` | `216px` |
| `Space/Xl- 8` | `224px` |
| `Space/Xl- 9` | `232px` |
| `Space/Xl- 10` | `240px` |
| `Space/Sm- 2` | `8px` |
| `Space/Sm- 3` | `12px` |
| `Space/Sm- 4` | `16px` |
| `Space/Sm- 5` | `20px` |
| `Numbers/2's/none` | `0px` |
| `Numbers/2's/xs` | `2px` |
| `Numbers/2's/sm` | `4px` |
| `Numbers/2's/md` | `8px` |
| `Numbers/2's/lg` | `16px` |
| `Numbers/2's/round` | `160px` |
| `Drop shadow/blur/none` | `0px` |
| `Drop shadow/blur/xs` | `4px` |
| `Drop shadow/blur/sm` | `16px` |
| `Drop shadow/blur/md` | `24px` |
| `Drop shadow/blur/lg` | `48px` |
| `Drop shadow/blur/xl` | `64px` |
| `Drop shadow/positioning/none` | `0px` |
| `Drop shadow/positioning/xxxs` | `2px` |
| `Drop shadow/positioning/xxs` | `4px` |
| `Drop shadow/positioning/xs` | `8px` |
| `Drop shadow/positioning/sm` | `12px` |
| `Drop shadow/positioning/md` | `16px` |
| `Drop shadow/positioning/lg` | `20px` |
| `Drop shadow/positioning/xl` | `24px` |
| `Drop shadow/positioning/xxl` | `32px` |
| `Drop shadow/positioning/xxxl` | `48px` |
| `Drop shadow/spread/none` | `0px` |
| `Drop shadow/spread/xs` | `-4px` |
| `Drop shadow/spread/sm` | `-8px` |
| `Drop shadow/spread/md` | `-12px` |
| `Drop shadow/spread/lg` | `-16px` |
| `Drop shadow/spread/xl` | `-20px` |
| `Drop shadow/spread/xxl` | `-24px` |
| `Drop shadow/Number` | `0px` |
| `Space/Sm- 0` | `2px` |

### Sizing tokens

| Token | Value |
|-------|-------|
| `Sm- 1` | `4px` |
| `Sm- 2` | `8px` |
| `Sm- 3` | `12px` |
| `Sm- 4` | `16px` |
| `Sm- 5` | `20px` |
| `Md- 1` | `24px` |
| `Md- 2` | `32px` |
| `Md- 3` | `40px` |
| `Md- 4` | `48px` |
| `Md- 5` | `56px` |
| `Md- 6` | `64px` |
| `Md- 7` | `72px` |
| `Md- 8` | `80px` |
| `Lg- 1` | `88px` |
| `Lg- 2` | `96px` |
| `Lg- 3` | `104px` |
| `Lg- 4` | `112px` |
| `Lg- 5` | `120px` |
| `Lg- 6` | `128px` |
| `Lg- 7` | `136px` |
| `Lg- 8` | `144px` |
| `Lg- 9` | `152px` |
| `Lg- 10` | `160px` |
| `Xl- 1` | `168px` |
| `Xl- 2` | `176px` |
| `Xl- 3` | `184px` |
| `Xl- 4` | `192px` |
| `Xl- 5` | `200px` |
| `Xl- 6` | `208px` |
| `Xl- 7` | `216px` |
| `Xl- 8` | `224px` |
| `Xl- 9` | `232px` |
| `Xl- 10` | `240px` |
| `Sm-0` | `2px` |

### Typhography

| Token | Value |
|-------|-------|
| `Br/Breakpoints` | `1400px` |
| `Br/Columns` | `12px` |
| `Br/Margin` | `40px` |
| `Br/Gutter` | `24px` |

### Typhography/Tablet

| Token | Value |
|-------|-------|
| `Br/Breakpoints` | `992px` |
| `Br/Margin` | `72px` |
| `Br/Gutter` | `16px` |

### Typhography/Mobile

| Token | Value |
|-------|-------|
| `Br/Breakpoints` | `576px` |
| `Br/Columns` | `4px` |
| `Br/Margin` | `56px` |

### Typhography/Large

| Token | Value |
|-------|-------|
| `Br/Breakpoints` | `1720px` |

## Border Radius Tokens

| Token | Value |
|-------|-------|
| `Radius/none` | `0px` |
| `Radius/xs` | `2px` |
| `Radius/sm` | `4px` |
| `Radius/md` | `8px` |
| `Radius/lg` | `16px` |
| `Radius/round` | `160px` |

## Border Width Tokens

| Token | Value |
|-------|-------|
| `borderWidth/none` | `0px` |
| `borderWidth/sm` | `1px` |
| `borderWidth/md` | `2px` |
| `borderWidth/lg` | `4px` |

## Opacity Tokens

| Token | Value |
|-------|-------|
| `Opacity/none` | `0` |
| `Opacity/sm` | `25` |
| `Opacity/md` | `50` |
| `Opacity/lg` | `75` |
| `Opacity/xl` | `100` |

## Font Weight Tokens

| Token | Value |
|-------|-------|
| `font-weight/bold` | `700` |
| `font-weight/semibold` | `600` |
| `font-weight/medium` | `500` |
| `font-weight/regular` | `400` |
| `font-weight/bold` | `700` |
| `font-weight/semibold` | `600` |
| `font-weight/medium` | `500` |
| `font-weight/regular` | `400` |
| `font-weight/bold` | `700` |
| `font-weight/semibold` | `600` |
| `font-weight/medium` | `500` |
| `font-weight/regular` | `400` |
| `font-weight/bold` | `700` |
| `font-weight/semibold` | `600` |
| `font-weight/medium` | `500` |
| `font-weight/regular` | `400` |
| `font-weight/bold` | `700` |
| `font-weight/semibold` | `600` |
| `font-weight/medium` | `500` |
| `font-weight/regular` | `400` |

## String Tokens

### Typhography

- `font-family/Zoho Puvi`: `Zoho Puvi`

### Typhography/Desktop

- `font-family/Zoho Puvi`: `Zoho Puvi`

### Typhography/Tablet

- `font-family/Zoho Puvi`: `Zoho Puvi`

### Typhography/Mobile

- `font-family/Zoho Puvi`: `Zoho Puvi`

### Typhography/Large

- `font-family/Zoho Puvi`: `Zoho Puvi`

## Paint Styles

| Style | Value |
|-------|-------|
| `Blue/950` | `#000719` |
| `Blue/900` | `#000e33` |
| `Blue/800` | `#001d66` |
| `Blue/700` | `#012b99` |
| `Blue/600` | `#003acc` |
| `Blue/500` | `#0047ff` |
| `Blue/400` | `#336dff` |
| `Blue/300` | `#6691ff` |
| `Blue/200` | `#9ab6ff` |
| `Blue/100` | `#ccdaff` |
| `Blue/50` | `#e4edff` |
| `Teal/950` | `#015d54` |
| `Teal/900` | `#008075` |
| `Teal/800` | `#05a79a` |
| `Teal/700` | `#00ccbb` |
| `Teal/600` | `#01e6d2` |
| `Teal/500` | `#0fffeb` |
| `Teal/400` | `#75fff4` |
| `Teal/300` | `#adfff9` |
| `Teal/200` | `#ccfffb` |
| `Teal/100` | `#ebfffd` |
| `Teal/100-stroke` | `#fff4cc` |
| `Teal/50` | `#f5fffe` |
| `Grey/950` | `#1a1a1a` |
| `Grey/900` | `#262626` |
| `Grey/800` | `#383838` |
| `Grey/700` | `#454545` |
| `Grey/600` | `#4f4f4f` |
| `Grey/500` | `#595959` |
| `Grey/400` | `#919191` |
| `Grey/300` | `#b5b5b5` |
| `Grey/200` | `#d1d1d1` |
| `Grey/100` | `#ebebeb` |
| `Grey/50` | `#f5f5f5` |
| `Cyan/950` | `#011619` |
| `Cyan/900` | `#012c32` |
| `Cyan/800` | `#035e69` |
| `Cyan/700` | `#03899c` |
| `Cyan/600` | `#07bad2` |
| `Cyan/500` | `#10dffa` |
| `Cyan/400` | `#40e5fb` |
| `Cyan/300` | `#6eebfc` |
| `Cyan/200` | `#9ff2fd` |
| `Cyan/100` | `#ccf8fe` |
| `Cyan/100-stroke` | `#fff4cc` |
| `Cyan/50` | `#e6fcff` |
| `DeepOrange/950` | `#190900` |
| `DeepOrange/900` | `#331300` |
| `DeepOrange/800` | `#662500` |
| `DeepOrange/700` | `#9e3a01` |
| `DeepOrange/600` | `#d14d00` |
| `DeepOrange/500` | `#ff6105` |
| `DeepOrange/400` | `#ff8138` |
| `DeepOrange/300` | `#ffa16b` |
| `DeepOrange/200` | `#ffbe9a` |
| `DeepOrange/100` | `#ffdfcb` |
| `DeepOrange/50` | `#ffeee5` |
| `Lime/950` | `#171900` |
| `Lime/900` | `#2e3300` |
| `Lime/800` | `#606b01` |
| `Lime/700` | `#8e9f00` |
| `Lime/600` | `#c1d601` |
| `Lime/500` | `#e6ff0a` |
| `Lime/400` | `#ebff3e` |
| `Lime/300` | `#f0ff6a` |
| `Lime/200` | `#f5ff9d` |
| `Lime/100` | `#faffcc` |
| `Lime/100-stroke` | `#fff4cc` |
| `Lime/50` | `#fdffe4` |
| `Pink/950` | `#180109` |
| `Pink/900` | `#310212` |
| `Pink/800` | `#620423` |
| `Pink/700` | `#970736` |
| `Pink/600` | `#c80b49` |
| `Pink/500` | `#f4115d` |
| `Pink/400` | `#f6417d` |
| `Pink/300` | `#f8729f` |
| `Pink/200` | `#fb9dbc` |
| `Pink/100` | `#fecedf` |
| `Pink/100-stroke` | `#fff4cc` |
| `Pink/50` | `#fee7ee` |
| `Purple/950` | `#090019` |
| `Purple/900` | `#130033` |
| `Purple/800` | `#240066` |
| `Purple/700` | `#37009f` |
| `Purple/600` | `#4900d1` |
| `Purple/500` | `#5e05ff` |
| `Purple/400` | `#7e38ff` |
| `Purple/300` | `#9f6bff` |
| `Purple/200` | `#bd99ff` |
| `Purple/100` | `#deccff` |
| `Purple/100-stroke` | `#fff4cc` |
| `Purple/50` | `#eee5ff` |
| `Lightblue/950` | `#001119` |
| `Lightblue/900` | `#002232` |
| `Lightblue/800` | `#004466` |
| `Lightblue/700` | `#01699e` |
| `Lightblue/600` | `#008bd1` |
| `Lightblue/500` | `#09abff` |
| `Lightblue/400` | `#38bdff` |
| `Lightblue/300` | `#6bceff` |
| `Lightblue/200` | `#99ddff` |
| `Lightblue/100` | `#cdeeff` |
| `Lightblue/100-stroke` | `#fff4cc` |
| `Lightblue/50` | `#e5f7ff` |
| `Green/950` | `#011902` |
| `Green/900` | `#003203` |
| `Green/800` | `#00660a` |
| `Green/700` | `#019e0d` |
| `Green/600` | `#04d111` |
| `Green/500` | `#03ff17` |
| `Green/400` | `#37ff49` |
| `Green/300` | `#6cff77` |
| `Green/200` | `#99ffa2` |
| `Green/100` | `#ccffd0` |
| `Green/100-stroke` | `#fff4cc` |
| `Green/50` | `#e5ffe8` |
| `Yellow/950` | `#564800` |
| `Yellow/900` | `#7a6600` |
| `Yellow/800` | `#ad9001` |
| `Yellow/700` | `#cba901` |
| `Yellow/600` | `#eac301` |
| `Yellow/500` | `#fed70b` |
| `Yellow/400` | `#fee253` |
| `Yellow/300` | `#feea85` |
| `Yellow/200` | `#fff3b3` |
| `Yellow/100` | `#fff9db` |
| `Yellow/100-stroke` | `#fff4cc` |
| `Yellow/50` | `#fffceb` |
| ` Orange/950` | `#180f00` |
| ` Orange/900` | `#331f00` |
| ` Orange/800` | `#6b4000` |
| ` Orange/700` | `#9e5f01` |
| ` Orange/600` | `#d68100` |
| `Orange/500` | `#ff9e08` |
| ` Orange/400` | `#ffb13d` |
| ` Orange/300` | `#ffc46b` |
| ` Orange/200` | `#ffd99e` |
| ` Orange/100` | `#ffebcb` |
| ` Orange/50` | `#fff5e5` |
| `Red/950` | `#190001` |
| `Red/900` | `#330000` |
| `Red/800` | `#660000` |
| `Red/700` | `#9f0101` |
| `Red/600` | `#d10000` |
| `Red/500` | `#ff0405` |
| `Red/400` | `#ff3938` |
| `Red/300` | `#ff6b6b` |
| `Red/200` | `#ff999a` |
| `Red/100` | `#ffcccc` |
| `Red/50` | `#ffe5e4` |

## Typography

> Match font family, weight, size, and line-height exactly. Do not substitute fonts.

| Style | Family | Weight | Size | Line height | Letter spacing |
|-------|--------|--------|------|-------------|----------------|
| `Heading/H1/H1 Bold` | Zoho Puvi | 700 | 88px | 96px | -3% |
| `Heading/H1/H1 Semibold` | Zoho Puvi | 400 | 88px | 96px | -3% |
| `Heading/H1/H1 Medium` | Zoho Puvi | 500 | 88px | 96px | -4% |
| `Heading/H1/H1 Regular` | Zoho Puvi | 400 | 88px | 96px | -4% |
| `Heading/H2/H2 Bold` | Zoho Puvi | 700 | 80px | 88px | -3% |
| `Heading/H2/H2 Semibold` | Zoho Puvi | 400 | 80px | 88px | -3% |
| `Heading/H2/H2 Medium` | Zoho Puvi | 500 | 80px | 88px | -3% |
| `Heading/H2/H2 Regular` | Zoho Puvi | 400 | 80px | 88px | -4% |
| `Heading/H3/H3 Bold` | Zoho Puvi | 700 | 72px | 80px | -3% |
| `Heading/H3/H3 Semibold` | Zoho Puvi | 400 | 72px | 80px | -3% |
| `Heading/H3/H3 Medium` | Zoho Puvi | 500 | 72px | 80px | -4% |
| `Heading/H3/H3 Regular` | Zoho Puvi | 400 | 72px | 80px | -4% |
| `Heading/H4/H4 Bold` | Zoho Puvi | 700 | 64px | 72px | -3% |
| `Heading/H4/H4 Semibold` | Zoho Puvi | 400 | 64px | 72px | -3% |
| `Heading/H4/H4 Medium` | Zoho Puvi | 500 | 64px | 72px | -4% |
| `Heading/H4/H4 Regular` | Zoho Puvi | 400 | 64px | 72px | -4% |
| `Heading/H5/H5 Bold` | Zoho Puvi | 700 | 56px | 64px | -3% |
| `Heading/H5/H5 Semibold` | Zoho Puvi | 400 | 56px | 64px | -3% |
| `Heading/H5/H5 Medium` | Zoho Puvi | 500 | 56px | 64px | -3% |
| `Heading/H5/H5 Regular` | Zoho Puvi | 400 | 56px | 64px | -4% |
| `Heading/H6/H6 Bold` | Zoho Puvi | 700 | 48px | 56px | -3% |
| `Heading/H6/H6 Semibold` | Zoho Puvi | 400 | 48px | 56px | -3% |
| `Heading/H6/H6 Medium` | Zoho Puvi | 500 | 48px | 56px | -3% |
| `Heading/H6/H6 Regular` | Zoho Puvi | 400 | 48px | 56px | -4% |
| `Paragraph/large/Large text Bold` | Zoho Puvi | 700 | 40px | 48px | -2% |
| `Paragraph/large/Large text Semibold` | Zoho Puvi | 400 | 40px | 48px | -3% |
| `Paragraph/large/Large text Medium` | Zoho Puvi | 500 | 40px | 48px | -3% |
| `Paragraph/large/Large text Regular` | Zoho Puvi | 400 | 40px | 48px | -4% |
| `Paragraph/Medium/Medium text Bold` | Zoho Puvi | 700 | 32px | 40px | -2% |
| `Paragraph/Medium/Medium text Semibold` | Zoho Puvi | 400 | 32px | 40px | -3% |
| `Paragraph/Medium/Medium text Medium` | Zoho Puvi | 500 | 32px | 40px | -3% |
| `Paragraph/Medium/Medium text Regular` | Zoho Puvi | 400 | 32px | 40px | -3% |
| `Paragraph/Regular/Regular text Bold` | Zoho Puvi | 700 | 24px | 32px | -1% |
| `Paragraph/Regular/Regular text Semibold` | Zoho Puvi | 400 | 24px | 32px | -1% |
| `Paragraph/Regular/Regular text Medium` | Zoho Puvi | 500 | 24px | 32px | -1% |
| `Paragraph/Regular/Regular text Regular` | Zoho Puvi | 400 | 24px | 32px | -2% |
| `Paragraph/Small/Small text Regular` | Zoho Puvi | 400 | 20px | 28px | 0 |
| `Paragraph/Small/Small text Medium` | Zoho Puvi | 500 | 20px | 28px | -1% |
| `Paragraph/Small/Small text Semibold` | Zoho Puvi | 400 | 20px | 28px | -1% |
| `Paragraph/Small/Small text Bold` | Zoho Puvi | 700 | 20px | 28px | -1% |
| `Paragraph/X-Small/X-Small text Bold` | Zoho Puvi | 700 | 16px | 24px | -1% |
| `Paragraph/X-Small/X-Small text Semibold` | Zoho Puvi | 400 | 16px | 24px | -1% |
| `Paragraph/X-Small/X-Small text Medium` | Zoho Puvi | 500 | 16px | 24px | -1% |
| `Paragraph/X-Small/X-Small text Regular` | Zoho Puvi | 400 | 16px | 24px | -2% |
| `Paragraph/Tiny/caption text Bold` | Zoho Puvi | 700 | 12px | — | 0 |
| `Paragraph/Tiny/caption text Semibold` | Zoho Puvi | 400 | 12px | — | 0 |
| `Paragraph/Tiny/caption text Medium` | Zoho Puvi | 500 | 12px | — | -1% |
| `Paragraph/Tiny/caption text Regular` | Zoho Puvi | 400 | 12px | — | -1% |

**Font families used:** Zoho Puvi

## Shadows & Effects

> Apply these exact values. Do not invent new shadows.

### Elevation/xs

- `box-shadow: 0px 2px 4px 0px #00000040;`

### Elevation/small

- `box-shadow: 0px 16px 24px -4px #00000040;`

### Elevation/medium

- `box-shadow: 0px 24px 48px -8px #00000040;`

### Elevation/large

- `box-shadow: 0px 40px 80px -16px #00000029;`

### Elevation/x-large

- `box-shadow: 12px 56px 112px -20px #0000002e;`

## Components

> Replicate structures exactly. Honour variant property names for interactive states.

### Variant Sets

#### Button CTA
- **Total variants**: 60
- **Frame size**: 1397 × 2036px
- **Variant properties**:
  - `Button type: button-Primary-md | button-secondary-xs | button-secondary-sm | button-secondary-md | button-secondary-lg | button-primary-xs | button-primary-sm | button-primary-md | button-primary-lg | button-primary-line-xs | button-primary-line-sm | button-primary-line-md | button-primary-line-lg | button-secondary-line-xs | button-secondary-line-sm | button-secondary-line-md | button-secondary-line-lg | button-tertiary-xs | button-tertiary-sm | button-tertiary-md | button-tertiary-lg`
  - `State: Default | Hover | Active`
- **Sample variant names**: `Button type=button-primary-sm, State=Default` · `Button type=button-primary-xs, State=Default` · `Button type=button-Primary-md, State=Default` · `Button type=button-primary-lg, State=Default` · `Button type=button-primary-line-sm, State=Default` · `Button type=button-primary-line-xs, State=Default` · `Button type=button-primary-line-md, State=Default` · `Button type=button-primary-line-lg, State=Default`

#### Action - Tick
- **Total variants**: 9
- **Frame size**: 64 × 416px
- **Variant properties**:
  - `Property 1: Blue - Primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary | Green - Primary | Green - Secondary | Green - Tertiary`
- **Sample variant names**: `Property 1=Blue - Primary` · `Property 1=Blue - Secondary` · `Property 1=Blue - Tertiary` · `Property 1=Black - Primary` · `Property 1=Black - Secondary` · `Property 1=Black - Tertiary` · `Property 1=Green - Primary` · `Property 1=Green - Secondary`

#### Action - Cross
- **Total variants**: 9
- **Frame size**: 64 × 416px
- **Variant properties**:
  - `Property 1: Blue - Primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary | Error - Primary | Error - Secondary | Error - Tertiary`
- **Sample variant names**: `Property 1=Blue - Primary` · `Property 1=Blue - Secondary` · `Property 1=Blue - Tertiary` · `Property 1=Black - Primary` · `Property 1=Black - Secondary` · `Property 1=Black - Tertiary` · `Property 1=Error - Primary` · `Property 1=Error - Secondary`

#### Frame 3467797
- **Total variants**: 9
- **Frame size**: 64 × 416px
- **Variant properties**:
  - `Checkbox: Blue - Primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary | Green - Primary | Green - Secondary | Green - Tertiary`
- **Sample variant names**: `Checkbox=Blue - Primary` · `Checkbox=Blue - Secondary` · `Checkbox=Blue - Tertiary` · `Checkbox=Black - Primary` · `Checkbox=Black - Secondary` · `Checkbox=Black - Tertiary` · `Checkbox=Green - Primary` · `Checkbox=Green - Secondary`

#### Radio Button
- **Total variants**: 8
- **Frame size**: 64 × 372px
- **Variant properties**:
  - `Radio Button: Blue - Inactive | Blue - Active | Black - Inactive | Black - Active | Disabled - Inactive | Disabled - Active | Green - Success State | Red - Error State`
- **Sample variant names**: `Radio Button=Blue - Inactive` · `Radio Button=Blue - Active` · `Radio Button=Black - Inactive` · `Radio Button=Black - Active` · `Radio Button=Disabled - Inactive` · `Radio Button=Disabled - Active` · `Radio Button=Green - Success State` · `Radio Button=Red - Error State`

#### Actions - Play
- **Total variants**: 6
- **Frame size**: 64 × 284px
- **Variant properties**:
  - `Property 1: Blue - primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary`
- **Sample variant names**: `Property 1=Blue - primary` · `Property 1=Blue - Secondary` · `Property 1=Blue - Tertiary` · `Property 1=Black - Primary` · `Property 1=Black - Secondary` · `Property 1=Black - Tertiary`

#### Actions - Pause
- **Total variants**: 6
- **Frame size**: 64 × 284px
- **Variant properties**:
  - `Property 1: Blue - Primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary`
- **Sample variant names**: `Property 1=Blue - Primary` · `Property 1=Blue - Secondary` · `Property 1=Blue - Tertiary` · `Property 1=Black - Primary` · `Property 1=Black - Secondary` · `Property 1=Black - Tertiary`

#### Action - Reload
- **Total variants**: 6
- **Frame size**: 64 × 284px
- **Variant properties**:
  - `Property 1: Blue - Primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary`
- **Sample variant names**: `Property 1=Blue - Primary` · `Property 1=Blue - Secondary` · `Property 1=Blue - Tertiary` · `Property 1=Black - Primary` · `Property 1=Black - Secondary` · `Property 1=Black - Tertiary`

#### Actions - Right Arrow
- **Total variants**: 6
- **Frame size**: 64 × 284px
- **Variant properties**:
  - `Property 1: Blue - Primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary`
- **Sample variant names**: `Property 1=Blue - Primary` · `Property 1=Blue - Secondary` · `Property 1=Blue - Tertiary` · `Property 1=Black - Primary` · `Property 1=Black - Secondary` · `Property 1=Black - Tertiary`

#### Action - Left Arrow
- **Total variants**: 6
- **Frame size**: 64 × 284px
- **Variant properties**:
  - `Property 1: Blue - Primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary`
- **Sample variant names**: `Property 1=Blue - Primary` · `Property 1=Blue - Secondary` · `Property 1=Blue - Tertiary` · `Property 1=Black - Primary` · `Property 1=Black - Secondary` · `Property 1=Black - Tertiary`

#### Download Icon
- **Total variants**: 6
- **Frame size**: 64 × 284px
- **Variant properties**:
  - `Download Icon: Blue - Primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary`
- **Sample variant names**: `Download Icon=Blue - Primary` · `Download Icon=Blue - Secondary` · `Download Icon=Blue - Tertiary` · `Download Icon=Black - Primary` · `Download Icon=Black - Secondary` · `Download Icon=Black - Tertiary`

#### Action - Information
- **Total variants**: 6
- **Frame size**: 64 × 284px
- **Variant properties**:
  - `Property 1: Blue - Primary | Blue - Secondary | Blue - Tertiary | Black - Primary | Black - Secondary | Black - Tertiary`
- **Sample variant names**: `Property 1=Blue - Primary` · `Property 1=Blue - Secondary` · `Property 1=Blue - Tertiary` · `Property 1=Black - Primary` · `Property 1=Black - Secondary` · `Property 1=Black - Tertiary`

#### Checkbox
- **Total variants**: 2
- **Frame size**: 60 × 168px
- **Variant properties**:
  - `State: False | True`
- **Sample variant names**: `State=False` · `State=True`

#### Checkbox contenc
- **Total variants**: 5
- **Frame size**: 159 × 548px
- **Variant properties**:
  - `State: Default | Hover | Active | Disable | State5`
- **Sample variant names**: `State=Default` · `State=Disable` · `State=State5` · `State=Hover` · `State=Active`

#### Checkbox contenc
- **Total variants**: 3
- **Frame size**: 56 × 140px
- **Variant properties**:
  - `State: Default | Hover | Active`
- **Sample variant names**: `State=Default` · `State=Hover` · `State=Active`

#### Checkbox
- **Total variants**: 2
- **Frame size**: 60 × 168px
- **Variant properties**:
  - `State: False | True`
- **Sample variant names**: `State=False` · `State=True`

#### Radio
- **Total variants**: 5
- **Frame size**: 159 × 548px
- **Variant properties**:
  - `State: Default | Hover | Active | Error | Disable`
- **Sample variant names**: `State=Default` · `State=Disable` · `State=Hover` · `State=Error` · `State=Active`

#### Radio content
- **Total variants**: 3
- **Frame size**: 56 × 140px
- **Variant properties**:
  - `State: Default | Hover | Active`
- **Sample variant names**: `State=Default` · `State=Hover` · `State=Active`

#### Tab-v1
- **Total variants**: 5
- **Frame size**: 509 × 617px
- **Variant properties**:
  - `Property 1: Default | Tab-v2 | Tab-v4 | Tab-v3 | Tab-v5`
- **Sample variant names**: `Property 1=Default` · `Property 1=Tab-v5` · `Property 1=Tab-v2` · `Property 1=Tab-v4` · `Property 1=Tab-v3`

## Design Rules — Mandatory for AI Agents

| Category | Rule |
|----------|------|
| Colours | Use only tokens defined above. Always output as `var(--token)`. Never hard-code. |
| Typography | Match family, weight, size, line-height exactly from the table above. |
| Spacing | Use only spacing token values. No arbitrary numbers. |
| Radius | Use only border-radius tokens. No arbitrary values. |
| Shadows | Use only defined elevation/effect styles. |
| Components | Replicate structures. Honour variant property names. |
| HTML | Output semantic HTML5 with ARIA roles. All components responsive by default. |
| Unknowns | If a decision is not defined here: ask the user, do not invent. |

## CSS Custom Properties

```css
:root {
  /* ── Colour tokens ──────────────────── */
  --blue-950: #000719;
  --blue-900: #000e33;
  --blue-800: #001d66;
  --blue-700: #012b99;
  --blue-600: #003acc;
  --blue-500: #0047ff;
  --blue-400: #336dff;
  --blue-300: #6691ff;
  --blue-200: #9ab6ff;
  --blue-100: #ccdaff;
  --blue-50: #e4edff;
  --teal-950: #015d54;
  --teal-900: #008075;
  --teal-800: #05a79a;
  --teal-700: #00ccbb;
  --teal-600: #01e6d2;
  --teal-500: #0fffeb;
  --teal-400: #75fff4;
  --teal-300: #adfff9;
  --teal-200: #ccfffb;
  --teal-100: #ebfffd;
  --teal-50: #f5fffe;
  --grey-950: #1a1a1a;
  --grey-900: #262626;
  --grey-800: #383838;
  --grey-700: #454545;
  --grey-600: #4f4f4f;
  --grey-500: #595959;
  --grey-400: #919191;
  --grey-300: #b5b5b5;
  --grey-200: #d1d1d1;
  --grey-100: #ebebeb;
  --grey-50: #f5f5f5;
  --cyan-950: #011619;
  --cyan-900: #012c32;
  --cyan-800: #035e69;
  --cyan-700: #03899c;
  --cyan-600: #07bad2;
  --cyan-500: #10dffa;
  --cyan-400: #40e5fb;
  --cyan-300: #6eebfc;
  --cyan-200: #9ff2fd;
  --cyan-100: #ccf8fe;
  --cyan-50: #e6fcff;
  --deeporange-950: #190900;
  --deeporange-900: #331300;
  --deeporange-800: #662500;
  --deeporange-700: #9e3a01;
  --deeporange-600: #d14d00;
  --deeporange-500: #ff6105;
  --deeporange-400: #ff8138;
  --deeporange-300: #ffa16b;
  --deeporange-200: #ffbe9a;
  --deeporange-100: #ffdfcb;
  --deeporange-50: #ffeee5;
  --lime-950: #171900;
  --lime-900: #2e3300;
  --lime-800: #606b01;
  --lime-700: #8e9f00;
  --lime-600: #c1d601;
  --lime-500: #e6ff0a;
  --lime-400: #ebff3e;
  --lime-300: #f0ff6a;
  --lime-200: #f5ff9d;
  --lime-100: #faffcc;
  --lime-50: #fdffe4;
  --pink-950: #180109;
  --pink-900: #310212;
  --pink-800: #620423;
  --pink-700: #970736;
  --pink-600: #c80b49;
  --pink-500: #f4115d;
  --pink-400: #f6417d;
  --pink-300: #f8729f;
  --pink-200: #fb9dbc;
  --pink-100: #fecedf;
  --pink-50: #fee7ee;
  --purple-950: #090019;
  --purple-900: #130033;
  --purple-800: #240066;
  --purple-700: #37009f;
  --purple-600: #4900d1;
  --purple-500: #5e05ff;
  --purple-400: #7e38ff;
  --purple-300: #9f6bff;
  --purple-200: #bd99ff;
  --purple-100: #deccff;
  --purple-50: #eee5ff;
  --lightblue-950: #001119;
  --lightblue-900: #002232;
  --lightblue-800: #004466;
  --lightblue-700: #01699e;
  --lightblue-600: #008bd1;
  --lightblue-500: #09abff;
  --lightblue-400: #38bdff;
  --lightblue-300: #6bceff;
  --lightblue-200: #99ddff;
  --lightblue-100: #cdeeff;
  --lightblue-50: #e5f7ff;
  --green-950: #011902;
  --green-900: #003203;
  --green-800: #00660a;
  --green-700: #019e0d;
  --green-600: #04d111;
  --green-500: #03ff17;
  --green-400: #37ff49;
  --green-300: #6cff77;
  --green-200: #99ffa2;
  --green-100: #ccffd0;
  --green-50: #e5ffe8;
  --yellow-950: #564800;
  --yellow-900: #7a6600;
  --yellow-800: #ad9001;
  --yellow-700: #cba901;
  --yellow-600: #eac301;
  --yellow-500: #fed70b;
  --yellow-400: #fee253;
  --yellow-300: #feea85;
  --yellow-200: #fff3b3;
  --yellow-100: #fff9db;
  --yellow-50: #fffceb;
  --orange-950: #180f00;
  --orange-900: #331f00;
  --orange-800: #6b4000;
  --orange-700: #9e5f01;
  --orange-600: #d68100;
  --orange-500: #ff9e08;
  --orange-400: #ffb13d;
  --orange-300: #ffc46b;
  --orange-200: #ffd99e;
  --orange-100: #ffebcb;
  --orange-50: #fff5e5;
  --red-950: #190001;
  --red-900: #330000;
  --red-800: #660000;
  --red-700: #9f0101;
  --red-600: #d10000;
  --red-500: #ff0405;
  --red-400: #ff3938;
  --red-300: #ff6b6b;
  --red-200: #ff999a;
  --red-100: #ffcccc;
  --red-50: #ffe5e4;
  --blue-color: #ffffff;
  --white--black-white: #ffffff;
  --white--black-black: #000000;
  --dark-grey-950: #030303;
  --dark-grey-900: #050505;
  --dark-grey-800: #080808;
  --dark-grey-700: #0a0a0a;
  --dark-grey-600: #0d0d0d;
  --dark-grey-500: #0f0f0f;
  --dark-grey-400: #121212;
  --dark-grey-300: #141414;
  --dark-grey-200: #171717;
  --dark-grey-100: #1a1a1a;
  --dark-grey-50: #1a1a1a;
  --semantic-success-subtle: #ccffd0;
  --semantic-success-bold: #03ff17;
  --semantic-error-subtle: #ffe5e4;
  --semantic-error-bold: #ff0405;
  --semantic-warning-subtle: #ffdfcb;
  --semantic-warning-bold: #ff6105;
  --semantic-button-primary-bg-subtle: #ffdfcb;
  --semantic-button-primary-bg-bold: #ff6105;
  --blue-950: #000719;
  --blue-900: #000e33;
  --blue-800: #001d66;
  --blue-700: #012b99;
  --blue-600: #003acc;
  --blue-500: #0047ff;
  --blue-400: #336dff;
  --blue-300: #6691ff;
  --blue-200: #9ab6ff;
  --blue-100: #ccdaff;
  --blue-50: #e4edff;
  --teal-950: #015d54;
  --teal-900: #008075;
  --teal-800: #05a79a;
  --teal-700: #00ccbb;
  --teal-600: #01e6d2;
  --teal-500: #0fffeb;
  --teal-400: #75fff4;
  --teal-300: #adfff9;
  --teal-200: #ccfffb;
  --teal-100: #ebfffd;
  --teal-50: #f5fffe;
  --gray-950: #1a1a1a;
  --gray-900: #262626;
  --gray-800: #383838;
  --gray-700: #454545;
  --gray-600: #4f4f4f;
  --gray-500: #595959;
  --gray-400: #919191;
  --gray-300: #b5b5b5;
  --gray-200: #d1d1d1;
  --gray-100: #ebebeb;
  --gray-50: #f5f5f5;
  --cyan-950: #011619;
  --cyan-900: #012c32;
  --cyan-800: #035e69;
  --cyan-700: #03899c;
  --cyan-600: #07bad2;
  --cyan-500: #10dffa;
  --cyan-400: #40e5fb;
  --cyan-300: #6eebfc;
  --cyan-200: #9ff2fd;
  --cyan-100: #ccf8fe;
  --cyan-50: #e6fcff;
  --deeporange-950: #190900;
  --deeporange-900: #331300;
  --deeporange-800: #662500;
  --deeporange-700: #9e3a01;
  --deeporange-600: #d14d00;
  --deeporange-500: #ff6105;
  --deeporange-400: #ff8138;
  --deeporange-300: #ffa16b;
  --deeporange-200: #ffbe9a;
  --deeporange-100: #ffdfcb;
  --deeporange-50: #ffeee5;
  --lime-950: #171900;
  --lime-900: #2e3300;
  --lime-800: #606b01;
  --lime-700: #8e9f00;
  --lime-600: #c1d601;
  --lime-500: #e6ff0a;
  --lime-400: #ebff3e;
  --lime-300: #f0ff6a;
  --lime-200: #f5ff9d;
  --lime-100: #faffcc;
  --lime-50: #fdffe4;
  --pink-950: #180109;
  --pink-900: #310212;
  --pink-800: #620423;
  --pink-700: #970736;
  --pink-600: #c80b49;
  --pink-500: #f4115d;
  --pink-400: #f6417d;
  --pink-300: #f8729f;
  --pink-200: #fb9dbc;
  --pink-100: #fecedf;
  --pink-50: #fee7ee;
  --purple-950: #090019;
  --purple-900: #130033;
  --purple-800: #240066;
  --purple-700: #37009f;
  --purple-600: #4900d1;
  --purple-500: #5e05ff;
  --purple-400: #7e38ff;
  --purple-300: #9f6bff;
  --purple-200: #bd99ff;
  --purple-100: #deccff;
  --purple-50: #eee5ff;
  --lightblue-950: #001119;
  --lightblue-900: #002232;
  --lightblue-800: #004466;
  --lightblue-700: #01699e;
  --lightblue-600: #008bd1;
  --lightblue-500: #09abff;
  --lightblue-400: #38bdff;
  --lightblue-300: #6bceff;
  --lightblue-200: #99ddff;
  --lightblue-100: #cdeeff;
  --lightblue-50: #e5f7ff;
  --green-950: #011902;
  --green-900: #003203;
  --green-800: #00660a;
  --green-700: #019e0d;
  --green-600: #04d111;
  --green-500: #03ff17;
  --green-400: #37ff49;
  --green-300: #6cff77;
  --green-200: #99ffa2;
  --green-100: #ccffd0;
  --green-50: #e5ffe8;
  --yellow-950: #564800;
  --yellow-900: #7a6600;
  --yellow-800: #ad9001;
  --yellow-700: #cba901;
  --yellow-600: #eac301;
  --yellow-500: #fed70b;
  --yellow-400: #fee253;
  --yellow-300: #feea85;
  --yellow-200: #fff3b3;
  --yellow-100: #fff9db;
  --yellow-50: #fffceb;
  --orange-950: #180f00;
  --orange-900: #331f00;
  --orange-800: #6b4000;
  --orange-700: #9e5f01;
  --orange-600: #d68100;
  --orange-500: #ff9e08;
  --orange-400: #ffb13d;
  --orange-300: #ffc46b;
  --orange-200: #ffd99e;
  --orange-100: #ffebcb;
  --orange-50: #fff5e5;
  --red-950: #190001;
  --red-900: #330000;
  --red-800: #660000;
  --red-700: #9f0101;
  --red-600: #d10000;
  --red-500: #ff0405;
  --red-400: #ff3938;
  --red-300: #ff6b6b;
  --red-200: #ff999a;
  --red-100: #ffcccc;
  --red-50: #ffe5e4;
  --blue-color: #ffffff;
  --white--black-white: #ffffff;
  --white--black-black: #000000;
  --dark-gray-950: #030303;
  --dark-gray-900: #050505;
  --dark-gray-800: #080808;
  --dark-gray-700: #0a0a0a;
  --dark-gray-600: #0d0d0d;
  --dark-gray-500: #0f0f0f;
  --dark-gray-400: #121212;
  --dark-gray-300: #141414;
  --dark-gray-200: #171717;
  --dark-gray-100: #1a1a1a;
  --dark-gray-50: #1a1a1a;
  --bg-page: #ffffff;
  --bg-subtle: #f5f5f5;
  --bg-muted: #ebebeb;
  --bg-emphasized: #d1d1d1;
  --surface-default: #ffffff;
  --surface-raised: #f5f5f5;
  --surface-overlay: #ebebeb;
  --state-error-bg: #ffe5e4;
  --state-error-bg-hover: #ffcccc;
  --state-error-bg-active: #ff999a;
  --state-warning-bg: #fff5e5;
  --state-warning-bg-hover: #ffebcb;
  --state-warning-bg-active: #ffd99e;
  --state-success-bg: #e5ffe8;
  --state-success-bg-hover: #ccffd0;
  --state-success-bg-active: #99ffa2;
  --state-info-bg: #e4edff;
  --state-info-bg-hover: #ccdaff;
  --state-info-bg-active: #9ab6ff;
  --state-notice-bg: #fffceb;
  --state-notice-bg-hover: #fff9db;
  --state-notice-bg-active: #fff3b3;
  --state-critical-bg: #ffe5e4;
  --state-critical-bg-hover: #ffcccc;
  --state-pink-bg: #fee7ee;
  --state-pink-bg-hover: #fecedf;
  --state-purple-bg: #eee5ff;
  --state-purple-bg-hover: #deccff;
  --state-teal-bg: #f5fffe;
  --state-teal-bg-hover: #ebfffd;
  --state-cyan-bg: #e6fcff;
  --state-cyan-bg-hover: #ccf8fe;
  --state-lightblue-bg: #e5f7ff;
  --state-lightblue-bg-hover: #cdeeff;
  --state-lime-bg: #fdffe4;
  --state-lime-bg-hover: #faffcc;
  --state-deeporange-bg: #ffeee5;
  --state-deeporange-bg-hover: #ffdfcb;
  --light-shade-red-1: #ffe5e4;
  --light-shade-red-2: #ffcccc;
  --light-shade-red-3: #ff999a;
  --light-shade-orange-1: #fff5e5;
  --light-shade-orange-2: #ffebcb;
  --light-shade-orange-3: #ffd99e;
  --light-shade-deeporange-1: #ffeee5;
  --light-shade-deeporange-2: #ffdfcb;
  --light-shade-deeporange-3: #ffbe9a;
  --light-shade-yellow-1: #fffceb;
  --light-shade-yellow-2: #fff9db;
  --light-shade-yellow-3: #fff3b3;
  --light-shade-green-1: #e5ffe8;
  --light-shade-green-2: #ccffd0;
  --light-shade-green-3: #99ffa2;
  --light-shade-lime-1: #fdffe4;
  --light-shade-lime-2: #faffcc;
  --light-shade-lime-3: #f5ff9d;
  --light-shade-blue-1: #e4edff;
  --light-shade-blue-2: #ccdaff;
  --light-shade-blue-3: #9ab6ff;
  --light-shade-lightblue-1: #e5f7ff;
  --light-shade-lightblue-2: #cdeeff;
  --light-shade-lightblue-3: #99ddff;
  --light-shade-cyan-1: #e6fcff;
  --light-shade-cyan-2: #ccf8fe;
  --light-shade-cyan-3: #9ff2fd;
  --light-shade-teal-1: #f5fffe;
  --light-shade-teal-2: #ebfffd;
  --light-shade-teal-3: #ccfffb;
  --light-shade-purple-1: #eee5ff;
  --light-shade-purple-2: #deccff;
  --light-shade-purple-3: #bd99ff;
  --light-shade-pink-1: #fee7ee;
  --light-shade-pink-2: #fecedf;
  --light-shade-pink-3: #fb9dbc;
  --beige-50: #fdf8f0;
  --beige-100: #faf0e1;
  --beige-200: #f5e1c3;
  --beige-300: #efcfa0;
  --beige-400: #e8bc7d;
  --beige-500: #e0a85a;
  --beige-600: #c48e3e;
  --beige-700: #a0722e;
  --beige-800: #7a5721;
  --beige-900: #543c17;
  --beige-950: #2e200c;
  --warmgray-50: #faf8f6;
  --warmgray-100: #f0edea;
  --warmgray-200: #e0dbd5;
  --warmgray-300: #c8c0b8;
  --warmgray-400: #ada39a;
  --warmgray-500: #93877c;
  --warmgray-600: #796d62;
  --warmgray-700: #5f544b;
  --warmgray-800: #463d35;
  --warmgray-900: #2e2721;
  --warmgray-950: #1a1512;
  --coolgray-50: #f5f7fa;
  --coolgray-100: #ebeef3;
  --coolgray-200: #d5dbe5;
  --coolgray-300: #b8c1d1;
  --coolgray-400: #9aa7bd;
  --coolgray-500: #7c8da8;
  --coolgray-600: #627390;
  --coolgray-700: #4b5a74;
  --coolgray-800: #354158;
  --coolgray-900: #212b3d;
  --coolgray-950: #121822;
  --dark-50: #e8e8ee;
  --dark-100: #c4c4d4;
  --dark-200: #9696b0;
  --dark-300: #6a6a8c;
  --dark-400: #464668;
  --dark-500: #2a2a4a;
  --dark-600: #22223c;
  --dark-700: #1a1a2e;
  --dark-800: #121222;
  --dark-900: #0a0a18;
  --dark-950: #05050c;
  --primary-50: #fbffe8;
  --primary-100: #f5ffcc;
  --primary-200: #eeff99;
  --primary-300: #e3ff77;
  --primary-400: #cfff55;
  --primary-500: #b8e64d;
  --primary-600: #9abf3d;
  --primary-700: #7a992f;
  --primary-800: #5c7322;
  --primary-900: #3d4d17;
  --primary-950: #1f260c;
  --secondary-50: #f0f2f7;
  --secondary-100: #dde1ec;
  --secondary-200: #bcc3d9;
  --secondary-300: #95a0bf;
  --secondary-400: #6e7da5;
  --secondary-500: #4d5d8a;
  --secondary-600: #3d4a6e;
  --secondary-700: #2f3953;
  --secondary-800: #232a3d;
  --secondary-900: #181c29;
  --secondary-950: #0c0e14;
  --accent-50: #fff3ee;
  --accent-100: #ffe2d4;
  --accent-200: #ffc4a8;
  --accent-300: #ffa070;
  --accent-400: #ff7a45;
  --accent-500: #e8632e;
  --accent-600: #c04f22;
  --accent-700: #983d1a;
  --accent-800: #702d13;
  --accent-900: #4a1e0d;
  --accent-950: #250f06;
  --neutral-50: #f8f9f5;
  --neutral-100: #f0f1ec;
  --neutral-200: #e0e2da;
  --neutral-300: #c8cbc0;
  --neutral-400: #a8aca0;
  --neutral-500: #888c80;
  --neutral-600: #6c7065;
  --neutral-700: #52554d;
  --neutral-800: #3a3c36;
  --neutral-900: #242521;
  --neutral-950: #121310;
  --success-50: #ecfdf5;
  --success-100: #d1fae5;
  --success-200: #a7f3d0;
  --success-300: #6ee7b7;
  --success-400: #34d399;
  --success-500: #10b981;
  --success-600: #059669;
  --success-700: #047857;
  --success-800: #065f46;
  --success-900: #064e3b;
  --success-950: #022c22;
  --warning-50: #fffbeb;
  --warning-100: #fef3c7;
  --warning-200: #fde68a;
  --warning-300: #fcd34d;
  --warning-400: #fbbf24;
  --warning-500: #f59e0b;
  --warning-600: #d97706;
  --warning-700: #b45309;
  --warning-800: #92400e;
  --warning-900: #78350f;
  --warning-950: #451a03;
  --error-50: #fef2f2;
  --error-100: #fee2e2;
  --error-200: #fecaca;
  --error-300: #fca5a5;
  --error-400: #f87171;
  --error-500: #ef4444;
  --error-600: #dc2626;
  --error-700: #b91c1c;
  --error-800: #991b1b;
  --error-900: #7f1d1d;
  --error-950: #450a0a;
  --info-50: #eff6ff;
  --info-100: #dbeafe;
  --info-200: #bfdbfe;
  --info-300: #93c5fd;
  --info-400: #60a5fa;
  --info-500: #3b82f6;
  --info-600: #2563eb;
  --info-700: #1d4ed8;
  --info-800: #1e40af;
  --info-900: #1e3a8a;
  --info-950: #172554;

  /* ── Spacing ────────────────────────── */
  --space-sm--1: 4px;
  --space-md-1: 24px;
  --space-md--2: 32px;
  --space-md--3: 40px;
  --space-md--4: 48px;
  --space-md--5: 56px;
  --space-md--6: 64px;
  --space-md--7: 72px;
  --space-md--8: 80px;
  --space-lg--1: 88px;
  --space-lg--2: 96px;
  --space-lg--3: 104px;
  --space-lg--4: 112px;
  --space-lg--5: 120px;
  --space-lg--6: 128px;
  --space-lg--7: 136px;
  --space-lg--8: 144px;
  --space-lg--9: 152px;
  --space-lg--10: 160px;
  --space-xl--1: 168px;
  --space-xl--2: 176px;
  --space-xl--3: 184px;
  --space-xl--4: 192px;
  --space-xl--5: 200px;
  --space-xl--6: 208px;
  --space-xl--7: 216px;
  --space-xl--8: 224px;
  --space-xl--9: 232px;
  --space-xl--10: 240px;
  --space-sm--2: 8px;
  --space-sm--3: 12px;
  --space-sm--4: 16px;
  --space-sm--5: 20px;
  --numbers-2s-none: 0px;
  --numbers-2s-xs: 2px;
  --numbers-2s-sm: 4px;
  --numbers-2s-md: 8px;
  --numbers-2s-lg: 16px;
  --numbers-2s-round: 160px;
  --drop-shadow-blur-none: 0px;
  --drop-shadow-blur-xs: 4px;
  --drop-shadow-blur-sm: 16px;
  --drop-shadow-blur-md: 24px;
  --drop-shadow-blur-lg: 48px;
  --drop-shadow-blur-xl: 64px;
  --drop-shadow-positioning-none: 0px;
  --drop-shadow-positioning-xxxs: 2px;
  --drop-shadow-positioning-xxs: 4px;
  --drop-shadow-positioning-xs: 8px;
  --drop-shadow-positioning-sm: 12px;
  --drop-shadow-positioning-md: 16px;
  --drop-shadow-positioning-lg: 20px;
  --drop-shadow-positioning-xl: 24px;
  --drop-shadow-positioning-xxl: 32px;
  --drop-shadow-positioning-xxxl: 48px;
  --drop-shadow-spread-none: 0px;
  --drop-shadow-spread-xs: -4px;
  --drop-shadow-spread-sm: -8px;
  --drop-shadow-spread-md: -12px;
  --drop-shadow-spread-lg: -16px;
  --drop-shadow-spread-xl: -20px;
  --drop-shadow-spread-xxl: -24px;
  --drop-shadow-number: 0px;
  --sm--1: 4px;
  --sm--2: 8px;
  --sm--3: 12px;
  --sm--4: 16px;
  --sm--5: 20px;
  --md--1: 24px;
  --md--2: 32px;
  --md--3: 40px;
  --md--4: 48px;
  --md--5: 56px;
  --md--6: 64px;
  --md--7: 72px;
  --md--8: 80px;
  --lg--1: 88px;
  --lg--2: 96px;
  --lg--3: 104px;
  --lg--4: 112px;
  --lg--5: 120px;
  --lg--6: 128px;
  --lg--7: 136px;
  --lg--8: 144px;
  --lg--9: 152px;
  --lg--10: 160px;
  --xl--1: 168px;
  --xl--2: 176px;
  --xl--3: 184px;
  --xl--4: 192px;
  --xl--5: 200px;
  --xl--6: 208px;
  --xl--7: 216px;
  --xl--8: 224px;
  --xl--9: 232px;
  --xl--10: 240px;
  --br-breakpoints: 1400px;
  --br-columns: 12px;
  --br-margin: 40px;
  --br-gutter: 24px;
  --sm-0: 2px;
  --space-sm--0: 2px;

  /* ── Border radius ──────────────────── */
  --radius-none: 0px;
  --radius-xs: 2px;
  --radius-sm: 4px;
  --radius-md: 8px;
  --radius-lg: 16px;
  --radius-round: 160px;

  /* ── Border width ───────────────────── */
  --borderwidth-none: 0px;
  --borderwidth-sm: 1px;
  --borderwidth-md: 2px;
  --borderwidth-lg: 4px;

  /* ── Font weight ────────────────────── */
  --font-weight-bold: 700;
  --font-weight-semibold: 600;
  --font-weight-medium: 500;
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-semibold: 600;
  --font-weight-medium: 500;
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-semibold: 600;
  --font-weight-medium: 500;
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-semibold: 600;
  --font-weight-medium: 500;
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-semibold: 600;
  --font-weight-medium: 500;
  --font-weight-regular: 400;

  /* ── Typography ─────────────────────── */
  --font-heading-h1-h1-bold-family: "Zoho Puvi";
  --font-heading-h1-h1-bold-size: 88px;
  --font-heading-h1-h1-bold-weight: 700;
  --font-heading-h1-h1-bold-line-height: 96px;
  --font-heading-h1-h1-semibold-family: "Zoho Puvi";
  --font-heading-h1-h1-semibold-size: 88px;
  --font-heading-h1-h1-semibold-weight: 400;
  --font-heading-h1-h1-semibold-line-height: 96px;
  --font-heading-h1-h1-medium-family: "Zoho Puvi";
  --font-heading-h1-h1-medium-size: 88px;
  --font-heading-h1-h1-medium-weight: 500;
  --font-heading-h1-h1-medium-line-height: 96px;
  --font-heading-h1-h1-regular-family: "Zoho Puvi";
  --font-heading-h1-h1-regular-size: 88px;
  --font-heading-h1-h1-regular-weight: 400;
  --font-heading-h1-h1-regular-line-height: 96px;
  --font-heading-h2-h2-bold-family: "Zoho Puvi";
  --font-heading-h2-h2-bold-size: 80px;
  --font-heading-h2-h2-bold-weight: 700;
  --font-heading-h2-h2-bold-line-height: 88px;
  --font-heading-h2-h2-semibold-family: "Zoho Puvi";
  --font-heading-h2-h2-semibold-size: 80px;
  --font-heading-h2-h2-semibold-weight: 400;
  --font-heading-h2-h2-semibold-line-height: 88px;
  --font-heading-h2-h2-medium-family: "Zoho Puvi";
  --font-heading-h2-h2-medium-size: 80px;
  --font-heading-h2-h2-medium-weight: 500;
  --font-heading-h2-h2-medium-line-height: 88px;
  --font-heading-h2-h2-regular-family: "Zoho Puvi";
  --font-heading-h2-h2-regular-size: 80px;
  --font-heading-h2-h2-regular-weight: 400;
  --font-heading-h2-h2-regular-line-height: 88px;
  --font-heading-h3-h3-bold-family: "Zoho Puvi";
  --font-heading-h3-h3-bold-size: 72px;
  --font-heading-h3-h3-bold-weight: 700;
  --font-heading-h3-h3-bold-line-height: 80px;
  --font-heading-h3-h3-semibold-family: "Zoho Puvi";
  --font-heading-h3-h3-semibold-size: 72px;
  --font-heading-h3-h3-semibold-weight: 400;
  --font-heading-h3-h3-semibold-line-height: 80px;
  --font-heading-h3-h3-medium-family: "Zoho Puvi";
  --font-heading-h3-h3-medium-size: 72px;
  --font-heading-h3-h3-medium-weight: 500;
  --font-heading-h3-h3-medium-line-height: 80px;
  --font-heading-h3-h3-regular-family: "Zoho Puvi";
  --font-heading-h3-h3-regular-size: 72px;
  --font-heading-h3-h3-regular-weight: 400;
  --font-heading-h3-h3-regular-line-height: 80px;
  --font-heading-h4-h4-bold-family: "Zoho Puvi";
  --font-heading-h4-h4-bold-size: 64px;
  --font-heading-h4-h4-bold-weight: 700;
  --font-heading-h4-h4-bold-line-height: 72px;
  --font-heading-h4-h4-semibold-family: "Zoho Puvi";
  --font-heading-h4-h4-semibold-size: 64px;
  --font-heading-h4-h4-semibold-weight: 400;
  --font-heading-h4-h4-semibold-line-height: 72px;
  --font-heading-h4-h4-medium-family: "Zoho Puvi";
  --font-heading-h4-h4-medium-size: 64px;
  --font-heading-h4-h4-medium-weight: 500;
  --font-heading-h4-h4-medium-line-height: 72px;
  --font-heading-h4-h4-regular-family: "Zoho Puvi";
  --font-heading-h4-h4-regular-size: 64px;
  --font-heading-h4-h4-regular-weight: 400;
  --font-heading-h4-h4-regular-line-height: 72px;
  --font-heading-h5-h5-bold-family: "Zoho Puvi";
  --font-heading-h5-h5-bold-size: 56px;
  --font-heading-h5-h5-bold-weight: 700;
  --font-heading-h5-h5-bold-line-height: 64px;
  --font-heading-h5-h5-semibold-family: "Zoho Puvi";
  --font-heading-h5-h5-semibold-size: 56px;
  --font-heading-h5-h5-semibold-weight: 400;
  --font-heading-h5-h5-semibold-line-height: 64px;
  --font-heading-h5-h5-medium-family: "Zoho Puvi";
  --font-heading-h5-h5-medium-size: 56px;
  --font-heading-h5-h5-medium-weight: 500;
  --font-heading-h5-h5-medium-line-height: 64px;
  --font-heading-h5-h5-regular-family: "Zoho Puvi";
  --font-heading-h5-h5-regular-size: 56px;
  --font-heading-h5-h5-regular-weight: 400;
  --font-heading-h5-h5-regular-line-height: 64px;
  --font-heading-h6-h6-bold-family: "Zoho Puvi";
  --font-heading-h6-h6-bold-size: 48px;
  --font-heading-h6-h6-bold-weight: 700;
  --font-heading-h6-h6-bold-line-height: 56px;
  --font-heading-h6-h6-semibold-family: "Zoho Puvi";
  --font-heading-h6-h6-semibold-size: 48px;
  --font-heading-h6-h6-semibold-weight: 400;
  --font-heading-h6-h6-semibold-line-height: 56px;
  --font-heading-h6-h6-medium-family: "Zoho Puvi";
  --font-heading-h6-h6-medium-size: 48px;
  --font-heading-h6-h6-medium-weight: 500;
  --font-heading-h6-h6-medium-line-height: 56px;
  --font-heading-h6-h6-regular-family: "Zoho Puvi";
  --font-heading-h6-h6-regular-size: 48px;
  --font-heading-h6-h6-regular-weight: 400;
  --font-heading-h6-h6-regular-line-height: 56px;
  --font-paragraph-large-large-text-bold-family: "Zoho Puvi";
  --font-paragraph-large-large-text-bold-size: 40px;
  --font-paragraph-large-large-text-bold-weight: 700;
  --font-paragraph-large-large-text-bold-line-height: 48px;
  --font-paragraph-large-large-text-semibold-family: "Zoho Puvi";
  --font-paragraph-large-large-text-semibold-size: 40px;
  --font-paragraph-large-large-text-semibold-weight: 400;
  --font-paragraph-large-large-text-semibold-line-height: 48px;
  --font-paragraph-large-large-text-medium-family: "Zoho Puvi";
  --font-paragraph-large-large-text-medium-size: 40px;
  --font-paragraph-large-large-text-medium-weight: 500;
  --font-paragraph-large-large-text-medium-line-height: 48px;
  --font-paragraph-large-large-text-regular-family: "Zoho Puvi";
  --font-paragraph-large-large-text-regular-size: 40px;
  --font-paragraph-large-large-text-regular-weight: 400;
  --font-paragraph-large-large-text-regular-line-height: 48px;
  --font-paragraph-medium-medium-text-bold-family: "Zoho Puvi";
  --font-paragraph-medium-medium-text-bold-size: 32px;
  --font-paragraph-medium-medium-text-bold-weight: 700;
  --font-paragraph-medium-medium-text-bold-line-height: 40px;
  --font-paragraph-medium-medium-text-semibold-family: "Zoho Puvi";
  --font-paragraph-medium-medium-text-semibold-size: 32px;
  --font-paragraph-medium-medium-text-semibold-weight: 400;
  --font-paragraph-medium-medium-text-semibold-line-height: 40px;
  --font-paragraph-medium-medium-text-medium-family: "Zoho Puvi";
  --font-paragraph-medium-medium-text-medium-size: 32px;
  --font-paragraph-medium-medium-text-medium-weight: 500;
  --font-paragraph-medium-medium-text-medium-line-height: 40px;
  --font-paragraph-medium-medium-text-regular-family: "Zoho Puvi";
  --font-paragraph-medium-medium-text-regular-size: 32px;
  --font-paragraph-medium-medium-text-regular-weight: 400;
  --font-paragraph-medium-medium-text-regular-line-height: 40px;
  --font-paragraph-regular-regular-text-bold-family: "Zoho Puvi";
  --font-paragraph-regular-regular-text-bold-size: 24px;
  --font-paragraph-regular-regular-text-bold-weight: 700;
  --font-paragraph-regular-regular-text-bold-line-height: 32px;
  --font-paragraph-regular-regular-text-semibold-family: "Zoho Puvi";
  --font-paragraph-regular-regular-text-semibold-size: 24px;
  --font-paragraph-regular-regular-text-semibold-weight: 400;
  --font-paragraph-regular-regular-text-semibold-line-height: 32px;
  --font-paragraph-regular-regular-text-medium-family: "Zoho Puvi";
  --font-paragraph-regular-regular-text-medium-size: 24px;
  --font-paragraph-regular-regular-text-medium-weight: 500;
  --font-paragraph-regular-regular-text-medium-line-height: 32px;
  --font-paragraph-regular-regular-text-regular-family: "Zoho Puvi";
  --font-paragraph-regular-regular-text-regular-size: 24px;
  --font-paragraph-regular-regular-text-regular-weight: 400;
  --font-paragraph-regular-regular-text-regular-line-height: 32px;
  --font-paragraph-small-small-text-regular-family: "Zoho Puvi";
  --font-paragraph-small-small-text-regular-size: 20px;
  --font-paragraph-small-small-text-regular-weight: 400;
  --font-paragraph-small-small-text-regular-line-height: 28px;
  --font-paragraph-small-small-text-medium-family: "Zoho Puvi";
  --font-paragraph-small-small-text-medium-size: 20px;
  --font-paragraph-small-small-text-medium-weight: 500;
  --font-paragraph-small-small-text-medium-line-height: 28px;
  --font-paragraph-small-small-text-semibold-family: "Zoho Puvi";
  --font-paragraph-small-small-text-semibold-size: 20px;
  --font-paragraph-small-small-text-semibold-weight: 400;
  --font-paragraph-small-small-text-semibold-line-height: 28px;
  --font-paragraph-small-small-text-bold-family: "Zoho Puvi";
  --font-paragraph-small-small-text-bold-size: 20px;
  --font-paragraph-small-small-text-bold-weight: 700;
  --font-paragraph-small-small-text-bold-line-height: 28px;
  --font-paragraph-x-small-x-small-text-bold-family: "Zoho Puvi";
  --font-paragraph-x-small-x-small-text-bold-size: 16px;
  --font-paragraph-x-small-x-small-text-bold-weight: 700;
  --font-paragraph-x-small-x-small-text-bold-line-height: 24px;
  --font-paragraph-x-small-x-small-text-semibold-family: "Zoho Puvi";
  --font-paragraph-x-small-x-small-text-semibold-size: 16px;
  --font-paragraph-x-small-x-small-text-semibold-weight: 400;
  --font-paragraph-x-small-x-small-text-semibold-line-height: 24px;
  --font-paragraph-x-small-x-small-text-medium-family: "Zoho Puvi";
  --font-paragraph-x-small-x-small-text-medium-size: 16px;
  --font-paragraph-x-small-x-small-text-medium-weight: 500;
  --font-paragraph-x-small-x-small-text-medium-line-height: 24px;
  --font-paragraph-x-small-x-small-text-regular-family: "Zoho Puvi";
  --font-paragraph-x-small-x-small-text-regular-size: 16px;
  --font-paragraph-x-small-x-small-text-regular-weight: 400;
  --font-paragraph-x-small-x-small-text-regular-line-height: 24px;
  --font-paragraph-tiny-caption-text-bold-family: "Zoho Puvi";
  --font-paragraph-tiny-caption-text-bold-size: 12px;
  --font-paragraph-tiny-caption-text-bold-weight: 700;
  --font-paragraph-tiny-caption-text-semibold-family: "Zoho Puvi";
  --font-paragraph-tiny-caption-text-semibold-size: 12px;
  --font-paragraph-tiny-caption-text-semibold-weight: 400;
  --font-paragraph-tiny-caption-text-medium-family: "Zoho Puvi";
  --font-paragraph-tiny-caption-text-medium-size: 12px;
  --font-paragraph-tiny-caption-text-medium-weight: 500;
  --font-paragraph-tiny-caption-text-regular-family: "Zoho Puvi";
  --font-paragraph-tiny-caption-text-regular-size: 12px;
  --font-paragraph-tiny-caption-text-regular-weight: 400;
}
```

## Tailwind Configuration

```javascript
// tailwind.config.js
module.exports = { theme: { extend: {

  colors: {
    'blue-950': '#000719',
    'blue-900': '#000e33',
    'blue-800': '#001d66',
    'blue-700': '#012b99',
    'blue-600': '#003acc',
    'blue-500': '#0047ff',
    'blue-400': '#336dff',
    'blue-300': '#6691ff',
    'blue-200': '#9ab6ff',
    'blue-100': '#ccdaff',
    'blue-50': '#e4edff',
    'teal-950': '#015d54',
    'teal-900': '#008075',
    'teal-800': '#05a79a',
    'teal-700': '#00ccbb',
    'teal-600': '#01e6d2',
    'teal-500': '#0fffeb',
    'teal-400': '#75fff4',
    'teal-300': '#adfff9',
    'teal-200': '#ccfffb',
    'teal-100': '#ebfffd',
    'teal-50': '#f5fffe',
    'grey-950': '#1a1a1a',
    'grey-900': '#262626',
    'grey-800': '#383838',
    'grey-700': '#454545',
    'grey-600': '#4f4f4f',
    'grey-500': '#595959',
    'grey-400': '#919191',
    'grey-300': '#b5b5b5',
    'grey-200': '#d1d1d1',
    'grey-100': '#ebebeb',
    'grey-50': '#f5f5f5',
    'cyan-950': '#011619',
    'cyan-900': '#012c32',
    'cyan-800': '#035e69',
    'cyan-700': '#03899c',
    'cyan-600': '#07bad2',
    'cyan-500': '#10dffa',
    'cyan-400': '#40e5fb',
    'cyan-300': '#6eebfc',
    'cyan-200': '#9ff2fd',
    'cyan-100': '#ccf8fe',
    'cyan-50': '#e6fcff',
    'deeporange-950': '#190900',
    'deeporange-900': '#331300',
    'deeporange-800': '#662500',
    'deeporange-700': '#9e3a01',
    'deeporange-600': '#d14d00',
    'deeporange-500': '#ff6105',
    'deeporange-400': '#ff8138',
    'deeporange-300': '#ffa16b',
    'deeporange-200': '#ffbe9a',
    'deeporange-100': '#ffdfcb',
    'deeporange-50': '#ffeee5',
    'lime-950': '#171900',
    'lime-900': '#2e3300',
    'lime-800': '#606b01',
    'lime-700': '#8e9f00',
    'lime-600': '#c1d601',
    'lime-500': '#e6ff0a',
    'lime-400': '#ebff3e',
    'lime-300': '#f0ff6a',
    'lime-200': '#f5ff9d',
    'lime-100': '#faffcc',
    'lime-50': '#fdffe4',
    'pink-950': '#180109',
    'pink-900': '#310212',
    'pink-800': '#620423',
    'pink-700': '#970736',
    'pink-600': '#c80b49',
    'pink-500': '#f4115d',
    'pink-400': '#f6417d',
    'pink-300': '#f8729f',
    'pink-200': '#fb9dbc',
    'pink-100': '#fecedf',
    'pink-50': '#fee7ee',
    'purple-950': '#090019',
    'purple-900': '#130033',
    'purple-800': '#240066',
    'purple-700': '#37009f',
    'purple-600': '#4900d1',
    'purple-500': '#5e05ff',
    'purple-400': '#7e38ff',
    'purple-300': '#9f6bff',
    'purple-200': '#bd99ff',
    'purple-100': '#deccff',
    'purple-50': '#eee5ff',
    'lightblue-950': '#001119',
    'lightblue-900': '#002232',
    'lightblue-800': '#004466',
    'lightblue-700': '#01699e',
    'lightblue-600': '#008bd1',
    'lightblue-500': '#09abff',
    'lightblue-400': '#38bdff',
    'lightblue-300': '#6bceff',
    'lightblue-200': '#99ddff',
    'lightblue-100': '#cdeeff',
    'lightblue-50': '#e5f7ff',
    'green-950': '#011902',
    'green-900': '#003203',
    'green-800': '#00660a',
    'green-700': '#019e0d',
    'green-600': '#04d111',
    'green-500': '#03ff17',
    'green-400': '#37ff49',
    'green-300': '#6cff77',
    'green-200': '#99ffa2',
    'green-100': '#ccffd0',
    'green-50': '#e5ffe8',
    'yellow-950': '#564800',
    'yellow-900': '#7a6600',
    'yellow-800': '#ad9001',
    'yellow-700': '#cba901',
    'yellow-600': '#eac301',
    'yellow-500': '#fed70b',
    'yellow-400': '#fee253',
    'yellow-300': '#feea85',
    'yellow-200': '#fff3b3',
    'yellow-100': '#fff9db',
    'yellow-50': '#fffceb',
    'orange-950': '#180f00',
    'orange-900': '#331f00',
    'orange-800': '#6b4000',
    'orange-700': '#9e5f01',
    'orange-600': '#d68100',
    'orange-500': '#ff9e08',
    'orange-400': '#ffb13d',
    'orange-300': '#ffc46b',
    'orange-200': '#ffd99e',
    'orange-100': '#ffebcb',
    'orange-50': '#fff5e5',
    'red-950': '#190001',
    'red-900': '#330000',
    'red-800': '#660000',
    'red-700': '#9f0101',
    'red-600': '#d10000',
    'red-500': '#ff0405',
    'red-400': '#ff3938',
    'red-300': '#ff6b6b',
    'red-200': '#ff999a',
    'red-100': '#ffcccc',
    'red-50': '#ffe5e4',
    'blue-color': '#ffffff',
    'white--black-white': '#ffffff',
    'white--black-black': '#000000',
    'dark-grey-950': '#030303',
    'dark-grey-900': '#050505',
    'dark-grey-800': '#080808',
    'dark-grey-700': '#0a0a0a',
    'dark-grey-600': '#0d0d0d',
    'dark-grey-500': '#0f0f0f',
    'dark-grey-400': '#121212',
    'dark-grey-300': '#141414',
    'dark-grey-200': '#171717',
    'dark-grey-100': '#1a1a1a',
    'dark-grey-50': '#1a1a1a',
    'semantic-success-subtle': '#ccffd0',
    'semantic-success-bold': '#03ff17',
    'semantic-error-subtle': '#ffe5e4',
    'semantic-error-bold': '#ff0405',
    'semantic-warning-subtle': '#ffdfcb',
    'semantic-warning-bold': '#ff6105',
    'semantic-button-primary-bg-subtle': '#ffdfcb',
    'semantic-button-primary-bg-bold': '#ff6105',
    'blue-950': '#000719',
    'blue-900': '#000e33',
    'blue-800': '#001d66',
    'blue-700': '#012b99',
    'blue-600': '#003acc',
    'blue-500': '#0047ff',
    'blue-400': '#336dff',
    'blue-300': '#6691ff',
    'blue-200': '#9ab6ff',
    'blue-100': '#ccdaff',
    'blue-50': '#e4edff',
    'teal-950': '#015d54',
    'teal-900': '#008075',
    'teal-800': '#05a79a',
    'teal-700': '#00ccbb',
    'teal-600': '#01e6d2',
    'teal-500': '#0fffeb',
    'teal-400': '#75fff4',
    'teal-300': '#adfff9',
    'teal-200': '#ccfffb',
    'teal-100': '#ebfffd',
    'teal-50': '#f5fffe',
    'gray-950': '#1a1a1a',
    'gray-900': '#262626',
    'gray-800': '#383838',
    'gray-700': '#454545',
    'gray-600': '#4f4f4f',
    'gray-500': '#595959',
    'gray-400': '#919191',
    'gray-300': '#b5b5b5',
    'gray-200': '#d1d1d1',
    'gray-100': '#ebebeb',
    'gray-50': '#f5f5f5',
    'cyan-950': '#011619',
    'cyan-900': '#012c32',
    'cyan-800': '#035e69',
    'cyan-700': '#03899c',
    'cyan-600': '#07bad2',
    'cyan-500': '#10dffa',
    'cyan-400': '#40e5fb',
    'cyan-300': '#6eebfc',
    'cyan-200': '#9ff2fd',
    'cyan-100': '#ccf8fe',
    'cyan-50': '#e6fcff',
    'deeporange-950': '#190900',
    'deeporange-900': '#331300',
    'deeporange-800': '#662500',
    'deeporange-700': '#9e3a01',
    'deeporange-600': '#d14d00',
    'deeporange-500': '#ff6105',
    'deeporange-400': '#ff8138',
    'deeporange-300': '#ffa16b',
    'deeporange-200': '#ffbe9a',
    'deeporange-100': '#ffdfcb',
    'deeporange-50': '#ffeee5',
    'lime-950': '#171900',
    'lime-900': '#2e3300',
    'lime-800': '#606b01',
    'lime-700': '#8e9f00',
    'lime-600': '#c1d601',
    'lime-500': '#e6ff0a',
    'lime-400': '#ebff3e',
    'lime-300': '#f0ff6a',
    'lime-200': '#f5ff9d',
    'lime-100': '#faffcc',
    'lime-50': '#fdffe4',
    'pink-950': '#180109',
    'pink-900': '#310212',
    'pink-800': '#620423',
    'pink-700': '#970736',
    'pink-600': '#c80b49',
    'pink-500': '#f4115d',
    'pink-400': '#f6417d',
    'pink-300': '#f8729f',
    'pink-200': '#fb9dbc',
    'pink-100': '#fecedf',
    'pink-50': '#fee7ee',
    'purple-950': '#090019',
    'purple-900': '#130033',
    'purple-800': '#240066',
    'purple-700': '#37009f',
    'purple-600': '#4900d1',
    'purple-500': '#5e05ff',
    'purple-400': '#7e38ff',
    'purple-300': '#9f6bff',
    'purple-200': '#bd99ff',
    'purple-100': '#deccff',
    'purple-50': '#eee5ff',
    'lightblue-950': '#001119',
    'lightblue-900': '#002232',
    'lightblue-800': '#004466',
    'lightblue-700': '#01699e',
    'lightblue-600': '#008bd1',
    'lightblue-500': '#09abff',
    'lightblue-400': '#38bdff',
    'lightblue-300': '#6bceff',
    'lightblue-200': '#99ddff',
    'lightblue-100': '#cdeeff',
    'lightblue-50': '#e5f7ff',
    'green-950': '#011902',
    'green-900': '#003203',
    'green-800': '#00660a',
    'green-700': '#019e0d',
    'green-600': '#04d111',
    'green-500': '#03ff17',
    'green-400': '#37ff49',
    'green-300': '#6cff77',
    'green-200': '#99ffa2',
    'green-100': '#ccffd0',
    'green-50': '#e5ffe8',
    'yellow-950': '#564800',
    'yellow-900': '#7a6600',
    'yellow-800': '#ad9001',
    'yellow-700': '#cba901',
    'yellow-600': '#eac301',
    'yellow-500': '#fed70b',
    'yellow-400': '#fee253',
    'yellow-300': '#feea85',
    'yellow-200': '#fff3b3',
    'yellow-100': '#fff9db',
    'yellow-50': '#fffceb',
    'orange-950': '#180f00',
    'orange-900': '#331f00',
    'orange-800': '#6b4000',
    'orange-700': '#9e5f01',
    'orange-600': '#d68100',
    'orange-500': '#ff9e08',
    'orange-400': '#ffb13d',
    'orange-300': '#ffc46b',
    'orange-200': '#ffd99e',
    'orange-100': '#ffebcb',
    'orange-50': '#fff5e5',
    'red-950': '#190001',
    'red-900': '#330000',
    'red-800': '#660000',
    'red-700': '#9f0101',
    'red-600': '#d10000',
    'red-500': '#ff0405',
    'red-400': '#ff3938',
    'red-300': '#ff6b6b',
    'red-200': '#ff999a',
    'red-100': '#ffcccc',
    'red-50': '#ffe5e4',
    'blue-color': '#ffffff',
    'white--black-white': '#ffffff',
    'white--black-black': '#000000',
    'dark-gray-950': '#030303',
    'dark-gray-900': '#050505',
    'dark-gray-800': '#080808',
    'dark-gray-700': '#0a0a0a',
    'dark-gray-600': '#0d0d0d',
    'dark-gray-500': '#0f0f0f',
    'dark-gray-400': '#121212',
    'dark-gray-300': '#141414',
    'dark-gray-200': '#171717',
    'dark-gray-100': '#1a1a1a',
    'dark-gray-50': '#1a1a1a',
    'bg-page': '#ffffff',
    'bg-subtle': '#f5f5f5',
    'bg-muted': '#ebebeb',
    'bg-emphasized': '#d1d1d1',
    'surface-default': '#ffffff',
    'surface-raised': '#f5f5f5',
    'surface-overlay': '#ebebeb',
    'state-error-bg': '#ffe5e4',
    'state-error-bg-hover': '#ffcccc',
    'state-error-bg-active': '#ff999a',
    'state-warning-bg': '#fff5e5',
    'state-warning-bg-hover': '#ffebcb',
    'state-warning-bg-active': '#ffd99e',
    'state-success-bg': '#e5ffe8',
    'state-success-bg-hover': '#ccffd0',
    'state-success-bg-active': '#99ffa2',
    'state-info-bg': '#e4edff',
    'state-info-bg-hover': '#ccdaff',
    'state-info-bg-active': '#9ab6ff',
    'state-notice-bg': '#fffceb',
    'state-notice-bg-hover': '#fff9db',
    'state-notice-bg-active': '#fff3b3',
    'state-critical-bg': '#ffe5e4',
    'state-critical-bg-hover': '#ffcccc',
    'state-pink-bg': '#fee7ee',
    'state-pink-bg-hover': '#fecedf',
    'state-purple-bg': '#eee5ff',
    'state-purple-bg-hover': '#deccff',
    'state-teal-bg': '#f5fffe',
    'state-teal-bg-hover': '#ebfffd',
    'state-cyan-bg': '#e6fcff',
    'state-cyan-bg-hover': '#ccf8fe',
    'state-lightblue-bg': '#e5f7ff',
    'state-lightblue-bg-hover': '#cdeeff',
    'state-lime-bg': '#fdffe4',
    'state-lime-bg-hover': '#faffcc',
    'state-deeporange-bg': '#ffeee5',
    'state-deeporange-bg-hover': '#ffdfcb',
    'light-shade-red-1': '#ffe5e4',
    'light-shade-red-2': '#ffcccc',
    'light-shade-red-3': '#ff999a',
    'light-shade-orange-1': '#fff5e5',
    'light-shade-orange-2': '#ffebcb',
    'light-shade-orange-3': '#ffd99e',
    'light-shade-deeporange-1': '#ffeee5',
    'light-shade-deeporange-2': '#ffdfcb',
    'light-shade-deeporange-3': '#ffbe9a',
    'light-shade-yellow-1': '#fffceb',
    'light-shade-yellow-2': '#fff9db',
    'light-shade-yellow-3': '#fff3b3',
    'light-shade-green-1': '#e5ffe8',
    'light-shade-green-2': '#ccffd0',
    'light-shade-green-3': '#99ffa2',
    'light-shade-lime-1': '#fdffe4',
    'light-shade-lime-2': '#faffcc',
    'light-shade-lime-3': '#f5ff9d',
    'light-shade-blue-1': '#e4edff',
    'light-shade-blue-2': '#ccdaff',
    'light-shade-blue-3': '#9ab6ff',
    'light-shade-lightblue-1': '#e5f7ff',
    'light-shade-lightblue-2': '#cdeeff',
    'light-shade-lightblue-3': '#99ddff',
    'light-shade-cyan-1': '#e6fcff',
    'light-shade-cyan-2': '#ccf8fe',
    'light-shade-cyan-3': '#9ff2fd',
    'light-shade-teal-1': '#f5fffe',
    'light-shade-teal-2': '#ebfffd',
    'light-shade-teal-3': '#ccfffb',
    'light-shade-purple-1': '#eee5ff',
    'light-shade-purple-2': '#deccff',
    'light-shade-purple-3': '#bd99ff',
    'light-shade-pink-1': '#fee7ee',
    'light-shade-pink-2': '#fecedf',
    'light-shade-pink-3': '#fb9dbc',
    'beige-50': '#fdf8f0',
    'beige-100': '#faf0e1',
    'beige-200': '#f5e1c3',
    'beige-300': '#efcfa0',
    'beige-400': '#e8bc7d',
    'beige-500': '#e0a85a',
    'beige-600': '#c48e3e',
    'beige-700': '#a0722e',
    'beige-800': '#7a5721',
    'beige-900': '#543c17',
    'beige-950': '#2e200c',
    'warmgray-50': '#faf8f6',
    'warmgray-100': '#f0edea',
    'warmgray-200': '#e0dbd5',
    'warmgray-300': '#c8c0b8',
    'warmgray-400': '#ada39a',
    'warmgray-500': '#93877c',
    'warmgray-600': '#796d62',
    'warmgray-700': '#5f544b',
    'warmgray-800': '#463d35',
    'warmgray-900': '#2e2721',
    'warmgray-950': '#1a1512',
    'coolgray-50': '#f5f7fa',
    'coolgray-100': '#ebeef3',
    'coolgray-200': '#d5dbe5',
    'coolgray-300': '#b8c1d1',
    'coolgray-400': '#9aa7bd',
    'coolgray-500': '#7c8da8',
    'coolgray-600': '#627390',
    'coolgray-700': '#4b5a74',
    'coolgray-800': '#354158',
    'coolgray-900': '#212b3d',
    'coolgray-950': '#121822',
    'dark-50': '#e8e8ee',
    'dark-100': '#c4c4d4',
    'dark-200': '#9696b0',
    'dark-300': '#6a6a8c',
    'dark-400': '#464668',
    'dark-500': '#2a2a4a',
    'dark-600': '#22223c',
    'dark-700': '#1a1a2e',
    'dark-800': '#121222',
    'dark-900': '#0a0a18',
    'dark-950': '#05050c',
    'primary-50': '#fbffe8',
    'primary-100': '#f5ffcc',
    'primary-200': '#eeff99',
    'primary-300': '#e3ff77',
    'primary-400': '#cfff55',
    'primary-500': '#b8e64d',
    'primary-600': '#9abf3d',
    'primary-700': '#7a992f',
    'primary-800': '#5c7322',
    'primary-900': '#3d4d17',
    'primary-950': '#1f260c',
    'secondary-50': '#f0f2f7',
    'secondary-100': '#dde1ec',
    'secondary-200': '#bcc3d9',
    'secondary-300': '#95a0bf',
    'secondary-400': '#6e7da5',
    'secondary-500': '#4d5d8a',
    'secondary-600': '#3d4a6e',
    'secondary-700': '#2f3953',
    'secondary-800': '#232a3d',
    'secondary-900': '#181c29',
    'secondary-950': '#0c0e14',
    'accent-50': '#fff3ee',
    'accent-100': '#ffe2d4',
    'accent-200': '#ffc4a8',
    'accent-300': '#ffa070',
    'accent-400': '#ff7a45',
    'accent-500': '#e8632e',
    'accent-600': '#c04f22',
    'accent-700': '#983d1a',
    'accent-800': '#702d13',
    'accent-900': '#4a1e0d',
    'accent-950': '#250f06',
    'neutral-50': '#f8f9f5',
    'neutral-100': '#f0f1ec',
    'neutral-200': '#e0e2da',
    'neutral-300': '#c8cbc0',
    'neutral-400': '#a8aca0',
    'neutral-500': '#888c80',
    'neutral-600': '#6c7065',
    'neutral-700': '#52554d',
    'neutral-800': '#3a3c36',
    'neutral-900': '#242521',
    'neutral-950': '#121310',
    'success-50': '#ecfdf5',
    'success-100': '#d1fae5',
    'success-200': '#a7f3d0',
    'success-300': '#6ee7b7',
    'success-400': '#34d399',
    'success-500': '#10b981',
    'success-600': '#059669',
    'success-700': '#047857',
    'success-800': '#065f46',
    'success-900': '#064e3b',
    'success-950': '#022c22',
    'warning-50': '#fffbeb',
    'warning-100': '#fef3c7',
    'warning-200': '#fde68a',
    'warning-300': '#fcd34d',
    'warning-400': '#fbbf24',
    'warning-500': '#f59e0b',
    'warning-600': '#d97706',
    'warning-700': '#b45309',
    'warning-800': '#92400e',
    'warning-900': '#78350f',
    'warning-950': '#451a03',
    'error-50': '#fef2f2',
    'error-100': '#fee2e2',
    'error-200': '#fecaca',
    'error-300': '#fca5a5',
    'error-400': '#f87171',
    'error-500': '#ef4444',
    'error-600': '#dc2626',
    'error-700': '#b91c1c',
    'error-800': '#991b1b',
    'error-900': '#7f1d1d',
    'error-950': '#450a0a',
    'info-50': '#eff6ff',
    'info-100': '#dbeafe',
    'info-200': '#bfdbfe',
    'info-300': '#93c5fd',
    'info-400': '#60a5fa',
    'info-500': '#3b82f6',
    'info-600': '#2563eb',
    'info-700': '#1d4ed8',
    'info-800': '#1e40af',
    'info-900': '#1e3a8a',
    'info-950': '#172554',
  },
  spacing: {
    'space-sm--1': '4px',
    'space-md-1': '24px',
    'space-md--2': '32px',
    'space-md--3': '40px',
    'space-md--4': '48px',
    'space-md--5': '56px',
    'space-md--6': '64px',
    'space-md--7': '72px',
    'space-md--8': '80px',
    'space-lg--1': '88px',
    'space-lg--2': '96px',
    'space-lg--3': '104px',
    'space-lg--4': '112px',
    'space-lg--5': '120px',
    'space-lg--6': '128px',
    'space-lg--7': '136px',
    'space-lg--8': '144px',
    'space-lg--9': '152px',
    'space-lg--10': '160px',
    'space-xl--1': '168px',
    'space-xl--2': '176px',
    'space-xl--3': '184px',
    'space-xl--4': '192px',
    'space-xl--5': '200px',
    'space-xl--6': '208px',
    'space-xl--7': '216px',
    'space-xl--8': '224px',
    'space-xl--9': '232px',
    'space-xl--10': '240px',
    'space-sm--2': '8px',
    'space-sm--3': '12px',
    'space-sm--4': '16px',
    'space-sm--5': '20px',
    'numbers-2s-none': '0px',
    'numbers-2s-xs': '2px',
    'numbers-2s-sm': '4px',
    'numbers-2s-md': '8px',
    'numbers-2s-lg': '16px',
    'numbers-2s-round': '160px',
    'drop-shadow-blur-none': '0px',
    'drop-shadow-blur-xs': '4px',
    'drop-shadow-blur-sm': '16px',
    'drop-shadow-blur-md': '24px',
    'drop-shadow-blur-lg': '48px',
    'drop-shadow-blur-xl': '64px',
    'drop-shadow-positioning-none': '0px',
    'drop-shadow-positioning-xxxs': '2px',
    'drop-shadow-positioning-xxs': '4px',
    'drop-shadow-positioning-xs': '8px',
    'drop-shadow-positioning-sm': '12px',
    'drop-shadow-positioning-md': '16px',
    'drop-shadow-positioning-lg': '20px',
    'drop-shadow-positioning-xl': '24px',
    'drop-shadow-positioning-xxl': '32px',
    'drop-shadow-positioning-xxxl': '48px',
    'drop-shadow-spread-none': '0px',
    'drop-shadow-spread-xs': '-4px',
    'drop-shadow-spread-sm': '-8px',
    'drop-shadow-spread-md': '-12px',
    'drop-shadow-spread-lg': '-16px',
    'drop-shadow-spread-xl': '-20px',
    'drop-shadow-spread-xxl': '-24px',
    'drop-shadow-number': '0px',
    'sm--1': '4px',
    'sm--2': '8px',
    'sm--3': '12px',
    'sm--4': '16px',
    'sm--5': '20px',
    'md--1': '24px',
    'md--2': '32px',
    'md--3': '40px',
    'md--4': '48px',
    'md--5': '56px',
    'md--6': '64px',
    'md--7': '72px',
    'md--8': '80px',
    'lg--1': '88px',
    'lg--2': '96px',
    'lg--3': '104px',
    'lg--4': '112px',
    'lg--5': '120px',
    'lg--6': '128px',
    'lg--7': '136px',
    'lg--8': '144px',
    'lg--9': '152px',
    'lg--10': '160px',
    'xl--1': '168px',
    'xl--2': '176px',
    'xl--3': '184px',
    'xl--4': '192px',
    'xl--5': '200px',
    'xl--6': '208px',
    'xl--7': '216px',
    'xl--8': '224px',
    'xl--9': '232px',
    'xl--10': '240px',
    'br-breakpoints': '1400px',
    'br-columns': '12px',
    'br-margin': '40px',
    'br-gutter': '24px',
    'sm-0': '2px',
    'space-sm--0': '2px',
  },
  borderRadius: {
    'radius-none': '0px',
    'radius-xs': '2px',
    'radius-sm': '4px',
    'radius-md': '8px',
    'radius-lg': '16px',
    'radius-round': '160px',
  },
  fontWeight: {
    'font-weight-bold': '700',
    'font-weight-semibold': '600',
    'font-weight-medium': '500',
    'font-weight-regular': '400',
    'font-weight-bold': '700',
    'font-weight-semibold': '600',
    'font-weight-medium': '500',
    'font-weight-regular': '400',
    'font-weight-bold': '700',
    'font-weight-semibold': '600',
    'font-weight-medium': '500',
    'font-weight-regular': '400',
    'font-weight-bold': '700',
    'font-weight-semibold': '600',
    'font-weight-medium': '500',
    'font-weight-regular': '400',
    'font-weight-bold': '700',
    'font-weight-semibold': '600',
    'font-weight-medium': '500',
    'font-weight-regular': '400',
  },
  fontFamily: {
    'zoho-puvi': ['Zoho Puvi', 'sans-serif'],
  },
}}};
```

---
