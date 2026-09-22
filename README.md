# TikTok Live Music Player

Local-first Windows music player designed for fast song lookup during live streams.

## MVP v0.1

Current scaffold includes a React/TypeScript UI, instant fuzzy search, keyboard Enter-to-play behavior, now-playing panel, and unit tests for search behavior.

> The current branch uses demo tracks while the native filesystem/audio layer is implemented next. It does not yet scan or play files from your Windows music folder.

## Development

Prerequisites: Node.js 20+.

```bash
npm install
npm test
npm run dev
npm run build
```

## Planned next increment

Native Tauri integration: folder picker, recursive audio scan (MP3/FLAC/WAV/M4A), metadata extraction, safe local playback, queue, history, and Windows packaging.

## Safety / privacy

The product is local-first. Music files should remain on the user's computer and must not be committed to this repository.
