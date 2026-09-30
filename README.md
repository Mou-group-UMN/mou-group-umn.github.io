# Mou Group website

Jekyll site hosted on GitHub Pages. Most updates are one-line edits in `_data/`:

| To change | Edit |
|---|---|
| News | `_data/news.yml` (add at top) |
| Members | `_data/people.yml` (photos in `assets/img/people/`) |
| Publications | `_data/publications.yml` (`area`: robust / design / stochastic) |
| Workshops | `_data/workshops.yml` (newest first; the first entry is shown as Latest) |
| Funded projects | `_data/projects.yml` (figures in `assets/img/projects/`) |
| Homepage | `_data/home.yml` (statement, openings, PI block, sponsors) |
| Pages | `teaching.md`, `software.md`, `photos.md`, `join.md`, `projects.html` (`research.html` is unpublished) |
| Menu | `nav` in `_config.yml` |

Preview locally: `bundle exec jekyll serve` (optional). Pushing to `main` redeploys automatically.
