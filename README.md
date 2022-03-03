# Static audio-only FFmpeg builds

This project contains scripts for small static audio-only FFmpeg builds that are used
for packaging [Open Note Block Studio](https://opennbs.org).

This is a fork from [acoustid/ffmpeg-build](https://github.com/acoustid/ffmpeg-build/), which
only supports audio decoding. Unlike that version, this build allows both decoding _and_
encoding audio to a variety of common formats.

Building is done using GitHub Actions. You can find the built binaries on the releases page.

Supported platforms:

- Linux
  - `x86\_64-linux-gnu`
- Windows
  - `x86\_64-w64-mingw32`
- macOS **_(temporarily disabled)_**
  - `x86_64-apple-macos10.9` (macOS Mavericks and newer on Intel CPU)
  - `arm64-apple-macos11` (macOS Big Sur and newer on Apple M1 CPU)
