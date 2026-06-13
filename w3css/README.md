# W3-Nord UI Framework

A Nord-inspired design system built on top of W3.CSS conventions, providing a complete utility + component library with consistent theming, full Nord palette usage (0–15), and W3-compatible class structure.

---

## Features

- Full Nord palette (nord0–nord15) utilization
- W3.CSS-compatible class system
- Prebuilt UI components (buttons, cards, navbar, modal, sidebar, alerts)
- Utility-first helpers (spacing, flex, radius, shadows)
- Clean semantic color system
- Responsive-ready structure
- Drop-in CSS file (no build tools required)

---

## Installation

### Option 1: Direct Usage (Recommended)

```html
<link rel="stylesheet" href="https://crazyrag778.github.io/nord-theme-css/w3css/w3-nord-theme.css/">
```

### Option 2: With W3.CSS

```html
<link rel="stylesheet" href="https://www.w3schools.com/w3css/5/w3.css">
<link rel="stylesheet" href="https://crazyrag778.github.io/nord-theme-css/w3css/w3-nord-theme.css/">
```

> Always load `w3-nord-ui.css` AFTER W3.CSS to override styles correctly.

---

## Design Philosophy

| Role | Nord Color |
|------|------------|
| Background | nord0–nord2 |
| Surface | nord1–nord2 |
| Border | nord3 |
| Text | nord4–nord6 |
| Primary | nord10 |
| Secondary | nord9 |
| Accent | nord8 |
| Info | nord7 |
| Success | nord14 |
| Warning | nord13 |
| Error | nord11 |
| Caution | nord12 |
| Special | nord15 |

---

## Core Usage

### Base Theme

```html
<div class="w3-nord-theme">
  Primary themed container
</div>
```

---

## Text Utilities

```html
<p class="w3-nord-text">Primary text</p>
<p class="w3-nord-text-muted">Muted text</p>

<p class="w3-nord-text-success">Success message</p>
<p class="w3-nord-text-error">Error message</p>
<p class="w3-nord-text-warning">Warning message</p>
<p class="w3-nord-text-info">Info message</p>
<p class="w3-nord-text-special">Special accent text</p>
```

---

## Buttons

```html
<button class="w3-button">Default</button>

<button class="w3-nord-btn w3-nord-btn-primary">Primary</button>
<button class="w3-nord-btn w3-nord-btn-secondary">Secondary</button>
<button class="w3-nord-btn w3-nord-btn-accent">Accent</button>

<button class="w3-nord-btn w3-nord-btn-success">Success</button>
<button class="w3-nord-btn w3-nord-btn-warning">Warning</button>
<button class="w3-nord-btn w3-nord-btn-error">Error</button>
<button class="w3-nord-btn w3-nord-btn-special">Special</button>
```

---

## Cards

```html
<div class="w3-card">
  <h3>Card Title</h3>
  <p>This is a Nord-themed card.</p>
</div>
```

---

## 🧾 Inputs

```html
<input type="text" placeholder="Enter text">
<textarea placeholder="Message"></textarea>
<select>
  <option>Option 1</option>
</select>
```

---

## Alerts

```html
<div class="w3-nord-alert w3-nord-alert-info">Info alert message</div>
<div class="w3-nord-alert w3-nord-alert-success">Success alert message</div>
<div class="w3-nord-alert w3-nord-alert-warning">Warning alert message</div>
<div class="w3-nord-alert w3-nord-alert-error">Error alert message</div>
<div class="w3-nord-alert w3-nord-alert-special">Special alert message</div>
```

---

## Navbar

```html
<div class="w3-nord-navbar">
  <div>Logo</div>
  <div>Menu</div>
</div>
```

---

## Sidebar

```html
<div class="w3-nord-sidebar">
  <p>Navigation</p>
</div>
```

---

## Modal

```html
<div class="w3-nord-modal" style="display:flex;">
  <div class="w3-nord-modal-content">
    <h3>Modal Title</h3>
    <p>Modal content here</p>
  </div>
</div>
```

---

## Layout Utilities

### Flex

```html
<div class="w3-nord-flex w3-nord-between">
  <div>Left</div>
  <div>Right</div>
</div>
```

### Centering

```html
<div class="w3-nord-flex w3-nord-center">
  Centered content
</div>
```

---

## Spacing Utilities

```html
<div class="w3-nord-m-1">Margin 1</div>
<div class="w3-nord-m-2">Margin 2</div>
<div class="w3-nord-m-3">Margin 3</div>

<div class="w3-nord-p-1">Padding 1</div>
<div class="w3-nord-p-2">Padding 2</div>
<div class="w3-nord-p-3">Padding 3</div>
```

---

## Borders & Radius

```html
<div class="w3-nord-border w3-nord-rounded-md">
  Box with border and radius
</div>
```

---

## Gradients

```html
<div class="w3-nord-gradient-primary">Primary gradient</div>
<div class="w3-nord-gradient-warm">Warm gradient</div>
<div class="w3-nord-gradient-cool">Cool gradient</div>
<div class="w3-nord-gradient-deep">Deep gradient</div>
```

---

## Best Practices

- Always use `w3-nord-*` classes instead of raw Nord variables
- Load CSS after W3.CSS
- Prefer semantic buttons (primary/success/error)
- Avoid inline styling when utilities exist

---

- JS modal + sidebar controller
- CDN via GitHub Pages
- Component expansion (tabs, dropdowns, tooltips)
