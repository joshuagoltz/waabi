# Joshua Goltz — Portfolio

A single-page personal portfolio site, tailored for **strategic partnerships / OEM / corporate-development** roles in autonomy and frontier technology.

**Live site:** _add your GitHub Pages URL here once deployed_

---

## Deploy to GitHub Pages (5 minutes)

1. Create a new repository on GitHub.
   - For a site at `https://<username>.github.io`, name the repo exactly **`<username>.github.io`**.
   - For a project site at `https://<username>.github.io/portfolio`, name it anything (e.g. `portfolio`).
2. Upload `index.html` (and this `README.md` and `.nojekyll`) to the repo — drag-and-drop in the GitHub web UI works fine.
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**, select the `main` branch and `/ (root)` folder, and **Save**.
5. Wait ~1 minute, then refresh. Your site is live at the URL shown on that Pages screen.

### Command line (optional)
```bash
git init
git add .
git commit -m "Portfolio"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```
Then enable Pages in Settings as above.

---

## Custom domain (optional)
In **Settings → Pages → Custom domain**, enter your domain (e.g. `joshuagoltz.com`) and add the DNS records GitHub shows you at your registrar. GitHub will create a `CNAME` file automatically.

## Editing
Everything — content, colors, fonts — lives in **`index.html`**. No build step and no external dependencies — fonts (Roboto Serif for headlines, Inter for body) are self-hosted in the `fonts/` folder, with their open-font licenses alongside. Open it in any browser to preview locally.

- **Colors / theme:** the `:root` block at the top of the `<style>` section.
- **Résumé:** `Joshua-Goltz-Resume.pdf` is included and wired to the "Download résumé" buttons in the hero and contact sections. To swap it, replace that file (keep the same filename) — no HTML changes needed.

## Notes
- `.nojekyll` tells GitHub Pages to serve the files as-is (skips Jekyll processing). Safe to keep.
