---
name: center-div
description: Comprehensive guide explaining how to center a div horizontally/vertically using modern CSS techniques.
---

# Div Centering

Master reference for centering elements in modern web development. Covers all major techniques with decision guidance.

## Method Selection

- **Flexbox** (Default): Use for most centering needs.
- **Grid**: Use when working within grid layouts or need precise 2D control.
- **Absolute**: Use for overlays, modals, or precise positioning requirements.
- **Auto margins**: Use for simple horizontal centering of block elements.

## Quick Reference

### Flexbox (Recommended Default)

Example: `.container { display: flex; justify-content: center; /* horizontal */ align-items: center; /* vertical */ }`. See other variants [here](resources/flexbox-variants.md).

### Grid

Example: `.container { display: grid; place-items: center; /* shorthand for align-items + justify-items */ }`. See other variants [here](resources/grid-variants.md).

### Absolute Positioning

Example: `.container { position: relative; } .centered { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); }`.

### Auto Margins

Example: `.block { width: 320px; margin-inline: auto; }`.
