# Charming Player

[English](README.md) | [简体中文](README_zh.md)

基于 Flutter 构建的跨平台 IPTV 播放器，具备 EPG 集成、多播放器引擎和MPD字幕样式定制功能。

## 功能特性

- **M3U 播放列表支持**：支持从本地文件、在线 URL 或文本内容导入播放列表
- **电子节目指南 (EPG)**：XMLTV EPG 集成，每日自动更新
- **多播放器引擎**：
  - MediaKit
  - VLC
  - Shaka Player
- **解密支持**：实现外置解密器，对 Clearkey 保护的流进行解密。
- **智能频道匹配**：智能 EPG 到频道的映射，支持自定义映射
- **更多的字幕支持**：DVB/PGS，TTML，WebVTT等
