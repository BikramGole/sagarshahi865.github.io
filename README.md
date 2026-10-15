# sagarshahi865.github.io

Personal portfolio of **Sagar Shahi** (Sagar Bahadur Shahi) — computer engineering student and Django developer in Kathmandu, Nepal. Live at **https://sagarshahi865.github.io/**.

## What's on the site

- **Hero** — intro, live-demo CTA, stats (team commits, live workouts, systems) and Nepal-time clock
- **Selected work** — team-built Fitness Hub (`FitHub-4/Fitness-Hub`, live at `fitnesshub123.pythonanywhere.com`), solo `fitness-hub` continuation, and open-source profile
- **Live from GitHub** — repositories auto-fetched from [`github.com/sagarshahi865`](https://github.com/sagarshahi865) via the public API (lazy, with static fallback)
- **Services & process** — Django apps, dashboards, store/checkout, CI
- **Journey** — FitHub-4 team build, Abyssal Oath collective membership, OJT, studies
- **Skills sphere** — draggable canvas (keyboard alternative included) plus plain-text lists
- **FAQ, contact + project-brief form** — writes a first-contact email for visitors

## Structure

Single-file static site — no build step, no dependencies:

- `index.html` — markup, styles and scripts (fonts via Google Fonts, portrait inlined as base64)

Preview locally:

```bash
python3 -m http.server 8000
# open http://127.0.0.1:8000
```

## Customizing

- Skills sphere words: edit the `WORDS` array near the end of `index.html`
- Hero stats: edit the `.stat` blocks (numbers animate via `data-to`)
- Repository links: update the `gh-live` fallback list and `sameAs` JSON-LD together

## Links

- GitHub: https://github.com/sagarshahi865
- Team build: https://github.com/FitHub-4/Fitness-Hub
- Live demo: https://fitnesshub123.pythonanywhere.com/
- Collective: https://github.com/Abyssal-oath
