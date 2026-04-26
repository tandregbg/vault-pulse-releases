# vault-pulse-releases

Public release feed for [VaultPulse](https://github.com/tandregbg/vault-pulse) — a macOS menu-bar app for tracking files in an Obsidian / core-skills vault.

This repo exists only to serve the Sparkle update feed and the signed `.app` zips. The application source lives in a private repository; this repo never sees source commits.

## Install

Download the latest signed, notarized build from [Releases](https://github.com/tandregbg/vault-pulse-releases/releases/latest) and drag `VaultPulse.app` into your Applications folder. macOS Gatekeeper will let it run without warnings.

## Auto-updates

Installed copies of VaultPulse poll this feed daily and apply notarized updates with no manual download needed. The Sparkle public key is embedded in the app at build time; tampered downloads are rejected.

Feed URL (read by Sparkle, not intended for humans):

```
https://github.com/tandregbg/vault-pulse-releases/releases/latest/download/appcast.xml
```

## Source

Source code is private. Issues and feature requests can be opened on this repo; they are reviewed manually.
