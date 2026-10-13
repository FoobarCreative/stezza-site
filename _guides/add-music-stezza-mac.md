---
title: "How to Add Music to Stezza on Your Mac"
short_title: "Add Music on Mac"
description: "Stezza for Mac plays the library of the Music app on your Mac. Here is how to get music into that library: import files, turn on Sync Library, download past purchases, and give Stezza access."
category: "Stezza for Mac"
priority: 1
item_id: "add-music-stezza-mac"
platforms:
  - mac
date: 2026-10-13
related:
  - enable-sync-library
  - apple-music-vs-itunes-match
  - library-empty-troubleshooting
faq:
  - q: "Does Stezza for Mac need the Music app?"
    a: "Yes. Stezza for Mac reads the library of the Music app on the same Mac. Anything the Music app can play from its library, Stezza can play too."
  - q: "Can I drag music files straight into Stezza on my Mac?"
    a: "No. Add the files to the Music app first, with File > Import or by dragging them into the Music window. Stezza then sees them."
  - q: "Do I need an Apple Music subscription to use Stezza on my Mac?"
    a: "No. Music you import, rip or buy plays without a subscription. Apple Music or iTunes Match is only needed if you want Sync Library to bring in your cloud library."
---

Stezza for Mac plays the music library of the **Music** app on your Mac. There is no cable sync and no Finder step. If a song is in your Music library, Stezza can play it. If the Music library is empty, Stezza is empty too.

This guide shows four ways to fill that library, and one fix for when Stezza cannot see it.

## 1. Import music files you already have

Got MP3, AAC, FLAC or Apple Lossless files in a folder? Add them to the Music app.

1. Open the **Music** app.
2. Choose **File > Import** in the menu bar. If the menu says **File > Add To Library** instead, use that.
3. Select the files or a whole folder and click **Open**.

You can also drag a file or a folder from Finder onto the Music window.

**Import or Add To Library?** The menu item depends on one setting: **Music > Settings > Files > Copy files to Music Media folder when adding to library**. With the box ticked, the menu says **Import** and Music keeps its own copy of each file. With the box clear, the menu says **Add To Library** and Music only points at the original file. If you later move or delete the original, the song stops playing. Tick the box if you are not sure.

Switch back to Stezza. If the new songs do not show, quit Stezza and open it again.

## 2. Turn on Sync Library (Apple Music or iTunes Match)

If your music lives in Apple Music or iTunes Match, or you built your library on an iPhone, Sync Library brings it to the Mac.

1. Open the **Music** app.
2. Choose **Account** in the menu bar and check that you are signed in with the Apple Account that has your subscription.
3. Choose **Music > Settings**, then click the **General** tab.
4. Tick **Sync Library** and click **OK**.

A large library can take 15 minutes or more to appear. Sync Library needs an Apple Music or iTunes Match subscription. See [Apple Music vs iTunes Match](/guides/apple-music-vs-itunes-match) if you are not sure which you have.

## 3. Download past purchases

Music you bought from the iTunes Store can be downloaded again on any Mac signed in with the same Apple Account.

1. Open the **Music** app.
2. Choose **Account > Purchased** in the menu bar.
3. Click **Not in My Library** to see only the songs that are missing from this Mac.
4. Click the download button next to a song or an album, or click **Download All** at the bottom.

If the Mac asks you to authorize the computer, choose **Account > Authorizations > Authorize This Computer** and sign in.

## 4. Rip a CD

Have an external optical drive? Insert the CD, and the Music app asks whether to import it. Click **Yes**. The tracks land in your library and in Stezza.

## 5. Give Stezza access to your library

The first time Stezza for Mac opens, macOS asks for permission to access your music library. If you clicked **Don't Allow**, Stezza has nothing to read.

1. Choose **Apple menu > System Settings**.
2. Click **Privacy & Security** in the sidebar.
3. Click **Media & Apple Music**.
4. Turn on the switch next to **Stezza**.
5. Quit Stezza and open it again.

## Still empty?

- Check the Music app first. If the Music app shows no songs, the problem is upstream. Work through steps 1 to 4 above.
- Check the Apple Account in **Music > Account**. A library synced to a different Apple Account does not show up.
- Quit Stezza and open it again after a change to the library. Stezza for Mac does not watch the library live.
- Restart the Mac if the library still does not appear.

For more causes and fixes, see [My Music Library Looks Empty in Stezza](/guides/library-empty-troubleshooting).
