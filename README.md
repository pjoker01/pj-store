# PJ Store — Premium Storefront

A responsive, premium-style storefront and browser-based Store Studio prototype.

## Files
- `index.html` — storefront, product catalogue, search, category filters, bag and WhatsApp order summary.
- `admin.html` — visual product management interface.
- `styles.css` — shared responsive design system.
- `app.js` — storefront and cart behaviour.
- `admin.js` — catalogue editing, image uploads and browser settings.

## Run it
Open `index.html` locally or deploy the repository as a static site on a host such as Vercel or Netlify. Open `admin.html` to manage products in the same browser.

## Important: starter version has no backend
This is intentionally a no-backend first version. Products, uploaded photos and the WhatsApp contact number are stored in that browser's `localStorage`. That means:
- Edits do not sync to other devices or automatically update a hosted storefront for customers.
- Clearing browser data can remove your edits.
- There is no protected admin login, database, image storage service, payment processing, order database or inventory synchronisation.
- Do not enter secrets or treat Store Studio as a secure production admin.

To launch as a real managed store, connect a backend/database (for example Supabase), secure admin authentication, cloud image storage and server-side order handling. Add a payment provider only when ready. WhatsApp checkout currently prepares an order message for manual confirmation; it does not charge customers.

## Configure WhatsApp
Open Store Studio and enter the store phone number with country code, digits only (South Africa example: `27XXXXXXXXX`). This setting is local to the browser in this starter version.

## Product photos and prices
The included products, photos and prices are sample catalogue content. Replace them with your actual inventory before presenting the store as a real shop. Use image files under 1.5 MB for the browser-based image upload feature.

## Branding and visual assets
Fonts are loaded from Google Fonts and sample photography from Unsplash, so an internet connection is required for those external assets.
