# Patreon TV

A free, open app that brings Patreon video content to your Smart TV, Fire TV Stick, or Android TV device.

Patreon doesn't offer a native TV app, so if you're a paying patron who wants to watch creator videos on your TV, you're stuck casting from your phone or using a browser — neither of which is a great couch experience. Patreon TV fixes that.

## What It Does

- **Browse your subscriptions** — see all the creators you support, with avatars and names
- **Watch exclusive video posts** — HLS and MP4 playback, right on your TV
- **Navigate with your remote** — full D-Pad support, designed for Fire TV and Android TV remotes
- **Stay logged in** — your session persists across app launches, no re-entering credentials every time
- **Auto-update** — the app checks for new versions and lets you update with one click

## Install

### Fire TV (Downloader App)

1. Open the **Downloader** app on your Fire TV
2. Enter code: **`2329486`**
3. The APK will download and prompt you to install

### Manual Install

1. Download the latest APK from the [Releases](https://github.com/niftiest/patreon-tv-releases/releases) page
2. Sideload it onto your device:
   - **Fire TV**: Use [Downloader](https://www.amazon.com/dp/B01N0BP507) or `adb install patreon-tv.apk`
   - **Android TV**: Use a file manager or `adb install patreon-tv.apk`
   - **Phone/Tablet**: Just open the APK

### Direct Download URL

```
https://github.com/niftiest/patreon-tv-releases/releases/latest/download/patreon-tv.apk
```

This URL always points to the latest version.

## How It Works

Everything runs locally on your device — there's no external server involved. The app bundles a lightweight web server that handles all communication with Patreon's API directly from your TV. Your credentials never leave your device.

## Requirements

- Android 5.1+ (API 22)
- An active Patreon account with at least one paid subscription
- Internet connection

## Login Options

- **Email & Password** — enter your Patreon credentials directly
- **Session ID** — if you use Google/Facebook/Apple to sign in to Patreon, you can paste your `session_id` cookie from a browser instead

## FAQ

**Is this affiliated with Patreon?**
No. This is an independent project. Patreon doesn't offer a TV app, so this fills the gap for paying patrons.

**Is my data safe?**
Yes. The app runs entirely on your device. No data is sent to any third-party server. Authentication goes directly between your device and Patreon's servers.

**What video formats are supported?**
HLS (most Patreon videos), MP4, and embedded videos (Vimeo, YouTube) via iframe.

**Does it work on regular Android phones/tablets?**
Yes, though the UI is optimized for TV screens and remote navigation.

## Updating

When a new version is available, an update button will appear on the main screen. Tap it to download and install the update directly.
