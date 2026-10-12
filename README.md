# Reviewer Generator — Vercel static deployment

## Project structure
- `index.html` — Vercel entry page
- `css/styles.css` — extracted styles
- `js/pdfjs-worker-bundle.js` — original bundled PDF.js worker code
- `js/pdfjs-viewer-bundle.js` — original bundled PDF.js code
- `js/reviewer-generator.js` — reviewer generation logic
- `js/app.js` — UI and interactions

## Deploy to Vercel
1. Upload/push the contents of this folder to the root of a GitHub repository.
2. In Vercel, import that repository.
3. Choose **Other** as the framework preset if prompted.
4. Leave Build Command empty and Output Directory as `.` (or leave the default if Vercel detects a static site).
5. Deploy.

Make sure `index.html`, `css/`, and `js/` are all at the repository root level. Do not put the whole project inside an extra nested folder unless you set that folder as Vercel's Root Directory.
