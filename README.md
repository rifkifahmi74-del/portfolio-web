# Miftakhul Rifki Al Fahmi - Portfolio

Apple-style (iOS / apple.com) single-page portfolio. Plain HTML, CSS, and JavaScript with no build step, so it runs anywhere and deploys to GitHub Pages as-is.

```
portfolio-web/
  index.html          <- the whole site
  assets/
    logo-uns.png                    (already added)
    Miftakhul-Rifki-Al-Fahmi-CV.pdf (already added, used by "Download CV")
    headshot.jpg        <- graduation portrait (hero, portrait ~4:5)
    artefac-dhani.jpg   <- photo with the headline artist (Artefac card, portrait)
    artefac-stage.jpg   <- team at the main stage (Artefac card, portrait)
    wmk.jpg             <- venture / team photo (Wirausaha Merdeka card, landscape ~16:9)
    cert-ssrn.jpg       <- SSRN paper (Certifications gallery)
    cert-coursera.jpg   <- Coursera / Wharton certificate (Certifications gallery)
    cert-claude.jpg     <- Claude 101 certificate (Certifications gallery)
    cert-toefl.jpg      <- Englishvit / TOEFL certificate, DOB+address redacted (Certifications gallery)
    cert-harisenin.jpg  <- Harisenin Business Development certificate (Certifications gallery)
    research.jpg        <- OPTIONAL: research visual for the SSRN work card (16:9)
```

## Adding photos

Drop the image files into the `assets/` folder using the exact names above.
Anywhere a photo is missing, the page shows a clean placeholder, so it always looks finished. Add photos when you have them, in any order.

Recommended sizes (for fast loading): keep each image under ~500 KB, max width ~1600 px. JPG is fine.

## Run locally

Double-click `index.html`, or open it in a browser. That's it.

## Deploy to GitHub Pages (same as your other projects)

1. Create a new public repository on GitHub, for example `portfolio`.
2. Upload the contents of this folder (`index.html`, `README.md`, and the `assets/` folder) to the repo. GitHub Desktop or drag-and-drop on github.com both work.
3. In the repo, go to **Settings > Pages**.
4. Under **Build and deployment > Source**, choose **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)`. Save.
6. After a minute, your site is live at `https://<your-username>.github.io/portfolio/`.

Tip: if you name the repo `<your-username>.github.io`, the site lives at the root domain `https://<your-username>.github.io/` instead.

## Editing content

All text lives directly in `index.html` and is clearly labeled by section
(`HERO`, `IMPACT BAND`, `SELECTED WORK`, `EXPERIENCE`, `ABOUT`, `CREDENTIALS`, `CONTACT`).
Colors and spacing are controlled by the CSS variables at the top of the file under `:root`.
