# 🎬 Netflix-Style Movie Streaming App

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,0,9&height=210&section=header&text=Netflix-Style%20Streaming%20App&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Build%20Your%20Own%20Cinematic%20Streaming%20Platform&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-3.2.0-B1063D?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Stack](https://img.shields.io/badge/React%20%7C%20Node%20%7C%20PostgreSQL-D90429?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-MIT-EF233C?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Status](https://img.shields.io/badge/status-production--ready-EDF2F4?style=for-the-badge&logo=checkmarx&logoColor=black)](https://github.com)

<br/>

### 🍿 A full-stack movie streaming platform with a cinematic, Netflix-inspired experience

*🎥 Video Streaming • 👤 Profiles • ❤️ Watchlists • 🔍 Search • 📊 Continue Watching*

<br/>

<a href="https://share.google/IgCjixiogKvsgWpdb">
  <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-B1063D?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=8B0430" alt="Live Demo" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/IgCjixiogKvsgWpdb">
  <img src="https://img.shields.io/badge/📥_GET_SOURCE-D90429?style=for-the-badge&logo=github&logoColor=white&labelColor=A80320" alt="Get Source" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/IgCjixiogKvsgWpdb">
  <img src="https://img.shields.io/badge/📚_DOCS-EF233C?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=BF1C30" alt="Docs" height="45"/>
</a>

</div>

<img width="1920" height="1080" alt="i-built-a-netflix-style-streaming-request-app-with-claude-6-v0-c3N2bTljejBseXdoMe0sw32UA2Y7pvrNY7EMwE4SgQOylXYMZTv2LKKxd_db" src="https://github.com/user-attachments/assets/0bb2de01-99cf-4750-8de7-d7919c0722a2" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Netflix-Style Movie Streaming App** is a **complete, production-ready streaming platform** that recreates the core Netflix experience — from the cinematic hero banner and horizontal genre rows to user profiles, personalized watchlists, and seamless video playback.

Built as a full-stack application with a modern frontend and a scalable backend, it's ready to power your own streaming service, internal media portal, or portfolio showpiece.

> 💡 **Perfect for:** Indie streaming services, film schools, media companies, and developers building a serious portfolio project.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🎥 **Video Streaming** | 👤 **Multi-Profile** | ❤️ **Watchlist** |
|:---:|:---:|:---:|
| HLS adaptive<br/>streaming | Up to 5 profiles<br/>per account | Save movies for<br/>later viewing |

| 🔍 **Smart Search** | 📊 **Continue Watching** | 🎨 **Cinematic UI** |
|:---:|:---:|:---:|
| Search by title, genre,<br/>actor or year | Pick up exactly<br/>where you left off | Hero banners, rows<br/>& smooth animations |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This App

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🎬 **True Streaming Quality** | HLS with adaptive bitrate — smooth playback on any connection |
| 🎨 **Cinematic Design** | Hero banner, genre rows and hover previews that feel premium |
| 👤 **Real User System** | Profiles, parental controls, and per-profile recommendations |
| 📊 **Recommendations** | Personalized suggestions based on watch history |
| 🔐 **Secure & Scalable** | JWT auth, rate limiting, and CDN-ready media delivery |
| 📱 **Every Device** | Responsive from phone to TV-sized screens |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 App Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🎬  Netflix-Style Streaming  v3.2.0             ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  ┌────────────────────────────────────────────┐  ║
║  │  🎥 FEATURED: "The Last Horizon"           │  ║
║  │  Action • Sci-Fi • 2026 • 4K HDR           │  ║
║  │  [ ▶ Play ]   [ + Watchlist ]              │  ║
║  └────────────────────────────────────────────┘  ║
║                                                  ║
║  🔥 Trending Now                                 ║
║  [🎬][🎬][🎬][🎬][🎬][🎬]                        ║
║                                                  ║
║  🎭 Drama                                        ║
║  [🎬][🎬][🎬][🎬][🎬][🎬]                        ║
║                                                  ║
║  😂 Comedy                                       ║
║  [🎬][🎬][🎬][🎬][🎬][🎬]                        ║
║                                                  ║
║  ▶ Continue Watching: Ep. 4 — 42% complete      ║
║  👤 Profile: Jane   🔔 Notifications: 2          ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🎬 netflix-style-streaming-app/
├── 🎯 frontend/               # React + Vite app
│   ├── pages/
│   ├── components/            # Hero, rows, player
│   └── hooks/
├── ⚙️  backend/                # Node.js + Express API
│   ├── routes/
│   ├── controllers/
│   ├── services/              # Streaming & auth logic
│   └── models/                # Prisma / PostgreSQL
├── 🎥 media/                  # HLS processing & CDN config
├── 👤 profiles/               # Multi-profile logic
├── 🧪 tests/                  # Unit & integration
└── 📖 docs/                   # API reference & deployment
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![HLS.js](https://img.shields.io/badge/HLS.js-1F2937?style=for-the-badge&logo=javascript&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want to add recommendations, subtitles, or payment integration?

<div align="center">

<a href="https://share.google/IgCjixiogKvsgWpdb">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/IgCjixiogKvsgWpdb">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-B1063D?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/IgCjixiogKvsgWpdb">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-EF233C?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 🎬 Made with 🍿 by the Streaming App Team

*If this app inspired your own streaming project — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,0,9&height=120&section=footer" width="100%"/>

</div>
