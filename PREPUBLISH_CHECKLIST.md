# IMPORTANT — before replacing live GitHub Pages files

- **DO NOT delete** `/hospital-joy-toolkit/index.html` (the parent guide) or `/hospital-joy-toolkit/feedback/index.html` (the QR redirect). They are not in this package because their original source HTML was not supplied here. Keep these existing repo files and confirm both URLs still work after deployment.
- **DO NOT delete** any existing custom domain configuration. The package includes `CNAME` for `smileoptimisticstudio.org.uk`.
- Back up the repository or deploy this package to a **separate test repository first**. The zip itself is not a full backup of the live site.
- For GitHub Pages Jekyll builds: Settings → Pages → Deploy from a branch → `main` → `/ (root)` (or keep the site's existing compatible workflow).
- Confirm title, dates (Leeds **2 October 2026**), author permissions, photos, and SoHPS acknowledgements.
- Check each article for personal medical details, and review approved wording with Lada where relevant.
- Confirm there are no unsupported efficacy, professional endorsement or completed-pilot claims.
- View desktop and mobile after deployment, validate the footer and contact email, verify links and images.
- Verify the QR points to `https://smileoptimisticstudio.org.uk/hospital-joy-toolkit/feedback/` and still reaches the Google Form.
- The current package includes neither a working newsletter signup nor an email-collection form.
- Search Console and visitor analytics require separate account setup, not included here.
- **Live Jekyll rendering has not been verified** in this environment; syntax and path checks are run locally, but check the GitHub Pages build log after deployment.
