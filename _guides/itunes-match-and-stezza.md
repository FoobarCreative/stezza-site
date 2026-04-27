---
title: "Does Stezza Work with iTunes Match?"
short_title: "iTunes Match + Stezza"
description: "How iTunes Match interacts with Stezza — what plays, how to set it up, and whether you need it if you already have Apple Music."
category: "Apple Music & iTunes Match"
priority: 3
difficulty: "Easy"
time_required: "3 minutes"
date: 2026-04-24
last_updated: 2026-04-24
item_id: "itunes-match-and-stezza"
related:
  - enable-sync-library
  - apple-music-vs-itunes-match
  - apple-music-and-stezza
  - library-empty-troubleshooting
---

Short answer: **yes**. iTunes Match puts your personal music library in the cloud and makes it available on all your signed-in devices. Stezza reads from the device's Music library, so iTunes Match tracks appear and play like any other music.

## What iTunes Match does

iTunes Match is Apple's cloud locker service for music you already own. For $24.99/year in the US, Apple scans your library (up to 100,000 songs), matches each track to the iTunes Store catalogue where possible, and uploads the rest. You can then access your entire library on any device signed into the same Apple ID.

It's **not** a streaming catalogue — you only get access to *your own music*. If you want Apple's catalogue of ~100 million songs, that's Apple Music (see [Apple Music vs iTunes Match](/guides/apple-music-vs-itunes-match)).

## Turn on iTunes Match on iPhone/iPad

1. Subscribe to iTunes Match on your Mac or PC (in the Music app on Mac, or iTunes on Windows).
2. On your iPhone or iPad, go to **Settings → Apps → Music**.
3. Turn on **Sync Library** (this is the same switch Apple Music subscribers use — iTunes Match and Apple Music share the "library in the cloud" mechanism).
4. Sign in with the Apple ID tied to your iTunes Match subscription if prompted.

Your cloud library starts populating. Large libraries can take several minutes to fully appear.

## Stezza sees what Music sees

Once your iTunes Match library is in the device's Music app, Stezza shows the same tracks. No extra setup in Stezza required.

You can play tracks that are:
- **Downloaded** to the device (cloud download icon tapped) — plays offline.
- **Cloud only** — streamed on demand when you hit play.

Both work in Stezza.

## Do I need iTunes Match if I already have Apple Music?

Usually no. Apple Music's **Sync Library** does the same library-in-the-cloud job, and you get the streaming catalogue on top. Paying for both is only worth it in niche cases — for example, if you want a long-term library locker that persists even if you cancel Apple Music.

See [Apple Music vs iTunes Match: What's the Difference?](/guides/apple-music-vs-itunes-match) for a full comparison.

## Common issues

**My library is empty after enabling Sync Library.**
Give it time — large libraries can take 15 minutes or more to populate. Also make sure the device is signed into the same Apple ID as your iTunes Match subscription. See [My Music Library Looks Empty in Stezza](/guides/library-empty-troubleshooting).

**Some tracks are greyed out.**
They're in the cloud but not currently playable — often due to a temporary issue or a track Apple can't serve. See [Why Are Some Songs Greyed Out?](/guides/songs-greyed-out).

**Matched tracks sound different from my originals.**
That's expected. Matched tracks are served as 256kbps AAC from Apple's catalogue, which is often higher quality than ripped CDs but can differ from your originals (different masters, remastered versions, etc.). Unmatched tracks you uploaded play back as you uploaded them.
