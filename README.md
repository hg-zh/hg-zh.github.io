# hg-zh.github.io

Source for [Hang Zhou's homepage](https://hg-zh.github.io), built with Jekyll and published by GitHub Pages.

## Where things live

| Path | What it is |
|---|---|
| `_config.yml` | Site-wide settings: name, bio, sidebar links, avatar |
| `_data/navigation.yml` | The top menu (Publications, Teaching, Talks, Software) |
| `_pages/about.md` | Home page |
| `_pages/publications.md` | Publications page (edited by hand) |
| `_pages/talks.html` | Talks page (edited by hand) |
| `_pages/cv.md` | Software page (served at `/cv/`) |
| `_pages/teaching.html` | Teaching index; lists every file in `_teaching/` |
| `_teaching/` | One Markdown file per course |
| `files/` | PDFs and BibTeX snippets linked from the pages, served at `https://hg-zh.github.io/files/<name>` |
| `images/pf.jpg` | Profile photo (other files in `images/` are favicons) |
| `_includes/`, `_layouts/`, `_sass/`, `assets/` | The theme itself; normally nothing to edit here |

## Previewing locally

```
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>.

## Credits

Built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, a fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme by Michael Rose, MIT License (see `LICENSE`).
