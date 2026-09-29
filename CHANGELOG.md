# Changelog

Release notes for every published Loopframe build. Each entry matches a [GitHub Release](https://github.com/loopframeapp/loopframerelease/releases).

## [0.0.1](https://github.com/loopframeapp/loopframerelease/releases/tag/v0.0.1) — 2026-09-21

First public early-access build.

### Added

- YouTube URL or local file import (drag-and-drop).
- Photos-style trim, crop/reframe, cover-mark on export, and multi-clip stitch with optional join fade.
- Speed control; audio kept for Instagram exports, stripped for wallpaper engines.
- Dual export (16:9 + 9:16) from one trim.
- Export queue, export library, Share / Reveal in Finder.

### Added (build 5, 2026-09-28)

- In-app updates: Loopframe now checks for new builds automatically and installs them with one click (Settings → About). Builds 3 and 4 have no updater, so install this build manually once.

### Changed (build 4, 2026-09-28)

- yt-dlp updates and the YouTube HD helper are now verified by SHA-256 before use.
- Browser cookies (YouTube fallback) and export notifications are now opt-in under Settings → Privacy & network.
- Added a privacy summary and third-party licenses to Settings → About.
- The HD helper server now stops when you quit Loopframe.
- “Check for updates” now opens this releases page.
- Fixed the bundled yt-dlp failing to start on signed builds.

### Fixed

- YouTube HD helper (PO-token server) failing to start with “Could not start the YouTube HD helper on port 4416” — bundled Deno is now signed with JIT entitlements and updated to 2.9.7; Homebrew Deno is preferred when installed.

### Notes

- Exports are play-once cuts for wallpaper engines and Instagram — Loopframe does not set your desktop wallpaper.
- Requires macOS 14 (Sonoma) or later.

### Download

[Loopframe.dmg](https://github.com/loopframeapp/loopframerelease/releases/download/v0.0.1/Loopframe.dmg)
