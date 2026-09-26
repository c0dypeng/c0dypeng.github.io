# c0dypeng.github.io

Personal website, built with Jekyll and hosted on GitHub Pages.

## Layout

- `index.md` — the home page (About, Education, Experience, Projects, Honors). Plain Markdown, edit freely.
- `_config.yml` — site title, contact links, and the YouTube URL in the nav.
- `_layouts/`, `_includes/` — page templates (header, footer).
- `assets/css/style.css` — the only stylesheet.
- `files/resume.pdf` — the public resume. Currently gitignored (see `.gitignore`); `resume.tex` is always ignored so the source stays private.

## Deploy

1. Create a GitHub repository named exactly `c0dypeng.github.io`.
2. Push this folder to its `main` branch:

   ```sh
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin git@github.com:c0dypeng/c0dypeng.github.io.git
   git push -u origin main
   ```

3. On GitHub, open Settings → Pages and make sure the source is "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site appears at https://c0dypeng.github.io within a minute or two. Every later push rebuilds it.

## Preview locally (optional)

Needs Ruby 3.x (e.g. `brew install ruby`).

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
