<div align="center">

# `DEMON895 // FIELD TERMINAL`

**PORTABLE SYSTEMS · EDGE COMPUTING · GAME DEVELOPMENT**

[![GitHub](https://img.shields.io/badge/GitHub-DEMON895-0b1220?style=for-the-badge&logo=github&logoColor=00f5d4)](https://github.com/DEMON895)
[![Main Project](https://img.shields.io/badge/PRIMARY_BUILD-CYBERDECK-0b1220?style=for-the-badge&logo=raspberrypi&logoColor=00f5d4)](#-primary-project-cyberdeck)
[![Status](https://img.shields.io/badge/STATUS-BUILDING-0b1220?style=for-the-badge&logo=gnubash&logoColor=00f5d4)](#-current-build-queue)

</div>

```text
┌──────────────────────────────────────────────────────────────┐
│ DEMON895 / PORTABLE COMPUTING LAB                            │
├──────────────────────────────────────────────────────────────┤
│ OPERATOR    : Abhinav                                        │
│ MAIN BUILD  : Raspberry Pi 3B+ Cyberdeck                     │
│ EDGE NODE   : ESP32-S3 WROOM-1 N16R8                         │
│ INTERESTS   : Linux / Embedded / AI / Networking / Games     │
│ MODE        : LEARN -> BUILD -> DEBUG -> IMPROVE             │
└──────────────────────────────────────────────────────────────┘
```

## `01 // ABOUT`

Engineering student interested in building practical systems where **hardware, software, Linux, and edge computing** meet.

My main project is a portable **Raspberry Pi cyberdeck** with a multi-display interface, an ESP32-S3 companion node, offline reference material, and networking tools. Alongside it, I'm learning software development, AI/ML, and game development while strengthening my programming fundamentals.

- **Main focus:** Cyberdeck engineering, Linux, embedded systems, and networking
- **Learning:** Python, C/C++, Java, web development, AI/ML, and game development
- **Goal:** Build useful projects, understand how they work, and document the process

> Learn the layers. Build the system. Improve the design.

---

## `02 // PRIMARY PROJECT: CYBERDECK`

A compact, portable Linux workstation for offline knowledge, experimentation, networking labs, and hardware telemetry.

### SYSTEM ARCHITECTURE

```text
                  ┌───────────────────────┐
                  │    5-INCH DISPLAY     │
                  │       MAIN UI         │
                  └───────────┬───────────┘
                              │
┌─────────────────────────────▼─────────────────────────────┐
│                    RASPBERRY PI 3B+                       │
│  Linux / XFCE / Kiwix / Python / Scapy / Main Controller  │
└─────────────────────────────┬─────────────────────────────┘
                              │ USB SERIAL
┌─────────────────────────────▼─────────────────────────────┐
│                       ESP32-S3                            │
│          Connectivity experiments / Edge telemetry       │
└─────────────────────────────┬─────────────────────────────┘
                              │
                  ┌───────────┴───────────┐
                  │                       │
           ┌──────▼──────┐         ┌──────▼──────┐
           │ OLED 01     │         │ OLED 02     │
           │ Companion / │         │ Link status │
           │ System state│         │ / Telemetry │
           └─────────────┘         └─────────────┘
```

### HARDWARE

| Component | Purpose |
|---|---|
| Raspberry Pi 3B+ · 1 GB RAM | Main computer and controller |
| 64 GB storage | Operating system, tools, scripts, offline resources |
| ESP32-S3 WROOM-1 N16R8 | Companion node for connectivity and edge experiments |
| 5-inch display | Main interface |
| Two 0.96-inch OLED displays | Compact status and telemetry |
| 10,000 mAh power bank | Portable power |

### SOFTWARE & TOOLS

<div align="center">

![Linux](https://img.shields.io/badge/Linux-0b1220?style=flat-square&logo=linux&logoColor=00f5d4)
![Python](https://img.shields.io/badge/Python-0b1220?style=flat-square&logo=python&logoColor=00f5d4)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-0b1220?style=flat-square&logo=raspberrypi&logoColor=00f5d4)
![ESP32-S3](https://img.shields.io/badge/ESP32--S3-0b1220?style=flat-square&logo=espressif&logoColor=00f5d4)
![Bash](https://img.shields.io/badge/Bash-0b1220?style=flat-square&logo=gnubash&logoColor=00f5d4)

</div>

- **Kiwix:** offline knowledge library
- **Scapy:** packet crafting and analysis in authorized lab environments
- **Linux / XFCE:** lightweight desktop and system experimentation
- **Python and shell scripts:** automation, diagnostics, and integration
- **I²C, SPI, USB serial:** display and device communication

### CURRENT BUILD QUEUE

- [ ] Improve desktop responsiveness on Pi 3B+ hardware
- [ ] Stabilize Raspberry Pi ↔ ESP32-S3 communication
- [ ] Build OLED status and telemetry screens
- [ ] Integrate system metrics into the main dashboard
- [ ] Document setup, wiring, scripts, and troubleshooting

---

## `03 // OTHER PROJECT TRACKS`

<table>
<tr>
<td width="50%" valign="top">

### 🎮 GAME DEVELOPMENT

Learning to create games from the ground up.

- Programming and gameplay logic
- Game engine fundamentals
- Input, physics, UI, and level design
- Goal: finish small playable projects

</td>
<td width="50%" valign="top">

### 🤖 AI / MACHINE LEARNING

Exploring models, data, and practical experiments.

- Python and data handling
- ML fundamentals and evaluation
- Small reproducible experiments
- Interest in edge-friendly workloads

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌐 WEB & APPS

Turning ideas into useful software.

- HTML, CSS, and JavaScript
- Private chat concept
- Lost-and-found app concept
- Productivity and time-management tools

</td>
<td width="50%" valign="top">

### 🧠 SDE FOUNDATIONS

Preparing for long-term software engineering growth.

- Data structures and algorithms
- Object-oriented programming
- Databases and software design
- Git, debugging, and documentation

</td>
</tr>
</table>

---

## `04 // TOOLCHAIN`

<div align="center">

![Python](https://img.shields.io/badge/Python-learning-17252d?style=for-the-badge&logo=python&logoColor=00f5d4)
![C](https://img.shields.io/badge/C-learning-17252d?style=for-the-badge&logo=c&logoColor=00f5d4)
![C++](https://img.shields.io/badge/C%2B%2B-learning-17252d?style=for-the-badge&logo=cplusplus&logoColor=00f5d4)
![Java](https://img.shields.io/badge/Java-learning-17252d?style=for-the-badge&logo=openjdk&logoColor=00f5d4)
![JavaScript](https://img.shields.io/badge/JavaScript-exploring-17252d?style=for-the-badge&logo=javascript&logoColor=00f5d4)
![Linux](https://img.shields.io/badge/Linux-exploring-17252d?style=for-the-badge&logo=linux&logoColor=00f5d4)
![Git](https://img.shields.io/badge/Git-version_control-17252d?style=for-the-badge&logo=git&logoColor=00f5d4)

</div>

*These are technologies I use, explore, or am actively learning, not a claim of equal proficiency in all of them.*

## `05 // LEARNING QUEUE`

```text
[ ACTIVE ]  Cyberdeck integration and Linux reliability
[ ACTIVE ]  Programming fundamentals
[ NEXT   ]  Finish a small playable game
[ NEXT   ]  Build and publish a complete web app
[ LONG   ]  Strengthen DSA and SDE placement preparation
[ ALWAYS ]  Document, refactor, and ship
```

## `06 // GITHUB TELEMETRY`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=DEMON895&show_icons=true&hide_border=true&bg_color=0b1220&title_color=00f5d4&text_color=d7e5ee&icon_color=00f5d4" alt="GitHub stats for DEMON895" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DEMON895&layout=compact&hide_border=true&bg_color=0b1220&title_color=00f5d4&text_color=d7e5ee" alt="Top languages for DEMON895" />

</div>

*These cards are provided by a third-party service and may occasionally be unavailable.*

## `07 // CONNECT`

<div align="center">

[![GitHub Profile](https://img.shields.io/badge/OPEN_PROFILE-DEMON895-0b1220?style=for-the-badge&logo=github&logoColor=00f5d4)](https://github.com/DEMON895)

**Build things. Understand the layers. Keep improving.**

`END OF TRANSMISSION // STATUS: LEARNING + BUILDING`

</div>
