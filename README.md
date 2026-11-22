# Card Forge — Turn into a person card

A single-page web app that turns your photo into a trading card.

## Features
- **Card styles:** Baseball (sports card), Duel Monster, Creature Battle, Playing Card (poker), Photo Minimal
- **Real card sizes:** MLB/Topps 2.5 × 3.5 in, standard TCG 63 × 88 mm (Pokémon/Magic), Japanese size 59 × 86 mm (Yu-Gi-Oh!), mini, jumbo or custom
- **Photo editing:** upload or take a photo, drag to position, zoom, brightness/contrast/saturation, black & white, vintage
- **Front and back text** in any language (CJK text wraps correctly)
- **Design:** colours and team combos, fonts, holo/gold/sparkle foil, rarity marks, frame patterns, emoji and text stickers, stat icons (ATK, DEF, HP, SPD, MAG, LV)
- **My cards:** save many different cards (kept in the browser via IndexedDB), set copies per card
- **Print sheets:** A3 / A4 / A5 / US Letter PDF with cards at exact size (never scaled), mixed sizes on one sheet, back pages for double-sided printing, crop marks, optional 3 mm bleed
- PNG and PDF export at 300 dpi (standard) or 600 dpi (extra sharp)

## Run
Open `index.html` in a browser. No build step. The PDF export loads jsPDF from cdnjs, so it needs an internet connection.

The official MLB, Pokémon and Yu-Gi-Oh! logos and card designs are not used; the styles are original designs in a similar spirit.

## Versions
- **v1.2.0**: Playing Card style (poker & bridge sizes, A–K + Joker, 4 suits, photo / classic face card / suit-symbol layouts, patterned back)
- **v1.1.0**: 300 / 600 dpi export quality; photos kept at up to 2400 px
- **v1.0.0**: first release (card styles, sizes, stickers, stat icons, My cards, A3/A4/A5 print sheets)
