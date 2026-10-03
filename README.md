# PASTOR ABAYOMI BIBLE STORIES HUB v1

Recommended domain: **hub.pastorabayomibiblestorykids.org**

Includes 19 application cards, search, category filters, local favourites, quick access, responsive UI, PWA support, and every app opens in a separate browser window/tab.


## v2 — 19 PWA app launchers
- The Hub itself remains installable as a PWA.
- All 19 app cards now include an **Install App** action.
- Each app has a distinct web-app manifest identity and standalone start URL under `/pwa/`.
- Shared 192×192 and 512×512 PASTOR ABAYOMI BIBLE STORIES icons are included.
- Supports Chromium install prompts and browser-menu installation; iPhone/iPad users can use Safari **Share → Add to Home Screen**.
- Each installed launcher opens the live app service in a separate browser window/tab.
- Important: because the 19 services are hosted on different subdomains, fully native origin-level offline PWA behavior still requires a manifest and service worker deployed inside each individual app repository. This Hub package provides installable launcher PWAs from the Hub origin.
