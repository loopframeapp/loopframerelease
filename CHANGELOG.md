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

### Fixed

- YouTube HD helper (PO-token server) failing to start with “Could not start the YouTube HD helper on port 4416” — bundled Deno is now signed with JIT entitlements and updated to 2.9.7; Homebrew Deno is preferred when installed.

### Notes

- Exports are play-once cuts for wallpaper engines and Instagram — Loopframe does not set your desktop wallpaper.
- Requires macOS 14 (Sonoma) or later.

### Download

[Loopframe.dmg](https://github.com/loopframeapp/loopframerelease/releases/download/v0.0.1/Loopframe.dmg)
