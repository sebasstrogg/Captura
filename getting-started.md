---
layout: page
title: Getting Started
---

1. [Visual Studio 2017](https://visualstudio.com) or greater is required.
2. Clone the repository: `git clone https://github.com/MathewSachin/Captura.git`.
3. Fetch Submodules: `git submodule init` and `git submodule update`.

## Optional Native Libraries
Download and place in build output directory (x86 or x64 as required).
These may need licensing for commercial use.
x64 libraries are available in [Releases](https://github.com/MathewSachin/Captura/releases).

### Audio Recording/Loopback and Mixing
- [BASS Audio library](http://www.un4seen.com/download.php?bass24) - *bass.dll*.
- [BASSmix](http://www.un4seen.com/download.php?bassmix24) - *bassmix.dll*.

### Video and/or Audio Encoding
- [FFMpeg](https://ffmpeg.zeranoe.com/builds/) - *ffmpeg.exe* (Static build recommended).

>Only _Screna.dll_ is required for Captura to run. All the other libraries add extra features if present.