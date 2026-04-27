# vault-pulse-releases

Public release feed for [VaultPulse](https://github.com/tandregbg/vault-pulse) — a macOS menu-bar app for tracking files in an Obsidian / core-skills vault.

This repo exists only to serve the Sparkle update feed and signed `.dmg` builds. The application source lives in a private repository; this repo never sees source commits.

## Install

Download the latest signed, notarized **DMG** from [Releases](https://github.com/tandregbg/vault-pulse-releases/releases/latest):

1. Double-click the downloaded `.dmg` to mount it.
2. Drag `VaultPulse.app` onto the `Applications` shortcut.
3. Eject the disk image and open VaultPulse from `/Applications`.

macOS Gatekeeper accepts the build directly — no warnings, no `xattr` workarounds.

## Auto-updates

Installed copies of VaultPulse poll this feed daily and apply notarized updates with no manual download needed. The Sparkle public key is embedded in the app at build time; tampered downloads are rejected.

Per-release artefacts are exposed only via the Releases page — `appcast.xml`, `release-notes.html`, and the DMG are uploaded with each tag. The repo's `main` branch intentionally stays minimal (just this README).

## Source

Source code is private. Issues and feature requests can be opened on this repo; they are reviewed manually.
