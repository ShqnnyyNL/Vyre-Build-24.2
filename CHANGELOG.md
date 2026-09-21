# Vyre Changelog

Public release notes only. Internal implementation details and proprietary source are intentionally omitted.

## 3.9.7.15 — Compatibility Baseline

**Target:** Paper 26.2 build 126 · Java 25

- Locked compilation to `paper-api 26.2.build.126-stable`.
- Declared `api-version: '26.2'` in plugin metadata.
- Enforced Java 25 bytecode as the release baseline.
- Added release checksums for integrity verification.
- Rejected CraftBukkit/NMS and other internal implementation references.
- Migrated Friends player-head handling to the modern profile data-component API.
- Verified 2,535 API references with zero unresolved or internal references.
- Passed 175/175 compatibility and regression checks.
- No gameplay, performance, GUI or event changes in this release.

## 3.9.7.14 — Runtime & ABI Stability

**Target:** Paper 26.2 build 126 · Java 25

- Completed the first runtime/ABI stabilization pass.
- Verified 2,537 API references with zero unresolved references.
- Confirmed no CraftBukkit or NMS linkage.
- Passed 197 automated checks covering:
  - startup, reload and restart;
  - existing player-data loading;
  - `/begin` and teleport flow;
  - Profile and all core GUIs;
  - Friends;
  - ranks, shop and kits;
  - homes;
  - cosmetics;
  - InfoBoard;
  - YAML configuration loading.
- Cleared the known ABI failure patterns tracked for this release line.

## Earlier 3.9.7 work

- Refined the unified medieval menu flow.
- Expanded apocalypse missions and event tuning.
- Added realm-level administration commands.
- Added configurable menus, kits, quests, cosmetics and InfoBoard files.
- Repaired malformed cosmetics configuration migration.

For security reasons, this public changelog does not list private class names, source locations or exploit-sensitive implementation details.
