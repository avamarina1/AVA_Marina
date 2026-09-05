# AVA Marina — reference-match fix

This version fixes the missing hero image seen on GitHub Pages.

Key fix:
- Hero is now `assets/hero.jpg`
- Homepage uses the image as a CSS background
- The path and filename are simple and case-safe for GitHub Pages
- Hero height is set to match the reference first-screen composition more closely

## Update the live GitHub site

In the `AVA_Marina` repository:
1. Upload/replace `index.html`
2. Upload/replace `styles.css`
3. Open the `assets` folder and upload `hero.jpg`
4. Commit the changes
5. Wait around 1–3 minutes, then hard-refresh the live page with Ctrl+F5

Do not upload only the ZIP. The files inside it must be in the repository.
