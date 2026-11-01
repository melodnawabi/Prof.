# Prof.

An AI tutor for executive-MBA and business-law judgment, set in Canadian practice.

- **Today** — a daily case, a spaced-repetition quiz, a graded written answer, and a weekly field project
- **Library** — 10 tracks across 4 schools, each with a drill, two lessons and a field project
- **Ask Prof** — office-hours chat that switches teaching method per question
- **Reading** — two books per track, plus free outside courses
- **Certificates** — one per completed track

## Run it

Open `index.html` in a browser, or publish with GitHub Pages:
Settings → Pages → Deploy from branch → `main` / root.

## AI features

Lessons, chat and grading call `window.claude.complete(...)`. That helper only exists in the environment this was designed in. To make AI work on your own site, define `window.claude.complete` before the app loads. It should forward the request to your own backend, which calls the Anthropic API. Never put an API key in front-end code.

Progress is saved in the browser's localStorage.

Teaching methods are modelled on Harvard, Yale, Columbia, Wilfrid Laurier, Waterloo, Conestoga and Tetr College. Prof is not affiliated with any of them. Education, not legal or financial advice.
