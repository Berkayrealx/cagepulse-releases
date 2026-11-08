<p align="center"><img src="media/app-icon.png" width="96" alt="CagePulse"></p>
<h1 align="center">CagePulse</h1>
<p align="center">MMA events, fighters and fight statistics.</p>
<p align="center"><a href="README.md">Türkçe</a> · <b>English</b></p>

## Download

| Platform | Latest package | Requirements |
| --- | --- | --- |
| Android | [Download APK](https://github.com/Berkayrealx/cagepulse-releases/releases/latest/download/CagePulse-Android-arm64.apk) | Android 8.0+ · ARM64 |
| iPhone / iPad | [Download IPA](https://github.com/Berkayrealx/cagepulse-releases/releases/latest/download/CagePulse-iPhone-iPad.ipa) | iOS 15.1+ · sign with your own Apple account |

[Latest release details](https://github.com/Berkayrealx/cagepulse-releases/releases/latest)

This repository contains app downloads, screenshots and documentation only. Application source code, API credentials, account information and private signing files are not published here.

## Screenshots

| Fighter profile | Fight statistics |
| :---: | :---: |
| <img src="media/fighter-profile.jpg" width="240" alt="Fighter profile and measurements"> | <img src="media/fight-stats.jpg" width="240" alt="Fight statistics from real data"> |

These images show an earlier version’s web preview at phone dimensions; they do not show the redesigned 0.2.6 event page. Native iPhone Liquid Glass is not rendered in browser screenshots. The Android app uses standard black/red controls.

## Features

- UFC/MMA schedule, promotional event artwork, and separate early-prelim / prelim / main-card start times. Missing times are not guessed.
- Tap a fighter image or name on a card to open their profile; retain scroll position and section selection when going back.
- Sliding page transitions, iOS edge-back gesture, animated tab indicators and reduced-motion support.
- Official META/media rankings, a division selector sheet, P4P, card/list layouts and A–Z fighter search.
- Fighter following, physical comparisons, win methods and career statistics.
- Full available career history across promotions for every fighter, with winners, finish methods, rounds and times.
- Full-fight strike, takedown, control-time, target and position statistics.
- Time-based main-card, preliminary-card and custom-time reminders.
- Turkish by default; English and Brazilian Portuguese interface options.
- iPhone/iPad: native UIKit Liquid Glass buttons and system tab navigation on supported iOS 26+ devices, plus nine themes.
- Android: standard black/red styling and a flat bottom navigation bar, without glass effects.
- Disk/memory image caching, 64 bundled headshots, 65 proportional full-body portraits and four event artworks.
- Saved news, read filters, personal notes and a local cache.

## Installation

**Android**

Download the APK and open it on your device. If Android prompts, allow installation for the browser or file manager you are using. A previous CagePulse installation can be updated using the new package signed with the same key; avoid uninstalling first if you want to keep local data.

**iPhone / iPad**

Download the IPA to your computer, select it in your existing iOS signing/installation tool, then sign and install it with your own Apple account. Complete the developer trust and Developer Mode steps if iOS requests them.

The IPA is an unsigned device build, not an App Store or TestFlight release. Simply opening it on an iPhone does not install it. Never post Apple passwords, verification codes or tokens in GitHub issues.

## Getting started

1. Open an upcoming or past card in **Events**.
2. Tap a fighter name or image to open their profile; tap the surrounding row for fight details. Past fights display winners, finish methods, rounds and times directly.
3. Find a fighter by name or division. The **Fights** tab automatically loads the full available history. Results are always visible here, and loaded fights are cached on the device.
4. Select your language in **Settings**. iPhone users can open the separate **Themes** gallery.
5. Open a future event’s reminder controls to schedule a notification. Notification permission is required.

## Data and current limits

Rankings come from the [official UFC rankings page](https://www.ufc.com/rankings); promotional event artwork and published card times come from official UFC event pages; other schedules and statistics come from ESPN, and news comes from free RSS sources. META and media lists are kept separate; P4P is labeled as the media panel. The ranking screen displays the last-check timestamp. Provider delays, missing fields and card changes are possible. When the source combines KO and TKO, the app displays **KO/TKO**. Missing measurements or statistics are not invented.

- This version shows full-fight totals; detailed per-round statistics and official scorecards are not included.
- Links to Fight Digitale, MMA101Türkiye and ChampRDS are available. An automatic X post feed is not connected, and no X token is required.
- Notifications triggered by the previous fight ending are not implemented yet. Current reminders are time-based.
- Community services, account synchronization and server push are not enabled in this distribution.
- Silent mode and Focus settings may suppress ordinary notification sounds.

CagePulse is not officially affiliated with UFC, ESPN or MMA360. News headlines, images and content belong to their respective publishers.

## Support

- [Report a problem on GitHub](https://github.com/Berkayrealx/cagepulse-releases/issues)
- Telegram: [@berkayrealx](https://t.me/berkayrealx)
- Discord: **@berkayrealx**

Include the app version, device, operating system and reproduction steps. Hide personal information in screenshots.

> GitHub’s automatically generated “Source code” archives contain this documentation repository and its images only, not the application source code.
