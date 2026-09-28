# AvaFix Crew Logbook

A single-file Android WebView app for tracking crew duty hours.

## Project structure

- `app/index.html` : complete app (HTML + CSS + JS), no build step, no external dependencies.
- Original APK: `app-release.apk` contains only `assets/index.html`, `classes.dex`, resources, manifest.

## Run locally

Open `app/index.html` directly in any modern browser. No server is required.

## Rebuild / edit

Because the app is a single HTML file, edits are done directly in `app/index.html`:
open it in a text editor, modify markup/styles/JavaScript, save, then repackage into the APK
(if needed) by zipping it back as `assets/index.html`.

## GitHub setup

1. Create a new empty GitHub repository.
2. Push the contents of this folder:

```bash
git init
git add .
git commit -m "Initial commit: AvaFix Crew Logbook"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```
