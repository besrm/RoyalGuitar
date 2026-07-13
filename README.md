# Royal Guitar Studio

**RoyalGuitar** is a native macOS media and music utility designed for working with images, video, audio, and guitar-focused tools from a single dashboard.

The app brings common creative and media-processing workflows into one interface, allowing users to open files, make adjustments, preview results, and export finished projects without relying on multiple separate applications.

---

## Download

Download the latest release from the **GitHub Releases** page:

https://github.com/besrm/RoyalGuitar/releases/latest

Latest version: **RoyalGuitar 1.5.5**

---

## Highlights

- Native macOS interface
- Image, video, audio, and guitar-focused tools
- Dashboard and sidebar navigation
- Batch processing for supported media operations
- Export presets and sharing tools
- Local-first media processing
- Sparkle update support
- Light, Dark, System, Gray, and translucent appearance modes
- Keyboard shortcut support
- Expanded localization
- Improved stability across media workflows

---

## Version 1.5.5

RoyalGuitar 1.5.5 improves the Advanced Video Trimmer, audio workflows, guitar tools, and general application reliability.

### Advanced Video Trimmer

- Fixed exported videos containing content outside the selected trim range
- Added accurate Fast and Frame Accurate export modes
- Connected codec, quality, preset, and hardware encoder controls
- Added real timeline zoom and horizontal scrolling
- Improved playback, scrubbing, jog wheel, and playhead synchronization
- Added timeline thumbnails and waveform alignment
- Improved Start and End range validation
- Added editable trim ranges for batch items
- Improved export progress reporting and cancellation
- Added drag-and-drop video loading
- Improved task cleanup and navigation persistence
- Added localized trimmer messages

### Audio Tools

- Improved Audio Converter validation and format handling
- Added FFprobe fallback behavior
- Added advanced conversion controls
- Expanded localization for Audio Converter settings
- Added Demucs stem extraction support to Audio Extractor

### Guitar Tools

- Improved Guitar Tab Generator state persistence when moving between tools

### General Improvements

- Removed excessive yt-dlp console logging while keeping the startup cookie health check and timeout monitoring
- Improved processing reliability
- Improved export and workflow stability
- General performance and interface refinements

---

## Version 1.5.3

RoyalGuitar 1.5.3 introduced major improvements to guitar-tab transcription, Learn mode, tuner feedback, MusicXML and PDF exports, source separation, and memory efficiency.

### Changes

- Added detailed fingering guidance
- Added an Accuracy Guide
- Improved full-song Basic Pitch analysis
- Improved source separation workflows
- Improved tuner feedback
- Improved MusicXML and PDF exports
- Reduced memory usage during longer analysis sessions
- Added stability fixes across guitar and transcription tools

---

## Version 1.5.2

- Fixed the BiliBili support issue
- Added minor stability and performance improvements

---

## Version 1.5.1

- Fixed crashes involving unusual or malformed video files
- Improved handling for interrupted or stalled downloads
- Reduced interface freezes during heavier media operations
- Improved protection against accidentally overwriting original files
- Improved export and processing workflows
- Added general reliability improvements

---

## Version 1.5.0

RoyalGuitar 1.5.0 focused on application polish, workflow improvements, and release packaging.

### Changes

- Improved media-processing reliability
- Updated export and sharing behavior
- Refined dashboard and tool interfaces
- Improved GitHub and Sparkle release packaging
- Added general fixes and cleanup throughout the app

---

## Version 1.4.0

RoyalGuitar 1.4.0 focused on localization, interface cleanup, slideshow controls, export workflows, and general application polish.

### Changes

- Expanded localization across major areas of the app
- Improved slideshow controls and inspector labels
- Refined interface text across video, audio, export, and dashboard tools
- Improved Sparkle update packaging
- Updated website release references
- Improved project, metadata, and gallery status messages
- Cleaned up untranslated menu and toolbar labels
- Added general stability and interface improvements

---

## Features

### Image Tools

- Photo adjustment controls
- Crop and resize tools
- Image format conversion
- Image compression
- Metadata removal
- Overlay and visual editing tools
- AI-assisted image utilities where supported
- Black-and-white image colorization where supported

### Video Tools

- Video playback
- Advanced video trimming
- Segment editing
- Video conversion
- Video compression
- Video resizing
- Watermarking
- Export presets
- Video metadata removal
- Slideshow creation
- Timeline-based editing tools
- Export and sharing workflows

### Audio Tools

- Audio trimming and editing
- Audio format conversion
- Audio extraction from video files
- Stem separation
- Audio merging
- Audio enhancement
- Frequency and spectrum analysis
- Audio repair and diagnostic tools where supported

### Guitar and Music Tools

- Guitar practice features
- Guitar tab generation
- Chord and audio analysis where supported
- Practice session tracking
- MusicXML and PDF export
- Tuner tools
- Music workflow utilities

### Utility Tools

- Batch processing for supported media operations
- Export and sharing tools
- Recent project and file browsing
- Dashboard-based navigation
- Appearance customization
- Local media processing without requiring an account

---

## Requirements

- macOS 15.0 Sequoia or later
- Apple Silicon or Intel Mac
- 4 GB RAM minimum
- 8 GB RAM recommended
- Additional storage space for media files, exports, and temporary processing files

Some machine-learning and media-processing features may perform faster on Apple Silicon Macs.

---

## Installation

Download the latest release from the **GitHub Releases** page.

### DMG Installation

1. Download the latest `.dmg` file.
2. Open the DMG.
3. Drag `RoyalGuitar.app` into the Applications folder.
4. Launch RoyalGuitar from Applications.

### ZIP Installation

1. Download the latest `.zip` file.
2. Extract the archive.
3. Move `RoyalGuitar.app` into the Applications folder.
4. Launch RoyalGuitar from Applications.

For most users, the DMG is the recommended installation method.

---

## First Launch on macOS

RoyalGuitar is distributed outside the Mac App Store. Depending on the build and macOS security settings, a warning may appear the first time the app is opened.

If macOS blocks the app:

1. Open **System Settings**.
2. Select **Privacy & Security**.
3. Scroll to the security message for RoyalGuitar.
4. Click **Open Anyway**.
5. Launch RoyalGuitar again.

Advanced users may remove the quarantine attribute manually:

```bash
xattr -dr com.apple.quarantine /Applications/RoyalGuitar.app
