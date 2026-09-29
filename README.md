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
- `ironlog-v1.0.ipa` — current signed build
- `icon.png` / `header.png` — source branding (placeholders; drop in your own)

## Updating

When a new build is ready: replace `ironlog-v1.0.ipa`, bump the version fields in `apps.json`, and `git push`. SideStore picks up the new version on next refresh.
