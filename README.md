# Smile Optimistic Studio CIC — website

A self-contained static site. Plain HTML, CSS, and a few lines of vanilla
JavaScript — **no build step, no framework, no dependencies**. It runs by
opening `index.html` in any browser, and deploys to GitHub Pages as-is.

## Files

```
index.html              The whole homepage
styles/
  colors_and_type.css   Brand tokens — colour, type, spacing
  site.css              Page + component styles
  responsive.css        Tablet / phone breakpoints
assets/
  marigold-color.png    Logo mark
.nojekyll               Tells GitHub Pages to serve files as-is
```

## Deploy to GitHub Pages (one time)

1. Create a new repository on GitHub (e.g. `smile-optimistic-studio`).
2. Upload everything in this folder to the repository root
   (drag the files into GitHub's "Add file → Upload files", or push with git).
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Pick branch **main** and folder **/ (root)**, then **Save**.
6. After a minute the site is live at
   `https://<your-username>.github.io/<repo-name>/`.

Every later edit you push to `main` republishes automatically.

## Custom domain (optional)

To serve it at `smileoptimisticstudio.org.uk`:

1. Add a file named `CNAME` to the repo root containing just the domain:
   `smileoptimisticstudio.org.uk`
2. At your DNS provider, point the domain at GitHub Pages
   (an `ALIAS`/`ANAME` to `<your-username>.github.io`, or four `A` records
   to GitHub's Pages IPs — see GitHub's "Managing a custom domain" guide).
3. Back in **Settings → Pages**, enter the domain and tick **Enforce HTTPS**.

## Fonts

The brand typeface is **Skolar Sans PE** (Rosetta Type, licensed). This build
substitutes **Mulish** (Google Fonts) for screen so it works with no licence
on hand. For production, load the licensed Skolar Sans webfont and override
`--font-sans` in `styles/colors_and_type.css`.

---
© Yuliia Barsukova / Smile Optimistic Studio CIC, 2025–2026.
