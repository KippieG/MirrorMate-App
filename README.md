<div align="center">
  <img src="assets/icon.png" width="100" height="100" alt="MirrorMate icon" />
  <h1>MirrorMate</h1>
  <p><strong>The instant mirror for your Mac — always one shortcut away.</strong></p>

  <img src="https://img.shields.io/badge/macOS-13.0%2B-black?style=flat-square&logo=apple" />
  <img src="https://img.shields.io/badge/Swift-5.9-orange?style=flat-square&logo=swift" />
  <img src="https://img.shields.io/badge/SwiftUI-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/AVFoundation-grey?style=flat-square" />
  <img src="https://img.shields.io/badge/StoreKit_2-purple?style=flat-square" />
  <img src="https://img.shields.io/badge/App_Store-4.9%E2%98%85-gold?style=flat-square&logo=appstore" />
  <br /><br />

  <a href="https://apps.apple.com/us/app/mirrormate-menubar-mirror/id6752225278">
    <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" height="40" alt="Download on the Mac App Store" />
  </a>
  &nbsp;
  <a href="https://mirrormateapp.com">mirrormateapp.com</a>
</div>

---

## What is MirrorMate?

MirrorMate turns your Mac's camera into an instant mirror — accessible from the menubar or via `⌘⇧M` at any moment. Zero switching, zero friction. The mirror is there when you need it and invisible when you don't.

Built for anyone who wants a quick mirror before a call, presentation, or just to check themselves — without picking up their phone.

**4.9★ on the App Store · 12K+ Mac users · 100% native · 0ms perceived latency**

---

## Screenshots

<table>
  <tr>
    <td align="center"><img src="assets/screenshot-settings.png" width="380" /><br /><sub>General Settings</sub></td>
    <td align="center"><img src="assets/screenshot-appearance.png" width="380" /><br /><sub>Appearance & Grid Overlay</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="assets/screenshot-shortcuts.png" width="380" /><br /><sub>Keyboard Shortcuts</sub></td>
    <td align="center"><img src="assets/screenshot-pro.png" width="380" /><br /><sub>MirrorMate Pro</sub></td>
  </tr>
</table>

---

## Features

### Free
- **Instant access** — Global shortcut `⌘⇧M` or menubar click, opens in under 50ms
- **Freeze frame** — Press `Space` to pause and examine details
- **Flip** — Toggle horizontal flip with `⌘F`
- **Zoom** — Up to 5× zoom with `⌘+` / `⌘-`
- **Screenshot** — Capture your reflection with `⌘S`
- **Floating window** — Stays on top while you work
- **Multi-Space support** — Works across all Spaces and full-screen apps

### Pro
- **1080p quality** — Highest camera resolution
- **Grid overlays** — Rule of thirds, golden ratio, center guides
- **Video recording** — Record with or without microphone audio
- **Before/After comparison** — Freeze and compare two moments side by side
- **Multi-camera support** — Switch between built-in and external cameras
- **Custom window shape** — Rounded, square, or circular
- **Window opacity** — Adjust transparency to your preference

---

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `⌘⇧M` | Show / hide mirror |
| `Space` | Freeze / unfreeze frame |
| `⌘F` | Flip mirror horizontally |
| `⌘G` | Toggle grid overlay |
| `⌘+` | Zoom in |
| `⌘-` | Zoom out |
| `⌘0` | Reset zoom |
| `⌘S` | Take screenshot |
| `⌘,` | Open settings |

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| UI | SwiftUI + AppKit (NSPanel, NSStatusBar) |
| Camera | AVFoundation (AVCaptureSession, up to 1080p) |
| State | Combine + `@MainActor` |
| Payments | StoreKit 2 (Lifetime, Annual, Monthly) |
| Architecture | MVVM — `MirrorViewModel`, `CameraManager`, `AppCoordinator` |
| Persistence | `UserDefaults` + `@AppStorage` |

The camera session pauses automatically when the mirror is hidden — zero CPU/GPU overhead when idle.

---

## Privacy

- No network requests — ever
- No analytics or tracking
- Camera activates only when the mirror window is visible
- No data stored or transmitted

---

## Requirements

- macOS 13.0 (Ventura) or later
- Any built-in or external camera
- ~10 MB disk space

---

<div align="center">
  Built solo as an indie macOS product.<br />
  <strong>Philippe Godfroy</strong> — <a href="https://github.com/KippieG">github.com/KippieG</a> · <a href="https://mirrormateapp.com">mirrormateapp.com</a>
  <br /><br />
  <em>This repository is a public showcase. Source code is kept private.</em>
</div>
