# updates/

Over-the-air update files for the Rosin app, written by `scripts/release/ota/publish-ota.sh` in the app repo (docs/services/ota-updates.md). Every manifest is signed offline; the app refuses anything else. Do not edit by hand.

- `assets/<sha256>.<ext>`: content-addressed bundles and assets
- `channels/<channel>/android/<runtime>/current.json`: what the update endpoint serves
- `channels/<channel>/android/<runtime>/history/`: every update published there
