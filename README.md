# Marmelade

One-page website for the Marmelade studio: map with parking, the base, 2nd floor plan, photos of the hall, and the price list for services and studio rental with a price calculator.

Source: Sami's InDesign design (PDF, 1920 × 8000 px).

## Structure

- `index.html`: the whole page (HTML, CSS and a short script that calculates the price list)
- `img/`: images taken from the PDF, WebP, each in two widths (1200 and 2400 px)
- `fonts/Vabedo.ttf`: price list typeface (wepfont.com)

The logo is a vector path inlined in `index.html`.

## Preview

No build step and no dependencies. Run a local server:

```bash
python3 -m http.server 8000
```

and open http://localhost:8000.

## Open questions

- The Unit column in the price list is empty. Add units, or remove the column?
- Contact details (address, phone, email) are missing.
- Vabedo licence for web use.
- Hosting and domain.
