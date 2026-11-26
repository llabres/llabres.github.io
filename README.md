# llabres.github.io

Personal profile page served by GitHub Pages (built with Jekyll automatically on push).

**All content lives in `_data/*.yml`** — this repo is the single source of truth for both the website and the CV generator (AutoCV).

| File | On website | Content |
|---|---|---|
| `profile.yml` | yes | name, bio, emails, links; CV summary |
| `publications.yml` | yes | papers (items with `site: false`, e.g. theses, are CV-only) |
| `projects.yml` | yes (Research Projects + Research Areas tabs, split by `kind`) | named/funded projects: website description + one-line CV bullet, related papers |
| `events.yml` | yes | organised competitions / schools / workshops |
| `talks.yml` | yes | talks |
| `code.yml` | yes (as "Related" links on projects) | GitHub repositories, referenced by id from `refs:` |
| `labels.yml` | yes | display names for badges and link types |
| `experience.yml` | no — CV only | positions; roles list `projects:` ids plus plain `highlights:` |
| `education.yml` | no — CV only | degrees |
| `awards.yml` | no — CV only | awards |
| `skills.yml` | no — CV only | skills and spoken languages |

CV-only files are not rendered on the website, but they are public in this repo — don't put private data (phone, address) here.

`index.html` is a Liquid template, `style.css` the styling, and `assets/photo.jpg` the photo.
