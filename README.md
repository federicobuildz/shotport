# Shotport

**Steam Deck screenshots on your phone, in one tap.** Over your own wifi. No cloud, no account, no Steam login.

- A small server runs on the Deck. Your phone opens `steamdeck.local:7777`.
- The latest screenshot is shown big, the others grouped by game with a filter.
- Tap one, it's saved to your gallery. Phone to Deck works too (lands in `~/Downloads/Shotport`).
- Files go straight from one device to the other, on your network.

**Landing page:** https://federicobuildz.github.io/shotport/ — leave your email to get one message when the proper version ships. No newsletter.

## Why

Steam's own "Send to Phone" exists, but the link expires, it doesn't save to the gallery, and it's one file at a time. Shotport is the boring fix: open a page, tap, done.

## Status

Personal tool, built in one evening with [Claude Code](https://claude.com/claude-code). Tested on one real Steam Deck (25 screenshots, it worked). It's rough: you start it from Desktop mode, there's no pairing yet (anyone on your wifi could open the page).

The proper version, if there's interest: pairing, starts with the Deck, one-time price around €9.99.

## Source

Not yet. Pairing first. This repository holds the landing page only.

## How it's built

- Server: ~300 lines of Node, bundled with a Linux x64 Node binary so nothing needs installing on SteamOS.
- Phone side: a plain web page, light/dark theme, no app to install.

Made in Rome by a window cleaner. Not affiliated with Valve. Questions: open an issue.
