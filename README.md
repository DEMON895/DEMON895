::: {align="center"}
`<img src="https://capsule-render.vercel.app/api?type=venom&height=220&color=0:07111f,45:102b35,100:00f5d4&text=DEMON895&fontColor=eaffff&fontSize=58&fontAlignY=42&desc=PORTABLE%20SYSTEMS%20%2F%20EDGE%20COMPUTING%20%2F%20GAME%20DEV&descAlignY=62&descSize=14&animation=fadeIn" width="100%" alt="Animated cyberdeck-themed header"/>`{=html}

`<a href="https://github.com/DEMON895">`{=html}
`<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2800&pause=850&color=00F5D4&center=true&vCenter=true&width=700&lines=BOOTING+DEMON895+SYSTEMS...;RASPBERRY+PI+3B%2B+%7C+ESP32-S3;BUILDING+A+PORTABLE+CYBERDECK;LEARNING+BY+BUILDING.+DEBUGGING+BY+NATURE." alt="Animated typing text"/>`{=html}
`</a>`{=html}

`<br/>`{=html}

[![GitHub](https://img.shields.io/badge/GitHub-DEMON895-101820?style=for-the-badge&logo=github&logoColor=00F5D4)](https://github.com/DEMON895)
[![Main
Build](https://img.shields.io/badge/MAIN%20BUILD-CYBERDECK-101820?style=for-the-badge&logo=raspberrypi&logoColor=00F5D4)](#-primary-build--the-cyberdeck)
[![Status](https://img.shields.io/badge/STATUS-UNDER%20CONSTRUCTION-101820?style=for-the-badge&logo=git&logoColor=00F5D4)](#-current-mission)
:::

``` text
┌──────────────────────────────────────────────────────────────────────┐
│  DEMON895 // FIELD TERMINAL                                         │
├──────────────────────────────────────────────────────────────────────┤
│  OPERATOR    : Abhinav                                               │
│  PRIMARY LAB : Raspberry Pi 3B+ + ESP32-S3                           │
│  INTERESTS   : Embedded Systems / Linux / AI / Networking / Games    │
│  DIRECTIVE   : Build useful things. Understand every layer.          │
│  STATUS      : [ ONLINE ]                                            │
└──────────────────────────────────────────────────────────────────────┘
```

## `01 / SYSTEM PROFILE`

Engineering student exploring the overlap between **hardware, software,
Linux, edge computing, and game development**.

My main build is a portable **Raspberry Pi cyberdeck**: a compact
field-computing setup with a small display stack, an ESP32-S3 companion
node, offline reference material, and networking tools. Around that
project, I'm learning the programming and engineering fundamentals
needed to build better systems from scratch.

-   `FOCUS` --- cyberdeck engineering, embedded systems, Linux, and
    networking
-   `LEARNING` --- Python, C/C++, Java, web fundamentals, AI/ML, and
    game development
-   `APPROACH` --- prototype → test → debug → document → improve

> Not claiming mastery. Building the skill set one working system at a
> time.

------------------------------------------------------------------------

## `02 / PRIMARY BUILD — THE CYBERDECK`

::: {align="center"}
`<img src="https://img.shields.io/badge/CORE-Raspberry%20Pi%203B%2B-13212b?style=flat-square&logo=raspberrypi&logoColor=00f5d4"/>`{=html}
`<img src="https://img.shields.io/badge/EDGE-ESP32--S3-13212b?style=flat-square&logo=espressif&logoColor=00f5d4"/>`{=html}
`<img src="https://img.shields.io/badge/OS-Linux-13212b?style=flat-square&logo=linux&logoColor=00f5d4"/>`{=html}
`<img src="https://img.shields.io/badge/TOOLS-Kiwix%20%2F%20Scapy-13212b?style=flat-square&logo=gnubash&logoColor=00f5d4"/>`{=html}
:::

### `BUILD CONCEPT`

A portable, low-power computer designed for offline knowledge, Linux
experimentation, networking labs, hardware telemetry, and a custom
multi-display interface.

``` text
              ┌───────────────────────────┐
              │       5" MAIN DISPLAY     │
              │       CYBERDECK UI        │
              └─────────────┬─────────────┘
                            │
┌───────────────────────────▼───────────────────────────┐
│                  RASPBERRY PI 3B+                     │
│     Linux • Kiwix • Python • Scapy • Main Control     │
└───────────────────────────┬───────────────────────────┘
                            │ USB / SERIAL
┌───────────────────────────▼───────────────────────────┐
│                      ESP32-S3                         │
│       Connectivity experiments • Edge telemetry      │
└───────────────────────────┬───────────────────────────┘
                            │
             ┌──────────────┴──────────────┐
             │                             │
       OLED STATUS 01                OLED STATUS 02
       Companion / State             Link / Telemetry
```

### `HARDWARE & SUBSYSTEMS`

  -----------------------------------------------------------------------
  Subsystem                           Role
  ----------------------------------- -----------------------------------
  Raspberry Pi 3B+ · 1 GB RAM         Main Linux computer and controller

  64 GB storage                       OS, tools, scripts, and offline
                                      resources

  ESP32-S3 WROOM-1 N16R8              Companion node for connectivity and
                                      edge experiments

  5-inch display                      Main interface

  Two 0.96-inch OLEDs                 Compact status and telemetry
                                      displays

  Portable 10,000 mAh power bank      Mobile power source
  -----------------------------------------------------------------------

### `SOFTWARE TOOLKIT`

-   **Kiwix** --- offline knowledge library
-   **Scapy** --- packet crafting and network analysis in authorized
    labs
-   **Linux / XFCE** --- lightweight desktop and system experimentation
-   **Python & shell scripts** --- automation, diagnostics, and
    integration
-   **I²C / SPI / USB serial** --- display and device communication
    experiments

### `CURRENT MISSION`

-   [ ] Keep the lightweight Linux desktop responsive on Pi 3B+
    hardware.
-   [ ] Stabilize Pi ↔ ESP32-S3 USB communication.
-   [ ] Build a useful OLED telemetry interface.
-   [ ] Connect display status, connectivity, and system metrics into
    one dashboard.
-   [ ] Document setup, wiring, scripts, and troubleshooting as the
    build evolves.

**Design rule:** every screen should have a purpose. Main display for
control, OLEDs for glanceable status, ESP32-S3 for companion-side
experiments.

------------------------------------------------------------------------

## `03 / OTHER ACTIVE TRACKS`

```{=html}
<table>
```
```{=html}
<tr>
```
```{=html}
<td width="50%" valign="top">
```
### 🎮 GAME DEVELOPMENT

Learning to make games from the ground up.

-   Programming and gameplay logic
-   Engine fundamentals and scenes
-   Input, physics, UI, and iteration
-   Goal: finish small playable projects

```{=html}
</td>
```
```{=html}
<td width="50%" valign="top">
```
### 🤖 AI / MACHINE LEARNING

Exploring models, data, and practical deployment.

-   Python and data handling
-   ML fundamentals
-   Small experiments and evaluation
-   Interest in edge-friendly workloads

```{=html}
</td>
```
```{=html}
</tr>
```
```{=html}
<tr>
```
```{=html}
<td width="50%" valign="top">
```
### 🌐 WEB & APPLICATIONS

Turning useful ideas into usable software.

-   HTML, CSS, and JavaScript fundamentals
-   Private chat concept
-   Lost-and-found app concept
-   Productivity and time-management tools

```{=html}
</td>
```
```{=html}
<td width="50%" valign="top">
```
### 🧠 SDE FOUNDATIONS

Building the base for long-term software engineering.

-   Data structures and algorithms
-   Object-oriented programming
-   Databases and software design
-   Git, debugging, and project documentation

```{=html}
</td>
```
```{=html}
</tr>
```
```{=html}
</table>
```

------------------------------------------------------------------------

## `04 / TOOLCHAIN`

::: {align="center"}
![Python](https://img.shields.io/badge/Python-1b2838?style=for-the-badge&logo=python&logoColor=00F5D4)
![C](https://img.shields.io/badge/C-1b2838?style=for-the-badge&logo=c&logoColor=00F5D4)
![C++](https://img.shields.io/badge/C%2B%2B-1b2838?style=for-the-badge&logo=cplusplus&logoColor=00F5D4)
![Java](https://img.shields.io/badge/Java-1b2838?style=for-the-badge&logo=openjdk&logoColor=00F5D4)
![JavaScript](https://img.shields.io/badge/JavaScript-1b2838?style=for-the-badge&logo=javascript&logoColor=00F5D4)

![Linux](https://img.shields.io/badge/Linux-1b2838?style=for-the-badge&logo=linux&logoColor=00F5D4)
![Raspberry
Pi](https://img.shields.io/badge/Raspberry%20Pi-1b2838?style=for-the-badge&logo=raspberrypi&logoColor=00F5D4)
![Espressif](https://img.shields.io/badge/ESP32--S3-1b2838?style=for-the-badge&logo=espressif&logoColor=00F5D4)
![Git](https://img.shields.io/badge/Git-1b2838?style=for-the-badge&logo=git&logoColor=00F5D4)
![Bash](https://img.shields.io/badge/Bash-1b2838?style=for-the-badge&logo=gnubash&logoColor=00F5D4)
:::

*These represent technologies I use, explore, or am actively learning,
not a claim of equal proficiency in each.*

------------------------------------------------------------------------

## `05 / LEARNING QUEUE`

``` text
[ IN PROGRESS ]  Cyberdeck integration & Linux reliability
[ IN PROGRESS ]  Programming fundamentals
[ NEXT UP      ]  Complete a small playable game
[ NEXT UP      ]  Build and publish a complete web app
[ LONG TERM    ]  Strong DSA + SDE placement preparation
[ ALWAYS       ]  Document, refactor, and ship
```

------------------------------------------------------------------------

## `06 / GITHUB TELEMETRY`

::: {align="center"}
`<img height="165" src="https://github-readme-stats.vercel.app/api?username=DEMON895&show_icons=true&hide_border=true&bg_color=0b1220&title_color=00f5d4&text_color=d7e5ee&icon_color=00f5d4&ring_color=00f5d4" alt="GitHub stats for DEMON895"/>`{=html}

`<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DEMON895&layout=compact&hide_border=true&bg_color=0b1220&title_color=00f5d4&text_color=d7e5ee" alt="Most used languages for DEMON895"/>`{=html}

`<img src="https://github-readme-streak-stats.herokuapp.com?user=DEMON895&hide_border=true&background=0B1220&ring=00F5D4&fire=00F5D4&currStreakLabel=00F5D4&sideLabels=D7E5EE&dates=8BA3B5&currStreakNum=FFFFFF&sideNums=FFFFFF" alt="GitHub contribution streak for DEMON895"/>`{=html}
:::

`<sub>`{=html}Stats and animation images are loaded from third-party
services, so they may occasionally be unavailable. Language statistics
are estimates based on repository contents.`</sub>`{=html}

------------------------------------------------------------------------

## `07 / CONNECT`

::: {align="center"}
[![GitHub](https://img.shields.io/badge/GitHub-Follow%20the%20build-101820?style=for-the-badge&logo=github&logoColor=00F5D4)](https://github.com/DEMON895)

**Have an interesting hardware, Linux, AI, or game-dev idea?** Let's
build and learn.

`<br/>`{=html}

`<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:00F5D4,50:1B8A9B,100:00F5D4" width="100%" alt="Teal divider"/>`{=html}

`END OF TRANSMISSION` · `SYSTEM STATUS: LEARNING / BUILDING / REPEATING`
:::
