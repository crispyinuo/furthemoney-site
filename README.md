# Fur the Money — website

Marketing site for **Fur the Money** (小猫有薪事), a SwiftUI app for iPhone, iPad
and Mac that draws your workday as an illustrated office and counts your pay as
it earns. App store release: 23 October 2026.

A single static page. No build step, no dependencies, no tracking. Open
`index.html`, or serve the folder:

```sh
python3 -m http.server
```

## What's in here

- `index.html` — the whole site: markup, styles and a little script that ticks
  the example earnings and cycles the cat's walk frames
- `img/` — artwork lifted from the app and downscaled for the web: the office
  illustration, the eight-frame walk cycle, two resting cat poses, the paper
  texture and the app icon

Palette and type match the app itself: the colors come from `Art.swift`, and the
headings use Baloo 2, the app's own Latin face.

The figures on the page (an example 09:00–17:30 day at $34/hr) are illustrations
of the app, not anyone's real pay, and are labelled as such. None of the
controls do anything; this is a marketing page, not the app.

## To do before launch

- Link the App Store page once the app is live
- Add privacy and support pages, and link them from the footer

© Yinuo Zhou. App artwork and copy all rights reserved.
