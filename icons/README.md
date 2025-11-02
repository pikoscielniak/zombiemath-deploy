# PWA Icons

## Required Icon Sizes

Generate the following icons for the ZombieMath PWA:

### Standard Icons (PNG format)
- `icon-16x16.png` - Browser favicon
- `icon-32x32.png` - Browser favicon
- `icon-72x72.png` - Android Chrome
- `icon-96x96.png` - Android Chrome
- `icon-128x128.png` - Android Chrome
- `icon-144x144.png` - Windows tiles
- `icon-152x152.png` - iOS Safari
- `icon-192x192.png` - Android Chrome (minimum)
- `icon-384x384.png` - Android Chrome
- `icon-512x512.png` - Android Chrome (recommended)

### Maskable Icons
Maskable icons have safe zones to ensure they look good on all platforms:
- `icon-maskable-192x192.png` - Android adaptive icon
- `icon-maskable-512x512.png` - Android adaptive icon

Maskable icons should have:
- Icon content centered within a 80% safe zone
- Full 100% area can be used for background color
- No transparent edges (fill to edges with solid color)

### Apple Specific
- `apple-touch-icon.png` (180x180) - iOS home screen icon

## Design Guidelines

### Theme
- Primary color: Purple (#6a0dad)
- Background: Dark purple (#1a0b2e)
- Include zombie and/or brain emoji/graphic
- Maintain kid-friendly, cartoony aesthetic
- Ensure high contrast for visibility

### Icon Content Ideas
- 🧠 Brain emoji with 🧟 zombie
- Calculator with zombie theme
- Math symbols (×, +, =) with playful zombie elements
- Combination of education + fun zombie theme

## Tools for Icon Generation

### Online Tools
- [PWA Asset Generator](https://github.com/elegantapp/pwa-asset-generator)
- [RealFaviconGenerator](https://realfavicongenerator.net/)
- [Maskable.app Editor](https://maskable.app/editor)

### Command Line
```bash
# Using pwa-asset-generator (npm package)
npx pwa-asset-generator source-icon.png ./icons --icon-only --favicon --type png
```

### Manual Creation
Use any graphics editor (GIMP, Figma, Photoshop, Inkscape) to create:
1. Create a base 1024x1024 SVG or high-res PNG
2. Export to all required sizes
3. For maskable icons, ensure 80% safe zone

## Current Status
⚠️ **TODO**: Icons need to be created. Currently using placeholder paths.

Once icons are created, place them in this directory (`src/assets/icons/`).
