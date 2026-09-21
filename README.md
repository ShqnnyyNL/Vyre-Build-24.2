<div align="center">

![Vyre — Explore, Survive, Belong](assets/vyre-banner.png)

# ⚔️ VYRE

### A private-source medieval survival framework for Minecraft

**One core plugin. One connected realm. Built for polished Java and Bedrock gameplay.**

[![Vyre](https://img.shields.io/badge/Vyre-3.9.7.15-6ee7f9?style=for-the-badge)](#current-release)
[![Paper](https://img.shields.io/badge/Paper-26.2%20build%20126-ffffff?style=for-the-badge)](COMPATIBILITY.md)
[![Java](https://img.shields.io/badge/Java-25-f59e0b?style=for-the-badge)](COMPATIBILITY.md)
[![Source](https://img.shields.io/badge/Source-Private-ef4444?style=for-the-badge)](LICENSE.txt)

**Explore · Survive · Belong**

</div>

---

## What is Vyre?

Vyre turns a Minecraft survival server into one coherent medieval realm. Progression, social systems, events, homes, ranks, cosmetics and administration share the same visual language and player flow instead of feeling like unrelated plugins.

The project follows one development order:

> **Enjoyment → Polish → Flow → Performance → Features**

## Current release

| Component | Current status |
| --- | --- |
| Vyre plugin | **3.9.7.15** |
| Production target | **Paper 26.2 build 126** |
| Java runtime | **Java 25** |
| API declaration | **26.2** |
| Java clients | Supported |
| Bedrock clients | Supported through Geyser/Floodgate |
| Source code | Private / proprietary |
| Vyre Server 26.3 | Under development for official launch |

### Soft dependencies

1. PlaceholderAPI
2. LuckPerms
3. Iris

Vyre is delivered as one core plugin. The integrations above are optional and are detected safely when present.

## Release 3.9.7.15 — Compatibility baseline

This release completes the second stability step and locks Vyre to a clean, auditable runtime baseline:

- compiled against `paper-api 26.2.build.126-stable`;
- declares `api-version: '26.2'`;
- targets Java 25 bytecode;
- rejects CraftBukkit and NMS implementation dependencies;
- moves Friends player-head rendering to the modern profile data-component API;
- verifies **2,535 API references** with **zero unresolved or internal references**;
- passes the complete **175/175 regression suite**;
- publishes reproducible checksums with the private release package.

This is a compatibility and stability release. It intentionally does not add new gameplay, GUI, event or performance features.

Read the full notes in [CHANGELOG.md](CHANGELOG.md).

## Realm systems

| System | Experience |
| --- | --- |
| Realm Levels | Progress from 1–50 through real play |
| Profiles | Rank, level, achievements, coins and playtime |
| Friends | Trusted building and social management |
| Homes & Warps | Safe, delayed travel with movement cancellation |
| Jobs & Quests | Purposeful objectives across survival activities |
| Events | Outbreaks, meteor crashes, expeditions, caravans and bosses |
| Cosmetics | Rank- and level-aware visual unlocks |
| Economy | Shops, rewards and server progression |
| Premium Chat | Hover details, mentions, messaging, ignore and moderation tools |
| InfoBoard | Compact live player and realm information |
| Administration | Diagnostics, setup, reset and testing tools |

## Stability standard

Every release candidate is checked across the critical server flow:

`startup → join → commands → GUI → teleport → reload → restart → existing data`

The compatibility gate covers `/begin`, Profiles, Friends, ranks, shops, kits, homes, cosmetics, InfoBoard, YAML loading and teleport services. Persistent player and server data must survive an update.

## Installation and distribution

Vyre is not distributed publicly from this repository. Authorized server operators receive the compiled plugin and release checksums through a private channel.

See [docs/INSTALLATION.md](docs/INSTALLATION.md) for the safe update procedure and [COMPATIBILITY.md](COMPATIBILITY.md) for supported versions.

## Closed-source policy

This repository is a project showcase and documentation hub. It does **not** grant permission to copy, redistribute, decompile, modify, resell or publish Vyre.

The following are intentionally excluded:

- Java source and build projects;
- compiled plugin JARs and private release ZIPs;
- production configuration and secrets;
- server, player, economy or world data;
- internal architecture and implementation details.

See [LICENSE.txt](LICENSE.txt) and [SECURITY.md](SECURITY.md).

## Community

Bug reports and feature ideas are welcome through GitHub Issues. Reports should describe visible behavior and reproduction steps without uploading proprietary binaries, private configuration, credentials or player data.

## Creator

<table>
  <tr>
    <td width="90"><img src="https://avatars.githubusercontent.com/u/331589727?v=4" width="72" alt="Shqnnyy Minecraft creator avatar"></td>
    <td><strong>Shqnnyy</strong><br>Owner · Developer · Creative Direction<br><em>“Turning ideas into worlds.”</em></td>
  </tr>
</table>

---

<div align="center">

**VYRE — SAME BLOCKS. A DIFFERENT STORY.**

© 2026 Shqnnyy. All rights reserved.

</div>
