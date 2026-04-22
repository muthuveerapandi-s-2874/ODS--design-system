---
alwaysApply: true
---

# WCAG Rules (Mandatory)

Follow WCAG 2.1 Level AA.

## Required

- All images must have meaningful alt text (decorative images use `alt=""`)
- Color contrast must be:
  - **≥ 4.5 : 1** for normal-size text
  - **≥ 3 : 1** for large text (≥ 18pt regular, or ≥ 14pt bold)
- Buttons and links must be keyboard accessible
- All interactive elements must have a **visible focus state** (not just the
  browser default — the focus style must be clearly perceivable)
- Inputs must have associated labels (`<label for>` or `aria-label`)
- Use semantic HTML elements (`<button>`, `<nav>`, `<main>`, `<header>`,
  `<footer>`) — required landmarks: header, main, nav, footer
- Error states must communicate the problem via **more than color** (text,
  icon, or `aria-invalid`)

## Forbidden

- Div-only buttons (`<div onclick>`)
- Placeholder-only inputs (no label)
- Color-only indicators for meaning
- Focus styles removed with `outline: none` and no replacement

## If any rule is violated

1. Stop
2. Explain the violation
3. Fix the code
