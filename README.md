# Kingston Bahá’í Community website

A lightweight, responsive static website for GitHub Pages. It uses no build
tools or runtime dependencies.

## Publishing with GitHub Pages

1. Push the repository to GitHub.
2. In the repository, open **Settings → Pages** and select **Deploy from a
   branch**, then choose the `main` branch and `/ (root)` as the folder.
3. Keep the `CNAME` file in the repository root. In the domain's DNS settings,
   point `www.kingston.bahai.org.au` to `mgiusfredi.github.io` with a CNAME
   record. Configure a redirect from the bare domain if one is needed.
4. Once DNS has propagated, set `www.kingston.bahai.org.au` as the custom
   domain in **Settings → Pages** and enable **Enforce HTTPS** when available.

GitHub Pages serves the files in the repository root; no build step is needed.

## Keeping the information useful

- Update the email address in `index.html` if the community's current contact
  address changes.
- Review the content periodically and remove details that are no longer current.
- `styles.css` contains the visual styles and responsive layouts;
  `script.js` only handles the mobile menu and current year.
