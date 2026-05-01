# 🎸 Retro 2000s Blog Garage

A fully hand-crafted early-2000s style personal weblog — no frameworks, no build tools, just one HTML file and a lot of nostalgia.

Built around the aesthetic of Y2K weblogs, garage band culture, alt-rock and the early internet. Inspired by the kind of site you'd find linked from a Newgrounds page in 2003.

## Features

- **Winamp-style music player** with real album art fetched from Wikipedia
- **Currently Watching / Reading / Playing** tabs with live poster art from TMDB and Wikipedia
- **Retro visitor counter** powered by CounterAPI
- **Quote generator** in that early-2000s AIM away message energy
- **Animated 88×31 link banners** — Newgrounds, DeviantArt, Neopets and more
- **Links page** with Y2K webring and guestbook shoutout
- **Stickers** scattered across every panel — stamps, ovals, starbursts
- **Milestone fireworks** at visitor count milestones
- **Clickable flip sticker** in the header
- **About Me** panel styled after a 2003 AIM profile
- **Retro footer** with IE6 joke and Y2K webring buttons
- **CRT scanline overlay** and grid background
- **No frameworks** — pure HTML, CSS and vanilla JavaScript

## Tech

- Pure HTML / CSS / JS — no React, no Node, no build step
- Self-hosted Google Fonts (TTF)
- TMDB API for movie and TV posters
- Wikipedia REST API for game covers and album art
- CounterAPI for the visitor counter
- Deployed on GitHub Pages

## Structure

```
index.html
banner.jpg
favicon.png
fonts/         ← self-hosted Google Fonts
images/
  main/        ← site photos
  gaming/      ← game box art
  watching/    ← movie & TV posters
  reading/     ← book covers
  album-art/   ← Winamp album art
```

