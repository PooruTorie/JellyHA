# JellyHA — Jellyfin for Home Assistant

**v1.4.0** · [Full Changelog](https://github.com/zupancicmarko/JellyHA/blob/main/CHANGELOG.md) · [Documentation](https://github.com/zupancicmarko/JellyHA/tree/main/docs)

![JellyHA Library Card](https://github.com/zupancicmarko/JellyHA/raw/main/docs/JellyHA-Library-Grid.png)

JellyHA integrates your Jellyfin media server directly into Home Assistant with a full-featured Lovelace card, rich media player entities, and powerful automation sensors.

---

### 🆕 What's new in v1.4.0

- 📡 **Live TV Channels & Direct Tuning** — Browse Live TV channels visually in Media Browser and tune by channel number or name via `jellyha.play_live_tv_channel` (compatible with Voice Assist) (#11, #38)
- 🎵 **Dedicated Music Search & Hi-Res Audio** — 1-step playback on any room speaker via `jellyha.play_music`, fast indexed search via `jellyha.music_search`, and bit-perfect FLAC / ALAC / Hi-Res audio inspection (#26)
- 📁 **Direct Media File Paths** — Expose `path` and `filepath` in actions and card click scripts for external media players like Kodi, VLC, or MPV (#37)
- 📊 **Watched Percentage & Per-Library Storage Sensors** — Standardized percentage sensors for Long-Term Statistics and per-library GB storage size meters (#35, #36)
- 🏷️ **Client Nicknames & Exact Device Tracking** — Custom dashboard names in Options Flow and exact device session matching to prevent webOS/browser session collisions (#39)
- 🎛️ **Card Editor Fix for Grid & List Layouts** — Resolved editor fields rendering smoothly across Carousel, Grid, and List layouts

---

### ✨ Features

- 🎬 **Library Card** — Browse movies & shows in Carousel, Grid, or List view with Next Up support
- ⏯️ **Full Playback Control** — Play, pause, stop, seek, shuffle, repeat, volume via `media_player` entities
- 📡 **Chromecast** — Cast with subtitle burn-in and language selection
- 🔍 **Search Service** — Filter by genre, studio, person, and more
- 📊 **Rich Sensors** — Library stats, storage, transcoding streams, connected clients, latest media
- 🤖 **Automation-Ready** — Device triggers, segment events, chapter events, HDR detection
- 🌐 **Multi-Instance** — Multiple Jellyfin servers in one HA instance
- 🃏 **Community Card Compatible** — Works with Mini Media Player, Mushroom, Universal Media Player

---

### 📦 Installation

1. Install via HACS.
2. **Restart Home Assistant**.
3. Go to **Settings → Devices & Services → Add Integration → JellyHA**.
4. Add the Lovelace resource:
   - **URL**: `/jellyha/jellyha-cards.js`
   - **Type**: JavaScript Module

[📖 Full documentation](https://github.com/zupancicmarko/JellyHA/tree/main/docs) · [💬 Community](https://github.com/zupancicmarko/JellyHA/discussions) · [🐛 Issues](https://github.com/zupancicmarko/JellyHA/issues)
