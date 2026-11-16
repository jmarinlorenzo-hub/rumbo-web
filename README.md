# Rumbo website

Static site (HTML + CSS, no frameworks, no scripts, no Jekyll) for GitHub Pages.
English at the root, Spanish in `es/`.

Published at: https://jmarinlorenzo-hub.github.io/rumbo-web/

| Page | English | Spanish |
|---|---|---|
| Home | `index.html` | `es/index.html` |
| Manual (from the app's Help) | `manual.html` | `es/manual.html` |
| Privacy policy | `privacy.html` | `es/privacy.html` |

## Publish (GitHub Pages)

1. Create a **public** repo named `rumbo-web` on GitHub (empty).
2. `git remote add origin https://github.com/jmarinlorenzo-hub/rumbo-web.git` and `git push -u origin main`.
3. Repo **Settings > Pages > Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
4. The privacy policy URL for Google Play Console is
   `https://jmarinlorenzo-hub.github.io/rumbo-web/privacy.html`.

## Where the personal values are

Written directly in the HTML (no scripts). To change them, use "Replace in files":

| Value | Text to search |
|---|---|
| Contact email | `rumbo.podcast.app@gmail.com` |
| Buy Me a Coffee | `https://buymeacoffee.com/jmarinlorenzo` |
| GitHub profile | `https://github.com/jmarinlorenzo-hub` |
| Site address | `https://jmarinlorenzo-hub.github.io/rumbo-web/` |

## Screenshots

The home pages show four placeholders: `assets/screens/screen-1.placeholder.svg` to
`screen-4.placeholder.svg` (Podcasts, Playlists, Player, Subscribe; about 9:19 portrait).

1. Save your real screenshots as `assets/screens/screen-1.png` ... `screen-4.png`.
2. In `index.html` and `es/index.html`, replace `.placeholder.svg` with `.png`.
3. Delete the placeholder files.

## Google Play button

It is disabled ("Coming soon" / "Próximamente"). When the app is published, in
`index.html` and `es/index.html` replace the `<button ... disabled>` block with a link
to the Play listing.

## Privacy policy

Dated 16 November 2026. Update the date (both languages) when it changes, and keep it in
line with the app's permissions and connections.
