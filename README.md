# Prashitha Umasekaran: Portfolio Website

A static, single-page portfolio (HTML, CSS, JavaScript). No build step, no paid services.

```
index.html   page content (all text and project cards)
style.css    design and responsive layout
script.js    mobile menu, scroll animation, footer year
assets/      project images (taken from the project repositories)
```

## Run locally
Open `index.html` in a browser. Or, for a local server: `python3 -m http.server 8000` and visit http://localhost:8000.

## Publish with GitHub Pages
1. On GitHub, create a new **public** repository named `Prashitha-Umasekaran.github.io` (gives you the URL `https://prashitha-umasekaran.github.io`). Any other name also works; the URL then ends with `/repo-name/`.
2. Upload all files and the `assets` folder so that `index.html` is at the repository root (use **Add file → Upload files**, then **Commit**).
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/ (root)`, then **Save**.
4. Wait 1–2 minutes and open the URL shown at the top of the Pages settings.
5. Add that URL to your LinkedIn and GitHub profiles.

## Update later
- **Project text:** In `index.html`, find the `<article class="card">` for the project and edit the paragraphs, the `.tags` list, or the link. Keep the *Limitations / Caveats* note accurate.
- **Screenshots:** Add the image to `assets/` (use a JPG/PNG under ~200 KB), then change the `<img src="assets/...">` and its `alt` text. Use only genuine screenshots of your own work. To make a text-only card, delete the `<img>` line and add `textcard` to the `body` div class (see the Cybersecurity Risk Governance card).
- **Experience:** Edit or copy an `<article class="exp">` block in the Professional Experience section. Delete the `<ul>` for entries without confirmed responsibilities. Only add details you can verify.
- **New project:** Copy an entire `<article class="card">…</article>` block and edit it.
- **Education status:** When you complete your MBA, change the status label in the Education section from "Currently pursuing" to "Completed" and remove the `now` class.
- **Contact:** Edit the `contact-list` in the Contact section of `index.html` (email uses a `mailto:` link, phone a `tel:` link).

## Image sources
- Credit Risk: `visuals/model_comparison.png`
- Wazuh: `documentation/Cybersecurity Project Architecture Flow.png`
- Ransomware: `cyber_kill_chain.png`
- Cyber Risk Governance: no image in the repository (the dashboard is a `.pbix` file), so it uses a text card.
