
# Floppy‑Eared Bunny (HTML + CSS)

Tiny animated bunny (flapping ears, blinking eyes, waving paw).

## Structure
```text
bunny/
├─ index.html
└─ style.css
```

## Quick Start
1. Save HTML → `index.html`, CSS → `style.css`.
2. In `<head>` add:
```html
<link rel="stylesheet" href="style.css">
```
3. Open `index.html` in a browser.

## Customize
- Size: `.bunny { width:200px; height:240px; }`
- Background: `body { background:#fef4ea; }`
- Speeds: `.ear { animation: flap 2s ... }`, `.eyeball { animation: blink 3s ... }`, `.right-arm { animation: wave 2.2s ... }`
- Colors: `.carrot` (orange), `.leaf` (green), borders `#ccc`.

## Notes
- Keep flex centering on `body`.
- Keyframe names must match: `flap`, `blink`, `wave`.

