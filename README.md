# CineMatch

A content-based movie recommender with a modern, streaming-style web interface.

**Live:** https://prathameshkulkarni2k4.github.io/cinematch/

Pick a movie and CineMatch ranks all 4,806 titles in the library by content
similarity (genres, keywords, cast, crew), with posters, ratings and where each
title streams legally (via TMDB / JustWatch).

Everything is in `index.html` — a single self-contained file. No build, no server.

## Run locally
Open `index.html` in a browser.

## Notes
- Metadata from TMDB. Replace `CONFIG.TMDB_KEY` in `index.html` with your own
  free key from https://www.themoviedb.org/settings/api
- This is a discovery tool. It does not host or stream any video.
