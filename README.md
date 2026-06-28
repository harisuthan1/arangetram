# Arangetram Website — Kavyamridula Venkatesan

A simple, single-page website for the Bharatanatyam Arangetram, styled in a
traditional maroon & gold temple look. Built to be hosted **free** on GitHub Pages.

## What's in this folder

| File | Purpose |
|------|---------|
| `index.html`   | The website (all the brochure content). |
| `styles.css`   | The maroon & gold styling. |
| `make-qr.html` | Open in a browser to generate & download the QR code once your site is live. |
| `images/`      | Web-optimized copies of the 6 brochure pages (shown in the gallery). |
| `.nojekyll`    | Tells GitHub Pages to serve files as-is. Leave it here. |

To preview locally, just **double-click `index.html`** — it opens in your browser.

---

## Publishing to GitHub Pages (free)

You're currently signed in to Apple's *internal* GitHub. Guests can't reach that,
so use **public github.com** instead.

1. **Create a free account** at https://github.com (skip if you already have a personal one).
2. **Create a new public repository**, e.g. named `arangetram`.
3. **Upload these files**: on the repo page click *Add file → Upload files*, drag in
   everything from this folder (`index.html`, `styles.css`, `make-qr.html`, `.nojekyll`,
   and the `images` folder), then *Commit changes*.
   - (Or via command line — see below.)
4. **Enable Pages**: repo *Settings → Pages → Build and deployment → Source: Deploy from
   a branch → Branch: `main` / root → Save.*
5. Wait ~1 minute. Your site will be live at:

   ```
   https://<your-username>.github.io/arangetram/
   ```

### Command-line upload (optional)
```bash
cd "arangetram-website"
git init
git add .
git commit -m "Arangetram website"
git branch -M main
git remote add origin https://github.com/<your-username>/arangetram.git
git push -u origin main
```

---

## Generating the QR code

1. Once your site is live, copy its URL (e.g. `https://yourname.github.io/arangetram/`).
2. Double-click **`make-qr.html`** to open it in your browser.
3. Paste the URL, click **Generate QR Code**, then **Download QR code (PNG)**.
4. Print the PNG on invitations, programs, or signage.

The QR uses high error-correction, so it still scans even if slightly obscured or printed small.

---

## Editing content

All the text lives in `index.html` — open it in any text editor to fix a name,
date, or description. Colors and fonts are in `styles.css` (see the `:root` block at the top).
