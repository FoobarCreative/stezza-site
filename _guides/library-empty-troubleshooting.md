---
title: "My Music Library Looks Empty in Stezza"
date: 2026-04-24
last_updated: 2026-10-13
short_title: "Empty Library Troubleshooting"
description: "Troubleshooting steps when your music library shows as empty or incomplete in Stezza."
category: "Troubleshooting"
priority: 1
item_id: "library-empty-troubleshooting"
platforms:
  - iphone
  - ipad
  - mac
related:
  - enable-sync-library
  - songs-greyed-out
  - apple-music-and-stezza
  - itunes-match-and-stezza
  - add-music-stezza-mac
---

Stezza reads directly from your iOS device's **Music library**, the same library the built-in Music app uses. If Stezza looks empty, the problem is almost always with the library itself, not with Stezza. Work through this list.

## 1. Check the Music app first

Open the built-in **Music** app and look at your library there.

- **Music app is also empty?** The issue is upstream, nothing has been synced or added to the library yet. See the sync guides for [Mac](/guides/sync-music-mac-finder) or [Windows](/guides/sync-music-windows-itunes).
- **Music app has your songs but Stezza doesn't?** Continue below.

## 2. Grant Stezza access to your music library

If you tapped "Don't Allow" when Stezza first asked for library access, it has nothing to read.

Go to **Settings → Privacy & Security → Media & Apple Music → Stezza** and make sure it's on.

Then force-quit Stezza and reopen it.

## 3. Check Sync Library (Apple Music / iTunes Match users)

If your music lives in Apple Music or iTunes Match, you need **Sync Library** enabled on the device.

**Settings → Apps → Music → Sync Library**, make sure it's on.

After turning it on, wait a few minutes for the library to populate. Large libraries can take 15+ minutes.

## 4. Make sure you're signed into the right Apple ID

Apple Music and iTunes Match libraries are tied to a specific Apple ID. If the device is signed into a different Apple ID than the one that owns your music, your library won't appear.

**Settings → [your name] at the top** shows the Apple ID in use. For Music specifically, check **Settings → Apps → Music → Account**.

## 5. Restart Stezza

Sometimes Stezza's view of the library gets out of sync after a large change (just enabled Sync Library, just completed a cable sync, etc.).

Swipe up from the bottom of the screen and swipe Stezza away. Then reopen it.

## 6. Restart the device

If everything above checks out and the library is still empty, a full device restart clears any lingering state in the Music framework. Press and hold the power button (and a volume button on Face ID devices) to power off, then turn it back on.

## 7. Check for a cable-sync in progress

If you're mid-sync from a Mac or PC, the device's library can be in a transitional state. Let the sync finish completely. The sync indicator at the top of Finder or the Apple Music / iTunes window tells you when it's done.

## Using Stezza on a Mac?

Stezza for Mac reads the library of the **Music** app on the same Mac. The steps above are for iPhone and iPad. On a Mac, check these instead.

1. **Open the Music app.** If its library is empty, Stezza is empty too. See [How to Add Music to Stezza on Your Mac](/guides/add-music-stezza-mac) to import files, turn on Sync Library, or download past purchases.
2. **Give Stezza access.** Choose **Apple menu → System Settings → Privacy & Security → Media & Apple Music** and turn on the switch next to **Stezza**. Then quit Stezza and open it again.
3. **Check Sync Library.** In the Music app choose **Music → Settings → General** and make sure **Sync Library** is ticked. Wait a few minutes for a large library.
4. **Check the Apple Account.** In the Music app choose **Account** and confirm it is the account that owns your music.
5. **Quit and reopen Stezza.** Stezza for Mac does not watch the library live. An empty library reloads when you switch back to Stezza. A library that already has songs refreshes on a pull-down on the home screen or on relaunch.

## Still empty?

If none of the above helped, [get in touch]({{ "/contact" | relative_url }}) with:

- Your iOS version (**Settings → General → About → iOS Version**), or your macOS version (**Apple menu → About This Mac**)
- Whether you use Apple Music, iTunes Match, or neither
- How your music got onto the device (cable sync, Sync Library, File Sharing, etc.)
- Whether the built-in Music app shows the same problem

That's usually enough for us to figure out what's going on.
