# TikTok Live Music Player

Local-first Windows desktop music player for fast song lookup during live streams.

## MVP v0.1

The development branch now includes a native Tauri shell, Windows folder picker, recursive local audio scan, fuzzy filename search, Enter/click-to-play, and a Now Playing panel. Supported extensions: MP3, FLAC, WAV, M4A, AAC and OGG.

Metadata tags and queue/history are not implemented yet; the current title is derived from the filename.

## Run locally

Prerequisites: Node.js 20+, Rust stable, and the Windows prerequisites required by Tauri 2.

```bash
npm install
npm test
npm run desktop
```

For the web-only UI shell use `npm run dev`. Native folder scanning requires `npm run desktop`.

## Privacy

Music remains on the user's computer. Do not commit music files or private library data to this repository.

## Next increment

1. Read embedded title/artist metadata with filename fallback.
2. Add queue, next/previous, history and keyboard controls.
3. Add GitHub Actions validation and Windows installer build.
4. Validate audio routing workflow with TikTok LIVE Studio.
