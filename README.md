# cloudbase-airspace

Public-domain airspace packs (OpenAIR) for the **Cloudbase** paragliding app,
served via GitHub Pages (Fastly CDN). The app reads `manifest.json` and lets
pilots download their region's airspace — no account or API key.

- **Data:** FAA (US Government public domain, 17 U.S.C. §105) — redistributable.
  **Not for navigation.** Currently Class B/C/D for all 50 US states + DC + PR + VI (53 regions).
- **Regenerate:** `Slide/Cloudbase/tools/faa-airspace/build.mjs` in the app repo
  (`CDN_BASE=https://kayo261.github.io/cloudbase-airspace CLASSES=B,C,D node build.mjs <STATES>`).
