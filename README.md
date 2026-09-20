<div align="center">

# ⚔️ VYRE

### Private-source medieval survival framework for Minecraft

**A unified survival experience built around progression, exploration, social gameplay and polished cross-platform UX.**

![Vyre](https://img.shields.io/badge/VYRE-3.9.7.12-7c3aed?style=for-the-badge&labelColor=111827)
![Paper](https://img.shields.io/badge/PAPER-26.2-22c55e?style=for-the-badge&labelColor=111827)
![Source](https://img.shields.io/badge/SOURCE-PRIVATE-ef4444?style=for-the-badge&labelColor=111827)
![Development](https://img.shields.io/badge/DEVELOPMENT-ACTIVE-38bdf8?style=for-the-badge&labelColor=111827)

**Enjoyment → Polish → Flow → Performance → Features**

</div>

---

## Overview

Vyre is a custom Minecraft server framework designed to make a survival server feel like **one coherent game experience** rather than a collection of unrelated plugins.

The project combines player progression, social systems, economy, homes, warps, quests, jobs, achievements, cosmetics, discoveries, server events and custom navigation behind a consistent Vyre interface.

Vyre is developed as a **private-source project**. This repository is its public-facing home for project information, release notes, compatibility information, bug reports and feature suggestions. The proprietary Java implementation is intentionally not included.

---

## Design philosophy

A feature is not considered finished simply because the command works.

Vyre development focuses on the complete player experience:

- Is the feature understandable without staff explaining it?
- Does it feel consistent with the rest of the server?
- Is navigation fast?
- Does it work cleanly for both Java and Bedrock players?
- Does it remain responsive under load?
- Can server administrators configure it without touching source code?
- Does it add meaningful survival gameplay rather than menu clutter?

This leads to a strict development order:

> **Stability first. Compatibility second. Performance third. Polish fourth. Features fifth.**

---

# ✦ Player Experience

## 👤 Profile

The Profile is the central location for systems that belong specifically to the player.

Instead of filling the main survival menu with progression shortcuts, player-focused systems are grouped together so navigation remains predictable as Vyre grows.

Typical Profile systems include:

- Friends
- Levels
- Skills
- Upgrades
- Achievements
- Quests
- Jobs
- Titles and supported personalization
- Daily/player rewards
- Personal settings

The intention is to make Profile feel like the player's own control center rather than another generic inventory GUI.

---

## 🤝 Friends & social gameplay

Vyre includes its own social direction rather than treating multiplayer as nothing more than chat.

The Friends system is designed around meaningful survival interactions such as:

- Managing friends
- Viewing friend-related actions
- Requesting access to supported player areas
- Interacting with homes where permitted
- Social navigation without exposing unrestricted teleportation
- Clear permission boundaries between land owner and visitor

Social features are designed to complement survival ownership instead of bypassing it.

---

## 📈 Levels, progression & upgrades

Progression gives players long-term objectives without requiring the server to become a traditional RPG.

Vyre's progression direction includes activity-based advancement from gameplay such as:

- Playtime
- Mining
- Farming
- Fishing
- Exploration
- Quests
- Jobs
- Events
- Mob encounters
- Discoveries and locations

Progression can unlock rewards, convenience improvements and cosmetic/status elements while keeping survival itself recognizable.

The system is intended to reward **playing the world**, not repeatedly opening menus.

---

## 🏆 Achievements

Achievements provide permanent milestones for meaningful player accomplishments.

Examples of achievement categories include:

- First progression milestones
- Exploration
- Economy
- Survival
- Building
- Combat
- Travel

Achievements are designed to create smaller goals between major progression levels.

---

# ✦ Survival Experience

## 🏠 Homes

Homes provide persistent player navigation while remaining part of the survival experience.

Vyre's home direction includes:

- Player-owned home locations
- Supported access controls
- Friend interaction where permitted
- Teleport preparation/delay behavior
- Movement cancellation where applicable
- GUI and command integration
- Preservation of home data across normal plugin updates

Player data safety is considered more important than cosmetic changes to the system.

---

## 🌍 Warps

Warps provide server-controlled navigation to important locations.

They are intended for destinations such as:

- Spawn
- Markets
- Community areas
- Event locations
- Server facilities
- Other configured destinations

Warp presentation is kept consistent with the rest of Vyre rather than behaving like a separate utility plugin.

---

## 🛒 Economy & Shop

Vyre's economy systems are built to give currency a reason to exist inside survival.

The Shop provides regular server-facing trade while additional systems can create rarer or more situational opportunities.

Economy design aims to avoid turning every activity into a pure money grind.

---

## ☠️ Black Market

The Black Market is treated as a survival/economy system — **not a cosmetic submenu**.

It is intended to feel more unusual than the standard shop and can be presented independently through Vyre's configurable menu structure.

Keeping it separate also makes the main navigation easier to understand.

---

## 🎒 Kits

Kits provide configured item packages tied to supported permissions, ranks or server progression.

Vyre's kit presentation is intended to keep:

- Default kits
- Ranked kits
- Requirement feedback
- Item presentation
- Claim behavior

visually consistent with the rest of the server.

---

## ✨ Cosmetics

Cosmetics provide optional personalization without replacing the core survival loop.

The design goal is:

> **Customization should make a player feel unique without making survival feel fake.**

Staff/testing access and player unlock requirements can be handled separately where configured.

---

# ✦ Quests, Jobs & World Activity

## 📜 Quests

Quests provide directed objectives for players who want something specific to work toward.

Vyre's quest direction favors objectives that naturally fit survival and the server's medieval/apocalyptic atmosphere rather than disconnected checklist tasks.

---

## ⛏️ Jobs

Jobs provide another progression/economy path through ordinary gameplay.

The system is intended to complement the player's chosen playstyle instead of forcing every player through exactly the same route.

---

## 🧭 Discoveries

Exploration should matter.

Discoveries allow important locations and world exploration to become part of progression, giving players reasons to travel beyond their home and spawn.

---

## ⚔️ Dynamic events

Vyre's event framework is intended to make the survival world occasionally feel unpredictable.

Event concepts can include experiences such as:

- Zombie outbreaks
- Supply drops
- Meteor crashes
- Treasure hunts
- Boss encounters
- Lost expeditions
- Abandoned laboratories
- Merchant caravans

The project does **not** aim to turn the server into a gun-focused shooter. Vyre's gameplay direction remains survival-oriented with a medieval atmosphere.

Events should enhance normal survival rather than constantly interrupt it.

---

# ✦ Menus & UX

## One visual language

Vyre uses a unified menu direction across its systems.

Menu design focuses on:

- Consistent titles
- Consistent Back navigation
- Predictable item placement
- Clear locked/unlocked states
- Short useful descriptions
- Reduced unnecessary lore
- Minimal visual clutter
- Consistent requirement presentation
- Fast menu opening
- Configuration-driven layouts where supported

The goal is for a player to recognize a Vyre interface immediately.

---

## Main Menu

The Main Menu is intentionally reserved primarily for **survival-facing destinations**.

Player progression systems belong under Profile.

This prevents the main menu from becoming a giant directory as new systems are added.

### Survival-oriented navigation may include

`Profile` · `Homes` · `Warps` · `Shop` · `Kits` · `Black Market` · `Cosmetics` · `Discoveries` · `Events` · `Realm Guide`

Exact contents may differ between server configurations and releases.

---

# ✦ Java & Bedrock

Vyre is developed with cross-platform server communities in mind.

Java inventory interfaces do not automatically translate into a good Bedrock or mobile experience, so Bedrock behavior is treated as its own UX concern.

Areas of focus include:

- Click reliability
- Menu responsiveness
- Mobile readability
- Navigation depth
- Interaction feedback
- Avoiding unnecessary menu refreshes
- Geyser/Floodgate compatibility
- Reducing expensive preparation before player actions

A menu that technically opens but feels frustrating on a phone is still considered a UX problem.

---

# ✦ Performance

Performance work is part of feature development, not an afterthought.

Vyre's performance direction includes:

- Avoiding unnecessary synchronous work
- Reducing repeated configuration parsing
- Caching suitable frequently-read state
- Keeping menu construction lightweight
- Limiting repeated scoreboard/UI updates
- Cleaning up temporary entities and visual objects correctly
- Avoiding duplicate hologram or display creation
- Moving suitable work away from hot event paths
- Preserving safe Bukkit/Paper thread boundaries
- Profiling before making high-player-count claims

### Player-count claims

Vyre is being engineered with larger communities in mind, but this repository intentionally does **not** advertise an arbitrary guaranteed player capacity.

A capacity claim is only useful when backed by representative profiling with the actual server configuration, worlds, plugins, hardware and gameplay load.

---

# ✦ Paper compatibility

Minecraft/Paper updates can change APIs and runtime behavior.

For that reason, Vyre treats Paper compatibility as a release requirement rather than assuming a build works because it compiles.

Compatibility work includes checking:

- API changes
- Runtime linkage errors
- Inventory APIs
- Scoreboard APIs
- Event handling
- World loading
- Item metadata
- Commands
- Configuration serialization
- Geyser-related behavior where applicable

### Current public target

| Component | Target |
| --- | --- |
| Vyre | `3.9.7.12` |
| Server software | Paper |
| Validated development line | Paper `26.2` |
| Source model | Private / proprietary |
| Development | Active |

Always check release notes before updating Paper on a production server.

---

# ✦ Configuration philosophy

Vyre aims to expose presentation and supported server behavior through configuration without exposing the implementation itself.

Where supported, administrators should be able to configure things such as:

- Menu items
- GUI positions
- Display names
- Descriptions
- Requirements
- Ranks
- Supported InfoBoard content
- Cosmetics
- Shop presentation
- Other module-specific options

Configuration files are not a substitute for source code and should not contain implementation secrets.

---

# ✦ Data safety & updates

Before updating Vyre on a production server:

```text
1. Stop the server.
2. Back up the complete plugins/Vyre directory.
3. Back up important world/player data.
4. Replace the Vyre build.
5. Do not blindly replace existing YAML/data files.
6. Start the server.
7. Read migration and compatibility messages in console.
8. Test critical systems before opening the server to players.
```

Critical checks should include:

- Player login
- Profile
- Main Menu
- Homes
- Warps
- Economy
- Friends
- Progression
- Scoreboard/UI
- Java client behavior
- Bedrock client behavior, if enabled

---

# ✦ Release philosophy

A Vyre release should improve the server without silently destroying existing configuration or player progress.

Where practical, migrations should preserve:

- Homes
- Warps
- Player progression
- Friend relationships
- Settings
- Existing compatible menu customization
- Other persistent player/server state

Breaking migrations should be clearly documented.

---

# ✦ Current development focus

The current project direction emphasizes:

### 01 — Blocking bugs
Fix startup failures, command failures, broken menus, corrupted configuration and player-data risks.

### 02 — Paper 26.2 stability
Remove runtime API/ABI incompatibilities and validate affected systems on the target Paper build.

### 03 — Performance
Reduce unnecessary work in menus, scoreboards, movement/event handlers, world preparation and repeated UI updates.

### 04 — Cross-platform polish
Make Java, Bedrock and especially mobile navigation feel deliberate rather than merely compatible.

### 05 — Consistency
Bring older Profile, Friends, Titles, Quests and related interfaces into the same visual language as newer Vyre menus.

New features come after those foundations are healthy.

---

# ✦ Reporting bugs

A useful report includes:

| Information | Example |
| --- | --- |
| Vyre version | `3.9.7.12` |
| Paper version | Exact build number |
| Java runtime | Exact Java version |
| Client | Java / Bedrock / Both |
| Reproduction | Exact steps |
| Expected | What should happen |
| Actual | What happened |
| Logs | Relevant stack trace |
| Frequency | Always / Sometimes / Once |

Do not post credentials, tokens, database passwords or other secrets.

Use the included **Bug Report** issue template whenever possible.

---

# ✦ Feature suggestions

Feature suggestions are welcome when they explain the **player problem** first.

A useful suggestion answers:

1. What currently feels missing or awkward?
2. Who benefits from the change?
3. How should the experience feel to the player?
4. Does it belong in Vyre or would it create unnecessary feature bloat?
5. How should it behave for Java and Bedrock players?

Implementation details are intentionally kept private.

---

# 🔒 Source & intellectual property

Vyre is a **private-source / proprietary project**.

This public repository is intended for documentation, project presentation, compatibility information, release notes and community issue tracking.

Unless separately authorized by the rights holder, the public repository does not grant permission to publish or redistribute proprietary Vyre source or private builds.

Do not submit:

- Leaked source
- Decompiled source
- Reconstructed implementation code
- Private build artifacts
- Internal development files

Nothing in this repository should be interpreted as publishing the Vyre implementation under an open-source license.

---

# ✦ Repository structure

```text
Vyre/
├── README.md
├── CHANGELOG.md
├── ROADMAP.md
├── COMPATIBILITY.md
├── CONTRIBUTING.md
├── SECURITY.md
├── .gitignore
└── .github/
    └── ISSUE_TEMPLATE/
        ├── bug-report.yml
        └── feature-request.yml
```

No proprietary Java source is required for this public repository.

---

<div align="center">

## ⚔️ VYRE

### Medieval survival, built as one experience.

**Private Source • Active Development • Paper**

`Vyre 3.9.7.12`

</div>
