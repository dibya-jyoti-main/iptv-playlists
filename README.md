# 📺 IPTV Playlists

<div align="center">

# ⚡ Fully Automated IPTV Playlist Collection

Auto-generated IPTV playlists with:

✅ Category Playlists  
✅ Language Playlists  
✅ Country Playlists  
✅ JSON APIs  
✅ DRM Metadata  
✅ GitHub Actions Automation  
✅ GitHub Pages Hosting

Updated automatically every **30 minutes**.

<br>

[![Total Channels](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdibya-jyoti-main.github.io%2Fiptv-playlists%2Fstats.json&query=totalChannels&label=Total%20Channels&color=blue&style=for-the-badge)](https://dibya-jyoti-main.github.io/iptv-playlists/stats.json)

[![DRM Channels](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdibya-jyoti-main.github.io%2Fiptv-playlists%2Fstats.json&query=drmChannels&label=DRM%20Channels&color=orange&style=for-the-badge)](https://dibya-jyoti-main.github.io/iptv-playlists/drm/drm.json)

[![Last Update](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdibya-jyoti-main.github.io%2Fiptv-playlists%2Fupdate.json&query=lastUpdated&label=Last%20Updated&color=purple&style=for-the-badge)](https://dibya-jyoti-main.github.io/iptv-playlists/update.json)

[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

</div>

---

# 🚀 Quick Start

Paste any playlist URL into your IPTV player:

- VLC Media Player
- IPTV Smarters Pro
- TiviMate
- Kodi
- OTT Navigator
- Perfect Player
- GSE Smart IPTV

---

# 📺 Main Playlist

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/all.m3u
```

---

# 📂 Category Playlists

## 📰 News

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/news.m3u
```

---

## 👶 Kids

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/kids.m3u
```

---

## 🎵 Music

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/music.m3u
```

---

## 🎬 Movie

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/movie.m3u
```

---

## 🍿 Movies

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/movies.m3u
```

---

## 🎭 Entertainment

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/entertainment.m3u
```

---

## 📺 Mix Entertainment

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/mix-entertainment.m3u
```

---

## 👗 Fashion

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/fashion.m3u
```

---

## 🌍 Other

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/other.m3u
```

---

## ⚽ Sports

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/sports.m3u
```

---

## 📚 Infotainment

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/infotainment.m3u
```

---

## 🛐 Religious

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/religious.m3u
```

---

## 📡 Local

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/local.m3u
```

---

## 📻 PLC

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/plc.m3u
```

---

## 🙏 Devotional

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/devotional.m3u
```

---

## 🎞️ Classic

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/categories/classic.m3u
```

---

# 🌍 Language Playlists

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/languages/
```

Examples:

```txt
bangla.m3u
english.m3u
hindi.m3u
urdu.m3u
tamil.m3u
arabic.m3u
```

---

# 🗺️ Country Playlists

```txt
https://dibya-jyoti-main.github.io/iptv-playlists/playlists/countries/
```

Examples:

```txt
bangladesh.m3u
india.m3u
usa.m3u
uk.m3u
pakistan.m3u
```

---

# 🔌 JSON API

| File | Description |
|------|-------------|
| `channels.json` | Full IPTV channel database |
| `stats.json` | Statistics and counts |
| `categories.json` | Category metadata |
| `languages.json` | Language metadata |
| `countries.json` | Country metadata |
| `update.json` | Last update information |
| `drm/drm.json` | DRM channels |
| `drm/drm_keys.json` | DRM KID and Keys |

---

# 📊 Example stats.json

```json
{
  "totalChannels": 5230,
  "cleanChannels": 5110,
  "drmChannels": 120,
  "categories": 16,
  "languages": 22,
  "countries": 30,
  "lastUpdated": "2026-05-24T00:00:00.000Z",
  "generatedBy": "Dibya Jyoti Mahanta"
}
```

---

# 🗂️ Repository Structure

```txt
iptv-playlists/
│
├── all.m3u
├── channels.json
├── stats.json
├── categories.json
├── languages.json
├── countries.json
├── update.json
├── README.md
│
├── playlists/
│   │
│   ├── categories/
│   │   ├── news.m3u
│   │   ├── kids.m3u
│   │   ├── music.m3u
│   │   ├── movie.m3u
│   │   ├── movies.m3u
│   │   ├── entertainment.m3u
│   │   ├── mix-entertainment.m3u
│   │   ├── fashion.m3u
│   │   ├── other.m3u
│   │   ├── sports.m3u
│   │   ├── infotainment.m3u
│   │   ├── religious.m3u
│   │   ├── local.m3u
│   │   ├── plc.m3u
│   │   ├── devotional.m3u
│   │   └── classic.m3u
│   │
│   ├── languages/
│   │   ├── bangla.m3u
│   │   ├── english.m3u
│   │   ├── hindi.m3u
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

# ⚙️ Automation System

This repository is powered by GitHub Actions automation.

Features:

- Automatic IPTV source fetching
- Auto category playlist generation
- Auto language playlist generation
- Auto country playlist generation
- JSON metadata generation
- DRM extraction
- Statistics generation
- Automatic GitHub Pages deployment

Update interval:

```txt
Every 30 Minutes
```

---

# ℹ️ Playlist Format

```m3u
#EXTM3U
#
# ==========================================
# IPTV Playlist — Auto Generated
# ==========================================
# Playlist Name : SPORTS PLAYLIST
# Total Channels: 530
# Last Updated  : Sun, 24 May 2026 00:00:00 GMT
# Generated By  : Dibya Jyoti Mahanta
# ==========================================
#
#EXTINF:-1 tvg-logo="https://..." group-title="Sports",Star Sports
https://example.com/live.m3u8
```

---

# 🔐 DRM Notice

DRM-related channels and metadata are stored inside the `/drm/` directory.

This repository is intended for:

- Educational purposes
- IPTV research
- Metadata indexing
- Playlist automation testing

No copyrighted video content is hosted in this repository.

---

# ⚖️ Disclaimer

- Streams are collected automatically from public IPTV sources
- Availability may change anytime
- No media files are hosted
- Users are responsible for their own usage
- All trademarks belong to their respective owners

---

# 👤 Author

<div align="center">

# Dibya Jyoti Mahanta
### দিব্য জ্যোতি মহন্ত

⚡ Automated • Modern • Fast • Always Updated

</div>

---

# 📄 License

MIT License © Dibya Jyoti Mahanta
