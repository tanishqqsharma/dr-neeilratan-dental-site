# Dr Neeilratan Dental Clinic — Static Elementor-ready prototype

## Files
- `index.html` — complete home page with doctor, services, technology, reviews, hours, map and calls to action.
- `services.html`, `technology.html`, `about.html`, `gallery.html`, `contact.html`, `book-appointment.html` — separate URLs for the multi-page structure.
- `custom.css` — named component classes and all non-Tailwind styling.
- `script.js` — mobile menu, smooth anchor scrolling, detail-page scrollspy, review controls, reveal animation and demo form feedback.

## Design system
The palette and component system are documented at the top of `custom.css` and in `DESIGN_SYSTEM.md`.

## Elementor conversion notes
HTML comments mark intended Elementor Sections, Columns, Inner Sections, and native Widgets. The contact form is intentionally static HTML inside a block labelled `EL:WIDGET:Text Editor`, matching the requested exception.

## Google Sheets form
The prototype does not send personal data. For production, connect a consent-reviewed Google Apps Script Web App endpoint or a WordPress form plugin that supports Google Sheets. Do not publish a script endpoint without validation, spam protection, and a privacy notice.

## Photography
Stock photographs elsewhere on the site are placeholders hotlinked from Unsplash. Replace the gallery images and doctor portrait with real images of Dr Neeilratan Chauhan's clinic before launch. Technology images are original locally stored vector illustrations, not photographs of the clinic's actual machines.

The original illustrations are used consistently in both the home technology cards and the technology detail page. Replace them with photographs of the clinic's actual machines when those are available.

## Responsive behavior

The stylesheet includes dedicated breakpoints for wide tablets, tablets, small tablets, mobile, compact mobile, and extra-small screens. The header switches to an accessible mobile menu, multi-column grids collapse progressively, detail-page side menus become horizontally scrollable, forms avoid iOS input zoom, maps and media resize fluidly, and CTA buttons become full-width where needed.
