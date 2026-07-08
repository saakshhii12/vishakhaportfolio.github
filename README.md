# Vishakha Gite — Portfolio

A sports-first portfolio site: Karate, boxing, district athletics, and college
sports leadership up front; engineering skills and experience further down.

## How to put this on Replit

1. Go to [replit.com](https://replit.com) and click **Create App / Repl**.
2. Choose the **HTML/CSS/JS** template (sometimes listed as "Static site" or "Vanilla").
3. Delete the default `index.html`, `style.css`, and `script.js` Replit gives you.
4. Upload these three files from this project into the Repl (drag-and-drop into
   the file panel, or use "Upload file"):
   - `index.html`
   - `style.css`
   - `script.js`
5. Create a folder called `assets` in the Repl and upload your photos into it
   (see the list below for exact filenames).
6. Click **Run**. Replit will give you a live `.replit.app` link you can put on
   your resume or LinkedIn.

## Adding your photos and certificate scans

Every photo on the site is currently a placeholder box that says **"Add photo
here"** with the exact filename it expects. To swap in a real photo:

1. Take a clear photo or scan of the certificate/photo.
2. Name the file exactly as listed below and put it in the `assets` folder.
3. In `index.html`, find the matching `<div class="photo-frame ...">` block and
   replace its inner `<div class="photo-frame__placeholder">...</div>` with:
   ```html
   <img src="assets/FILENAME.jpg" alt="short description">
   ```

Expected filenames (all go inside `assets/`):

| File | What it should be |
|---|---|
| `portrait.jpg` | Your main hero photo (portrait or action shot) |
| `cert-karate.jpg` | Karate brown belt certificate |
| `cert-boxing.jpg` | Inter-Dojo Boxing silver medal certificate |
| `cert-district.jpg` | District athlete selection letter/certificate |
| `cert-sports-head.jpg` | Sports Head appointment/appreciation certificate |
| `action-1.jpg` | Photo of you on the mat, in the ring, or on the field |
| `sports-head-1.jpg` | Photo of you running/organizing a tournament |
| `sports-head-2.jpg` | A second Sports Head photo |

Tip: crop certificate photos to fill the frame (no big white margins) so they
sit nicely inside the rounded photo frames — the CSS already handles
`object-fit: cover` sizing once you add `img` tags with the class
`photo-frame__img` (add this class to any `<img>` you insert, so it fills the
frame correctly):

```html
<img src="assets/cert-karate.jpg" alt="Karate brown belt certificate" class="photo-frame__img">
```

## Structure

- **Hero** — name, tagline, scrolling achievement ticker
- **Stat strip** — belt rank, medal, district leagues, sports-head year at a glance
- **Achievements** — Karate, boxing, district athletics detail
- **Leadership** — College Sports Head, 2024–2025, full writeup
- **Gallery** — 6 photo/certificate frames, ready for your uploads
- **Engineering** — skills, experience, BloodO project, education (condensed)
- **Contact** — email + LinkedIn

## Contact info already wired in

- Email: `vishakha120106@gmail.com` (mailto link in the Contact section)
- LinkedIn: `https://www.linkedin.com/in/vishakha-gite12/`

If either changes, search for them in `index.html` and update both spots.
