---
alwaysApply: true
---

# WCAG Examples

## ❌ Bad
```html
<div onclick="submit()">Submit</div>
```

## ✅ Good
```html
<button type="submit">Submit</button>
```

---

## ❌ Bad
```html
<input placeholder="Email">
```

## ✅ Good
```html
<label for="email">Email</label>
<input id="email" type="email">
```

