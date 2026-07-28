# Minhyuk Jo — Academic Homepage

Source for [mindol7.github.io](https://mindol7.github.io/), an academic
homepage built with Jekyll and a customized version of the
[Minimal Light](https://github.com/yaoyao-liu/minimal-light) theme.

## Content

- `index.md` — introduction, research interests, and recent highlights
- `publications.md` and `_data/publications.yml` — publications and patents
- `experience.md` — education, experience, projects, skills, and certifications
- `honors.md` — awards and scholarships
- `assets/files/Minhyuk_CV.pdf` — privacy-reviewed public CV

Shared page structure is in `_layouts/` and `_includes/`. Site-specific styling
and mobile navigation are in `assets/css/site.scss` and
`assets/js/navigation.js`.

## Local preview

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000>.

## Deployment

In the repository's GitHub Pages settings, publish from the `main` branch and
the repository root. No custom domain is configured.

## Privacy

The public pages and downloadable CV omit personal phone numbers, third-party
reference contact details, and confidential project information. The source CV
is kept outside this repository.

## License and attribution

The theme source is derived from Minimal Light. See `LICENSE` and the site
footer for attribution.
