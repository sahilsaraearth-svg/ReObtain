# ReObtain

**Get Android app updates straight from the source.**

ReObtain lets you track and install Android apps directly from GitHub, GitLab, F-Droid, APKMirror, and 20+ other sources — no app store required. No middleman, no delays, no account needed.

Built and maintained by **sahilcodex**.

---

## 📥 Install

Download the latest APK from the [Releases](../../releases) page.

Requires Android 8.0+ (arm64).

---

## ✨ Features

- **Track apps from 20+ sources** — GitHub, GitLab, F-Droid, APKMirror, APKPure, Huawei AppGallery, IzzyOnDroid, and more
- **Bulk Import from Device** — Select installed apps and ReObtain finds their sources automatically. No URL hunting.
- **Background update checks** — Get notified when updates are available, even when the app is closed
- **Installer choice** — Use the built-in installer or send APKs to InstallerX, App Manager, or any privileged installer
- **Folders** — Organise your app list with named folders, auto-assignment rules, and independent view settings per folder
- **Configurable swipe gestures** — Set left/right swipe actions per row (Update, Install, Pin, Edit, Delete, Open, etc.)
- **Custom app icons** — Set your own icon for any tracked app from gallery or web
- **Skip Version** — Pass on a release without marking the app as updated
- **Update size preview** — See exact download size before hitting update
- **Undo on delete** — 5-second undo snackbar after any delete action
- **On-Demand Only mode** — Hide rarely-updated apps from the main list
- **Save assets** — Save APKs to a folder of your choice during the update process

## 🎨 UI

- Material 3 design throughout
- Dynamic color (Material You) + 9 preset palettes + custom hex accent
- Per-app color theming derived from app icon
- True black / gradient background options
- Adjustable UI scale
- Inline search, collapsible action bars, card-grouped settings

## 🔧 Smart Version Tracking

Six distinct version states instead of a binary up-to-date/not:
- Up to date
- Update available
- Device is ahead
- Same version shown differently
- Genuinely unclear
- Not installed

Editable package ID on the app page — fixes broken install detection instantly.

---

## 🔄 Import from Obtainium

Already using Obtainium? Bring everything over:

1. In Obtainium → Import/Export → **Export** → save the `.json`
2. In ReObtain → Import/Export → **Import** → select that file

All your tracked apps carry over instantly.

---

## Build from Source

```bash
git clone https://github.com/sahilsaraearth-svg/ReObtain.git
cd ReObtain
flutter pub get
flutter build apk --flavor normal --target-platform android-arm64 --split-per-abi
```

Requires Flutter 3.10+, Android SDK, NDK 28.2.13676358.

---

## License

GPL-3.0 — see [LICENSE](./LICENSE)
