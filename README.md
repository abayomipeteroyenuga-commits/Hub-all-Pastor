# PASTOR ABAYOMI BIBLE STORIES HUB v3

Recommended domain: **hub.pastorabayomibiblestorykids.org**

## v3 ecosystem
The Hub now contains **22 applications** and **22 installable Hub PWA launchers**.

### Newly integrated / upgraded builds
- **Bible Audio** — audio.pastorabayomibiblestorykids.org
- **Bible Memory Centre** — memory.pastorabayomibiblestorykids.org
- **Resource Studio** — resources.pastorabayomibiblestorykids.org
- **Certificate & Achievement Centre** — certificate.pastorabayomibiblestorykids.org (upgrades the earlier Certificate card)

## Hub features
- 22 application cards
- Search and category filters
- Local favourites
- Latest Builds section
- Expanded Quick Access
- Every app opens in a separate browser tab/window
- Every app card includes **Install App**
- 22 distinct Hub-origin launcher manifests
- Shared 192×192 and 512×512 PASTOR ABAYOMI BIBLE STORIES icons
- Hub itself is installable as a PWA
- Cache version upgraded to v3

## Important PWA architecture note
The 22 services live on separate subdomains. This Hub provides installable launcher PWAs from the Hub origin. Fully native origin-level offline/install behaviour for an individual service still requires that service's own manifest and service worker to be deployed in its own repository.
