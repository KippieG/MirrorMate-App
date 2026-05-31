<div align="center">
  <img src="assets/icon.png" width="110" height="110" alt="MirrorMate icon" />
  <h1>MirrorMate</h1>
  <p><strong>The instant mirror for your Mac — always one shortcut away.</strong></p>

  <img src="https://img.shields.io/badge/macOS-13.0%2B-000000?style=flat-square&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/Swift-5.9-F05138?style=flat-square&logo=swift&logoColor=white" />
  <img src="https://img.shields.io/badge/SwiftUI-0070C9?style=flat-square&logo=swift&logoColor=white" />
  <img src="https://img.shields.io/badge/AVFoundation-636363?style=flat-square" />
  <img src="https://img.shields.io/badge/StoreKit_2-5856D6?style=flat-square" />
  <img src="https://img.shields.io/badge/App_Store-★_4.9-FFD60A?style=flat-square&logo=appstore&logoColor=000" />
  <br /><br />

  <a href="https://apps.apple.com/us/app/mirrormate-menubar-mirror/id6752225278">
    <img src="assets/mac-appstore-badge.svg" height="44" alt="Download on the App Store" />
  </a>
  &nbsp;&nbsp;
  <a href="https://mirrormateapp.com">
    <img src="https://img.shields.io/badge/Website-mirrormateapp.com-1C1C1E?style=flat-square" height="20" />
  </a>
</div>

---

## What is MirrorMate?

MirrorMate turns your Mac's camera into an instant mirror — accessible from the menubar or via `⌘⇧M` at any moment. Zero switching, zero friction. The mirror appears in under 50ms and disappears just as fast.

Built for anyone who wants a quick mirror before a Zoom call, presentation, or just to check themselves — without picking up their phone.

**4.9★ on the App Store &nbsp;·&nbsp; 12K+ Mac users &nbsp;·&nbsp; 100% native macOS &nbsp;·&nbsp; < 50ms to open**

---

## Screenshots

<table>
  <tr>
    <td align="center"><img src="assets/screenshot-settings.png" width="370" /><br /><sub><b>General Settings</b></sub></td>
    <td align="center"><img src="assets/screenshot-appearance.png" width="370" /><br /><sub><b>Appearance & Grid Overlay</b></sub></td>
  </tr>
  <tr>
    <td align="center"><img src="assets/screenshot-shortcuts.png" width="370" /><br /><sub><b>Keyboard Shortcuts</b></sub></td>
    <td align="center"><img src="assets/screenshot-pro.png" width="370" /><br /><sub><b>MirrorMate Pro</b></sub></td>
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
| UI | SwiftUI + AppKit (`NSPanel`, `NSStatusBar`) |
| Camera | AVFoundation (`AVCaptureSession`, up to 1080p) |
| State | Combine + `@MainActor` |
| Payments | StoreKit 2 — Lifetime, Annual, Monthly |
| Architecture | MVVM — `MirrorViewModel`, `CameraManager`, `AppCoordinator` |
| Persistence | `UserDefaults` + `@AppStorage` |

The camera session pauses automatically when the mirror is hidden — zero CPU/GPU overhead when idle.

---

## Privacy

- No network requests — ever
- No analytics or tracking
- Camera activates only when the mirror window is open
- No data stored or transmitted anywhere

---

## Requirements

- macOS 13.0 (Ventura) or later
- Any built-in or external camera
- ~10 MB disk space

---

<div align="center">
  <br />
  Built solo as an indie macOS product.
  <br /><br />
  <strong>Philippe Godfroy</strong>
  <br />
  <a href="https://github.com/KippieG">github.com/KippieG</a> &nbsp;·&nbsp; <a href="https://mirrormateapp.com">mirrormateapp.com</a>
  <br /><br />
  <sub>This repository is a public showcase. Source code is private.</sub>
</div>
