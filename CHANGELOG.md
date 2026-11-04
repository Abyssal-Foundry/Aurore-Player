# Changelog

## 0.2.5

### English

- "Always search online" now also fills the Artists, Albums and Playlists tabs with YouTube Music results. Artist, album and playlist pages open with their songs ready to play.
- PC: with "Always search online" on, the separate Online page merges into the search.
- PC: reorganized settings screen.
- Android: the spectrum now reacts to the music on every phone. It's computed from the song itself, because Android's audio capture is silent on many phones. With music playing, the shape follows the sound instead of flowing like a wave, the same as on PC.
- Android: online album tracks show their length.

### Português

- "Sempre buscar online" agora também preenche as abas Artistas, Álbuns e Playlists com resultados do YouTube Music. As páginas de artista, álbum e playlist abrem com as músicas prontas para tocar.
- PC: com "Sempre buscar online" ligado, a página Online separada passa a fazer parte da busca.
- PC: tela de configurações reorganizada.
- Android: o spectrum agora reage à música em qualquer celular. Ele é calculado a partir da própria música, porque a captura de áudio do Android fica muda em muitos aparelhos. Com música tocando, o formato acompanha o som em vez de correr como uma onda, igual ao PC.
- Android: as faixas de álbuns online mostram a duração.

## 0.2.4

### English

- New setting on Android (GitHub version) and PC: "Always search online". The search also shows YouTube Music songs as you type, and they play with one tap.
- Android: online songs start in about 3 seconds. The song you tap plays first, and the next results are queued so Next keeps going. Songs played online aren't added to your library.
- Android: the cover shows a play icon on online results, a spinner while a song loads and bars while it plays. The download button stays separate.
- Android: the spectrum styles are drawn like the PC app. The wave is smooth, flows sideways and follows the sound.
- Android: the theme takes its colors from the online song's cover.
- PC: the spectrum styles are back to normal, with the progress bar and knob under the styles that don't show progress.
- PC: online songs without a known length now show their real duration and progress.

### Português

- Nova opção no Android (versão do GitHub) e no PC: "Sempre buscar online". A busca também mostra músicas do YouTube Music enquanto você digita, e elas tocam com um toque.
- Android: músicas online começam em cerca de 3 segundos. A música tocada vai primeiro, e as próximas da busca entram na fila, então o "próxima" continua funcionando. Músicas tocadas online não entram na biblioteca.
- Android: a capa mostra um ícone de play nos resultados online, um indicador enquanto carrega e barrinhas enquanto toca. O botão de download continua separado.
- Android: os estilos de spectrum são desenhados igual ao app de PC. A onda é suave, corre para o lado e acompanha o som.
- Android: o tema pega as cores da capa da música online.
- PC: os estilos de spectrum voltaram ao normal, com a barra de progresso e o botão de arrastar nos estilos que não são de progresso.
- PC: músicas online sem duração conhecida agora mostram a duração e o progresso reais.

## Desktop 0.2.3

### English

- All spectrum styles now use the current theme color and highlight the played portion.
- The mini player has extra room so its controls and spectrum are not clipped.
- Automatic updates retry periodically, report installation errors, and show localized release notes.

### Português

- Todos os estilos de espectro agora usam a cor atual do tema e destacam o trecho já tocado.
- O mini player ganhou um pouco mais de espaço para não cortar os controles nem o espectro.
- A atualização automática tenta novamente periodicamente, informa erros de instalação e mostra as novidades no idioma escolhido.

## 0.2.2

Android and PC now ship together in one release.

- Android: "Import YouTube Music playlist" in the Library menu (was "Download online playlist").

### PC

- Import YouTube Music playlists from the Online page or the button next to Playlists (long playlists come in full).

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
