# Compatibility

## Supported baseline

| Component | Version / status |
| --- | --- |
| Vyre | 3.9.7.15 |
| Server software | Paper |
| Paper target | 26.2 build 126 |
| Paper API | `26.2.build.126-stable` |
| Plugin API version | `26.2` |
| Java runtime | Java 25 |
| Java clients | Supported |
| Bedrock clients | Supported through Geyser/Floodgate |

Paper 26.3 support is under development for the official Vyre Server launch. It is not the production baseline of release 3.9.7.15.

## Soft dependencies

- PlaceholderAPI
- LuckPerms
- Iris

Vyre remains one core plugin. Missing soft dependencies must not prevent the core from starting; only their matching integrations should be unavailable.

## Compatibility policy

- CraftBukkit and NMS linkage is not allowed.
- Release builds must pass API-reference and regression checks.
- Existing player, home, rank, economy and progression data must remain intact during supported updates.
- `/reload` is not recommended for production Minecraft servers; use a full restart for plugin updates.
