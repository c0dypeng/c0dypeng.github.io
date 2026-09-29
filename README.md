# chijenpeng.github.io

Personal website, built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (MIT, see `LICENSE`) and hosted on GitHub Pages.

## Where things are

- `_pages/about.md` — the home page. One narrative About; plain Markdown.
- `_pages/music.md` — the Music page (YouTube uploads embed).
- `files/cv.pdf` — the CV. The nav's CV link opens it directly; `/cv/` and `/resume` redirect to it. To update, copy the new PDF over it (source lives in the separate `resume` repo).
- `_config.yml` — site name, sidebar (photo, bio line, location, links). Academic links such as ORCID are commented out; uncomment to show them.
- `_data/navigation.yml` — top nav. Only Music and CV are enabled; Publications, Talks, Teaching, Portfolio and Blog Posts are commented out.
- `images/profile.jpg` — sidebar photo. Overwrite to change it.
- `_publications/`, `_talks/`, `_teaching/`, `_portfolio/`, `_posts/` — empty collections, ready when needed.
- `resume.tex` (old resume source) is gitignored and never published.

## Deploy

Push to `main`. GitHub Pages builds the site automatically; it appears at https://chijenpeng.github.io within a minute or two.

## Preview locally (optional)

Needs Ruby 3.x (e.g. `brew install ruby`).

```sh
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open http://localhost:4000.
