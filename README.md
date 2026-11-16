# Locked In

Italian iPhone-first progressive web app.

## Current features
- Focus timer with start, pause and reset.
- Daily usage target saved in local browser storage.
- Completed focus-session counter and accumulated focus minutes.
- Direct links to official Instagram, YouTube and TikTok websites.
- PWA manifest and service worker for an offline app shell.

## Platform limits
A PWA cannot remove Reels or Shorts from the official native apps, inspect their screens, or impose iOS system app shields. Those features require a separately developed native iOS application and Apple's Screen Time APIs/entitlements where approved. This MVP does not claim to perform those actions.

## Deployment
GitHub Pages workflow is configured in `.github/workflows/deploy.yml`. Enable GitHub Pages with **GitHub Actions** as the build and deployment source in repository Settings → Pages if it is not already enabled.