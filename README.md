# c0dypeng.github.io

Personal website, built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (MIT, see `LICENSE`) and hosted on GitHub Pages.

## Where things are

- `_pages/about.md` — the home page. One narrative About; plain Markdown.
- `_pages/music.md` — the Music page (YouTube uploads embed).
- `_pages/cv.md` — the CV page.
- `_config.yml` — site name, sidebar (photo, bio line, location, links). Academic links such as ORCID are commented out; uncomment to show them.
- `_data/navigation.yml` — top nav. Only Music and CV are enabled; Publications, Talks, Teaching, Portfolio and Blog Posts are commented out.
- `images/profile.jpg` — sidebar photo. Overwrite to change it.
- `_publications/`, `_talks/`, `_teaching/`, `_portfolio/`, `_posts/` — empty collections, ready when needed.
- `files/resume.pdf` — the public resume. Currently gitignored; `resume.tex` is always ignored so the source stays private.

## Deploy

Push to `main`. GitHub Pages builds the site automatically; it appears at https://c0dypeng.github.io within a minute or two.

## Preview locally (optional)

Needs Ruby 3.x (e.g. `brew install ruby`).

```sh
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open http://localhost:4000.
