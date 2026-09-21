# Installation & Update Guide

Vyre binaries are distributed privately to authorized operators and are not included in this repository.

## Requirements

- Paper 26.2 build 126
- Java 25
- An authorized Vyre 3.9.7.15 release JAR

Optional integrations:

1. PlaceholderAPI
2. LuckPerms
3. Iris

## Safe update procedure

1. Stop the server completely.
2. Back up the existing Vyre plugin directory and server data.
3. Preserve the current configuration, homes, warps and player data.
4. Replace only the previous Vyre JAR with the authorized 3.9.7.15 JAR.
5. Verify the supplied checksum before starting the server.
6. Start Paper normally with Java 25. Do not use `/reload` for an update.
7. Review startup logs and run the normal join, GUI, teleport and restart checks.

## Never publish

- the Vyre JAR or release ZIP;
- source or decompiled output;
- production configuration;
- tokens, passwords or database credentials;
- player, economy or world data.
