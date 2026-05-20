# zsaistack-media

Public media hosting for the `ig-zsaistack-pipeline` Instagram pipeline
(`@zsaistack`). The Instagram Graph API can only fetch media from public URLs
— this repo serves the day's rendered slide PNGs over GitHub Pages so the
Graph API can pull them at publish time.

- Each day's media lives at `<YYYY-MM-DD_HHMMSS>/slide-N.png` etc.
- The selftest image lives at `selftest/test.png`.
- `push-media.js` from the pipeline copies + pushes here at bundle time.
- Public only because the images are about-to-be-posted; nothing sensitive.
