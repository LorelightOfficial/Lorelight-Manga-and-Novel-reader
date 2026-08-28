<div align="center">

# 🌿 Lorelight

**A calm, forest-themed reading companion for Android.**\
Web novels, manga, and hands-free text-to-speech in one offline-first library.

[![Latest release](https://img.shields.io/github/v/release/LorelightOfficial/lore-app-link?label=latest%20release&color=2e7d32)](https://github.com/LorelightOfficial/lore-app-link/releases/latest)
[![Build](https://github.com/LorelightOfficial/lore-app-link/actions/workflows/build-and-release.yml/badge.svg)](https://github.com/LorelightOfficial/lore-app-link/actions/workflows/build-and-release.yml)
[![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-3ddc84?logo=android&logoColor=white)](#requirements)
[![Built with Kotlin](https://img.shields.io/badge/Built%20with-Kotlin%20%26%20Jetpack%20Compose-7f52ff?logo=kotlin&logoColor=white)](#about)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-1f6feb)](LICENSE)

[Download](#download) · [Features](#features) · [Contributing](CONTRIBUTING.md) · [Security](SECURITY.md)

</div>

---

## About

Lorelight is a self-contained Android reader for long-form web fiction and comics. It pulls chapters from community-maintained sources, keeps them available offline, and can read them aloud in the background with full media controls — so a novel keeps going while the screen is off. The interface is built around quiet, nature-inspired themes instead of dense list UI.

The app is sideloaded and free. No ads, no accounts, no analytics, no tracking. Every release published here is built and signed automatically by the workflow in this repository, from the same source the maintainer develops — see [Release process](#release-process) below.

## Features

**Library and reading**
- Offline-first library with 3D book covers, categories, filters, and reading history
- Configurable reader: fonts, spacing, margins, themes, gestures, and volume-key paging
- Reading position saved automatically per chapter
- EPUB import and export

**Text-to-speech**
- Background playback with a media-style notification and lock-screen controls
- Voice, speed, pitch, and sentence-tracking controls
- Manga panels read aloud using bundled offline OCR, no network round-trip

**Sources and content**
- Plugin-based source system with global search across enabled sources
- Compatibility with community manga extension repositories
- Chapter crawler with a download queue and offline caching

**Manga reader**
- Webtoon and paged modes, tap zones, autoscroll, and tall-image handling

**Maintenance and privacy**
- Scheduled library updates with new-chapter notifications
- Backup and restore, with automatic recovery if a backup goes missing
- Incognito mode and 70+ interface languages

## Download

Signed APKs are published on the [Releases page](https://github.com/LorelightOfficial/lore-app-link/releases/latest).

| File | Choose this when |
| --- | --- |
| `Lorelight-<version>-arm64-v8a.apk` | Almost every phone from 2017 onward — **start here** |
| `Lorelight-<version>-armeabi-v7a.apk` | Older 32-bit ARM devices |
| `Lorelight-<version>-x86_64.apk` | Emulators, ChromeOS, x86 tablets |
| `Lorelight-<version>-universal.apk` | Not sure which to pick; largest download |

Android will ask for permission to install from an unknown source the first time. Installing a newer APK over an existing one keeps your library, as the release is always signed with the same key.

## Requirements

| | |
| --- | --- |
| Minimum Android | 7.0 Nougat (API 24) |
| Architectures | arm64-v8a, armeabi-v7a, x86, x86_64 |
| Permissions | Internet, foreground service (playback and sync), notifications, wake lock |

Lorelight does not request storage, package-install, or package-query permissions.

## Release process

This repository is the public face of the project: it publishes signed releases and project documentation. The application source is maintained in a private repository and is not published here. Each release is produced by the [`build-and-release`](.github/workflows/build-and-release.yml) workflow, which fetches the source at build time, compiles and signs it, and publishes the resulting APKs directly to this repo's Releases page — so every download traces back to an auditable, automated build rather than a manually uploaded file.

## Contributing

Source code isn't hosted in this repository, so contributions here are bug reports, feature requests, and translation feedback. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Security

Found a vulnerability? Please use the private reporting process in [SECURITY.md](SECURITY.md) rather than a public issue.

## License and acknowledgements

Released under the [Apache License 2.0](LICENSE).

Lorelight includes and adapts work from [Mihon](https://github.com/mihonapp/mihon) and Tachiyomi (Apache-2.0), [LNReader](https://github.com/LNReader/lnreader), and open-source libraries including OkHttp, Jsoup, Coil, and Google ML Kit.

Lorelight hosts no copyrighted content of its own: every chapter comes from a third-party source the user chooses to add.
