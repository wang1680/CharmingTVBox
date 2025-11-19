# Charming Player

[English](README.md) | [简体中文](README_zh.md)

A cross-platform IPTV player built with Flutter, featuring EPG integration, multiple player engines, and MPD subtitle styling customization.

## Features

- **M3U Playlist Support**: Import playlists from local files, online URLs, or text content
- **Electronic Program Guide (EPG)**: XMLTV EPG integration with daily automatic updates
- **Multiple Player Engines**:
  - MPV
  - VLC
  - Shaka Player
- **Decryption Support**: External decryptor implementation for decrypting Clearkey-protected streams
- **Smart Channel Matching**: Intelligent EPG-to-channel mapping with custom mapping support
- **Enhanced Subtitle Support**: DVB/PGS, TTML, WebVTT, and more


## FAQ
Q1. Windows users receive prompts stating that files like MSVCP140.dll, VCRUNTIME140_1.dll, or VCRUNTIME140.dll are missing.
- The Visual C++ Redistributable v14 runtime library is missing. Please download it from [https://learn.microsoft.com/zh-cn/cpp/windows/latest-supported-vc-redist](https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist).
- Do not download individual DLL files from third-party websites, as this can pose security risks.
