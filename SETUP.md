# Putting this live

Your GitHub profile README comes from the special repo named exactly your
username: `jay7-tech/jay7-tech`.

## 1. Replace the files

Copy everything in this folder into the root of `jay7-tech/jay7-tech`,
overwriting what's there:

```
jay7-tech/jay7-tech/
├── README.md
├── assets/
│   ├── hero.svg
│   ├── notepad-about.svg
│   ├── explorer-projects.svg
│   ├── nav-portfolio.svg
│   ├── nav-linkedin.svg
│   ├── nav-email.svg
│   ├── nav-resume.svg
│   ├── icon-about.svg
│   ├── icon-skills.svg
│   ├── icon-experience.svg
│   ├── icon-projects.svg
│   ├── icon-telemetry.svg
│   └── icon-window.svg
└── .github/workflows/profile-live.yml
```

A tip from last time: GitHub's drag-and-drop "Upload files" box can drop the
folder structure on hidden/dot folders. If `.github/workflows/profile-live.yml`
doesn't land in the right place, open it after uploading, click the pencil to
edit, and change the filename field at the top to the full path
`.github/workflows/profile-live.yml` — GitHub moves it there on commit.

## 2. Turn on the live section (optional, 2 minutes)

1. Push the files above, go to the **Actions** tab, and confirm "Live
   profile telemetry" runs green (click "I understand my workflows, go
   ahead and enable them" if it's the first Action on this repo).
2. After it finishes, `assets/github-languages.svg` and
   `assets/github-snake.svg` will exist and the "LIVE" section of the
   README will fill in with your real language mix and a contribution
   snake, both regenerated automatically every 6 hours.

If you want deeper stats later, add a classic Personal Access Token with
the `repo` scope as a repo secret named `METRICS_TOKEN`
(Settings → Secrets and variables → Actions → New repository secret). The
workflow already falls back to the default token without it.

## 3. If you'd rather skip the Actions setup

Delete the whole "LIVE" section from `README.md` (and the workflow file) —
everything else is fully static and needs no setup.

## What changed in this round

- Hero: bigger, bolder name treatment with a glowing double helix
  "AI / connection" motif, and a kicker line that reads AI, ML, Software,
  Robotics instead of just Robotics.
- Nav row: the four shields.io badges are replaced with custom icon chips
  (assets/nav-*.svg) in the same visual language as the hero.
- Section headers use small custom icons (assets/icon-*.svg) instead of
  emoji.
- Experience is now a real wrapping table instead of a fixed-width ASCII
  block, so it reads cleanly at any screen width.
- Each project title links straight to its repo.
- Copy was passed through to remove dash-as-punctuation constructions.
- The "LIVE" section drops the generic header/activity metrics card and
  shows only a language breakdown plus the contribution snake.
