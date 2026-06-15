# Nord Theme CSS

A lightweight CSS implementation of the **Nord colour palette** for modern web projects, extended with a **W3.CSS-compatible theme system**.

This project now provides:

- Nord design tokens (`nord0`–`nord15`)
- W3.CSS-compatible theme utilities (`w3-nord-*`)
- UI component system (buttons, cards, alerts, layout helpers)
- Zero-dependency CSS framework layer

It is designed for:
- UI libraries
- dashboards
- static sites
- design systems
- W3.CSS-based projects

---

## Features

### Core Palette System
- Complete Nord palette (`nord0`–`nord15`)
- CSS variable-based architecture
- Easy theming for any project

### W3.CSS Theme Support
- `w3-nord-theme-*` utility classes
- Compatible with W3.CSS structure
- Drop-in replacement theme layer
- Extended button, card, text, and border utilities

### UI System (W3-Nord Layer)
- Buttons (`w3-nord-btn-*`)
- Cards (`w3-card` enhanced)
- Alerts system
- Navbar + sidebar components
- Layout utilities (flex, spacing, radius)

### Developer Friendly
- No build tools required
- CDN ready
- Works with plain HTML or frameworks

---

## CDN

### 1. Nord Core Palette (Required)

```html
<link rel="stylesheet"
      href="https://crazyrag778.github.io/nord-theme-css/palettes/nord-main.css">
```

---

### 2. W3-Nord Theme System (Optional but recommended)

```html
Refer to WEBSITE
```

> Load W3-Nord AFTER W3.CSS if you are using W3.CSS.

---

## Usage

### Core Nord Usage

```css
body {
    background: var(--nord0);
    color: var(--nord6);
}

.card {
    background: var(--nord1);
    border: 1px solid var(--nord3);
}

.button {
    background: var(--nord8);
    color: var(--nord0);
}
```

## Color System Overview

### Polar Night

| Variable  | HEX       | Usage |
|-----------|-----------|------|
| `--nord0` | `#2e3440` | Background |
| `--nord1` | `#3b4252` | Surface |
| `--nord2` | `#434c5e` | Elevated surface |
| `--nord3` | `#4c566a` | Borders |

---

### Snow Storm

| Variable  | HEX       | Usage |
|-----------|-----------|------|
| `--nord4` | `#d8dee9` | Muted text |
| `--nord5` | `#e5e9f0` | Secondary text |
| `--nord6` | `#eceff4` | Primary text |

---

### Frost

| Variable   | HEX       | Usage |
|------------|-----------|------|
| `--nord7`  | `#8fbcbb` | Info |
| `--nord8`  | `#88c0d0` | Accent |
| `--nord9`  | `#81a1c1` | Secondary |
| `--nord10` | `#5e81ac` | Primary |

---

### Aurora

| Variable   | HEX       | Usage |
|------------|-----------|------|
| `--nord11` | `#bf616a` | Error |
| `--nord12` | `#d08770` | Warning |
| `--nord13` | `#ebcb8b` | Caution |
| `--nord14` | `#a3be8c` | Success |
| `--nord15` | `#b48ead` | Special |

---

## Compatibility

Works with:

- W3.CSS
- Plain HTML/CSS
- React / Vue / Svelte
- Static websites
- UI dashboards

---

## Project Status

> Active Development

This project is evolving into a full design system.

Planned improvements include:
- Component expansion
- Dark/light theme switching
- Better W3 integration layer
- Documentation site
- CDN optimization

---

## Contributing

Contributions are welcome.

You can help by:
- Improving W3 theme support
- Adding UI components
- Fixing bugs
- Suggesting design improvements
- Expanding documentation

---

## Roadmap

- Dark/Light Nord variants
- Full W3 component library expansion
- Documentation website
- JS plugin helpers (modal/sidebar control)
- Versioned releases (v1.0+)

---

## Author

Created and maintained by **Dibyojit Datta (CrazyRag778)**

Website: https://crazyrag778.github.io/nord-theme-css/
