RoyalGuitar

RoyalGuitar is a native macOS media and music utility app designed for working with audio, video, images, and guitar-focused tools from one interface.

It provides a dashboard-based workflow for opening media files, choosing tools, editing content, and exporting finished results.

⸻

Features

Image Tools

* Photo editing controls for basic image adjustments
* Crop, resize, and format conversion tools
* Image compression
* Metadata removal for safer sharing
* Image overlay and visual editing utilities

Video Tools

* Video playback
* Video trimming and segment editing
* Video conversion and compression
* Video resizing
* Watermarking and export tools
* Metadata removal for video files

Audio Tools

* Audio trimming and editing
* Audio format conversion
* Audio extraction from video files
* Audio merging
* Basic audio enhancement tools
* Frequency and spectrum analysis tools

Guitar & Music Tools

* Guitar-focused practice features
* Chord and audio-analysis tools where supported
* Practice session tracking

Utility Features

* Batch processing for supported media operations
* Export presets
* Modern macOS dashboard interface
* Light, Dark, System, and translucent appearance modes
* Keyboard shortcut support

⸻

Requirements

* macOS 15.0 Sequoia or later
* Apple Silicon or Intel Mac
* 4 GB RAM minimum
* 8 GB RAM recommended
* Additional storage space for media files and exports

Some media-processing and machine-learning features may perform better on Apple Silicon Macs.

⸻

Installation

Download the latest version from the Releases page.

DMG Install

1. Download the latest .dmg file.
2. Open the DMG.
3. Drag RoyalGuitar.app into the Applications folder.
4. Launch RoyalGuitar from Applications.

PKG Install

1. Download the latest .pkg installer.
2. Open the installer.
3. Follow the installation steps.
4. Launch RoyalGuitar from Applications.

⸻

First Launch on macOS

RoyalGuitar is distributed outside the Mac App Store. Depending on the build, macOS may show a security warning the first time the app is opened.

If macOS blocks the app:

1. Open System Settings.
2. Go to Privacy & Security.
3. Scroll down to the security message for RoyalGuitar.
4. Click Open Anyway.
5. Launch RoyalGuitar again.

Advanced users may also remove the quarantine flag manually:

xattr -dr com.apple.quarantine /Applications/RoyalGuitar.app

⸻

Basic Usage

1. Open RoyalGuitar.
2. Use the dashboard or sidebar to choose a tool category.
3. Open a supported image, video, or audio file.
4. Edit or process the file using the available controls.
5. Export the finished file to your chosen location.

Supported tools and export options may vary depending on the media type.

⸻

Privacy

RoyalGuitar is designed to process media locally on your Mac.

Depending on which features are used, macOS may request permission for:

Permission	Purpose
Microphone	Audio input, analysis, or live music tools
Photos	Importing images from the Photos library
Camera	Camera-based features, if enabled
Media Library	Accessing local media, if enabled

RoyalGuitar does not require an account to use local media tools.

Internet access may be required for features that browse, fetch, or reference online content. Users are responsible for ensuring they have the right to access and save any online media they use with the app.

⸻

Known Limitations

* Some advanced features may require additional bundled tools or models.
* AI or machine-learning features may use more memory and may run slower on Intel Macs.
* Online media features may stop working if third-party websites or services change.
* Unsigned or unnotarized builds may require manual approval in macOS Privacy & Security.
* Large video and audio files may require significant storage and processing time.

⸻

Support

Use the GitHub Issues page to report bugs or request features.

When reporting an issue, include:

* macOS version
* Mac model
* RoyalGuitar version
* Steps to reproduce the issue
* Any error messages or crash logs

⸻

Changelog

v1.0.0

* Initial macOS release
* Dashboard-based media workflow
* Image, video, and audio utility tools
* Guitar and music-focused tools
* Export and batch-processing support
* Light, Dark, System, and translucent appearance modes

⸻

License

Proprietary. All rights reserved.

Copyright © 2026 RoyalGuitar. All rights reserved.

This release repository is for distributing RoyalGuitar application builds. Source code is not included unless otherwise stated.
