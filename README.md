# albansalihaj.ch

Personal portfolio site for Alban Salihaj — Business Intelligence & Analytics Lead.

Live at [albansalihaj.ch](https://albansalihaj.ch) · German version at [albansalihaj.ch/de](https://albansalihaj.ch/de)

## Stack

Plain HTML, CSS, and vanilla JavaScript — no framework, no build step. Fonts via Google Fonts (Manrope, JetBrains Mono).

## Structure

```
index.html          English homepage
de/index.html        German homepage
css/style.css         Shared styles
js/main.js            Nav, scroll spy, reveal animations, stat counters
assets/               Resume PDF and profile photo
```

## Local development

Serve the folder with any static file server, e.g.:

```
npx serve .
```

## Deployment

Hosted on Netlify, auto-deploying from the `main` branch. Custom domain `albansalihaj.ch` is configured at Infomaniak (DNS only — nameservers stay with Infomaniak so email hosting is unaffected).

## Editing content

- Update copy directly in `index.html` / `de/index.html`.
- Replace `assets/resume.pdf` to update the downloadable CV.
- Replace `assets/profile.jpg` to update the hero photo.
