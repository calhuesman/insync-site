# insync-site

The public InSync website: home, Privacy Policy, Terms of Use and Support. Plain HTML + CSS, no build step, no scripts, no analytics, no cookies. Served by GitHub Pages from `main` (root).

The privacy and terms pages are generated word for word from `docs/legal/` in the app repo.

`review.html` is an unlisted, noindex page for reviewing the recipe photos (not linked from any page). It's the one page with a script: search, filters and flags saved in the reviewer's own browser (localStorage), nothing sent anywhere. Rebuilt from `assets/data/recipes.json` in the app repo.
