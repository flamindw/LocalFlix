# LocalFlix

A Netflix-style app for the movies and TV shows on your own drives. Point it at a drive or folder and LocalFlix finds your titles, adds posters, backdrops and details from TMDB (saving the artwork onto the drive so it's only downloaded once), and gives you a streaming-service experience — fully local, no server required.

## Download

Get the latest version from the **[Releases page](https://github.com/flamindw/LocalFlix/releases/latest)**.

| Platform | File | How to install |
| --- | --- | --- |
| Mac (macOS 27 or later) | `LocalFlix-Mac.dmg` | Open the DMG and drag LocalFlix to Applications. The first time, right-click LocalFlix → **Open** (or System Settings → Privacy & Security → **Open Anyway**), since the app isn't notarized. |
| Windows 10 / 11 (64-bit) | `LocalFlix-Windows.zip` | Unzip anywhere and double-click **LocalFlix.exe** (keep it next to the `runtime` and `lib` folders). If SmartScreen appears, click **More info → Run anyway**. Install [VLC](https://www.videolan.org) to play videos inside the app. |
| Android (8.0 or later) | `LocalFlix-Android.apk` | Open the APK on your phone or tablet and allow installing from this source when asked. |
| iPad / iPhone (iPadOS 26 or later) | `LocalFlix-iPad.ipa` | Unsigned — install with a sideloading tool such as [AltStore](https://altstore.io) or [Sideloadly](https://sideloadly.io), which sign it with your own Apple ID. |

## Features

- **Your library, streaming-style** — movies and shows from one or more drives, with artwork, descriptions, ratings and episode lists. Artwork is saved next to your files and only fetched when it's missing.
- **Continue Watching**, Most Watched, Recently Added and genre rows; resume where you left off on any episode.
- **Recommendations that learn your taste** — LocalFlix's own recommender looks at what you own, watch and star, and suggests titles you don't have yet, with a reason for each ("Because you watched…"). Tell it "Not Interested" to steer it away.
- **Watchlist** — star anything, on your drives or not.
- **Profiles** — separate watch history, Watchlist and recommendations for everyone, with custom profile pictures.
- **Watch history for titles you don't have** — mark movies, single episodes or whole seasons as watched.
- **Import & export** — move your watched movies and episodes and your Watchlist between devices (Mac, iPad, Windows, Android) with a small file, in Settings → Watch History.
- **Cast & actors** — see who's in every title, open an actor's page with everything they've been in, and search by actor.
- **Discover** — browse by genre, see where titles are available to stream, rent or buy in your country.
- **Your own server & download site** — optional links to stream from your own media server or open your preferred download site, set up in Settings.

## Getting started

1. Open LocalFlix and choose the drive or folder with your movies and TV shows (or skip and add one later in Settings).
2. Add a free TMDB API key in **Settings → Online Info** to get artwork, details, cast and recommendations. Get one at [themoviedb.org](https://www.themoviedb.org/settings/api).

Folders like `Movies/Inception (2010)/Inception.2010.1080p.mkv` and `TV/Breaking Bad/Season 1/Breaking.Bad.S01E01.mkv` are recognised automatically.

---

This product uses the TMDB API but is not endorsed or certified by TMDB. Streaming availability data from JustWatch.
