# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Reveal.js presentation about AllStar (amateur radio VoIP linking system). It uses Reveal.js 5.1.0 loaded from the unpkg CDN — no build step or npm required.

## Development

**Serve locally:**
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

You can also open `index.html` directly in a browser — speaker notes work with direct file access in Zen browser.

## Reveal.js Keyboard Shortcuts

- Arrow keys / Space — Navigate slides
- `s` — Open speaker notes window
- `F` — Fullscreen
- `O` / `Esc` — Slide overview
- `B` / `.` — Pause (black screen)

## Slide Editing

All slides live in `index.html` inside `<section>` elements within `<div class="slides">`. Add speaker notes with `<aside class="notes">` inside any section.

## Keeping README.md and index.html in Sync

`README.md` contains the authoritative presentation outline. Whenever you add, remove, rename, or reorder slides in `index.html`, you must also update the outline in `README.md` in the same response — and vice versa.
