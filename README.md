# mptv-updates

Public update feed for the MPTV Android TV app. MPTV checks `update.json` on the `main` branch and downloads the APK from this repo's Releases.

**Do not delete, rename or make this repo private** — customer TVs would stop receiving updates.

## Shipping a new version
1. Create a Release tagged `vX.Y.Z` and attach `mptv-X.Y.Z-tv.apk`.
2. Edit `update.json`: set `version`, `versionCode` (from the APK) and `apkUrl` to the new asset.
