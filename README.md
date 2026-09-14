# EliphEdge Website

Premium, responsive portfolio website for **EliphEdge**, the personal graphic design brand of **Adeyinka Elijah Ayanfejesu**, Oyo State, Nigeria.

## Run locally

This is a dependency-free static website. Open `index.html` directly in a browser, or serve the folder with any static web server.

Example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

- `index.html` — main page and semantic content
- `css/styles.css` — responsive premium visual system
- `js/script.js` — navigation, portfolio modal, FAQ, testimonial carousel and contact-to-WhatsApp form
- `assets/images/` — the 8 uploaded EliphEdge portfolio artworks, copied without replacement
- `assets/favicon.svg` — simple site favicon

## Contact form

The form intentionally does **not** pretend to have a backend. It validates the project brief, then opens WhatsApp to `+234 905 167 5882` with the form details. If a reference file was selected, the visitor is told to attach it manually in WhatsApp.

For a production deployment with stored submissions, connect the form to a real service/API and update the `setupForm()` function in `js/script.js`.

## Editable content

Portfolio metadata, services, testimonials and FAQs are centralized near the top of `js/script.js` for easy editing. Testimonials are clearly marked placeholders because no real testimonials were supplied.

No fixed prices, awards, client counts, years of experience, certifications or other unsupported claims are included.
