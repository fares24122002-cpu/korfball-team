# Korfball Team Manager (standalone)

A phone-installable app that stores everything locally on the device — no
account, no server, no internet needed once installed.

## Get it onto your phone (GitHub Pages — free, ~5 minutes)

1. Go to github.com and sign in (or create a free account).
2. Click **New repository**. Name it e.g. `korfball-team`. Keep it Public. Create it.
3. Click **Add file → Upload files**, then drag in all 5 files from this
   folder: `index.html`, `manifest.json`, `icon.svg`, `sw.js`, `README.md`.
   Commit the upload.
4. In the repo, go to **Settings → Pages**. Under "Build and deployment",
   set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
   Save.
5. Wait ~1 minute, then refresh — GitHub shows your live URL, something like
   `https://yourusername.github.io/korfball-team/`.
6. Open that URL on your phone's browser (Safari on iPhone, Chrome on
   Android).
7. Tap **Share → Add to Home Screen** (iPhone) or the **⋮ menu → Install
   app / Add to Home screen** (Android).
8. Open it from the home screen icon — it now runs like a normal app.

## About your data

- Everything (squad, matches, training, tasks) is saved in the browser's
  local storage **on that specific phone**.
- It will NOT appear on a different phone or in this Claude chat — it's
  local to the device you installed it on.
- Because it's local-only, there's no automatic backup. If you clear
  Safari/Chrome site data or get a new phone, the data is gone unless you
  back it up yourself.
- If you'd rather have your data follow you across devices, that needs a
  small sync backend added later — just ask.

## Making changes later

Edit `index.html` (it's a single self-contained file — HTML, CSS and
JavaScript all in one), re-upload it to the same GitHub repo, and the live
site updates automatically within a minute.
