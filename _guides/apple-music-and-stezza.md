---
title: "Does Stezza Work with Apple Music?"
short_title: "Apple Music + Stezza"
description: "How Apple Music subscriptions interact with Stezza, what plays, what doesn't, and how to make sure your library shows up."
category: "Apple Music & iTunes Match"
priority: 2
item_id: "apple-music-and-stezza"
related:
  - enable-sync-library
  - apple-music-vs-itunes-match
  - itunes-match-and-stezza
  - library-empty-troubleshooting
---

Short answer: **yes**. Stezza streams Apple Music tracks and plays anything in your Sync Library, exactly the same songs you'd see in the built-in Music app. The one thing you need to do is make sure **Sync Library** is turned on.

Here's the full picture.

## How Stezza sees your library

Stezza doesn't have its own music store or catalogue. It reads from the **Music library on your iOS device**, the same library the built-in Music app uses. Anything that library contains, Stezza can play.

That means Stezza's behaviour with Apple Music is really a question of "what does iOS put in my Music library?"

## If you don't subscribe to Apple Music

No Apple Music subscription means your library consists of:

- Music you synced from a Mac or PC
- Music you bought from the iTunes Store
- Music you imported from other sources (e.g. Files app)

All of it plays in Stezza without issue.

## If you subscribe to Apple Music: turn on Sync Library

When you subscribe to Apple Music, there's a setting called **Sync Library** (formerly "iCloud Music Library"). You need this on for Apple Music tracks to appear in your device's Music library.

Turn it on under:

**Settings → Apps → Music → Sync Library**

Once it's on, every song you've added to your Apple Music library, by tapping "+" or "Add to Library" in the Music app, shows up in Stezza too.

> **Gotcha:** turning Sync Library on can take a few minutes to propagate, especially for large libraries. If Stezza looks empty immediately after enabling it, give it 5–15 minutes and restart the app.

## Streaming vs offline

With Sync Library on, Apple Music tracks appear in your library in two states:

- **Downloaded**, stored locally on the device. Plays in Stezza with no network needed.
- **Not downloaded (cloud only)**, streamed on demand when you hit play.

**Stezza handles both.** Streaming tracks play straight through, the same way the Music app does it. No need to download first.

That said, if you're about to go somewhere without signal (a flight, the subway, a long drive), downloading your music in advance avoids buffering and saves cellular data.

**To download Apple Music tracks for offline playback:**

1. Open the Music app.
2. Find the song, album, or playlist.
3. Tap the download icon (a cloud with a down arrow), or tap the "..." menu and choose **Download**.

Once downloaded, Stezza plays them offline, same as any synced music.

## What happens if I cancel Apple Music?

When you cancel:
- Downloaded Apple Music tracks become unplayable: they're licensed, not owned. They disappear from your library.
- Music you *own* (synced, purchased, or uploaded through Sync Library's matching) remains.

Stezza reflects this automatically. Anything still in the library still plays.

## Common issues

**My Apple Music library is empty in Stezza.**
Sync Library is probably off. Check **Settings → Apps → Music → Sync Library**.

**Some songs are greyed out.**
They're cloud-only and not downloadable or playable in the current state. See [Why Are Some Songs Greyed Out in My Library?](/guides/songs-greyed-out).

**A track won't play at all.**
Check whether it plays in the built-in Music app. If it doesn't play there either, the track is unavailable (removed from Apple Music, region-locked, or a file problem). If it plays in Music but not Stezza, try restarting Stezza and checking your network connection for streaming tracks.

## See also

- [Apple Music vs iTunes Match: What's the Difference?](/guides/apple-music-vs-itunes-match)
- [My Music Library Looks Empty in Stezza](/guides/library-empty-troubleshooting)
