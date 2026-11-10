---
layout: page
title:  "Privacy Policy"
permalink: /privacy-policy
comments: false
imageshadow: false
include_in_header: false
include_in_footer: true
last_updated: 2026-11-11
---

**Last updated**  
November 2026

# Privacy Policy

This following document sets forth the Privacy Policy for the _Stezza_ website and app, produced by _Foobar Creative_.

_Foobar Creative_ is committed to providing you with the best possible customer service experience. _Foobar Creative_ is bound by the Privacy Act 1988 (Cth) (Australia), which sets out a number of principles concerning the privacy of individuals.

### Collection of your personal information

Stezza does not collect personal information when viewing our website. Within the iOS app, non-personally identifiable data such as device locale, app version, operating system, and crash logs are collected to improve performance and troubleshoot issues. If you contact us via email, we will store your email address.

The app may also utilize third-party tools, such as Google Analytics and Facebook SDK, to monitor app performance and usage patterns.

### Sharing of your personal information

We may employ other companies to provide services on our behalf, such as customer support or transaction processing. These companies will only have access to the personal information required to perform their services. Foobar Creative ensures these organizations comply with confidentiality and privacy obligations when handling your information.

### Use of your personal information

The non-personally identifiable information collected is used internally for performance monitoring, bug fixes, and app improvements. This includes user locale, app version, operating system, and crash data.

Any updates to our data collection practices will only apply to information collected after the policy change.

### Autoplay and third-party AI processing of listening data

Autoplay is an optional feature, currently in beta. When your play queue is about to end, Autoplay adds songs that fit what you have been listening to.

Autoplay is off by default. When you turn it on, Stezza shows a consent sheet first. You can turn Autoplay off at any time in Settings, or with the infinity button in the Up Next queue. When you turn it off, Stezza stops sending listening data at once.

**What Stezza sends to its server**

When Autoplay is on and your queue is about to end, the app sends the following to Stezza's server, which runs on Google Cloud (Firebase Cloud Functions, us-central1 region in the United States):

- Up to 10 recent songs from your queue: title, artist, album, genre, release year, and whether you played each song to the end, skipped it, or removed it.
- Up to about 70 candidate songs from your music library and the Apple Music catalog: title, artist, album, genre and release year. For library songs, this also includes a play count and a coarse "last played" period (1 week, 1 month, 6 months, over 1 year, or never).
- Your "allow explicit" setting, your Apple Music country code, and the app language.
- A pseudonymous anonymous user ID created by Firebase. There is one ID per app install. It is not linked to your name or any account. Stezza uses it to authenticate the request and to apply a rate limit.

Stezza does not send your name, email address, Apple Account, Apple Music user token, device identifiers, location, library file identifiers, or any song audio.

**Third-party AI processor**

Stezza's server sends the song details, without your anonymous user ID, to OpenAI (the OpenAI API). OpenAI's model chooses the songs to add to your queue. OpenAI states that data sent to its API is not used to train its models by default, and that it keeps API logs for abuse monitoring for up to 30 days. For current details, see [OpenAI's data controls documentation](https://developers.openai.com/api/docs/guides/your-data) and [OpenAI's enterprise privacy page](https://openai.com/enterprise-privacy/).

**Retention and use**

Stezza's server keeps a log of each Autoplay request for 30 days: the request contents, the songs chosen, timing, and the anonymous user ID. We use this log to check and improve the quality of the picks. After 30 days the log is deleted automatically. The server also keeps a small per-user counter (anonymous user ID and the number of calls in the current hour) for rate limiting.

Stezza uses this data only to choose songs and to improve Autoplay. We do not sell it and we do not use it for advertising.

### Mixtape and third-party AI processing of your prompt

Mixtape is an optional feature, currently in preview, for Apple Music subscribers. You type a short text prompt, for example "rainy sunday indie", and Mixtape builds a playlist of songs that fit it. Nothing is sent until you submit a prompt.

**What Stezza sends to its server**

When you submit a prompt, the app sends the following to Stezza's server, which runs on Google Cloud (Firebase Cloud Functions, us-central1 region in the United States):

- Your prompt text (3 to 200 characters).
- The number of songs you asked for and your "allow explicit" setting.
- Your Apple Music country code and the app language.
- The same pseudonymous anonymous user ID created by Firebase that Autoplay uses. Stezza uses it to authenticate the request and to apply a daily limit.

Stezza does not send your name, email address, Apple Account, Apple Music user token, device identifiers, location, or the contents of your music library.

**Third-party AI processor**

Stezza's server sends your prompt text, the song count, your country code and your explicit setting, without your anonymous user ID, to OpenAI (the OpenAI API). OpenAI's model returns a list of song titles and artists. The app then matches that list against your music library on your device and the Apple Music catalog, and plays the songs it finds. OpenAI's data handling is described in the Autoplay section above.

**Retention and use**

Stezza's server keeps a log of each Mixtape request for 30 days: the prompt, the songs returned, timing, and the anonymous user ID. We use this log to check and improve the quality of the playlists. After 30 days the log is deleted automatically. The server also keeps a small per-user counter (anonymous user ID and the number of requests in the current day) to enforce a limit of 100 requests a day.

Your last 20 prompts are stored only on your device so you can reuse them. You can clear this history at any time in the Mixtape screen. Stezza uses Mixtape data only to build playlists and to improve Mixtape. We do not sell it and we do not use it for advertising.

### Changes to this Privacy Policy

Foobar Creative reserves the right to modify this Privacy Policy at any time. Any significant changes will be reflected here. If you disagree with the Privacy Policy, please refrain from using the app or site.

### Accessing Your Personal Information

You have a right to access your personal information, subject to exceptions allowed by law. If you would like to do so, please let us know. You may be required to put your request in writing for security reasons. _Foobar Creative_ reserves the right to charge a fee for searching for, and providing access to, your information on a per request basis.

### Contacting us

_Foobar Creative_ welcomes your comments regarding this Privacy Policy. If you have any questions about this Privacy Policy and would like further information, please [contact us via email](mailto:support@stezza.app).