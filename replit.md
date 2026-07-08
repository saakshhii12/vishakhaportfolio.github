# Vishakha Gite — Portfolio

A sports-first personal portfolio site built with plain HTML, CSS, and JavaScript.

## How to run

The site is served by Python's built-in HTTP server on port 5000.
The **Start application** workflow handles this automatically — just press Run.

## Adding photos

Upload your photos/certificates into the `assets/` folder (drag-and-drop in the file panel), then name them exactly as listed below:

| Filename | What it should be |
|---|---|
| `portrait.jpg` | Main hero photo (portrait or action shot) |
| `cert-karate.jpg` | Karate brown belt certificate |
| `cert-boxing.jpg` | Inter-Dojo Boxing silver medal certificate |
| `cert-district.jpg` | District athlete selection letter/certificate |
| `cert-sports-head.jpg` | Sports Head appointment/appreciation certificate |
| `action-1.jpg` | Action photo (mat, ring, or field) |
| `sports-head-1.jpg` | Photo running/organizing a tournament (Leadership section) |
| `sports-head-2.jpg` | Second Sports Head photo (Gallery section) |

After uploading, open `index.html` and find the matching `<div class="photo-frame ...">` block.
Replace the inner `<div class="photo-frame__placeholder">...</div>` with:

```html
<img src="assets/FILENAME.jpg" alt="short description" class="photo-frame__img">
```

## Structure

- `index.html` — all page content
- `style.css` — all styles
- `script.js` — scroll animations and nav behaviour
- `assets/` — your photos and certificates go here

## User preferences

- Keep the existing HTML/CSS/JS stack — no framework migration needed.
