# Compatibility

## Current public target

| Component | Status |
| --- | --- |
| Vyre | 3.9.7.12 |
| Server | Paper |
| Development line | Paper 26.2 |
| Java clients | Supported project target |
| Bedrock via Geyser/Floodgate | Supported project direction; validate per build |
| Source | Private |

## Production guidance

Do not assume a new Paper build is safe merely because the server starts.

After updating Paper, verify at minimum:
- startup;
- commands;
- inventory/menu interaction;
- item metadata;
- scoreboard/UI;
- world loading;
- homes and warps;
- player persistence;
- Java clients;
- Bedrock clients where applicable.

Back up the server before changing either Paper or Vyre.
