# ydbendasan.github.io

GitHub Pages user site serving [Apex Swing](https://github.com/ydbendasan/NovaIntel):

- `index.html` — the single-file game build, deployed by the NovaIntel repo's
  `deploy-pages.yml` workflow (do not edit by hand; it gets overwritten).
- `privacy.html` / `support.html` — the store-listing privacy policy and
  support pages (also deployed from NovaIntel).
- `.well-known/assetlinks.json` — Android App Links digital asset link for
  `com.ydbendasan.apexswing`, so `https://ydbendasan.github.io/` share links
  open the installed app. Managed **here** (the deploy workflow never touches
  it). The SHA-256 fingerprint must match the Play App Signing key
  certificate: Play Console → Setup → App signing.
