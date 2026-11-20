# MOBILEWALA Kathlal website
Plain HTML/CSS/JS. No build step, no API keys. Works on GitHub Pages.

## Folders
- `index.html` page · `css/style.css` styles · `js/main.js`, `js/theme.js` behaviour
- `js/products.js` **the file you edit** (brands, featured mobiles, gallery)
- `assets/images` photos · `assets/videos` videos · `assets/logo` your logo · `assets/brands` brand logos

## Run in VS Code
1. Install VS Code, then the **Live Server** extension.
2. File > Open Folder > `MOBILEWALA-WEBSITE`.
3. Right-click `index.html` > Open with Live Server.

## Deploy on GitHub Pages
1. Create a GitHub account, then New repository (Public), e.g. `mobilewala-kathlal`.
2. Upload all files so `index.html` is at the top level (Add file > Upload files > commit).
3. Settings > Pages > Source: Deploy from a branch > `main` / `(root)` > Save.
4. After about a minute your site is at `https://YOUR-USERNAME.github.io/mobilewala-kathlal/`.

## Update content
- **Add a featured mobile:** put its photo in `assets/images/products/`, then add an entry to `products: []` in `js/products.js` (an example is in the file). Prices are never shown; each card links to WhatsApp with the model name.
- **Add photos/videos:** copy files into `assets/images` or `assets/videos`, then add a line to `gallery` in `js/products.js`.
- **Add an official brand logo (HMD, Redmi, Nothing, Realme):** save it in `assets/brands/` and set `logo: "assets/brands/hmd.svg"` for that brand.
- Keep file names lowercase with no spaces. Commit and push; the site refreshes in about a minute.
