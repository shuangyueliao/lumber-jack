# Lumber Jack — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Chop the giant tree, dodge the falling branches, and race the shrinking
timer. Fast chops build a x2 combo and rare gold branches pay +5. One wrong
side and it's over — how high can you score?

## Details

- Genre: Arcade / Timing / Action
- Controls: Mobile — tap the LEFT or RIGHT half of the screen to move and
  chop. Desktop — mouse click either side, or ←/→ and A/D keys. Space/Enter
  starts and restarts.
- Rules: every tap switches your side and swings the axe in one move. When
  the trunk slides down, a branch landing on your side is game over. The
  timer bar refills with every chop but its decay time tightens from 2.5 s
  toward 0.9 s as your score grows; let it empty and you're out of time.
- Scoring: +1 per segment, x2 while fast-chop combo is alive (chops under
  0.5 s apart), rare gold branch segments pay +5 (x10 in a combo).
- Features: branch generator always leaves one safe side (no dead-end
  positions), procedural tree with bark texture and growth-ring
  cross-sections, 3-frame axe swing animation, wood-chip particles, flying
  chopped segments, layered parallax forest silhouettes, day/night cycle
  every 50 points (day, sunset, night with stars and moon, dawn), best score
  saved locally, mute toggle.
- Tech: Vanilla JavaScript, Canvas, WebAudio (synthesized chop noise, chimes
  and deaths). Single-file HTML5, no external assets, no frameworks, no
  tracking, works offline once loaded.

## Tags

lumberjack, timber, chopping, timing, arcade, casual, tree, reflex, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas fills viewport, portrait & landscape friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## itch.io
- Upload zip (lumber-jack-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport: fits screen (480×720 design, letterboxed),
  kind: html
- Pricing: $0 (donations optional)
