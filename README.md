# ironlog-sidestore

SideStore / AltStore source for [IronLog MBE](https://github.com/Wingzii/IronLog).

## Add this source to SideStore

Paste this URL into SideStore → Sources → "+":

```
https://raw.githubusercontent.com/Wingzii/ironlog-sidestore/main/apps.json
```

Or open this deeplink on your iPhone (SideStore must already be installed):

```
sidestore://source?url=https://raw.githubusercontent.com/Wingzii/ironlog-sidestore/main/apps.json
```

## What lives here

- `apps.json` — the AltSource manifest
- `ironlog-v929.ipa` — current signed build (v929, commit e2f4078, 77 MB)
- `icon.png` / `header.png` — source branding (extracted from the app bundle, upscaled)

## Updating

When a new build is ready: replace `ironlog-v<N>.ipa`, bump the `version` / `versionDate` / `size` / `downloadURL` / `versionDescription` fields in `apps.json`, and `git push`. SideStore picks up the new version on next refresh.
