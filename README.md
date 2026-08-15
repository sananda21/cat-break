# Cat Break 🐾

A small, cozy webpage for looking at cats for a minute. Built to be simple, calming, and require nothing but a browser.

**Live site:** https://sananda21.github.io/cat-break/
Also available at https://cat-break.netlify.app/

## What it does

- Shows a random cat photo/gif on load
- **Next cat** button to fetch a new one anytime
- **Auto-play** toggle to rotate a new cat every 6 seconds, hands-free
- A rotating line of gentle, low-key encouragement under each cat
- Soft floating paw prints drifting in the background

## How it works

The cat images/gifs come from [cataas.com](https://cataas.com) ("Cat as a Service"), a free public API that returns a random cat image or gif on every request — no API key or sign-up required. Each time you click **Next cat**, the page requests a fresh one.

Everything else — layout, colors, fonts, animation — is a single self-contained `index.html` file. No build step, no dependencies, no backend.

## Tech

- Plain HTML, CSS, and vanilla JavaScript (no frameworks)
- Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) (headings) and [Karla](https://fonts.google.com/specimen/Karla) (body), via Google Fonts
- Images/gifs: [cataas.com](https://cataas.com)

## Running it locally

No build tools needed — just open the file:

```bash
git clone https://github.com/sananda21/cat-break.git
cd cat-break
open index.html   # macOS
# or just double-click index.html in your file explorer
```

## Deploying changes

This site is hosted with GitHub Pages, serving straight from the `main` branch. To publish an update:

```bash
git add .
git commit -m "describe your change here"
git push
```

GitHub Pages picks up the change automatically within a minute or two.


## License

Personal project, made for fun and comfort. Cat images/gifs are served by cataas.com and are not owned by this repo.
