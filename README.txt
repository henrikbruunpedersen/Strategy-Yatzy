STRATEGY YATZY - hostable version
=================================

Contents:
  index.html             <- the app itself (open this one)
  manifest.webmanifest   <- app info (name, icon, full screen)
  icon-180.png           <- icon for the iPhone/iPad home screen
  icon-512.png           <- large icon (Android / installation)

How to play
-----------
- On the start screen, pick 1-6 players, type each name, and tap
  "Bot" on any slot to add an auto-playing computer opponent.
- Choose a difficulty: Normal (54 throws), Difficult (50) or Hard (46).
- Large field = points, small field = throws used that round
  (enter 0 to save the whole round).
- Every throw you have left when the game is finished is worth 2 bonus points.
- Bots play automatically: each time you finish a round they play one too.
  In a bots-only game, use the "Bot round" button to advance them.

How to host it
--------------
1. Upload ALL four files to the same folder on a web server.
   Works on any static host, e.g.:
   - Your own web host / a subdomain
   - GitHub Pages, Netlify, Cloudflare Pages (free)
2. Open the address in Safari on iPhone or iPad.
3. Tap the Share icon -> "Add to Home Screen".
   Strategy Yatzy now sits as an app with its own icon and runs full screen.

Note: keep the files together in the same folder - index.html references
the icon and manifest via relative paths.

Prefer EVERYTHING in a single file (no hosting)? Use the standalone
strategy-yatzy.html instead.
