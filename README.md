# Granum Core (Portal)

![System Status](https://img.shields.io/badge/SYSTEM-OPERATIONAL-00ff41?style=for-the-badge)
![Scope](https://img.shields.io/badge/SCOPE-FRONTEND_ONLY-blue?style=for-the-badge)

**The Entry Point & Runtime Environment.**
This repository contains the source code for the [www.granum.online](https://www.granum.online) portal interface. It serves as the central hub linking to various external utilities and applications operated by [Asfact Inc.](https://asfact.jp)

> "Stay Hungry, Stay Mad & Punk."

## 🌐 Endpoints

| Service | URL | Note |
| :--- | :--- | :--- |
| **Granum Core** | [www.granum.online](https://www.granum.online) | **Managed in this repo.** System Root. |
| **Apps Hub** | [apps.granum.online](https://apps.granum.online) | External Link. Collection of utilities. |

## 🔗 Connected Applications

The following tools are linked from this portal but hosted/managed as separate external systems.

* **[touki-diff](https://apps.granum.online/touki-diff/)** - Corporate Registration PDF Diff Tool
* **[md2pdf](https://apps.granum.online/md2pdf/)** - MadPunks Markdown to PDF Engine
* **[svg2dist](https://apps.granum.online/svg2dist/)** - Static Resource Generator
* **[svg-preview](https://apps.granum.online/svg-preview/)** - Real-time SVG Color Simulator

---

## 📂 Repository Structure

Simple single-page application structure.

```text
.
├── index.html      # Production entry point for www.granum.online
├── icon.svg        # System Icon
└── ...             # Static assets (favicons, manifest, etc.)
