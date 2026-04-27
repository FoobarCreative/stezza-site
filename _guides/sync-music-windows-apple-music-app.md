---
title: "How to Sync Music from Windows 11 Using the Apple Music and Apple Devices Apps"
short_title: "Sync from Windows 11 (Apple apps)"
description: "Apple now offers dedicated Apple Music and Apple Devices apps for Windows 11 that replace iTunes. Here's how to sync music using them."
category: "Sync from Windows"
priority: 2
difficulty: "Easy"
time_required: "10 minutes"
date: 2026-04-24
last_updated: 2026-04-24
item_id: "sync-music-windows-apple-music-app"
related:
  - sync-music-windows-itunes
  - apple-music-vs-itunes-match
  - library-empty-troubleshooting
---

On Windows 11, Apple has split the job iTunes used to do into **three separate apps**, all available in the Microsoft Store:

- **Apple Music** — manages your library and lets you play, buy, and download music.
- **Apple TV** — for Apple TV+ content and iTunes movies/TV shows.
- **Apple Devices** — handles device syncing, backups, and software updates.

This guide covers the music sync workflow using **Apple Music** (for your library) and **Apple Devices** (for the actual sync).

> **Prefer iTunes?** iTunes for Windows still works and is still supported. See [How to Sync Music from Windows Using iTunes](/guides/sync-music-windows-itunes).

## What you'll need

- A PC running Windows 11
- **Apple Music** app installed — from the Microsoft Store
- **Apple Devices** app installed — from the Microsoft Store
- Your iPhone or iPad
- A Lightning or USB-C cable
- Music in your Apple Music app library on the PC

## Step 1: Get your music into the Apple Music app

If your music is already in iTunes, the Apple Music app imports it automatically on first launch. Otherwise:

- Drag files into the Apple Music app window, or
- Use **File → Add to Library** (or the equivalent menu option) to point it at a folder.

## Step 2: Open Apple Devices and connect your device

Plug the iPhone or iPad into the PC. Tap **Trust** on the device if prompted.

Open the **Apple Devices** app. Your device appears in the sidebar.

## Step 3: Open the Music section

Click your device, then click **Music** in the tabs or side navigation.

## Step 4: Enable syncing

Check **Sync music onto [device name]**.

Then choose:
- **Entire music library** — copies everything from the Apple Music app's library to the device.
- **Selected playlists, artists, albums, and genres** — pick what you want.

## Step 5: Apply the sync

Click **Apply** or **Sync**. The first sync can take a while for large libraries; subsequent syncs only copy changes.

## Wi-Fi sync

In the Apple Devices app, open the device's **General** tab, find **Show this device when on Wi-Fi** (or similar), tick it, and click Apply. After that, the device appears whenever it's on the same Wi-Fi and plugged into power.

## Apple Music subscribers: use Sync Library instead

If you subscribe to Apple Music and have **Sync Library** turned on (in the Apple Music app's settings on Windows, and on the device), your library is already shared across devices through the cloud. In that case you don't need to cable-sync music at all — new additions propagate automatically.

See [Does Stezza Work with Apple Music?](/guides/apple-music-and-stezza) for more on that flow.

## Common issues

**Apple Devices doesn't see my iPhone.**
- Unlock the device and tap **Trust** if you haven't.
- Try a different USB cable or port (data, not charge-only).
- Restart both the app and the PC.

**Apple Music and iTunes are fighting over my library.**
If both are installed, they share the same underlying library data on Windows. Pick one for day-to-day use to avoid confusion. You can uninstall iTunes if you've fully migrated.

**Sync is slower than iTunes was.**
The new apps are still maturing. If performance is consistently bad, iTunes for Windows remains a valid fallback.

## After syncing

Open Stezza on your iPhone or iPad. Synced music appears automatically — Stezza reads from your device's Music library.

If it's empty, see [My Music Library Looks Empty in Stezza](/guides/library-empty-troubleshooting).
