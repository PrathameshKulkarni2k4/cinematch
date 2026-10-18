# CineMatch

A content-based movie recommender with a modern, streaming-style web interface.

**Live:** https://prathameshkulkarni2k4.github.io/cinematch/

Pick a movie and CineMatch ranks all 4,806 titles in the library by content
similarity (genres, keywords, cast, crew) — with posters, ratings, official
trailers, and where each title streams legally (via TMDB / JustWatch).

Everything is in `index.html` — a single self-contained file. No build, no server.

## Features
- Recommendations by cosine similarity over movie metadata (4,806 titles)
- Hero banner, Trending / Top 10 / genre rows, instant search
- Official trailers (streamed from YouTube)
- Where to watch legally (TMDB / JustWatch), with a region switcher

## Run locally
Open `index.html` in a browser.

## Notes
- Metadata from TMDB. Replace `CONFIG.TMDB_KEY` in `index.html` with your own
  free key from https://www.themoviedb.org/settings/api
- Trailers are official trailers served by YouTube. No video is hosted or
  streamed here.
