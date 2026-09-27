# Flash Cars — Elementor Conversion Package

Source: `index.html` from `MitMike/wordpress-with-ai_xpro`.

## Pages
- Home
- About
- Inventory
- Sell Your Car
- Contact

## Import
1. Create the five WordPress pages.
2. Import each JSON file in `pages/` with Elementor.
3. Create the three WPForms listed in `forms/wpforms-map.json`.
4. Replace the placeholders `HOME_SEARCH`, `SELL_VALUATION`, and `CONTACT_INQUIRY` with the real WPForms IDs.
5. Import the header/footer JSON as Elementor templates and save/assign them through XPRO.
6. Create the `Flash Cars Primary` menu.
7. Set Home as the static homepage.
8. Replace remote Unsplash URLs with Media Library images for production.

## Conversion rules
- Elementor Containers only.
- No Inner Sections.
- No Atomic Elements.
- No Elementor Pro widgets.
- Source SPA routes are converted to five real WordPress pages.
- Source JS filtering is intentionally not embedded in a large HTML widget; inventory cards remain editable.
- Forms are recreated in WPForms.

## Important
The supplied header/footer files are Elementor-compatible template content intended for use with XPRO. XPRO-specific proprietary export metadata can vary by installed XPRO version, so save/assign them through the local XPRO workflow after import.