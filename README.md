# WebQSLForge  
**ADIF → ready-to-print QSL cards, the lazy way™**

![WebQSLForge in action](https://via.placeholder.com/800x400/2c3e50/ffffff?text=WebQSLForge+-+QSL+Made+Too+Easy)  
*(replace with a real screenshot when you feel like it)*

## What is this thing?

A tiny, single-file HTML tool that eats your ADIF log  
→ lets you design a good-looking QSL card template  
→ auto-sorts your QSOs (especially nice for bureau)  
→ spits out a PDF ready to print, cut, and send. Belive me when i say that i have testet this with 1354 qso at once.

No installation.  
No account.  
No creepy app asking for your location, contacts and soul.

Just open the file in your browser and feel like a 3026 QSL wizard.

## Why bother with yet another QSL tool?

Because manually sorting bureau cards in 2026 still feels like sending smoke signals with a damp match.

WebQSLForge does the heavy lifting:

- Reads standard ADIF files
- Pulls fresh prefix & bureau info straight from [github.com/rSignal86/QSL-BY-BUREAU](https://github.com/rSignal86/QSL-BY-BUREAU)
- Filters and sorts bureau-only destinations automatically (the rest you can pretend you'll do via LoTW and qrz… later)
- Drag & drop layout — scroll wheel resizes text, right-click pans background, middle-click rotates (yes, really)
- Smart bureau sorting so the post office doesn’t hate you
- Exports 4-up A4 PDF — print, cut, curse when you glued it upside down anyway

## Features (with a pinch of self-roast)

- **Single HTML file** — works on Windows, Mac, Linux, iPad, your grandma’s 2011 netbook
- **GDPR-compliant by accident** — stores nothing, sends nothing, judges nothing (except maybe your grid square typos)
- **Mouse-first design** — drag text, zoom background, rotate image, resize fonts with scroll wheel
- **Bureau mode** — shows only countries that still accept bureau cards (others go to the “maybe next year” pile)
- **Three included fonts** — serious, typewriter-vintage, or “old military RTTY receiver” vibes
- **Personal message field** — perfect for your classic “73 de [your call] – still waiting for your card from 2019”

## Installation? lol no

1. Download [`WebQSLForge.html`](WebQSLForge.html)
2. Double-click (or drag into Chrome / Firefox / Edge / whatever)
3. Done. You are now officially forging QSLs.

Pro move: Upload it to your club website → let everyone use it → claim you wrote it.

## Quick Start (real lazy mode)

1. Click the big yellow ❓ **OPEN HELP / WIKI** button
2. Upload a background image (optional but classy)
3. Upload your `.adi` / `.adif` file
4. Pick font, colors, box opacity, border style…
5. Drag stuff around on the preview until it looks decent
6. Check **Bureau Only / Sort** if you want to be a model citizen
7. Hit **SAVE TABLE TO PDF**
8. Print → cut → realise you put the callsign upside down anyway

## Known limitations (full honesty mode)

- Needs internet once to fetch the prefix list (then works offline)
- Very exotic prefixes may show as “Unknown” — blame DXCC, not the code
- PDF file size grows if you have 9,000 FT8 QSOs on 2 meters
- No undo button — but there **is** a **Reset Layout** button

## Standing on the shoulders of giants

WebQSLForge is heavily inspired by — and builds directly on — the legendary **QSL BY BUREAU** project by **LB6QJ**.  
We just wrapped it in more drag-and-drop laziness and print-friendly cosmetics.


## License

MIT — do whatever you want i give a fuck.

73 de LB6QJ 
and respect to everyone still sending paper QSLs in 2026 — you are the real MVPs
