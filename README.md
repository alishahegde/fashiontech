# ANRCHSM Trend Database

This is a standalone public HTML version of the uploaded React file.

## What changed
- Converted the app into a single `index.html` file
- Kept the searchable/filterable trend database
- Removed the browser-side AI/API calls, so no login or secret key is required

## Publish on GitHub Pages
1. Create a GitHub repo
2. Upload `index.html`
3. Go to **Settings → Pages**
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**
5. Choose your main branch and `/root`
6. Save
7. GitHub will give you a public URL

## Notes
The original uploaded file was a React component with inline styling and a direct fetch call to Anthropic. That API-dependent functionality would not work as a public no-login page, so this version focuses on the public-facing database UI.
