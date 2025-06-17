# Snark Floats - Dev Notes & Style Guide (v4.0c)

Welcome to the wonderful world of sarcasm-structured design.

## 🔤 Fonts
- **Headers:** Raleway
- **Body:** Work Sans
- Google Fonts embedded via `<link>` in HTML `<head>`

## 🎨 Color Palette

| Color Name       | Hex       | Usage                              |
|------------------|-----------|-------------------------------------|
| Twilight Eggplant| `#2E003E` | Header background, footer           |
| Emerald Teal     | `#38B2AC` | Borders, buttons, highlight lines   |
| Warm Gold        | `#FFD700` | Dividers, outlines, TL;DR border    |
| Electric Rose    | `#FF4DB8` | Easter eggs, accents, hover states  |

## 🧱 Section Class Utilities

Add `.section`, then a modifier:
- `.section-teal`
- `.section-gold`
- `.section-rose`

These apply left borders and soft background fills.

## 🧩 TL;DR Blocks

Use `<details><summary>TL;DR</summary><ul>...</ul></details>`  
- Intended to be hidden rewards, not upfront spoilers  
- Styled with gold border and light background

## 🥚 HTML Easter Eggs

Examples hidden in:
- `index.html` and major section templates
- `style.css` with developer commentary
- Comments range from passive-aggressive to vaguely wise

## 📁 File Naming

Each ZIP is a snapshot. Always **overwrite** older files when deploying new versions.

## 📬 Questions?

Ask Hex. Or just yell into the void—results may vary.
