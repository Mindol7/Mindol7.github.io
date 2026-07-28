# Minhyuk Jo — Academic Homepage

Source for [mindol7.github.io](https://mindol7.github.io/), an academic
homepage built with Jekyll and a customized version of the
[Minimal Light](https://github.com/yaoyao-liu/minimal-light) theme.

## Content

- `index.md` — short introduction, news, and contact information
- `aboutme.md` — biography, education, experience, projects, honors, and skills
- `publications.md` and `_data/publications.yml` — categorized publications
- `patents.md` — registered patents and patent applications
- `honors.md` and `_data/honors.yml` — awards and scholarships
- `_data/news.yml` — reverse-chronological homepage news
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

The homepage publishes the email address, phone number, and lab location
provided for public contact. The downloadable CV continues to omit third-party
reference contact details and confidential project information. The source CV
is kept outside this repository.

## License and attribution

The theme source is derived from Minimal Light. The GitHub and LinkedIn SVG
icons are from Font Awesome Free 6.4.2; its license is stored with the icons.
See `LICENSE` and the site footer for additional attribution.
