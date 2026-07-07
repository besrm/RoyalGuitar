# RoyalGuitar

**RoyalGuitar** is a native macOS media and music utility app for working with images, video, audio, and guitar-focused tools from one dashboard.

It brings common creative utilities into a single interface so you can open media files, process them, preview changes, and export finished results without jumping between a dozen separate apps like some kind of digital raccoon.

---

## Highlights

- Native macOS interface
- Image, video, audio, and guitar-focused tools in one app
- Dashboard and sidebar workflow
- Batch processing for supported media operations
- Export presets and sharing utilities
- Local-first media processing
- Light, Dark, System, Gray, and translucent appearance modes
- Keyboard shortcut support
- Expanded localization support in v1.4

---

## What’s New in v1.4

RoyalGuitar **v1.4** focuses on localization, interface cleanup, slideshow controls, export workflows, and general polish across the app.

### v1.4.0 Changes

- Expanded localization across major app areas
- Improved slideshow controls and inspector labels
- Cleaned up UI text across video, audio, export, and dashboard tools
- Improved Sparkle update packaging support
- Updated website release references
- Improved project, metadata, and gallery status messages
- Cleaned up remaining untranslated menu and toolbar labels
- General stability and interface polish

---

## Features

### Image Tools

- Photo editing controls for common adjustments
- Crop, resize, and format conversion tools
- Image compression
- Metadata removal for safer sharing
- Image overlays and visual editing tools
- AI-assisted image utilities where supported

### Video Tools

- Video playback
- Video trimming and segment editing
- Video conversion and compression
- Video resizing
- Watermarking tools
- Export presets
- Metadata removal for video files
- Slideshow and timeline-based video tools

### Audio Tools

- Audio trimming and editing
- Audio format conversion
- Audio extraction from video files
- Audio merging
- Audio enhancement tools
- Frequency and spectrum analysis
- Audio repair and diagnostic workflows where supported

### Guitar & Music Tools

- Guitar-focused practice features
- Chord and audio-analysis tools where supported
- Practice session tracking
- Music workflow utilities

### Utility Tools

- Batch processing for supported media operations
- Export and sharing workflows
- Recent projects and file browsing
- Dashboard-based navigation
- Appearance customization
- Local media workflows without requiring an account

---

## Requirements

- macOS 15.0 Sequoia or later
- Apple Silicon or Intel Mac
- 4 GB RAM minimum
- 8 GB RAM recommended
- Additional storage space for media files, exports, and temporary processing files

Some media-processing and machine-learning features may run faster on Apple Silicon Macs.

---

## Installation

Download the latest version from the **Releases** page.

### DMG Install

1. Download the latest `.dmg` file.
2. Open the DMG.
3. Drag `RoyalGuitar.app` into the Applications folder.
4. Launch RoyalGuitar from Applications.

### ZIP Install

1. Download the latest `.zip` file.
2. Extract the archive.
3. Move `RoyalGuitar.app` to Applications.
4. Launch RoyalGuitar from Applications.

---

## First Launch on macOS

RoyalGuitar is distributed outside the Mac App Store. Depending on the build, macOS may show a security warning the first time the app is opened.

If macOS blocks the app:

1. Open **System Settings**.
2. Go to **Privacy & Security**.
3. Scroll down to the security message for RoyalGuitar.
4. Click **Open Anyway**.
5. Launch RoyalGuitar again.

Advanced users may remove the quarantine flag manually:

```bash
xattr -dr com.apple.quarantine /Applications/RoyalGuitar.app
