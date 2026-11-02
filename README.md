# Bloom & Co. Artisan Bakery Website

A responsive, multi-page website concept for Bloom & Co., a boutique artisan bakery specialising in handmade breads, pastries and personalised celebration cakes.

## Project pages

- `index.html` — homepage, featured products, daily-specials section and calls to action.
- `about.html` — bakery story, values and brand introduction.
- `menu.html` — sample product menu, category filters and live search.
- `enquiry.html` — custom cake, event and bulk-order enquiry form with client-side validation and a response summary.
- `gallery.html` — responsive image gallery with a lightbox, next/previous controls and keyboard support.
- `contact.html` — general contact form that prepares an email draft, contact details area and interactive Leaflet map with address search.

## Technologies

- HTML5 semantic elements
- CSS3, responsive media queries and reduced-motion support
- Vanilla JavaScript for DOM interaction, filtering, validation and lightbox
- Leaflet and OpenStreetMap for the interactive map
- Google Fonts for typography

## Run locally

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Run `index.html` with the Live Server extension, or use a local web server.
4. Internet access is required for externally hosted fonts, images, map tiles and the Leaflet library.

## Important setup before publishing

This is a front-end academic project. The enquiry form currently validates the form and displays a summary in the browser; it does **not** send or store an order. Connect a secure backend or form-processing service before accepting real customer enquiries.

The contact form opens the visitor's default email application. In `js/main.js`, replace `hello@example.com` with the bakery's real monitored email address.

The bakery's real address, telephone number and opening hours were not included in the supplied business proposal. Add verified details to `contact.html` and the footer before launch. The map deliberately asks the visitor to search the real address instead of displaying an invented business location.

Menu names and prices are illustrative sample content for the website build. Confirm actual products, prices, availability and allergen information with the bakery before publication.

Replace `https://www.example.com` in each page's canonical link, `robots.txt` and `sitemap.xml` with the final domain. Add the bakery's genuine social links and original product photography where available.

## SEO and accessibility

- Unique page titles and meta descriptions
- Relevant keyword phrases and semantic heading structure
- Descriptive image alternative text
- Canonical URL placeholders, `robots.txt` and `sitemap.xml`
- Responsive mobile-first layouts and keyboard-accessible controls
- Skip link, form labels, validation feedback and reduced-motion preference

Meta keywords are included to match the assignment brief, but modern search engines generally do not use the keywords meta tag as a ranking signal. Useful page content, descriptive titles, local business information and good performance are more important.

## Suggested Git commit history

Use multiple commits as the project develops, for example:

1. `Create initial bakery website structure`
2. `Add responsive shared stylesheet and navigation`
3. `Build bakery homepage and story page`
4. `Add searchable menu and product categories`
5. `Implement custom order form validation`
6. `Add gallery lightbox and keyboard controls`
7. `Add contact form and interactive address map`
8. `Add SEO metadata, robots and sitemap`
9. `Update README and prepare deployment`

## Changelog

### Part 3 — Functionality and SEO
- Added JavaScript-powered mobile navigation with an accessible expanded state.
- Added dynamic menu filtering by product category and text search, including a live result count and no-results message.
- Added a gallery lightbox with image captions, previous/next navigation, Escape-to-close and left/right keyboard controls.
- Added custom-order form validation for customer details, contact format, order type, date, quantity, description and consent. The form displays a clear response summary after successful validation.
- Added contact-form validation and email-draft generation through the visitor's default mail application. The recipient is a placeholder and must be replaced.
- Added an interactive Leaflet map with OpenStreetMap tiles and address lookup. No unverified bakery coordinates are hard-coded.
- Added responsive layouts for desktop, tablet and mobile, hover/focus states and reduced-motion support.
- Added unique page titles, meta descriptions, keyword phrases, canonical URL placeholders, descriptive image alt text, `robots.txt` and `sitemap.xml`.
- Added page navigation, calls to action, product descriptions and explanatory content across all six pages.

### Part 2 feedback updates
- No lecturer feedback for Part 2 was included in the supplied material. Record the actual corrections requested by the lecturer here before final submission; do not claim feedback changes that have not been made.

## Deployment

The website can be deployed as a static site using Netlify or GitHub Pages. Publish the project root folder so all six HTML pages, the `css` and `js` folders, `robots.txt` and `sitemap.xml` are included.

## References

- Leaflet (n.d.) *Leaflet — an open-source JavaScript library for interactive maps*. Available at: https://leafletjs.com/ (Accessed: 2 November 2026).
- OpenStreetMap contributors (n.d.) *OpenStreetMap*. Available at: https://www.openstreetmap.org/ (Accessed: 2 November 2026).
- Google (n.d.) *SEO Starter Guide*. Available at: https://developers.google.com/search/docs/fundamentals/seo-starter-guide (Accessed: 2 November 2026).
- MDN Web Docs (n.d.) *HTML forms: validation*. Available at: https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation (Accessed: 2 November 2026).
- MDN Web Docs (n.d.) *Document Object Model (DOM)*. Available at: https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model (Accessed: 2 November 2026).
