# VeinHammer

A lightweight datapack that lets you mine entire ore veins or chop whole trees by breaking a single block. No mods required — just drop it in your world's datapacks folder.

## Features

- **Vein Mining** — Break one ore and the entire connected vein pops. Works with all overworld ores, deepslate variants, and nether ores.
- **Tree Felling** — Chop one log and the whole trunk comes down. Supports all wood types including cherry, mangrove, pale oak, and nether stems.
- **Enchantment Support** — Fortune and Silk Touch are applied to every block in the vein automatically.
- **Max Vein Size** — Configurable limit (default 64 blocks) so you don't accidentally mine a whole chunk.
- **Sneak-to-Activate** — Optional mode where vein mining only triggers while sneaking.
- **Cooldown** — Configurable cooldown between vein mines (default 10 ticks).
- **Fully Configurable** — Add or remove blocks and tools per category (pickaxe, axe, shovel, hoe) with in-game commands.

## Commands

| Command | Description |
|---|---|
| `/function veinhammer:settings` | Open the clickable settings menu |
| `/function veinhammer:reset` | Restore all defaults |
| `/function veinhammer:enable` | Enable the datapack |
| `/function veinhammer:disable` | Disable the datapack |
| `/function veinhammer:add_block {ns: "minecraft", id: "ancient_debris", cat: "pickaxe"}` | Add a custom block |
| `/function veinhammer:add_tool {ns: "minecraft", id: "netherite_shovel", cat: "shovel"}` | Add a custom tool |

## Installation

1. Download the zip file
2. Place it in your world's `datapacks` folder (or drag it onto the Data Packs screen when creating a world)
3. Run `/reload` if the world is already open
4. You should see **[VeinHammer] Loaded!** in chat
