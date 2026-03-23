# Alyssa Clark — Personal Website

Static personal site hosted on GitHub Pages at [alyssaclark.org](https://alyssaclark.org).

## How it works

- **`index.html`** — page structure and content (all the text lives here)
- **`styles.css`** — all styling, with colour variables at the top
- **`fonts/`** — self-hosted web fonts (no external requests)
- **`images/`** — your headshot and any other images
- **`files/`** — downloadable files (CV PDF, etc.)

## Common tasks

### Update text content

Open `index.html` and edit the text directly. Each section has an HTML comment like `<!-- EDIT YOUR BIO HERE -->` to help you find what to change. Use Claude Code if unsure.

### Add your photo

1. Add your image to the `images/` folder (e.g., `images/headshot.jpg`)
2. In `index.html`, find the hero section and replace the smiley placeholder with:
   ```html
   <img src="images/headshot.jpg" alt="Alyssa Clark">
   ```

### Add your CV

1. Add your CV PDF to a `files/` folder (e.g., `files/alyssa-clark-cv.pdf`)
2. The download button in the hero already links to this path

### Change colours

Edit the CSS variables at the top of `styles.css` — the `--color-accent` variable controls the sage green used throughout.

### Deploy

GitHub Pages: repo **Settings → Pages → Source: `main`, folder: `/ (root)`**.

The `CNAME` file is already set to `alyssaclark.org`. You'll need to configure DNS with your domain registrar to point to GitHub Pages — see [GitHub's guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-github-pages).
