<div align="center">

# ⚔️ VYRE

### A premium medieval survival framework for Minecraft

**Progression • Social Systems • Events • Custom Menus • Java & Bedrock UX**

![Version](https://img.shields.io/badge/Vyre-3.9.7.12-7c3aed?style=for-the-badge)
![Platform](https://img.shields.io/badge/Paper-26.2-111827?style=for-the-badge)
![Source](https://img.shields.io/badge/Source-Private-ef4444?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-22c55e?style=for-the-badge)

**Built to make survival feel like a world — not a collection of commands.**

</div>

---

## ✦ What is Vyre?

Vyre is a private-source Minecraft server plugin built around a polished **medieval survival experience**.

Instead of stacking disconnected utility plugins and generic inventories, Vyre brings progression, social features, navigation, events, cosmetics and server UX together under one consistent system.

The project is designed around a simple priority:

> **Enjoyment → Polish → Flow → Performance → Features**

This repository is the public home of Vyre. It contains project information, compatibility notes, changelogs and issue reporting — **not the implementation source code**.

---

## ✦ Core Experience

| System | What it adds |
| --- | --- |
| 👤 **Player Profile** | One home for player progression and personal systems |
| 🤝 **Friends** | Social connections, friend actions and survival interactions |
| 📈 **Levels & Upgrades** | Long-term progression without turning survival into a grind |
| 🏆 **Achievements** | Milestones that reward exploration and play |
| 📜 **Quests & Jobs** | Structured objectives integrated into survival |
| 🏠 **Homes & Warps** | Fast navigation with a consistent Vyre experience |
| 🛒 **Shop & Black Market** | Economy-driven survival systems |
| ✨ **Cosmetics** | Optional personalization without replacing core gameplay |
| 🌍 **Discoveries & Events** | Reasons to explore and return to the world |
| ⚙️ **Settings** | Player-facing controls for supported Vyre systems |

---

## ✦ Designed as one ecosystem

Vyre separates **player progression** from **survival gameplay** so menus stay understandable as the server grows.

### Profile
Friends · Levels · Skills · Upgrades · Achievements · Quests · Jobs · Personal Settings

### Survival
Homes · Warps · Shop · Kits · Black Market · Cosmetics · Discoveries · Events · Realm Guide

The goal is simple: players should spend less time figuring out commands and more time playing.

---

## ✦ Java + Bedrock

Vyre is being built with both **Java Edition** and **Bedrock/Geyser** players in mind.

Menu behavior, navigation and interaction flow are treated as real UX problems rather than assuming a desktop Java inventory is good enough everywhere.

> Bedrock and mobile behavior may differ between builds. Reproducible device-specific issues are welcome in the issue tracker.

---

## ✦ Configuration

Vyre uses modular YAML configuration for supported menus and gameplay presentation.

The project aims to keep server-facing configuration flexible while keeping the proprietary implementation private.

When updating:

1. Stop the server.
2. Back up your existing `plugins/Vyre/` directory.
3. Replace the Vyre build.
4. Keep existing player data and configuration unless release notes explicitly require a migration.
5. Start the server and review the console for warnings.

**Never overwrite production data without a backup.**

---

## ✦ Compatibility

| Component | Current target |
| --- | --- |
| Server | Paper |
| Validated branch | Paper 26.2 |
| Vyre | 3.9.7.12 |
| Source availability | Private / proprietary |
| Development status | Active |

Compatibility is validated per release. A newer Paper build should not automatically be assumed compatible until tested.

---

## ✦ Development priorities

Vyre development follows this order:

**01 — Blocking bugs & data safety**  
Crashes, broken commands, corrupted configuration and player-data risks come first.

**02 — Paper compatibility**  
API/ABI changes and server-version regressions are handled before expanding systems.

**03 — Performance**  
Hot paths, menu rendering, storage work and high-player-count behavior are optimized before unnecessary complexity is added.

**04 — Polish**  
Consistent menus, text, navigation, feedback and Java/Bedrock behavior.

**05 — New features**  
New gameplay comes after the existing experience is stable.

---

## ✦ Reporting a bug

Open an issue and include:

- Vyre version
- Exact Paper build
- Java version
- Java or Bedrock/Geyser client
- Steps to reproduce
- Relevant console error or stack trace

Please remove passwords, tokens, database credentials, IP information you do not want public, and other secrets before posting logs.

---

## 🔒 Private-source project

The Vyre implementation is intentionally **not published in this repository**.

Public documentation does not grant permission to reproduce, redistribute or republish Vyre's proprietary implementation. Do not upload leaked source, decompiled code or private builds to issues or pull requests.

---

<div align="center">

### VYRE

**Medieval survival. Built as an experience.**

`3.9.7.12`

</div>
