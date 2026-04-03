<img width="1440" height="810" alt="Screenshot 2026-04-03 at 8 46 47 AM" src="https://github.com/user-attachments/assets/faf111d3-6690-45c5-beb7-08d8704946ab" /># Modi Lipi Translator

Convert Devanagari (Marathi) text to historic Modi script — and back — directly in your browser. No installation, no API key, no internet required after the page loads.

[Uploading Screenshot 2026-04-03 at 8.46.47 AM.png…]


**[Live Demo →] https://hardik13190.github.io/Modi-Lipi-Translator/**

---

## What it does

- Converts Devanagari (Marathi) ↔ Modi script instantly
- Full Unicode 17.0 accuracy — every consonant, vowel, matra, virama, anusvara, visarga, digit, and punctuation mark mapped correctly
- Works completely offline — pure client-side JavaScript, no server, no API
- UI available in English, हिंदी, and मराठी
- Includes a full Modi script reference chart (vowels, consonants, matras, signs, digits)

## How to use

1. Download or clone the repo
2. Open `index.html` in any browser
3. Install [Noto Sans Modi](https://fonts.google.com/noto/specimen/Noto+Sans+Modi) font for correct display of Modi characters

That's it. No npm, no build step, nothing to install.

## Technical details

- Devanagari Unicode block: U+0900–U+097F
- Modi Unicode block: U+11600–U+1165F
- All mapping sourced from Unicode Standard 17.0 (U0900.pdf and U11600.pdf)
- Fonts: [Laila](https://fonts.google.com/specimen/Laila) for Devanagari, [Noto Sans Modi](https://fonts.google.com/noto/specimen/Noto+Sans+Modi) for Modi script
- Single HTML file — no dependencies, no frameworks

## Credits

- Unicode mappings: [Unicode Standard 17.0](https://www.unicode.org/charts/)
- Modi encoding proposal: Anshuman Pandey, University of Michigan (ISO/IEC JTC1/SC2/WG2 N4034)
- Fonts: Google Fonts

## License

MIT — free to use, modify, and share.
