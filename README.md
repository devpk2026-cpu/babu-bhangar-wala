# Babu Bhangar Wala

A single-page nostalgic retro Indian music player.

## Run locally

1. Keep `index.html` in a folder.
2. Open it directly in Chrome/Edge, or run a local server:
   - VS Code + Live Server
   - `python -m http.server 5500`
3. Visit `http://localhost:5500`

## Music

The default source is the YouTube video from the supplied URL.

The supplied URL is a YouTube `RD...` radio/mix URL rather than a standard YouTube playlist ID, so the page uses the supplied video ID as the default source. Users can paste a normal YouTube playlist URL containing `?list=PLAYLIST_ID` into **Apni Playlist Lao**.

## Notes

- YouTube's IFrame API is used for playback.
- Browser autoplay restrictions are respected; the user can press Play.
- No local images are required. The retro radio and paper/sign details are built entirely with HTML/CSS.
