# Night Fantom Projects website

A responsive, static website for Night Fantom Projects featuring **HOODRAT only**. No frameworks, build steps, or paid hosting are required.

## Files

- `index.html` — homepage and editable website content.
- `styles.css` — colors, layout, desktop and mobile styling.
- `script.js` — mobile navigation and automatic copyright year.
- `assets/nfprojects-logo.png` — main phantom/moon logo.
- `assets/hoodrat-artwork.png` — illustrative HOODRAT image cropped from the concept mockup; replace with an official HOODRAT logo/artwork when ready.
- `docs/website-design-reference.png` — full visual reference mockup for an AI website builder; **not** the actual webpage.
- `docs/AI-BUILDER-INSTRUCTIONS.md` — instructions for an AI builder connected to GitHub.

## Publish using GitHub Pages

1. Create a new GitHub repository, for example `NFProjects-Website`.
2. Upload the **contents** of this folder to the repository root (not an extra nested folder).
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save.
5. Wait for GitHub Pages to publish and use the website link displayed in Settings → Pages.

Alternatively, open `index.html` locally to preview the design before publishing.

## Important before public launch

- Add verified official social links in the Contact section; placeholders are deliberate.
- Replace illustrative HOODRAT artwork with approved branding if desired.
- Do not present concept mockup headlines, dates, or links as verified announcements.
- This site is an original functional interpretation of the reference image, not a pixel-perfect copy.

## Changing the main image

Replace `assets/nfprojects-logo.png` with another PNG of the same name, or change the image path in `index.html` inside the `hero-art` element. The hero uses this file as the main image.
