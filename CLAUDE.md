# Marmelade

One-page website for the Marmelade studio (studio rental for shoots). Sami owns this repo and makes the design and content decisions. **Talk to Sami in English.** The site copy is in English.

- The source of truth for the look is Sami's InDesign PDF (1920 × 8000 px). Colours: navy `#002166`, pink `#FF9EAB`. The price list uses Vabedo (`fonts/`), the logo is the vector path from the PDF, inlined in `index.html`.
- Static site, no build step, no dependencies: `index.html`, `img/`, `fonts/`.
- The price list multiplies Rate by Quantity per row and sums a Total row. The Total row and the editable Quantity cells are web additions, not in the PDF.
- Never invent content (prices, contacts, units). List gaps under "Open questions" in `README.md`.
- Quality floor: works from 360 px, no horizontal page scroll, no word split inside table headers, visible keyboard focus, alt text on every image, pinch zoom never disabled.
