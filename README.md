# DungeonCrawler Tester

Public home for testing utilities used by the DungeonCrawler product.

## Scope

This repository is intended to hold reusable testing support for DungeonCrawler, including:

- regression and validation helpers
- fixture data and test harness utilities
- release verification support
- product-specific QA scripting that should live outside the main platform monorepo

## Current status

This repository is currently a public staging repo. Tooling and test assets are being extracted from the main platform workspace into a cleaner standalone package.

## Related repositories

- Platform workspace: [`Forseti-Life/forseti.life`](https://github.com/Forseti-Life/forseti.life)
- Shared conversation module: [`Forseti-Life/forseti-ai-conversation`](https://github.com/Forseti-Life/forseti-ai-conversation)

## Goal

Keep DungeonCrawler testing assets easier to discover, version, and reuse without requiring the full platform monorepo checkout.
