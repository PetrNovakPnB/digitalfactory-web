# digitalfactory-web

Public static site hosted on GitHub Pages. It serves:

- **Privacy policy** for *PixelPerfect: HEIC to JPG Converter* —
  [`pixelperfect-heic-privacy.html`](pixelperfect-heic-privacy.html)
- **App configuration feed** read by the desktop apps —
  [`apps-config.json`](apps-config.json)

## apps-config.json

Public runtime configuration for the apps: optional promotions, feature flags,
cross-promotion entries and bundle definitions (schema version 2). It is fetched
at most once per day, is opt-in in the app, and the app works fully without it.

Prices shown in the store are owned by the Microsoft Store; this file never acts
as the source of truth for pricing.
