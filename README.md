# Latch — releases

Public download host for **[Latch](https://latch.nachoaverage.app)**, a menu-bar grid window
manager for macOS by [Nacho Average Apps](https://nachoaverage.app).

This repository contains **no source code**. It exists only to host signed, notarised release
builds so downloads are fast, versioned, and free of bandwidth limits.

## Download

**[Download the latest version](https://github.com/WVandergrift/latch-releases/releases/latest/download/Latch.dmg)**

That link always resolves to the newest release, so it is safe to bookmark or link to.

Every build is signed with a Developer ID certificate and **notarised by Apple**, with the ticket
stapled into the disk image — so Gatekeeper clears it on first launch even on a machine that is
offline.

## Requirements

- macOS 14 (Sonoma) or later, Apple silicon or Intel
- Accessibility permission, granted on first run. Latch moves other applications' windows, which is
  only possible through the macOS Accessibility API. That API is unavailable to sandboxed apps and
  the Mac App Store requires sandboxing, which is why Latch is distributed directly.

## Support

Questions, bugs, or anything not working: **support@nachoaverage.app**

Release notes for each version are on the [releases page](https://github.com/WVandergrift/latch-releases/releases).
