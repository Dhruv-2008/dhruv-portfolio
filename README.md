# Dhruv Gandhi — Portfolio Site

A static, no-build-step personal site (HTML/CSS/JS only) — ready to deploy on
GitHub Pages or Netlify.

## Structure
```
index.html      → all page content
css/style.css   → styling (flight-computer / blueprint theme)
js/script.js    → mobile nav toggle + footer year
```

## Before you deploy — a few placeholders to update
- **Email**: replace `hello@dhruvgandhi.dev` (appears twice — hero contact button and footer) with your real email.
- **GitHub link**: the footer links to the AI-DJ-WEB-APP repo — add your GitHub profile link too if you have one.
- **LinkedIn / other socials**: none were in your CV, so none are linked. Add a link in the footer (`footer-links` in `index.html`) if you'd like.
- **Photo**: the hero currently shows a "DG" monogram inside the HUD frame instead of a photo. To swap in a real photo, replace the `.hud-avatar` div in `index.html` with an `<img>` tag pointing to a photo in `assets/`.

## Deploy on GitHub Pages
1. Create a new GitHub repo (e.g. `dhruv-portfolio`).
2. Push these files to the repo's default branch.
3. Go to **Settings → Pages**, set source to the default branch, root folder.
4. Your site will be live at `https://<username>.github.io/dhruv-portfolio/`.
   (For a root-level `username.github.io` site, name the repo exactly `username.github.io`.)

## Deploy on Netlify
1. Go to [app.netlify.com](https://app.netlify.com) → **Add new site → Deploy manually**.
2. Drag the whole project folder onto the upload area.
3. Netlify gives you a live URL immediately; add a custom domain later under **Domain settings** if you want.

No build command or framework is needed — it's plain static files.
