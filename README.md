# vaew.github.io

Personal academic homepage of **Jing Tang**, Ph.D. candidate at Huazhong University of Science and Technology — <https://vaew.github.io>

Built with [Jekyll](https://jekyllrb.com/) on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template and deployed by GitHub Actions (`.github/workflows/jekyll.yml`).

## Where to edit

| Content | File |
| --- | --- |
| Name, sidebar links, site settings | `_config.yml` |
| Top navigation | `_data/navigation.yml` |
| Home page | `_pages/about.md` |
| Publications (one file per paper) | `_publications/` |
| Competitions & awards | `_pages/competitions.md` |
| Patents | `_pages/patents.md` |
| Academic service | `_includes/academic-service.md` |
| Others page | `_pages/cv.md` |
| Blog posts | `_posts/YYYY-MM-DD-title.md` |
| Site-specific styles | `_sass/layout/_custom.scss` |

## Run locally

```sh
bundle install
npm install && npm run build:js   # builds assets/js/main.min.js
bundle exec jekyll serve
```
