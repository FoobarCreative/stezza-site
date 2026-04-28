---
title: "How to Copy Videos to Stezza Using iTunes or Finder File Sharing"
short_title: "Copy Videos to Stezza"
description: "Stezza plays video files transferred directly to the app via iTunes (Windows) or Finder (Mac). Here's how to copy them across."
category: "Videos & File Sharing"
priority: 1
difficulty: "Easy"
time_required: "5 minutes"
item_id: "video-playback-file-sharing"
related:
  - sync-music-mac-finder
  - sync-music-windows-itunes
---

In addition to music, Stezza plays **video files** you transfer directly to the app via **File Sharing** — the mechanism that lets you drop files straight into an iOS app's own storage from your computer. No iCloud, no library sync, no re-encoding through the Music app. Just drag and drop.

This guide covers both the Mac (Finder) and Windows (iTunes) workflows.

## What you can transfer

Stezza supports common video formats that iOS handles natively — typically **MP4, M4V, and MOV** files with H.264 or HEVC video. If iOS's built-in Videos or Files app can play it, Stezza can too.

File Sharing is only for files you drop directly into Stezza. Videos in your device's general Photos library, or videos synced through the TV app, aren't touched by this flow — this is for files you want to keep specifically inside Stezza's own storage.

## On a Mac (macOS Catalina or later): use Finder

### 1. Connect your iPhone or iPad

Plug the device in and tap **Trust** if prompted.

### 2. Open Finder and select your device

In the Finder sidebar under **Locations**, click your device.

### 3. Click the "Files" tab

Along the top of the device window: General, Music, Movies, TV Shows, Podcasts, Audiobooks, Books, Photos, **Files**, Info. Click **Files**.

This tab lists every installed app that supports File Sharing. Stezza is one of them.

### 4. Drop your videos into Stezza

Click the disclosure triangle next to **Stezza** to expand it. Any files already shared with Stezza appear underneath.

Drag video files from Finder directly onto the Stezza row. Alternatively, click Stezza and use the "..." or drag target to add files.

Files copy over immediately — no separate sync step needed for File Sharing transfers.

### 5. Open Stezza on your device

Your videos are now inside Stezza and ready to play.

## On Windows: use iTunes

### 1. Open iTunes and connect your device

Plug in your iPhone or iPad. Tap **Trust** on the device if prompted.

### 2. Click the device icon

The small device icon appears near the top-left of iTunes, below the playback controls.

### 3. Click "File Sharing" in the left sidebar

In the sidebar listing for your device, you'll see sections like Summary, Music, Movies, TV Shows, Podcasts, Books, Photos, Info — and **File Sharing** further down. Click it.

### 4. Select Stezza

The main pane shows a list of every installed app that supports File Sharing. Click **Stezza**. A **Stezza Documents** list appears on the right showing files currently shared with the app.

### 5. Add your videos

Either:
- Drag video files from File Explorer directly onto the Stezza Documents list, or
- Click **Add File...** and pick the videos you want.

Files copy over immediately. No sync required.

### 6. Open Stezza on your device

Your videos are ready to play.

## Removing files later

To remove a video you've transferred:

- **Finder (Mac):** select the file under Stezza in the Files tab and press Delete, or right-click → Move to Trash.
- **iTunes (Windows):** select the file in the Stezza Documents list and press Delete, or click the file and choose **Delete**.

You can also clear files from inside Stezza itself.

## Common issues

**Stezza doesn't appear in the Files / File Sharing list.**
Make sure Stezza is installed on the connected device and fully launched at least once. Disconnect and reconnect the cable.

**A video file won't play after transfer.**
It's probably in a format iOS doesn't support natively (for example, MKV, AVI, or a less common codec). Convert to MP4 with H.264 video using a tool like HandBrake, then transfer the converted file.

**Transferred videos aren't in the Photos app.**
They shouldn't be — File Sharing puts files inside Stezza's own storage, not in Photos or the shared device media library. Open Stezza to see them.

**Is this the same as syncing?**
No. File Sharing copies files directly into Stezza and doesn't touch your music library or the Movies section of Finder/iTunes. It's a parallel mechanism, specifically for apps that want to accept files directly.

## See also

- [Sync Music from Mac (macOS Catalina or later)](/guides/sync-music-mac-finder)
- [Sync Music from Windows using iTunes](/guides/sync-music-windows-itunes)
