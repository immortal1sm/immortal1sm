# Hi there, I'm Allan Solomon 👋

<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1500&color=7C9CF5&center=true&width=600&lines=Systems+developer+%26+Linux+sysadmin;Embedded+IoT+%26+homelab+enthusiast;Rust+%E2%9A%99%EF%B8%8F+PHP+%2B+JavaScript+%2B+Python)

[![Profile Views](https://komarev.com/ghpvc/?username=immortal1sm&label=Profile%20Views&color=7C9CF5&style=flat-square)](https://github.com/immortal1sm)
[![GitHub Followers](https://img.shields.io/github/followers/immortal1sm?label=Followers&style=flat-square&color=7C9CF5)](https://github.com/immortal1sm)
[![Last Commit](https://img.shields.io/github/last-commit/immortal1sm/immortal1sm?style=flat-square&color=7C9CF5)](https://github.com/immortal1sm/immortal1sm/commits/main)
[![Commits](https://img.shields.io/github/commit-activity/m/immortal1sm/immortal1sm?label=Commits&style=flat-square&color=7C9CF5)](https://github.com/immortal1sm/immortal1sm/commits/main)

</div>

---

## About Me 🧑‍💻

I build things end-to-end — from **Rust daemons** and **embedded firmware** that talks to hardware over USB and I2C, to **full-stack web apps** in PHP and JavaScript, down to the **self-hosted infrastructure** they run on (Proxmox, Docker, Linux servers).

- 🖥️ **Daily driver** — Arch-based Linux + KDE
- 🔧 **Building** — real-time PC monitors, water level monitoring, OLED display daemons
- 🌾 **Domain** — IoT monitoring for rice fields, agricultural dashboards
- ⚡ **Fun fact** — my keyboard's OLED panel runs a Rust daemon I wrote

---

## 🏆 Featured Projects

<table>
<tr><td width="50%" valign="top">

### <a href="https://github.com/immortal1sm/ss-oled">ss-oled</a> 🖥️

**Linux OLED daemon for SteelSeries Apex Pro keyboards** — on Linux, without SteelSeries GG.

Eight rotating providers on a 128×40 panel: MPRIS2 now-playing (event-driven, jumps to front on any track change), sysinfo bars, weather + 5-day forecast, animated icons, synchronized lyrics, clock, and your own images with Floyd–Steinberg dithering so multi-tone art survives the 1-bit screen. Per-provider dwell times, event-driven switching, GUI, and engine split into separate crates.

`Rust` `USB HID` `D-Bus/MPRIS` `systemd`

[![ss-oled](https://img.shields.io/github/stars/immortal1sm/ss-oled?style=for-the-badge&logo=github&color=7C9CF5)](https://github.com/immortal1sm/ss-oled)

</td><td width="50%" valign="top">

### <a href="https://github.com/immortal1sm/arduino-pc-monitor">Arduino PC Monitor</a> 📊

**Real-time PC system monitor on a hardware OLED.**

An Arduino drives a 128×64 SH1106 over USB serial while a Python host reads CPU/GPU usage, temps, power draw, and RAM/VRAM. Swappable "faces" — the system monitor is stable, an MPRIS media face works, and a merged stats + now-playing face is in progress. Robust serial protocol with auto-recovery.

`Arduino` `C++` `Python` `SH1106` `I2C`

[![stars](https://img.shields.io/github/stars/immortal1sm/arduino-pc-monitor?style=for-the-badge&logo=github&color=7C9CF5)](https://github.com/immortal1sm/arduino-pc-monitor)

</td></tr>
<tr><td width="50%" valign="top">

### <a href="https://github.com/immortal1sm/water-monitoring-system">Water Level Monitoring System</a> 💧

**IoT water level monitor for rice fields — ESP32 mesh.**

Waterproof JSN-SR04T ultrasonic sensors on ESP32 nodes measure every 30s and report over **ESP-NOW** to a gateway node, which batches readings and uploads them to the dashboard over **WiFi via a REST GET** request. The PHP/MySQL dashboard does live visualization, history, and threshold-based alerts, with over-the-air firmware updates on the nodes.

`ESP32` `ESP-NOW` `JSN-SR04T` `WiFi` `PHP` `MySQL`

[![stars](https://img.shields.io/github/stars/immortal1sm/water-monitoring-system?style=for-the-badge&logo=github&color=7C9CF5)](https://github.com/immortal1sm/water-monitoring-system)

</td><td width="50%" valign="top">

### <a href="https://github.com/immortal1sm/Game-Server-Bot">Game Server Bot</a> 🎮

**Discord slash commands for self-hosted game servers.**

Trusted users start, stop, restart, and check status on Docker-hosted game servers. Deliberately locked down: no raw shell, single Discord channel, confirmation on destructive actions, and only predefined scripts ever execute.

`Discord` `Docker` `Node.js` `Bash`

[![stars](https://img.shields.io/github/stars/immortal1sm/Game-Server-Bot?style=for-the-badge&logo=github&color=7C9CF5)](https://github.com/immortal1sm/Game-Server-Bot)

</td></tr>
</table>

### Also here

| Repo | What it is |
| :-- | :-- |
| <a href="https://github.com/immortal1sm/Discord-Docker-Serverbot">Discord-Docker-Serverbot</a> | Companion bot for Docker game servers — system telemetry streamed to Discord channels, health checks, crash recovery |
| <a href="https://github.com/immortal1sm/kflix-laravel">kflix-laravel</a> | A streaming discovery app on Laravel 11 + MySQL, rebuilt from raw PHP with a full UI redesign and Dockerized deployment |
| <a href="https://github.com/immortal1sm/blocklist">blocklist</a> | A small personal blocklist file |

---

## 🔧 Tech Stack

<table>
<tr><td valign="top" width="50%">

### Languages

![Rust](https://img.shields.io/badge/-Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/-Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Frontend & Mobile

![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![React Native](https://img.shields.io/badge/-React%20Native-20232A?style=for-the-badge&logo=react-native&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend & Frameworks

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

</td><td valign="top" width="50%">

### DevOps & Infrastructure

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/-Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Arch Linux](https://img.shields.io/badge/-Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Databases

![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MariaDB](https://img.shields.io/badge/-MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=for-the-badge)

### Embedded & IoT

![Arduino](https://img.shields.io/badge/-Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Embedded C/C%2B%2B](https://img.shields.io/badge/-Embedded%20C%2FC%2B%2B-5C2D91?style=for-the-badge&logo=c&logoColor=white)

### AI & Automation

![Ollama](https://img.shields.io/badge/-Ollama-000000?style=for-the-badge)
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![RAG](https://img.shields.io/badge/-RAG-1C3C3C?style=for-the-badge)

</td></tr>
</table>

---

## 🧰 What I Work With

| Area | Details |
| :-- | :-- |
| **Systems Programming** | Rust daemons — USB HID, D-Bus/MPRIS, IPC sockets; C/C++ firmware |
| **Embedded & IoT** | ESP32 (WiFi, ESP-NOW, OTA), Arduino (serial/I2C), SH1106 OLEDs, JSN-SR04T ultrasonic sensors |
| **Linux & Sysadmin** | Arch/Debian/Ubuntu Server, systemd, SSH, user & system administration, cron |
| **DevOps & Self-Hosting** | Proxmox VE (LXC/VMs), Docker, Nginx reverse proxy, SSL/TLS, Cloudflare Tunnel, AdGuard Home DNS, Terraform, Bash scripting |
| **Full-Stack Web** | React, Node.js/Express, PHP/Laravel, Firebase, REST APIs, MySQL/MongoDB |
| **AI & Automation** | Local LLMs via Ollama, RAG pipelines, vector search with Qdrant, n8n workflows |

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=immortal1sm&show_icons=true&theme=dark&hide_border=true&count_private=true" height="165" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=immortal1sm&layout=compact&theme=dark&hide_border=true" height="165" alt="Top languages"/>
</div>

<img src="https://streak-stats.demolab.com/?user=immortal1sm&theme=dark&hide_border=false&border_radius=10" width="500" alt="Streak stats"/>

---

## 🌐 Connect

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/immortal1sm)
[![X / Twitter](https://img.shields.io/badge/X/𝕏-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/im_immortalism)

---

> ⚡ Always learning. Always building.
