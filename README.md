# Warissath GERALDO — Personal Portfolio

This repository contains the Jekyll source for **https://gwarissath.github.io**.

## Sections

- Home
- Education
- Professional Experience
- Projects
- CV
- Contact

## Before publishing

1. Upload your portrait to `assets/images/profile.jpg`.
2. Upload your CV PDF to `assets/files/cv.pdf`.
3. Edit the placeholder content in `_pages/education.md`, `_pages/experience.md`,
   `_pages/projects.md`, and `_pages/contact.md`.
4. Add your real email and LinkedIn URL.
5. Check `_config.yml` and confirm the site URL and GitHub username.

## Publish with GitHub Actions

The workflow in `.github/workflows/pages.yml` builds the Jekyll site and deploys it
to GitHub Pages whenever you push to the `main` branch.

In GitHub, open **Settings → Pages** and set **Build and deployment → Source** to
**GitHub Actions**.

## Local preview (optional)

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` in your browser.
