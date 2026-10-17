# Undistract

Block distracting apps (and their websites) at set times or after a daily time limit, with an optional accountability partner who approves before you can loosen your rules. Free, no ads.

This repository only hosts release downloads. Get the latest APK from **[Releases](../../releases/latest)**.

## Install

1. On your Android phone (Android 10 or newer), download `undistract-<version>.apk` from the latest release.
2. Open it. If Android asks, allow your browser or file manager to **install unknown apps**.
3. Open Undistract and follow the setup:
   - **See which app is open** (Accessibility): Settings → Accessibility → Installed apps → Undistract → On. If Android says it's a **restricted setting**, go to Settings → Apps → Undistract → ⋮ → **Allow restricted settings**, then try again. Leave Undistract's "shortcut" switch off.
   - **See screen time** (Usage access), needed for daily limits.

### "App blocked to protect your device"

In some countries (including India), Google Play Protect blocks installing any app from a browser, messaging app or file manager if it uses Accessibility, which Undistract needs to see which app is open. It's a blanket rule for that permission, not a finding about this app. Until Undistract is on the Play Store, the ways around it are:

- **Install from a computer over USB** with `adb install undistract-<version>.apk` (needs USB debugging on). This isn't affected.
- Or temporarily turn off Play Protect scanning (Play Store → profile → Play Protect → ⚙ → Scan apps with Play Protect), install, then turn it back on. Only do this if you trust the download (check the SHA-256 below).

### Automatic updates (optional)

Install [Obtainium](https://github.com/ImranR98/Obtainium) and add this repository's URL. It will notify you about new releases.

## Verify the download

Each release lists the APK's SHA-256. All releases are signed with the same key:

```
SHA-256 of signing certificate:
66:29:70:0E:9C:90:1B:2E:8B:18:E6:40:2E:39:56:9C:E1:86:65:0D:F5:71:48:53:03:B7:5F:AB:23:4E:01:A5
```

## Privacy

Blocking and screen time stay on your phone. The optional accountability partner feature sends your name, your partner's email and the change requests through a server. No ads, no analytics.
