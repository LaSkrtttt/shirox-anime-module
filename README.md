# AnimeStream Community — Shirox Module

A GitHub-ready Shirox anime module.

## Features

• Anime search
• Cover artwork
• Anime details and aliases
• Episode lists
• SUB and DUB episode selection when the provider exposes them
• HLS/MP4 playback
• Soft subtitles when exposed by the embedded player
• HLS master playlists are preferred, allowing the Shirox player to select an available quality

## Install

1. Upload `animestream.json` and `animestream.js` to the root of your GitHub repository.
2. Edit `animestream.json` and replace `YOUR_USERNAME` with your GitHub username.
3. In Shirox, open **Settings → Modules → Add**.
4. Paste the raw GitHub URL for `animestream.json`, for example:

`https://raw.githubusercontent.com/YOUR_USERNAME/shirox-anime-module/main/animestream.json`

> **Note:** Do not use the normal `github.com/.../blob/...` page URL.

## Notes

The module depends on the provider’s public endpoints and Shirox’s module runtime, so provider-side changes can require updates. 1080p is not guaranteed for every title/episode; the module returns the highest-quality HLS source exposed by the provider.

*Use only content you are authorized to access.*

## Files

• `animestream.json` — Shirox import manifest
• `animestream.js` — module implementation
