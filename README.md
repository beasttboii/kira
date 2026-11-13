# ViewerGuide — WhatsApp HTML Viewer explainer

A responsive, standalone website that redesigns and summarizes the WhatsApp Help Center article about its HTML web viewer.

## Files
- `index.html` — page content and structure
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and current year

## Preview locally
Open `index.html` in a browser.

## Publish free with Cloudflare Pages (Direct Upload)
1. Sign in to Cloudflare (create a free account if needed).
2. In the dashboard, open **Workers & Pages**.
3. Choose **Create application** → **Pages** → **Upload assets** (wording may vary).
4. Give the project a name, such as `viewer-guide`.
5. Upload the three website files (`index.html`, `styles.css`, `script.js`) or upload the ZIP if the dashboard offers ZIP upload.
   - If ZIP upload is not accepted, unzip this package first and upload the folder's contents.
6. Deploy. Cloudflare will provide a free address similar to `https://viewer-guide.pages.dev`.

## Notes
- This is an independent educational redesign, not an official WhatsApp or Meta website.
- The article is summarized in original wording; the official source is linked in the page.
- Google Fonts are an optional external enhancement. The page has sensible system-font fallbacks if they cannot load.
- No API key or backend is required for this static website.
- To update the site, upload the revised files to the same Cloudflare Pages project.
