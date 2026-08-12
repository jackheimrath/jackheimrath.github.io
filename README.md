# jackheimrath.github.io

Personal academic website of Jack Heimrath, PhD candidate in Mathematics (Probabilistic Number Theory) at Queen's University. Built with Jekyll on the [al-folio](https://github.com/alshedivat/al-folio) theme (v0.16.3) and deployed to GitHub Pages via GitHub Actions.

Live at: https://jackheimrath.github.io

## Structure


- `_pages/about.md` — home page / bio
- `_pages/publications.md` — renders `_bibliography/papers.bib` automatically
- `_pages/cv.md` + `_data/cv.yml` — CV page (education, teaching, industry experience, etc.)
- `_pages/teaching.md` + `_teachings/*.md` — one file per course
- `_data/socials.yml` — contact links (email, GitHub, LinkedIn, ORCID, ...)
- `_config.yml` — site-wide settings

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch. In the repo's **Settings → Pages**, set the source to deploy from the `gh-pages` branch.

## Still to do

- [ ] Add a real profile photo (`assets/img/`, referenced from `_pages/about.md`)
- [ ] Replace `assets/pdf/CV.pdf` with a real CV
- [ ] Fill in the placeholder entries in `_data/cv.yml`, `_teachings/example-course.md`, and `_bibliography/papers.bib`
- [ ] Add social links in `_data/socials.yml`

## License

