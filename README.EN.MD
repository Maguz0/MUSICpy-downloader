<div align="center">

```
███╗   ███╗██╗   ██╗███████╗██╗ ██████╗██████╗ ██╗   ██╗
████╗ ████║██║   ██║██╔════╝██║██╔════╝██╔══██╗╚██╗ ██╔╝
██╔████╔██║██║   ██║███████╗██║██║     ██████╔╝ ╚████╔╝ 
██║╚██╔╝██║██║   ██║╚════██║██║██║     ██╔═══╝   ╚██╔╝  
██║ ╚═╝ ██║╚██████╔╝███████║██║╚██████╗██║        ██║   
╚═╝     ╚═╝ ╚═════╝ ╚══════╝╚═╝ ╚═════╝╚═╝        ╚═╝  
```

# 🎵 Musicpy Downloader

**The most complete music downloader. Unlimited. No commitments.**

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Platforms](https://img.shields.io/badge/Plataformas-5-success?style=for-the-badge)](#plataforms-support)
[![Formats](https://img.shields.io/badge/Formatos-7-blueviolet?style=for-the-badge)](#formats-downloader)
[![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)](LICENSE)

</div>

---
[English](README.md) | [Spanish](README.md) | [CHINESE](README.zn.md) | [RUSSIAN](README.ru.md)
## ✨ What is Musicpy Downloader?

Musicpy Downloader is a tool with a Python interface that allows you to download music from the world's most popular platforms—with support for embedded lyrics, multiple formats, and complete visual customization.

> 🎯 One tool. Five platforms. Zero download limits. No registration.

---

## 🚀 Main Features
---

| Feature | Description |
|---|---|
|🎨 **Customizable Colors** | Change the interface colors to your liking |
|📁 **7 Download Formats** | MP3 (320k and 128k), M4A (AAC), FLAC, WAV, OGG, OPUS, AAC |
|🌐 **7 Download Sources** | Multiple backends for maximum availability |
|🎤 **Embedded LRC Lyrics** | Synced and embedded directly in the file |
|🔗 **Download with Link Only** | Paste the link and you're done, no extra configuration |
|📋 **Playlist Support** | Download entire playlists at once |
|🎵 **5 Platforms** | YouTube, Spotify, SoundCloud, Deezer, and Tidal |
|📁 **Change Download Folder 
---

## 🎧 Supported Platforms

<div align="center">

| | Plataforma | Song | Playlists | Álbumes |
|:---:|:---:|:---:|:---:|:---:|
| 🔴 | **YT y YTMUSIC** | ✅ | ✅ | ✅ |
| 🟢 | **Spotify** | ✅ | ✅ | ✅ |
| 🟠 | **SoundCloud** | ✅ | ✅ | ✅ |
| 🩵 | **Deezer** | ✅ | ✅ | ✅ |
| 🔵 | **Tidal** | ✅ | ✅ | ✅ |

</div>

---

## 📦 Download Formats

```
┌───────────────────────────────────────────────┐
│ 🎵 MP3 — Compatible with all devices          │
│ 🎵 FLAC — Lossless quality                    │
│ 🎵 WAV — Uncompressed audio                   │
│ 🎵 M4A — AAC optimized for Apple              │
│ 🎵 OGG — Open source and lightweight          │
│ 🎵 OPUS — Best for streaming                  │
│ 🎵 AAC — High quality, smaller size           │
└────────────────────────────────────────────────┘
```

---

## 🎤 LRC Lyrics

Musicpy Downloader supports **three lyrics modes**:

- ✅ **Embedded in the file** — The lyrics travel along with the song, synchronized to the millisecond
- ✅ **Link only** — Download without lyrics if you don't need them
- ✅ **Separate `.lrc` file** — Save the lyrics as an external file

```
[00:12.00] 🎵 The lyrics appear synchronized...
[00:15.30] 🎵 while you listen to the song.

[00:18.60] 🎵 No external apps. No configuration.

```

---

## ⚙️ Installation
1. Download the .zip file from the release folder
2. Run install.py
3. After passing the 6 requirements
4. Run run.bat

---
#*IMPORTANT* ffmpeg.exe and ffprobe.exe will be included for download in case of errors in install.py

IMPORTANT: The command prompt window that opens should not be deleted; it will close automatically once the program is closed.

---

## 🎨 Color Customization

Musicpy Downloader allows you to modify the **interface colors** directly from the settings menu. Choose from predefined palettes or define your own ANSI colors for a completely personalized experience.

```

┌────────────────────────────┐

│ 🎨 Theme: Night Purple     │

│ 🎨 Theme: Matrix Green     │

│ 🎨 Theme: Fire Red         │

│ 🎨 Theme: Automatic        │

│ 🎨 Custom...               │
└─────────────────────────────┘
```

---

## 🖥️ Basic Usage

```
This downloader has a user-friendly interface, so you don't need to know much about Python. Just copy the link, change the font, format, and style, and press DOWNLOAD. Easy and fast!
```

---

## 📂 Project Structure

```
musicpy-downloader/
│
├── 📄 main.py # Entry Point
├── 📄 downloader.py # Logic Download
├── 📄 lyrics.py # LRC Lyrics Module
├── 📄 platforms/ # Connectors per platform
│ ├── youtube.py
│ ├── spotify.py
│ ├── soundcloud.py
│ ├── deezer.py
│ └── tidal.py
├── 📄 themes.py # Color system
├── 📄 requirements.txt # Dependencies
└── 📄 README.md
```

---

## 📋 Requirements

- Python **3.8 or higher**
- `ffmpeg` installed on the system
- Internet connection

---

## 🤝 Contribute

Do you have ideas? Found a bug? Contributions are welcome.

1. Fork the project
2. Open an issue for bugs or ideas; you will be thanked and mentioned in the program.

---

## 📄 License

Distributed under the MIT license. See the [LICENSE](LICENSE) file for more information.

---

<div align="center">

Made with 🎶 and lots of Python

**[⬆ Back to top](#-musicpy-downloader)**

</div>
