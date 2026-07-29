# D-10 Trainer

A single-file, offline-capable web app that guides and tracks a seven-period
periodized training program (**D-10 2019 Prep**). Built to live on a phone's
home screen and shareable with anyone via a single link.

No accounts, no backend, no build step — it's one `index.html` file.

## What it does

- **Full program, P1 → P7** — Intro/GPP, Hypertrophy 1 & 2, Strength, Power/Strength,
  Realization, and Last Kick, on a cool-to-hot period spine.
- **Every lift** with its week-by-week progression (sets, reps, tempo, rest, warm-up
  loads), plus the top-sheet **Session 1** speed / acceleration / agility / decel /
  COD field work for each training day.
- **Per-set logging** — weight × reps with a done check; jump and vertec work logs a
  single height/distance value per set.
- **Last-week ghost values** show under each set so you always know the number to beat.
- **Extra-credit reps** flagged as optional.
- **Conditioning** built out faithfully: row/run interval series with per-week work and
  rest, each rep with its own start button.
- **Timers** — a rest countdown on every lift and a work/rest interval timer on
  conditioning days. Both buzz at zero.
- **Weekly progression** via the WK pips; browse any period, week, or day.

## Your log stays on your phone

Everything you enter saves to **that device only** (browser local storage). Share the
same link with training partners and each person keeps their own private log — nobody
sees anyone else's numbers.

## Use it on your phone

1. Open the live URL in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. It launches full-screen like an app and works offline.

## Hosting (GitHub Pages)

1. Put `index.html` in the **root** of this repository.
2. **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save.**
3. Wait ~1–2 minutes; your site goes live at `https://<username>.github.io/<repo>/`.

### Updating

Replace `index.html` in the repo (edit in place or re-upload) and commit. It redeploys
at the same URL within a minute. Your saved workout log is unaffected — updates change
the program, not your data.

## Notes

- The whole app is one file with zero external dependencies, so it loads instantly and
  runs with no network once installed.
- Prescriptions come straight from the source program sheets. If a number ever reads
  wrong against the paper, the fix is a one-line edit in the data section near the top
  of `index.html`.

---

*Personal training tool. Not medical or coaching advice — train sensibly.*
