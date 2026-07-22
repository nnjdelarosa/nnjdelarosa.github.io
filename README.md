# Portfolio — Nathan Dela Rosa

Single-page portfolio site. Plain HTML/CSS/JS, zero build step, ready for GitHub Pages.

## Publish at `<username>.github.io`

1. Create a **public** repo on GitHub named exactly `<your-username>.github.io` (e.g. `natedelarosa.github.io`).
2. Push these files:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. That's it — repos named `<username>.github.io` deploy to GitHub Pages automatically. Live within a minute or two at `https://<your-username>.github.io`.

   (If it doesn't appear: repo **Settings → Pages** → Source: *Deploy from a branch* → `main` / root.)

## Alternative: project site

If you'd rather keep your `<username>.github.io` slot free, name the repo anything (e.g. `portfolio`), enable Pages the same way, and it deploys to `https://<your-username>.github.io/portfolio`.

## Editing

Everything lives in `index.html` — content, styles, and scripts. Sections: hero stats, About, Skills (years-of-experience bars), How I Lead Delivery, Experience timeline, Project engagements, Education, Contact.
