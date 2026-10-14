# Not the Desert You Know: travel sketchbook

An interactive sketchbook for the Rajasthan road trip (Udaipur and Banswara, 20 to 22 August 2026), part of the *Not the Desert You Know* series.

Each spread has a polaroid on the left with a caption, and a hand-drawn SVG marker illustration of the same scene on the right. Pages turn by dragging a page corner, with the arrow keys, or by swiping on a phone.

## Open it

Open `index.html` in a browser. Keep it next to `photos/` and `logo.jpg`, because they load by relative path. The handwriting font (Caveat) loads from Google Fonts, so you need to be online to see it.

## Contents

- `index.html`: the whole sketchbook (HTML, CSS, JS and the inline SVG drawings, no libraries)
- `photos/`: 50 web-ready JPEGs (1600px long edge) in trip order, with all metadata and GPS removed
- `notes.md`: trip overview and one caption per photo
- `logo.jpg`: series logo used on the cover

## Status

Cover, title page, closing page and spreads for photos 01 to 05 are done. Photos 17, 20 and 22 are near-duplicates and are skipped. The remaining spreads are being added in batches.

## Put it online (GitHub Pages)

Repository Settings, Pages, then deploy from the `main` branch, root folder. The site will be at `https://<your-username>.github.io/<repo-name>/`.
