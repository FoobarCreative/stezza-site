---
title: "How to Sync Music from a Mac to iPhone or iPad (macOS Catalina or Later)"
short_title: "Sync from Mac (Catalina+)"
description: "On macOS Catalina and later, music syncs through Finder instead of iTunes. Here's the full walkthrough for getting your music library onto your iPhone or iPad."
category: "Sync from Mac"
priority: 1
difficulty: "Easy"
time_required: "5 minutes"
date: 2026-04-24
last_updated: 2026-04-24
item_id: "sync-music-mac-finder"
related:
  - sync-music-mac-itunes
  - apple-music-vs-itunes-match
  - library-empty-troubleshooting
---

If you're on **macOS Catalina (10.15) or later** — which is everything from late 2019 onward — iTunes has been split into separate Music, TV, Podcasts, and Books apps. Device syncing no longer lives inside the Music app. Instead, you manage it from **Finder**.

This catches a lot of people out when they upgrade: "where did iTunes go?" The answer: the sync part moved to Finder; the library part moved to the Music app.

## What you'll need

- A Mac running macOS Catalina (10.15) or later
- Your iPhone or iPad
- A Lightning or USB-C cable (or Wi-Fi sync, once you've enabled it — see below)
- Music already in your **Music app** library on the Mac

## Step-by-step: sync over cable

### 1. Connect your iPhone or iPad to your Mac

Plug the device in. If it's the first time, you may need to tap **Trust** on the device and enter your passcode.

### 2. Open Finder

Click the Finder icon in your Dock. In the Finder sidebar, under **Locations**, you should see your device by name (e.g. "Rick's iPhone"). Click it.

If you don't see Locations in the sidebar, open **Finder → Settings → Sidebar** and make sure "CDs, DVDs, and iOS Devices" is checked.

### 3. Click the "Music" tab

Along the top of the device window you'll see tabs: General, Music, Movies, TV Shows, Podcasts, Audiobooks, Books, Photos, Files, Info. Click **Music**.

### 4. Enable syncing

Check the box **Sync music onto [device name]**.

You now have two choices:

- **Entire music library** — syncs everything the Music app has. Fastest to set up; uses the most space.
- **Selected artists, albums, genres, and playlists** — gives you fine control over what goes on the device. Recommended if your full library won't fit.

If you pick the second option, tick the playlists, artists, albums, and genres you want in the lists below.

### 5. Click Apply (or Sync)

At the bottom right, click **Apply**. The first sync can take a while depending on library size. Subsequent syncs only copy changes.

## Enable Wi-Fi sync (so you don't need the cable again)

Still in the device view in Finder:

1. Click the **General** tab.
2. Scroll down to **Options**.
3. Tick **Show this [device] when on Wi-Fi**.
4. Click **Apply**.

From now on, the device shows up in Finder any time it's on the same Wi-Fi network as your Mac, plugged into power. You can start syncs without a cable.

## Common issues

**"The device is not eligible for the requested build."**
Your device's iOS version is older than the minimum supported by this version of macOS. Update iOS on the device, then retry.

**Syncing overwrites music I added directly on the device.**
By default, Finder-managed syncing replaces the device's music library with what's on your Mac. If you've been adding music directly to the iPhone, it'll be wiped on sync. To keep things you've added manually, enable **Manually manage music** in the **General** tab before syncing.

**Apple Music subscribers: songs won't sync this way.**
If you subscribe to Apple Music and have **Sync Library** enabled, your library already syncs over the cloud — you don't use Finder sync for those tracks. Finder sync is for music you own (ripped CDs, purchases, imported files). See [What is Apple Music, and does it work with Stezza?](/guides/apple-music-and-stezza) for the full picture.

## After the sync

Open Stezza on your iPhone or iPad. Your synced music appears automatically — Stezza reads from the device's Music library, so anything the Music app sees, Stezza sees.

If the library looks empty after syncing, see [My Music Library Looks Empty in Stezza](/guides/library-empty-troubleshooting).
