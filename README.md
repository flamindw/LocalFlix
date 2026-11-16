<div align="center">

# LOCALFLIX

**Your movies and TV shows, Netflix-style. On your own drives, on every device.**

[**Download for Mac, Windows, Android & iPad →**](https://github.com/flamindw/LocalFlix/releases/latest)

</div>

---

You already own a pile of movies and shows on hard drives. LocalFlix turns them into a streaming service: point it at a drive and seconds later you're browsing your own collection with posters, backdrops, descriptions, cast lists and "Continue Watching", like the big streaming apps but **fully local**.

No server to set up, no account to create, no subscription, no ads, and nothing uploaded anywhere.

## Why LocalFlix?

- **It just works with the files you have.** No renaming, no media server, no database to run. Choose a drive or folder and LocalFlix finds your movies and episodes, even in messy folders with names like `The.Matrix.1999.1080p.BluRay.x264.mkv`.
- **It looks great.** A modern streaming-style interface with a swipeable banner, rows of posters, rich detail pages and a top bar that slides out of the way while you scroll.
- **Your artwork stays with your media.** Posters and backgrounds are saved onto the drive next to your files, in the same names Plex and Kodi use. They're only downloaded once, so a drive you plug into another computer already has its artwork.
- **It recommends things you'll actually like.** LocalFlix has its own recommendation engine that learns from what you own, what you watch and what you star. It's not a generic "trending" list.
- **It's on all your screens.** Mac, Windows, Android and iPad, with the same features everywhere. Move your watch history between them with a single file.
- **It's private.** Your library, watch history and profiles are stored only on your device. The only thing it talks to is TMDB, for artwork and movie info.

## Features

### 🎬 Your library, streaming-style
- **Automatic scanning** of one or more drives or folders. Add as many as you like, and titles on a drive that's unplugged stay in your library until it's back.
- **Smart file recognition** for movies (`Inception (2010)/Inception.mkv`) and shows (`Breaking Bad/Season 1/S01E02.mkv`, `1x02`, "Season 1" folders, specials and more). Sample files, trailers and extras folders are ignored.
- **Posters, backdrops, episode stills, descriptions, ratings, genres and runtimes** from The Movie Database, plus any artwork already on your drive.
- **Home screen** with a swipeable hero banner (a progress bar fills as each slide plays), Continue Watching, Most Watched This Month (Top 5), Recently Added, and rows for your top genres.
- **Movies and TV Shows pages** that you can sort by title, date added, year or rating.
- **Detail pages** with episode lists by season, an "Up Next" marker, time left and resume, plus which drive and folder each title lives in.
- **Hover a poster** (on Mac and Windows) to see its title, and right-click (or long-press on touch screens) for quick actions.

### ▶️ Playback
- **Built-in player** that resumes where you left off and keeps Continue Watching up to date. It handles MKV, MP4 and most other formats.
- The Mac player has controls that hide after a few seconds, and it stops the screen saver kicking in mid-movie.
- **Mark Watched / Unwatched** for any movie, episode or whole season.

### ✨ Recommendations that learn your taste
- LocalFlix's **own recommender** builds a taste profile from the genres, keywords, cast, directors and franchises of everything you own, watch and star, then ranks titles you don't have yet by how well they match.
- **Every pick says why**: "Because you watched…", "From the same series as…", or "Sci-Fi picked for you".
- Rows such as **Top Picks for You**, **Because You Watched…** and **Trending That Fits Your Taste**, and a home banner of recommended movies that aren't in your library.
- **Not Interested**: dismiss anything and future suggestions steer away from similar titles.

### ⭐ Watchlist
- **Star anything**, whether it's on your drives or not, from posters, detail pages or the home banner.
- A Watchlist page that you can filter (On My Drives, Not Downloaded, Movies, TV Shows) and sort, with a clear status for each title.
- **Undo** straight from the "Added to Watchlist" notice.

### 👥 Profiles
- **A profile for everyone in the house**, each with their own watch history, Watchlist, recommendations and "Not Interested" list.
- **Custom profile pictures**: choose from 12 built-in designs or use your own photo.
- A "Who's watching?" screen when the app opens, and quick profile switching from the top bar.

### 📺 Track what you watch anywhere
- Mark movies **and individual episodes** as watched even if they're not on your drives, for things you saw on a streaming service, at the cinema or at a friend's place.
- Shows you don't have still get their **real season and episode lists**, with episode names, air dates, runtimes and stills, plus **Mark Season Watched** and **Mark Up to Here as Watched**.
- LocalFlix remembers where you got to and starts you on the **next episode**.
- Everything you watch, on your drives or not, helps your recommendations.

### 🎭 Cast & actors
- **"Starring…"** under every title and a **Cast** row with photos, character names and episode counts.
- **Actor pages** with a photo, biography, birthday and everything they've been in. Titles you already own are shown first, and you can filter by movies or TV and sort by popularity, release date or rating.
- **Search by actor**: type a name and see their movies and shows, including the ones on your drives.

### 🔍 Discover & search
- **Search** your library, all of TMDB and people at once.
- **Browse by genre** for movies and TV, with an endless scroll of popular titles that hides what you've already watched.
- **Where to Watch**: see which streaming, rental and purchase services carry a title in your country.
- **More Like This** on every detail page.

### 🔁 Import & export
- **Move your watched titles and Watchlist between devices** (Mac ↔ Windows ↔ Android ↔ iPad) with one small file.
- Titles are matched by their TMDB info, so they line up even when your files are in different places on each device.
- Importing only ever adds; it never removes or changes anything you've already marked.

### 🔗 Optional: your own server & download site
- If you run your own media server, add its link pattern in Settings and titles you don't have on the drive get a **Play from Server** button (with season and episode pickers for shows).
- Set a **preferred download site** for your legitimate downloads. On Mac, iPad and Android it opens in a private in-app window that keeps no history or cookies; on Windows it opens in an InPrivate browser window.
- Add an optional **warning message** that's shown before either one opens.

## Download

Get the latest version from the **[Releases page](https://github.com/flamindw/LocalFlix/releases/latest)**.

| Platform | File | How to install |
| --- | --- | --- |
| 🍎 **Mac** (macOS 27 or later) | `LocalFlix-Mac.dmg` | Open the DMG and drag LocalFlix to Applications. The first time, right-click LocalFlix → **Open** (or System Settings → Privacy & Security → **Open Anyway**), because the app isn't notarized by Apple. |
| 🪟 **Windows** 10 / 11 (64-bit) | `LocalFlix-Windows.zip` | Unzip anywhere and double-click **LocalFlix.exe** (keep it next to the `runtime` and `lib` folders). If SmartScreen appears, click **More info → Run anyway**. Nothing else is needed, because Java is included. Install [VLC](https://www.videolan.org) to play videos inside the app; without it, videos open in your default player. |
| 🤖 **Android** 8.0 or later | `LocalFlix-Android.apk` | Open the APK on your phone or tablet and allow installing from this source when asked. Updates install over the previous version and keep your library. |
| 📱 **iPad / iPhone** (iPadOS 26 or later) | `LocalFlix-iPad.ipa` | Unsigned. Install it with a sideloading tool such as [AltStore](https://altstore.io) or [Sideloadly](https://sideloadly.io), which signs it with your own Apple ID. |

## Getting started

1. **Install** LocalFlix for your device (see above).
2. **Choose your drive or folder** with your movies and TV shows. You can also skip this and add one later in Settings → Media Drives.
3. **Add a free TMDB API key** in Settings → Online Info to unlock posters, details, cast, episode lists and recommendations. Getting one takes a minute at [themoviedb.org](https://www.themoviedb.org/settings/api).
4. Grab some popcorn. 🍿

**Tip:** LocalFlix recognizes most layouts, but these work best:

```
Movies/
  Inception (2010)/Inception.2010.1080p.mkv
  The Matrix (1999).mp4
TV/
  Breaking Bad/
    Season 1/Breaking.Bad.S01E01.mkv
    Season 1/Breaking.Bad.S01E02.mkv
```

## Privacy

- **No account and no sign-in.** There's no tracking and no analytics.
- Your library, watch history, Watchlist and profiles are stored **only on your device**.
- LocalFlix connects to **TMDB** for artwork and info (only once you add a key), and to your own server or download site only if you set them up.
- Your video files never leave your drives.

## FAQ

**Is it free?** Yes.

**Do I need a server or NAS?** No. LocalFlix reads your files directly from any drive or folder your device can see, including USB drives and network shares.

**Does it change my files?** It never renames, moves or deletes anything. The only thing it adds is artwork images (like `poster.jpg`) next to your media, and if the drive is read-only it keeps them inside the app instead.

**Why does my Mac or PC warn me when I first open it?** The apps aren't signed with paid Apple or Microsoft developer certificates. The install steps above show how to open them.

**Can I use it without a TMDB key?** Yes. Your library and playback work without one, using the file names for titles. The key adds artwork, details, cast and recommendations.

---

<sub>This product uses the TMDB API but is not endorsed or certified by TMDB. Streaming availability data from JustWatch.</sub>
