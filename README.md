# Portfolio: Prapathomsit Attapakkanon

A static single-page site with no build step. To preview it locally:

    python3 -m http.server 5220   # then open http://localhost:5220

## Making edits
- **Links**: the `LINKS` object in the script at the bottom of `index.html`
- **Add a project**: add one object to the `PROJECTS` array. The filter buttons are generated from `CATEGORIES`
- **Screenshots**: save files into `assets/screens/` using these names: `trace-viewer.png`, `sheets-report.png`, `checkout-bug.png`, `spec-code.png`. A missing file is skipped automatically.
- **Profile photo**: `assets/profile.jpg`
- **Colors**: the `:root` block in the `<style>` tag

## Deploying
- **GitHub Pages**: push to a repo named `Prapathomsit.github.io`, or any repo with Settings → Pages → Deploy from branch `main` / root
- **Vercel**: import the repo with Framework set to "Other". No build command is needed.
