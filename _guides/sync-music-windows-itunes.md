---
title: "How to Sync Music from Windows to iPhone or iPad Using iTunes"
short_title: "Sync from Windows (iTunes)"
description: "Step-by-step guide to syncing your music library from a Windows PC to iPhone or iPad using iTunes for Windows."
category: "Sync from Windows"
priority: 1
item_id: "sync-music-windows-itunes"
related:
  - sync-music-windows-apple-music-app
  - apple-music-vs-itunes-match
  - library-empty-troubleshooting
---

On Windows, iTunes is still the most common way to get music onto an iPhone or iPad — particularly on Windows 10, or on Windows 11 if you haven't switched to the newer Apple Music app. This guide covers the full workflow.

> **On Windows 11?** You also have the option to use Apple's newer Microsoft Store apps. See [How to Sync Music from Windows 11 Using the Apple Music and Apple Devices Apps](/guides/sync-music-windows-apple-music-app) for that path.

## What you'll need

- A Windows PC (Windows 10 or 11)
- **iTunes for Windows** installed — download from [apple.com/itunes](https://www.apple.com/itunes/) or the Microsoft Store
- Your iPhone or iPad
- A Lightning or USB-C cable
- Music in your iTunes library on the PC

## Step-by-step

### 1. Add your music to iTunes

Open iTunes. If your music is loose files on your PC (MP3, M4A, etc.):

- Drag the folder or individual files into the iTunes window, or
- Go to **File → Add Folder to Library** and point it at your music folder.

iTunes copies (or references, depending on your settings) the files into its library.

### 2. Connect your iPhone or iPad

Plug the device into the PC. If it's the first time:

- On the device, tap **Trust** and enter your passcode.
- In iTunes, click **Continue** when prompted.

### 3. Open the device view

Once connected, a small device icon appears near the top-left of iTunes, just below the playback controls. Click it.

### 4. Open the Music section

In the sidebar on the left (under the device name), click **Music**.

### 5. Enable syncing

Check the box **Sync Music**.

Choose what to sync:

- **Entire music library** — everything in iTunes goes to the device.
- **Selected playlists, artists, albums, and genres** — pick only what you want.

If you go with the second option, tick the items you want in the lists that appear.

Optional tickboxes:
- **Include music videos** — adds music videos if you have any.
- **Include voice memos** — syncs Voice Memos across.
- **Automatically fill free space with songs** — fills any leftover storage with random songs from your library.

### 6. Click Apply (or Sync)

At the bottom right, click **Apply**. If syncing doesn't start automatically, click **Sync**.

The first sync can take a while for large libraries. Later syncs only copy changes.

## Enable Wi-Fi sync

You can skip the cable after the first sync. In the device's **Summary** tab in iTunes:

1. Scroll down to **Options**.
2. Tick **Sync with this iPhone over Wi-Fi**.
3. Click **Apply**.

The device will now appear in iTunes whenever it's on the same Wi-Fi network as the PC and plugged into power.

## Common issues

**iTunes doesn't see the device.**
- Unlock the device and tap **Trust** if you haven't.
- Try a different USB cable or port (a data cable, not a charge-only one).
- Make sure the **Apple Mobile Device Support** service is running (Windows Services).
- Reinstall iTunes as a last resort.

**"Cannot sync music to your iPhone because you are not authorized..."**
Go to **Account → Authorizations → Authorize This Computer**. Sign in with the Apple ID you used to buy the music.

**Syncing wipes music I added from another computer.**
iTunes syncs to one library at a time by default. If you sync with a different PC or Mac, iTunes offers to erase and replace. To add music from multiple sources, use **Manually manage music and videos** in the device's **Summary** tab.

**Apple Music subscribers: use Sync Library, not iTunes sync.**
If you subscribe to Apple Music, your library already syncs through the cloud. See [What is Apple Music, and does it work with Stezza?](/guides/apple-music-and-stezza).

## After syncing

Open Stezza on your iPhone or iPad. Your synced music appears automatically — Stezza reads from the device's Music library.

If your library still looks empty, see [My Music Library Looks Empty in Stezza](/guides/library-empty-troubleshooting).
