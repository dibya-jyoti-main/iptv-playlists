# 📺 IPTV Playlists

<div align="center">

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?logo=github&style=for-the-badge)](https://github.com/dibya-jyoti-main.github.io/iptv-playlists)
[![Total Channels](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub.com%2Fdibya-jyoti-main.github.io%2Fiptv-playlists%2Fstats.json&query=totalChannels&label=Total%20Channels&color=blue&style=for-the-badge)](https://github.com/dibya-jyoti-main.github.io/iptv-playlists/stats.json)
[![DRM Channels](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub.com%2Fdibya-jyoti-main.github.io%2Fiptv-playlists%2Fstats.json&query=drmChannels&label=DRM%20Channels&color=orange&style=for-the-badge)](https://github.com/dibya-jyoti-main.github.io/iptv-playlists/drm/drm.json)
[![Last Update](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub.com%2Fdibya-jyoti-main.github.io%2Fiptv-playlists%2Fupdate.json&query=lastUpdated&label=Last%20Updated&color=purple&style=for-the-badge)](https://github.com/dibya-jyoti-main.github.io/iptv-playlists/update.json)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Author](https://img.shields.io/badge/Author-Dibya%20Jyoti%20Mahanta-blueviolet?style=for-the-badge)](https://dibya-jyoti.vercel.app)

</div>

---

<div align="center">

**Auto-generated IPTV playlists with category, language, country, and DRM support.**  
Updated automatically and ready for all IPTV players.

[📺 All Channels](https://github.com/dibya-jyoti-main.github.io/iptv-playlists/all.m3u) · [📊 Stats](https://github.com/dibya-jyoti-main.github.io/iptv-playlists/stats.json) · [🔌 API](https://github.com/dibya-jyoti-main.github.io/iptv-playlists/channels.json) · [🌐 Portfolio](https://dibya-jyoti.vercel.app)

</div>

---

# 🚀 Quick Start

Paste any playlist URL below into:

- VLC Media Player
- TiviMate
- Kodi
- IPTV Smarters Pro
- OTT Navigator
- Perfect Player
- GSE Smart IPTV

---

## 📺 Master Playlist

```txt
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/all.m3u
```

---

# 📂 Category Playlists

```txt
# News
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/news.m3u

# Sports
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/sports.m3u

# Movies
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/movies.m3u

# Entertainment
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/entertainment.m3u

# Music
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/music.m3u

# Kids
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/kids.m3u

# Documentary
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/documentary.m3u

# Religious
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/religious.m3u

# Education
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/education.m3u

# Anime
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/anime.m3u
```

---

# 🌍 Language Playlists

```txt
# Bangla
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/languages/bangla.m3u

# English
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/languages/english.m3u

# Hindi
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/languages/hindi.m3u

# Tamil
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/languages/tamil.m3u

# Urdu
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/languages/urdu.m3u

# Arabic
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/languages/arabic.m3u
```

---

# 🗺️ Country Playlists

```txt
# Bangladesh
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/countries/bangladesh.m3u

# India
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/countries/india.m3u

# USA
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/countries/usa.m3u

# UK
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/countries/uk.m3u

# Pakistan
https://github.com/dibya-jyoti-main.github.io/iptv-playlists/playlists/countries/pakistan.m3u
```

---

# 🔌 JSON API Reference

| Endpoint | Description |
|----------|-------------|
| `/stats.json` | Channel statistics and metadata |
| `/channels.json` | Full IPTV channel database |
| `/categories.json` | Category list with playlist links |
| `/languages.json` | Language list with playlist links |
| `/countries.json` | Country list with playlist links |
| `/update.json` | Last update information |
| `/drm/drm.json` | DRM channel metadata |
| `/drm/drm_keys.json` | DRM KID and Key pairs |

### Example

```json
{
  "totalChannels": 5230,
  "cleanChannels": 5110,
  "drmChannels": 120,
  "categories": 18,
  "languages": 22,
  "countries": 30,
  "lastUpdated": "2026-05-24T00:00:00.000Z",
  "generatedBy": "Dibya Jyoti Mahanta",
  "repository": "https://github.com/dibya-jyoti-main.github.io/iptv-playlists",
  "portfolio": "https://dibya-jyoti.vercel.app"
}
```

---

# 🗂️ Repository Structure

```txt
iptv-playlists/
├── all.m3u
├── channels.json
├── stats.json
├── categories.json
├── languages.json
├── countries.json
├── update.json
├── README.md
├── setup.txt
│
├── playlists/
│   ├── categories/
│   │   ├── news.m3u
│   │   ├── sports.m3u
│   │   ├── movies.m3u
│   │   └── ...
│   │
│   ├── languages/
│   │   ├── bangla.m3u
│   │   ├── english.m3u
│   │   └── ...
│   │
│   └── countries/
│       ├── bangladesh.m3u
│       ├── india.m3u
│       └── ...
│
└── drm/
    ├── drm.json
    ├── drm_keys.json
    └── drm_channels.json
```

---

# ⏰ Auto Update System

This repository updates automatically every **30 minutes** using GitHub Actions workflows.

Generated playlists include:

- All Channels Playlist
- Category Playlists
- Country Playlists
- Language Playlists
- DRM Metadata
- Statistics APIs
- Auto-generated JSON indexes

---

# ℹ️ Playlist Format

```m3u
#EXTM3U
#
# ==========================================
# IPTV Playlist — Auto Generated
# ==========================================
# Playlist Name : NEWS PLAYLIST
# Total Channels: 342
# Last Updated  : Mon, 24 May 2026 00:00:00 GMT
# Generated By  : Dibya Jyoti Mahanta
# Repository    : https://github.com/dibya-jyoti-main.github.io/iptv-playlists
# Portfolio     : https://dibya-jyoti.vercel.app
# ==========================================
#
#EXTINF:-1 tvg-logo="https://..." group-title="News" tvg-language="English",BBC News
https://stream.example.com/bbc-news/index.m3u8
```

---

# 🔐 DRM Information

DRM-related channels and metadata are stored inside the `/drm/` directory.

This repository is intended for:

- Educational purposes
- Research
- IPTV metadata organization
- Playlist automation experiments

The project does not host or own any protected content.

---

# ⚖️ Disclaimer

- All streams are collected from publicly available sources
- No video files are hosted in this repository
- Stream availability may change anytime
- Users are responsible for their own usage
- All trademarks belong to their respective owners

---

# 👤 Author

<div align="center">

## Dibya Jyoti Mahanta  
### দিব্য জ্যোতি মহন্ত

🌐 Portfolio: https://dibya-jyoti.vercel.app  
🐙 GitHub: https://github.com/dibya-jyoti-main

**Automated • Fast • Modern • Always Updated**

</div>

---

# 📄 License

MIT License © Dibya Jyoti Mahanta
