# Vhelaphi George Maluleke — Data Analytics Portfolio Website

A responsive one-page portfolio website built with plain HTML, CSS, and a small amount of JavaScript. The visual theme uses charcoal, white, and a richer teal accent. The Selected Work section uses text-first project cards without photo or image placeholders. The site uses Manrope headings and DM Sans body text, with system fallbacks. There is no build step or external package dependency, so it can be published directly with GitHub Pages.

## What's included

- `index.html` — website structure, styling, and mobile navigation
- `assets/favicon.svg` — matching VGM favicon in neon teal, black, and white
- `assets/george-maluleke-cv.pdf` — CV linked from the website

## Publish with GitHub Pages

### Recommended: use a dedicated profile website repository

1. Create a **public** repository named `georgem135.github.io` under your GitHub account.
2. Upload `index.html` and the entire `assets` folder to the repository root. Keep their names and relative paths unchanged.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then click **Save**.
6. After deployment, visit `https://georgem135.github.io/`.

### Or publish from an existing repository

Upload the same files to the root of `georgem135portfolio2` and configure **Settings → Pages → Deploy from a branch → `main` → `/(root)`**. Its project-site URL should be `https://georgem135.github.io/georgem135portfolio2/` when Pages is enabled.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Before publishing

This package includes a downloadable CV. GitHub Pages sites are publicly viewable, so remove `assets/george-maluleke-cv.pdf` and the CV button in `index.html` if you do not want the full CV available publicly.

## Updating the website

Edit `index.html` in any text editor. The primary teal accent is `#2DD4BF`; dark teal for links and labels on light backgrounds is `#087F74`. Headings use Manrope and body text uses DM Sans, both with system fallbacks. Keep links and asset paths relative so they work on both profile and project sites.
