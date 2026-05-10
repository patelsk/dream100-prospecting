# Dream 100 Prospecting — Website Redesigns

Free website redesigns built for Dream 100 / free deliverable prospecting. Each prospect gets their own subfolder. Hosted via GitHub Pages.

**Live site:** https://patelsk.github.io/dream100-prospecting/

---

## Prospects

| Folder | Business | Location | Industry |
|--------|----------|----------|----------|
| [`/zimmer-dds/`](https://patelsk.github.io/dream100-prospecting/zimmer-dds/) | Shawn L. Zimmer, DDS | Mount Pleasant, MI | Dentistry |

---

## Adding a New Prospect

1. Build the site with the correct base path:
   ```
   vite build --base=/dream100-prospecting/<prospect-folder>/
   ```
2. Copy the built `dist/public/` contents into a new subfolder here
3. Remove `__manus__` folder and Manus-specific scripts from `index.html`
4. Add the prospect to the table above and to `index.html`
5. Commit and push — GitHub Pages auto-deploys

---

## Hosting

Deployed via **GitHub Pages** from the `main` branch root.
