# Dream 100 Prospecting — Website Redesigns

Free website redesigns built for Dream 100 / free deliverable prospecting. Each prospect gets their own subfolder. Hosted via GitHub Pages.

**Live site:** https://patelsk.github.io/zimmer-dds/

---

## Prospects

| Folder | Business | Location | Industry | Live URL |
|--------|----------|----------|----------|----------|
| [`/zimmer-dds/`](https://patelsk.github.io/zimmer-dds/) | Shawn L. Zimmer, DDS | Mount Pleasant, MI | Dentistry | [View Site](https://patelsk.github.io/zimmer-dds/) |

---

## Adding a New Prospect

1. Build the site with the correct base path:
   ```
   vite build --base=/<prospect-folder>/
   ```
2. Copy the built `dist/public/` contents into a new subfolder here
3. Remove `__manus__` folder and Manus-specific scripts from `index.html`
4. Add the prospect to the table above and to `index.html`
5. Commit and push — GitHub Pages auto-deploys in ~60 seconds

---

## Hosting

Deployed via **GitHub Pages** from the `main` branch root of `patelsk/patelsk.github.io`.
Each prospect's site is live at `patelsk.github.io/<prospect-folder>/`.
