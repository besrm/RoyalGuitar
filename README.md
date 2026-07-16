**RoyalGuitar** is a native macOS media and music utility that brings image, video, audio, download, and guitar-focused tools together in one application.

Open files, make adjustments, preview results, process supported operations in batches, and export finished projects without moving between a pile of separate programs pretending to be a workflow.

## Download

### Recommended

Download RoyalGuitar from the official website:

**[Download RoyalGuitar](https://royalguitarstudio.com/download)**

### GitHub

The newest published version is always available here:

**[Latest GitHub Release](https://github.com/besrm/RoyalGuitar/releases/latest)**

The `/releases/latest` link and release badge update automatically when a new GitHub release is published. The README does not require a manual version-number change for each release.

## Highlights

- Native macOS interface
- Universal support for Apple Silicon and Intel Macs
- Image, video, audio, download, utility, and guitar-focused tools
- Dashboard and sidebar navigation
- Batch processing for supported media operations
- Export presets and sharing workflows
- Local-first media processing
- Sparkle automatic-update support
- Light, Dark, System, Gray, and translucent appearance modes
- Keyboard shortcuts
- English, Japanese, German, French, Spanish, and Simplified Chinese localization
- Official website access from the About, Help, and Credits views
- Reliability improvements across media workflows

## Features

### Image Tools

- Photo adjustment controls
- Crop and resize tools
- Image format conversion
- Image compression
- Metadata removal
- Overlay and visual-editing tools
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
- Timeline-based editing
- Scene composition
- Export and sharing workflows

### Audio Tools

- Audio trimming and editing
- Audio format conversion
- Audio extraction from video
- Stem separation
- Audio merging
- Audio enhancement
- Frequency and spectrum analysis
- Audio repair and diagnostic tools where supported

### Guitar and Music Tools

- Guitar practice features
- Guitar tab generation
- Chord and audio analysis where supported
- Practice-session tracking
- MusicXML and PDF export
- Tuner tools
- Music-workflow utilities

### Download and Archival Tools

- yt-dlp support
- gallery-dl support
- Lux support
- YouTubeDR support
- FFmpeg-based media processing
- Architecture-aware bundled-tool selection
- Local download and archival workflows

### Utility and Workflow Tools

- Batch processing for supported operations
- Export and sharing tools
- Recent-project and file browsing
- Dashboard-based navigation
- Appearance customization
- Local media processing without requiring an account

## Requirements

- macOS 15.0 Sequoia or later
- Apple Silicon or Intel Mac
- 4 GB RAM minimum
- 8 GB RAM recommended
- Additional storage for media, exports, machine-learning models, and temporary processing files

Some machine-learning and media-processing operations perform faster on Apple Silicon Macs.

## Installation

### DMG installation

1. Download the latest `.dmg` from the [official download page](https://royalguitarstudio.com/download).
2. Open the DMG.
3. Drag `RoyalGuitar.app` into the Applications folder.
4. Launch RoyalGuitar from Applications.

### ZIP installation

1. Download the latest `.zip` from [GitHub Releases](https://github.com/besrm/RoyalGuitar/releases/latest).
2. Extract the archive.
3. Move `RoyalGuitar.app` into the Applications folder.
4. Launch RoyalGuitar from Applications.

The DMG is recommended for most users. The ZIP is also used by Sparkle for application updates.

## First Launch on macOS

RoyalGuitar is distributed outside the Mac App Store. Depending on the build and macOS security settings, macOS may display a warning the first time the application is opened.

When macOS blocks the application:

1. Open **System Settings**.
2. Select **Privacy & Security**.
3. Scroll to the security message for RoyalGuitar.
4. Click **Open Anyway**.
5. Launch RoyalGuitar again.

Advanced users may remove the quarantine attribute manually:

```bash
xattr -dr com.apple.quarantine "/Applications/RoyalGuitar.app"
