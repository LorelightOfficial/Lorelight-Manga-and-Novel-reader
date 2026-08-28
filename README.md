<div align="center">

# Lorelight

**Manga & Novel Reader — with a voice.**

[![Release](https://img.shields.io/github/v/release/LorelightOfficial/Lorelight-Manga-and-Novel-reader?label=latest&style=for-the-badge)](https://github.com/LorelightOfficial/Lorelight-Manga-and-Novel-reader/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/LorelightOfficial/Lorelight-Manga-and-Novel-reader/total?style=for-the-badge)](https://github.com/LorelightOfficial/Lorelight-Manga-and-Novel-reader/releases)
[![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)](#requirements)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge)](LICENSE)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/nyFMhq9EFw)

</div>

---

**Lorelight is one Android app for everything you read — web novels, EPUBs and manga — and it reads them out loud to you.** Your whole library lives in a single offline-first shelf with animated 3D covers, and opens into a reader you can tune down to the line spacing, paragraph gap, text alignment and exact letter colour, with any font you like — bundled system faces or thousands pulled live from the Google Fonts catalogue. Then, when your eyes give out, Lorelight keeps going: full background text-to-speech with lock-screen and notification controls, per-sentence and per-paragraph pause tuning, speech pacing, accent and voice selection, a sleep timer, sentence highlighting that follows the narrator, and automatic chapter-to-chapter advance so a whole novel can play like an audiobook. **Manga gets narrated too** — an on-device OCR engine reads the actual speech bubbles off the page, in reading order, stitching dialogue that spills across a page break, correcting stylised lettering it knows it misreads, and skipping the watermarks and site names it knows aren't story. Everything is yours: add novel sources from community plugin repositories and manga sources from Mihon/Tachiyomi-compatible extension repos, follow series and let background checks notify you the moment a new chapter drops, download it all for the commute, and dress the whole app in one of nine handcrafted palettes with a sun-and-moon theme switch that draws itself. No account, no sign-up, no telemetry, no ads.

---

## Download

Grab the latest signed APK from the [**Releases page**](https://github.com/LorelightOfficial/Lorelight-Manga-and-Novel-reader/releases/latest).

| Your device | Download |
|---|---|
| Most phones & tablets from ~2017 onward | `arm64-v8a` |
| Older / budget 32-bit devices | `armeabi-v7a` |
| Emulators, ChromeOS, x86 tablets | `x86_64` or `x86` |

Not sure? Take `arm64-v8a` — it fits almost every modern Android phone.

> Every release here is built and signed automatically, so what you download is exactly what came out of the build — nothing hand-assembled in between.

### Requirements

- **Android 7.0 (Nougat) or newer**
- ~150 MB free space to start, plus whatever you download
- A text-to-speech engine for voice playback (Google's is preinstalled on nearly every device)
- **No storage permission required** — Lorelight never asks for access to your files

---

## What's inside

### Read
- Web novels, imported **EPUB** files, and **manga** in the same library
- Reader controls for text size, line spacing, paragraph spacing, margins, alignment and justification
- **Typography that's actually yours** — system fonts plus a searchable, downloadable Google Fonts catalogue with a live preview
- Custom text colour, background style and highlight accent, plus a true **AMOLED black** mode
- Immersive full-screen reading, volume-key page turning, auto-advance to the next chapter
- **Text filter rules** — find-and-replace anything ugly in a chapter (global or just for one book), clever enough to catch spam written as `f.r.e.e`, `F R E E` or `fr33`
- Reading position is remembered per chapter, to the pixel, and survives crashes

### Listen
- Real background playback: **notification and lock-screen controls** for play/pause, next/previous sentence and next/previous chapter
- Pauses itself when you unplug your headphones
- Speech speed and pacing, voice **accent by region**, and independent pause lengths between sentences and paragraphs
- **Sleep timer** for reading yourself to sleep
- The current sentence highlights as it's spoken, and the page follows along
- Playback continues chapter after chapter, and resumes exactly where it stopped

### Manga
- **Paged** and **Long Strip (Webtoon)** modes, fit-width / fit-height / fit-screen scaling, double-tap zoom
- Configurable **tap zones** (standard, L-shape, left/right, invertible) with an on-screen overlay, plus volume-key page turning
- Autoscroll with adjustable speed and pause-on-tap, orientation lock, keep-screen-on, grayscale and colour inversion, border cropping, page slider and page counter
- Smart page preloading and automatic recovery of stalled page loads
- **Read aloud (beta)** — on-device OCR narrates the page's dialogue: adjustable text detail, cross-page bubble stitching, a misread-word autocorrect list, a skip list for words you never want spoken, and an option to show exactly what it detected
- OCR can be **pre-computed while chapters download**, so narration starts instantly and works fully offline

### Your library
- Animated 3D book covers, grid browsing, filters, and full reading history
- A dedicated **New Chapters** feed and a live **download queue** with per-title control
- **Background chapter checks** on your schedule — Wi-Fi-only, charging-only, skip-completed-titles — with notifications when something new lands
- Offline chapter cache with a storage monitor, plus **EPUB export** of anything you've collected

### Sources
- **Novels:** community plugin repositories (LNReader-compatible), with global search across every source at once, filters, migration between sources, and your own custom repo URLs
- **Manga:** **Mihon / Tachiyomi-compatible extensions**, multi-repo support with per-repo toggles, language filtering, and Shizuku-assisted installation
- Built-in browser with forced dark mode, a **Cloudflare challenge solver**, DNS-over-HTTPS and polite request throttling

### It looks after itself
- **Automatic daily backups** to local storage and, optionally, a folder you pick — plus manual export/import
- A **self-healing engine**: if the app ever crash-loops, it restores your library from the newest good backup on its own, and tells you it did
- Crash and diagnostic logs are kept **on your device only, never uploaded**

### Themes
Nine full palettes, each with matched light and dark variants: **Forest Green**, **Ocean Blue**, **Blood Red**, **Purple**, **Cyan**, **Satin Pink**, **Black Gold**, **Creme White**, and **Midnight OLED Black**. The light/dark toggle is a hand-drawn celestial sun-and-moon altar that animates as it flips — and a small companion who occasionally has something to say about what you're reading.

---

## Privacy

Lorelight has **no accounts, no analytics, no ads and no trackers**. Your library, reading progress, downloads and backups stay on your device. Crash reports exist only so you can read them yourself in Settings; nothing is transmitted anywhere. Network access is used for exactly two things: fetching content from the sources you chose, and downloading fonts or extensions when you ask for them.

The permission list is deliberately short — internet, notifications, foreground playback, wake lock, and installing extension packages. There is no storage permission at all.

---

## Content

Lorelight is a reader, not a library of books. It ships with **no content of its own** and hosts none. What you can read depends entirely on the third-party sources and extensions you choose to add, and those are not affiliated with, endorsed by, or maintained by this project. Please support authors and publishers through official channels wherever they're available.

---

## Support & community

- 🐛 **Found a bug?** [Open an issue](https://github.com/LorelightOfficial/Lorelight-Manga-and-Novel-reader/issues/new/choose)
- 💡 **Have an idea?** [Request a feature](https://github.com/LorelightOfficial/Lorelight-Manga-and-Novel-reader/issues/new/choose)
- 💬 **Want to talk?** [Join the Discord](https://discord.gg/nyFMhq9EFw)
- 🔒 **Security concern?** See [SECURITY.md](SECURITY.md)

Please include your Android version, device model and the app version when reporting a bug — Settings → Advanced & About has all three.

---

## Built with

Kotlin, Jetpack Compose and Material 3, Kotlin Coroutines & Flow, Room and SQLDelight, OkHttp, Coil, Jsoup, ML Kit on-device text recognition, and QuickJS for the source plugin engine.

The app's source code is maintained in a private repository. This repository is Lorelight's public home: it hosts the official releases, documentation, and issue tracker.

---

## License & acknowledgments

Lorelight is released under the [Apache License 2.0](LICENSE).

Manga source and extension compatibility is built on code derived from [**Mihon**](https://github.com/mihonapp/mihon) (Apache-2.0), itself descended from Tachiyomi. Enormous thanks to those projects and their contributors, to the [Keiyoushi](https://github.com/keiyoushi/extensions) and [LNReader](https://github.com/LNReader/lnreader-plugins) communities for the source ecosystems, and to everyone maintaining the open-source libraries above.

<div align="center">

**Designed and handcrafted with passion.**

</div>
