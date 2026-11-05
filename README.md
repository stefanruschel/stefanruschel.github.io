# stefanruschel.github.io

Personal academic website of Stefan Ruschel, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (MIT licence) and published at <https://stefanruschel.github.io>.

## Where things live

| What | File(s) |
|---|---|
| Name, sidebar, email, Google Scholar, ORCID | `_config.yml` (section `author:`) |
| Home page (about, research interests, contact) | `_pages/about.md` |
| Top menu | `_data/navigation.yml` |
| Publications (one file per paper) | `_publications/` |
| Talks and events (one file per event) | `_talks/` |
| Teaching and service | `_pages/teaching.md` |
| CV | `_pages/cv.md` |
| Profile photo | `images/stefan-ruschel.jpg` |
| PDFs and other downloads | `files/` (served at `/files/<name>`) |

## Adding a publication

Copy any file in `_publications/`, rename it `YYYY-MM-DD-short-name.md` and edit the header. `category` is one of `manuscripts`, `preprints`, `conferences`, `thesis`; `link` is where the title points (DOI or arXiv).

## Publishing

Every push to `main` triggers `.github/workflows/jekyll.yml`, which builds and deploys the site. In the repository's **Settings → Pages**, set **Source** to **GitHub Actions** (once).

## Local preview (optional)

Requires Ruby and Bundler: `bundle install`, then `bundle exec jekyll serve -l -H localhost`, and open <http://localhost:4000>. Alternatively `docker compose up`.
