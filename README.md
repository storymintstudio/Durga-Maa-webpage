# Durga Ashtami Webpage — Storymint Studio

A single-file festive webpage for Durga Ashtami. Pure HTML, CSS and JavaScript. No framework, no build step.

## Run it
Open `index.html` in any browser. To publish, upload the file to any static host (GitHub Pages, Netlify, Vercel).

## Sections
1. **Opening:** Maa Durga hero image, Hindi and English greetings, falling petals and 🌷 flowers, golden particles.
2. **Divine Blessings:** Sanskrit mantra with its English meaning, and four blessing cards.
3. **Receive a Blessing:** each click shows a new Hindi or English blessing.
4. **Maa Durga with her Lion:** framed illustration.
5. **Pass on a Little Light:** Share button (phone share sheet) and Copy wish.
6. **Footer:** Storymint Studio branding.

A music button on the right side turns the festive instrumental on and off.

## Customise
- **Blessings:** edit the `B` array in the script.
- **Share wish text:** edit the `wish` variable.
- **Colours:** change the CSS variables at the top of `:root`.
- **Music:** the `M` array is the melody (frequencies in Hz) and `SP` sets the tempo.
- **Images:** replace the base64 `src` of `.maa` and `.maa2`, or point them to image files.

## Notes
- Music starts only after the first tap, because browsers block autoplay.
- Fonts (Cormorant Garamond, Tiro Devanagari Hindi, UnifrakturCook) load from Google Fonts and need internet.
- Both illustrations come from other artists. Get permission or give credit before posting the page publicly.
- Animations switch off automatically for visitors who prefer reduced motion.
