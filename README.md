# DragonNet Home Assistant

DragonNet Home Assistant is a private link between its owner's own Home Assistant and his own Google account.
It is not a public service.

This repository holds only the link's public information pages, which Google requires for an OAuth app:

| Page | URL |
|---|---|
| Home | <https://jrcuster.github.io/dragonnet-home/> |
| Privacy policy | <https://jrcuster.github.io/dragonnet-home/privacy.html> |

## Repository layout

```
docs/          GitHub Pages site (published from the main branch, /docs folder)
  index.html   home page
  privacy.html privacy policy
  style.css    shared styles
```

## Conventions

- Plain static HTML and CSS: no build step, no scripts, no trackers.
- The pages carry no personal information beyond the app name and the maintainer's GitHub handle.
- Changes to `docs/` go live on GitHub Pages within a few minutes of a push to `main`.
