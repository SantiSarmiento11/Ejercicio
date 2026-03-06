# MusicStream — Storefront

A dark-mode music streaming & store interface built with semantic HTML5 and modular CSS.

## Structure

```
music-stream-app/
├── css/
│   ├── main.css            # Reset, variables, typography, imports
│   ├── base/
│   │   ├── layout.css      # Grid, Header, Sidebar, Main
│   │   └── components.css  # Buttons, Cards, Section headers
│   └── views/
│       ├── store.css       # Hero banner, Albums grid, Tracks grid
│       ├── player.css      # (reserved)
│       └── checkout.css    # (reserved)
├── assets/
│   ├── img/
│   └── icons/
├── index.html              # Storefront (Home)
├── album-detail.html
├── player.html
├── cart.html
├── checkout.html
├── success.html
└── README.md
```

## Design System

| Token | Value |
|---|---|
| Background | `#0b1424` |
| Surface | `#111c2e` |
| Primary accent | `#2d6cdf` |
| Text primary | `#ffffff` |
| Text secondary | `#9aa4b2` |

## Features
- Fully responsive (mobile sidebar collapses)
- Semantic HTML5 with ARIA labels
- CSS custom properties (design tokens)
- Hover micro-interactions on all cards and buttons
- No JavaScript, no frameworks
