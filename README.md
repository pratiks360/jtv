<p align="center">
  <h1 align="center">📺 JTV Server</h1>
  <p align="center">
    <strong>Self-hosted Express server that turns JioTV live channels into web playback and M3U playlists.</strong>
  </p>
  <p align="center">
    <img src="https://img.shields.io/badge/Node.js-18+-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
    <img src="https://img.shields.io/badge/Express-4-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express">
    <img src="https://img.shields.io/badge/Docker-ready-2496ed?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
    <img src="https://img.shields.io/github/last-commit/pratiks360/jtv?style=for-the-badge&label=Last+Commit" alt="Last Commit">
  </p>
</p>

---

## ✨ What Is This?

**JTV Server** (`jtvserver` v2.6.4) lets you watch JioTV live channels in a browser or any IPTV player, hosted on your own machine or an India-based VPS.

## 🎯 Features

| Feature | Description |
|---|---|
| 🔑 **Login** | Web login page and cookie/token management with refresh |
| 📋 **Playlist** | Generates an M3U playlist of all channels |
| 📡 **Channel proxy** | Parses and proxies HLS (`m3u8`) streams |
| 🌐 **Web UI** | Static player page with dark mode |
| 🐳 **Docker** | Included `Dockerfile` |

## 🚀 Quick Start

**Prerequisites:** Node.js 18+, a JioTV account.

```bash
git clone https://github.com/pratiks360/jtv.git
cd jtv
npm install
npm start          # runs start.sh; use start.bat on Windows
```

Open the printed local URL, sign in and import the generated playlist into your player.

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Server** | Express, http-proxy, node-fetch |
| **Streaming** | m3u8-parser |
| **Storage** | node-json-db |

> ℹ️ `index.js` and `routes/` ship minified/obfuscated, so this README documents behaviour from the file layout and package metadata. For personal use with your own account only.

---

<p align="center">
  <sub>Built with ❤️ for cord-cutters.</sub>
</p>
