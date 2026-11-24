# Data Science Portfolio — Qu Ying

Source of <https://qyyyyy123.github.io/data-science-portfolio/>.

A static site: plain HTML and one stylesheet, no build step, no external CDN, no JavaScript. It is
served directly from the `main` branch by GitHub Pages.

## Pages

| File | Contents |
|---|---|
| `index.html` | Introduction, skills with evidence, the semester project showcase (research question, two figures, findings, limitation, status), the Netflix project, coursework links, reflection, feedback summary |
| `projects/xiamen.html` | Deep dive: method table, six figures, the two dashboards, all headline numbers, limitations, reproduction route |
| `projects/netflix.html` | Earlier project: question, data, three findings, limitation |
| `feedback.html` | Review log (comment → response → commit), responsible-sharing checklist, accessibility checks |
| `assets/css/style.css` | The whole design, including responsive breakpoints and print rules |
| `assets/img/` | Every figure, committed here rather than hotlinked |

## Editing

Open `index.html` in a browser — that is the entire development loop. Relative paths mean the site
also works when opened from disk.

## Deployment

GitHub Pages, `main` branch, repository root. Pushing to `main` redeploys within about a minute. The
`.nojekyll` file stops Jekyll from trying to process the directory.

## Responsible sharing

* No credentials, tokens or `.env` files, at any point in the history.
* No personal or contact data beyond the public GitHub handle.
* The bike-share dataset is third-party and CC BY-NC 4.0: linked via its Zenodo DOI, never re-hosted.
* The Netflix dataset is a public Kaggle extract; only derived figures are shown.
