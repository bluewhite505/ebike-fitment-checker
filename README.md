# Fitment Evidence Checker

Static, dependency-free site prepared for GitHub Pages.

## Publish

1. Create a new public GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

No build command is required. Upload every file and all five report folders; the
folder names are the public URLs of the indexable evidence pages.

## Search indexing

- `robots.txt` allows crawling.
- `sitemap.xml` lists the homepage and all five report pages.
- Every page has a self-referencing canonical URL.
- Submit `https://bluewhite505.github.io/ebike-fitment-checker/sitemap.xml`
  in Google Search Console after publishing.

## Before launch

- Replace `fociva.tech@gmail.com` in `app.js` if submissions should go elsewhere.
- Add analytics only after choosing a provider.
- Treat all records as research evidence, not certified compatibility.
