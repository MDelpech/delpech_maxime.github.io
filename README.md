# Maxime Delpech — AI Research Portfolio

A simple static portfolio designed for GitHub Pages.

## Files

- `index.html`: home/about page
- `cv.html`: CV page
- `research.html`: research page
- `styles.css`: global design
- `script.js`: automatic footer year
- `assets/`: place your photo and PDF CV here

## Publish on GitHub Pages

1. Copy all files to your `USERNAME.github.io` repository.
2. Commit and push to the `main` branch.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**, then `main` and `/root`.
5. Open `https://USERNAME.github.io`.

## Personalize

Search for:

- `YOUR_USERNAME`
- `YOUR_PROFILE`
- `YOUR_EMAIL`
- `YOUR_REPOSITORY`

To add a real profile photo, replace this block in `index.html`:

```html
<div class="portrait-placeholder">
  <span>MD</span>
</div>
```

with:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Portrait of Maxime Delpech">
```

Then add this CSS in `styles.css`:

```css
.profile-photo {
  width: 100%;
  aspect-ratio: 4 / 5;
  object-fit: cover;
  display: block;
}
```
