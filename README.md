# Certificate Details Webpage (Demo)

A single self-contained `index.html` page: a blue "Verify" hero header with responsive navigation, a certificate-details card with a checkmark watermark, and a dark footer — all built to match the reference screenshots.

**This is a demo page only** — fictional branding ("Demo Infotech"), fictional certificate data, a fictional footer address, and no real verification logic. A "DEMO — NOT AN OFFICIAL CERTIFICATE" line sits above the card.

## Certificate data shown
```
CIN:              PIT/AUG26/05563
Name:             Sarfaraz Malik
Internship Track: Web Development
College:          Adgips
Start Date:       01/08/2026
End Date:         30/09/2026
Issue Date:       08/10/2026
```

## Stack
Plain HTML + CSS + vanilla JS, no build step, no dependencies besides the Google Fonts "Inter" stylesheet. All icons (logo, field icons, social icons, scroll-to-top arrow) are inline SVG — no icon-font dependency.

## Structure
- **Header/hero**: solid blue background, white circular logo badge + "DEMO INFOTECH" wordmark, large centered "Verify" title.
- **Nav**: on phones/tablets (< 1024px) the hamburger opens a full-width dropdown (Home / About / Internships / FAQs / Contact / Verify) under the logo row. At **≥ 1024px** ("laptop" width) it switches to an inline row next to the logo and the hamburger disappears.
- **Card**: white, bordered, rounded, subtle shadow, over a lavender band that fades to white; icon + `Label: value` rows with thin dividers; a low-opacity green checkmark watermark centered behind the text.
- **Footer**: dark background with two soft teal/blue gradient blobs, brand blurb, About Us / Social / Our Services / Other Info columns, and a bottom legal-links bar (Privacy policy, Code of Conduct, Terms & Conditions, Returns).
- **Scroll-to-top**: blue square button, `position: fixed` bottom-right of the viewport (visible over any section, including the footer); smooth-scrolls to top on click.

## Responsive behavior
- **< 360px**: tighter side padding, smaller heading.
- **360–767px**: phone layout, hamburger dropdown nav, single-column footer.
- **640–1023px**: footer grows to 3 columns; nav still a dropdown.
- **≥ 1024px**: nav becomes an inline row (no hamburger); footer becomes 5 columns; larger type scale throughout.

## Run it
Open directly in a browser — no server needed:
```
file:///D:/industry internship sarfaraz/index.html
```

## Notes
- Branding, logo mark, footer address, and all certificate values are fictional/demo per the request — this does not reproduce or impersonate the real Prodigy InfoTech site, despite following its layout for the header/nav/footer design.
