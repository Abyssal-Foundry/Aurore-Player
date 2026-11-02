# Changelog

## Desktop 0.2.1

- System tray icon: click to open; menu with play/pause, next, previous, mini player and quit.
- Minimize (main window or mini player) hides to the tray.
- Only one copy of the app runs: opening it again brings back the open one.
- Closing the app stops the music right away.
- Songs start faster, with a loading animation while an online song starts.
- Synced lyrics follow the song exactly.
- Mini player keeps its compact size.

## Desktop 0.2.0

First release of Aurore Player for PC: Linux AppImage and portable Windows zip.

- Home, library (songs, playlists, artists, albums), artist and album pages.
- Now playing with blurred artwork, synced lyrics with translation, 15 visualizer styles.
- Up next queue, sleep timer, crossfade, resume the last song where you left off.
- Floating mini player (from the minimize/close buttons or the player).
- Themes: dynamic colors from the artwork, 8 fixed themes, custom color, AMOLED black.
- Online: YouTube Music songs, artists and albums. Spotify search is not working yet.
- Import YouTube Music playlists; playlists can mix local and online songs; stacked playlist covers.
- "Save locally" downloads a whole playlist or album into a folder with its name.
- Twitch song requests (chat !sr and channel points) with moderation, and an OBS overlay.
- Automatic updates from GitHub Releases (Linux AppImage).
- ffmpeg (LGPL build) and yt-dlp are bundled: nothing else to install.

## 0.2.0

### New
- **Aurore Player**: the GitHub build is now its own app, with a new dawn icon. It installs next to Aurora from Google Play without replacing it.
- **Lyrics translation** into the app language, on-device: the original line small, the translation large below it. Toggle it with the button on the lyrics.
- **Home screen**: greeting, quick Shuffle / Play, recently played, most played, albums, artists and playlists.
- **Navigation style** in Settings: side menu (default) or bottom bar (Home / Search / Library).
- **Library tabs**: Songs, Playlists, Artists and Albums.
- **Artist and album pages** with large artwork, song count, total length and Play / Shuffle buttons.
- **Now playing** opens over everything: blurred artwork background, swipe the cover to skip, pull down to close, swipe the mini player up to open it.
- **Up next queue**: "Play next" and "Add to queue" in the song menu, plus a queue screen.
- **Synced lyrics**: from a `.lrc` file next to the song, lyrics embedded in the file, or LRCLIB. The current line follows the music; tap a line to jump there.
- **Sleep timer** (5–90 min or end of song) with a gentle fade-out.
- **Crossfade** between songs (2–12 s).
- **Button vibration**, can be turned off in Settings.
- **Search screen** with Songs, Artists, Albums and Playlists tabs; accent-insensitive.
- **15 visualizer styles** (new: area, LED, peaks, center, progress area, progress LED), picked from a grid with live previews.
- **New menus** that slide up from the bottom, with icons and artwork; the actions menu drops down from the ⋮ button.
- **High-resolution artwork** (up to 1200 px); small covers saved earlier are upgraded to a sharper copy of the same image.
- The same mini player on every screen.

### Improvements
- The visualizer is smooth (updates every frame) and reacts to real frequencies.
- The playing song is highlighted in lists with a small animated equalizer instead of being dimmed.
- Player shows artist and album on separate lines.
- Songs without artwork get a colorful placeholder.

### Fixes
- Menus had dark text on a dark background when the phone was in light mode.
- "Remove from playlist" appeared for songs that were not in any playlist.
- Creating a playlist with an existing name replaced the old playlist.
- The mini player on the download screen showed 0:00 / 0:00.
- Permission prompts no longer appear behind the welcome screen.
- Playing from search, an album or Home no longer shrinks the Songs list.

## 0.1.9.9
- First-time support guide (6 languages).
- Background downloads with floating progress and artwork.
- Online playlist download.
- Playlist management, batch actions and empty states.
- Splash screen and readability fixes.
