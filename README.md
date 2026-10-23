# Yori releases

Yori is a local tool for reading, verifying and growing OKF (Open Knowledge Format) knowledgebases: rendered entries in tabs, a computed link graph and git as the only store. This repository holds the built apps and the update manifest; the source is private.

## Install

1. Open the [latest release](https://github.com/kenmclennan/yori-releases/releases/latest) and download `Yori.app.tar.gz` (Apple silicon only).
2. Unpack it and move `Yori.app` to `~/Applications`.
3. The app is ad-hoc signed, not Apple-signed, so macOS blocks the first open. Open it once, then go to System Settings > Privacy & Security and choose Open Anyway. Alternatively run `xattr -dr com.apple.quarantine ~/Applications/Yori.app` before the first open.

## Updates

Later updates install from inside the app. When a newer release exists, the footer shows "Yori X.Y.Z available - Install"; choosing it downloads the release, installs it and relaunches.
