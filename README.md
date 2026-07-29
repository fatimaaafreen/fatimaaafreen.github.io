# Portfolio

Single-page static site — no build step, no framework, no dependencies.
Just `index.html` + `resume.pdf`.

## Before you deploy — 3 placeholders to fill in

Open `index.html` and replace these (Cmd+F / Ctrl+F for each):

1. `YOUR-GITHUB-USERNAME` (appears 5 times) → your actual GitHub username
2. `YOUR-ADOPTION-RADAR-DEPLOY-URL` (appears once) → the live Render/Railway
   URL once Adoption Radar is deployed
3. Double check `resume.pdf` in this folder is your latest résumé version

## Deploy with GitHub Pages

1. Push this repo to GitHub (see the root-level setup instructions).
2. On GitHub: repo → **Settings** → **Pages** → under "Build and
   deployment", set **Source** to `Deploy from a branch`, branch `main`,
   folder `/ (root)`. Save.
3. GitHub gives you a URL like `https://fatimaaafreen.github.io/portfolio/`
   within a minute or two.

That URL is what goes on your resume/LinkedIn and in the Darwinbox
application's portfolio field.
