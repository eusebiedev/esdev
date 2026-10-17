# EusebieDev Portfolio

Personal developer portfolio for EusebieDev: a front-end engineer (React, Next.js, TypeScript)
moving full stack.

Static site in vanilla HTML and CSS. No framework, no build step, no JavaScript. The design is
Swiss Industrial Print: paper and ink with one oxblood accent, a 1px blueprint grid, and a short
terminal-style hero that types in with CSS only. No analytics, trackers or third-party requests.

**Status:** work in progress. Some content and project links are still placeholders.
The contact form is a disabled scaffold; LinkedIn is the current contact route.

## Local preview

No install step. From the repository root:

```sh
python3 -m http.server 8000 --bind 0.0.0.0
```

Open http://localhost:8000. Serve over HTTP rather than opening `index.html` with `file://`
so asset paths and fonts behave like production. Stop the server with Ctrl+C when finished.

## Files

```
index.html            hero, work index, stack inventory, contact
assets/css/style.css  all styles
assets/fonts/         self-hosted woff2 fonts (Archivo Black, JetBrains Mono, Playfair Display; SIL OFL)
assets/images/        profile image and other local images
```

## License

All rights reserved. See [LICENSE](LICENSE).
