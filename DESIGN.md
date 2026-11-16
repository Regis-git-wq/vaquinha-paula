# DESIGN.md — Vaquinha da Paula (paulaprotese-vaquinha.com.br)

Feeling: warm, hopeful, trustworthy. A real person's story, not a medical
or charity-template page. The photo (stand-up paddle on the water) sets
the tone: water + sun. Light mode only.

Direction chosen without real-site references (UXKIN not connected).

## Color
| Token | Value | Role |
|---|---|---|
| --sand-50 | #FBF7F1 | page background |
| --sand-100 | #F3EBDF | alternate section background, cards |
| --sand-300 | #DCCDB8 | borders, dividers |
| --ink-500 | #6B6259 | secondary text (5.6:1 on sand-50) |
| --ink-900 | #2A2420 | body text and headings |
| --primary | #0F6B6B | buttons, links, focus ring (deep teal, water) |
| --primary-dark | #0B5252 | button hover |
| --accent | #C2541F | one highlight only: amount raised and progress bar (4.6:1 on sand-50) |
| --success | #276B43 | "copiado!" confirmation |
| --on-primary | #FFFFFF | text on primary |

## Typography
- Headings: **Fraunces** (serif, 600). Warm and personal.
- Body/UI: **Nunito Sans** (400, 700). Friendly, very legible.
- Scale (px / line height): 14/1.5 · 16/1.6 (body min) · 18/1.6 · 22/1.35 · 28/1.25 · 36/1.15 · 48/1.05 (hero desktop).
- Measure: 60–70ch for story text.

## Spacing
8-based: 4, 8, 12, 16, 24, 32, 48, 64, 96. Section padding 64 (mobile) / 96 (desktop).
Content width 1120px; text column 680px.

## Shape and depth
Radius: 8 (inputs, small), 16 (cards, photo), 999 (pill buttons).
One shadow: 0 8px 24px rgba(42,36,32,.08) for the donation card only.

## Components
- Primary button: teal pill, white text, 48px tall; hover darker; focus 3px ring #0F6B6B offset 3px.
- Secondary button: transparent, 2px teal border.
- Copy field: monospace value + "Copiar" button; shows "Copiado!" in success color.
- Card: sand-100, radius 16, no border.
- Footer: ink-900 background, sand text.

## Imagery and icons
One real photo of Paula (supplied). Icons: inline SVG line icons, 1.75px stroke, currentColor. No emoji as icons.
