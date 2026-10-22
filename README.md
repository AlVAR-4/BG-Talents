**BG Talents** is a Minecraft **Fabric** mod that adds a fully customizable talent system with 12 unique abilities to enhance your combat experience. Collect Soul Stones by defeating monsters, unlock powerful talents, and become the ultimate warrior!

> **Note:** This version is adapted for **Fabric**. It requires **Fabric API** as an additional mandatory mod dependency in order to work properly.

## ✨ Features

- **12 Unique Talents** — 8 Attack + 4 Defense abilities
- **20 Levels per Talent** — Progressive power scaling
- **Soul Stone System** — Earn currency by killing mobs
- **GUI Menu** — Intuitive interface (press **U** to open)
- **Virtual Balance** — Respec without losing stones
- **PvP 1.8 Mode** — Command to disable attack cooldown
- **Multi-language Support** — English & Spanish
- **Custom Sounds & Particles** — Immersive feedback for every ability

## ⚔️ Talent List

### Attack Talents (8)

| Talent | Effect | Max Bonus |
|---|---|---|
| Lifesteal | Steals life based on damage dealt | 30% lifesteal |
| Bloody Blade | Weaker version of Lifesteal | 5% lifesteal |
| Ice | Slows enemies by 30% on hit | 30% chance |
| Blazing | Sets enemies on fire for 3 seconds | 30% chance |
| Strategic Strike | Chance to trigger a critical strike | 20% chance |
| Critical Hit | Increases critical strike damage | +50% damage |
| Thunder | Summons lightning (5 damage, ignores armor) | 30% chance |
| Storm | 3 hits in 4s → Movement Speed boost | +1–20% speed |
| Berserker | Less health = More damage | Up to +100% damage |

### Defense Talents (4)

| Talent | Effect | Max Bonus |
|---|---|---|
| Bedrock Shield | Magical shield reflecting projectiles | 20% chance, 50% reduction |
| Health | Increases maximum health | +6.25 hearts |
| Tough | Reduces all incoming damage | 20% reduction |
| Gold-Blood | Generates golden hearts when hurt | 20% chance, 2–3 hearts |

## 🎮 How to Play

### 1. Get Soul Stones
Kill Zombies, Skeletons, Spiders, and Creepers.

- 50% drop chance
- 1–5 Soul Stones per drop

### 2. Open the Menu
Press **U** (configurable in controls).

- Clean Minecraft-style interface with Attack/Defense tabs

### 3. Unlock & Upgrade
Each talent has 20 levels.

- Spend Soul Stones to unlock (25–50 stones) and upgrade (20–30 stones)
- Click the talent name to Activate/Deactivate

### 4. Reset Talents
Refunds all invested Soul Stones.

- Per category (Attack/Defense)
- Stones returned as Virtual Balance

### 5. Materialize Balance
Convert Virtual Balance into physical Soul Stones in your inventory.

## ⚡ Commands

| Command | Description | Permission |
|---|---|---|
| `/bgtalents give <amount>` | Gives Soul Stones to the player | None |
| `/bgtalents reset attack` | Resets all attack talents | None |
| `/bgtalents reset defense` | Resets all defense talents | None |
| `/bgtalents admin wipe <player>` | Resets ALL talents with NO refund | OP Level 2 |
| `/bgtalents admin maxout <player>` | MAX ALL talents WITH refund | OP Level 2 |
| `/bgtalents admin maxout-norefund <player>` | MAX ALL talents with NO refund | OP Level 2 |
| `/bgtalents pvp` | Toggles PvP 1.8 mode (no attack cooldown) | None |

## 📥 Installation

1. Download the latest `.jar` file from **Releases**.
2. Install **Fabric Loader** for Minecraft **1.20.1**.
3. Download **Fabric API** for Minecraft **1.20.1**.
4. Place **BG Talents** and **Fabric API** in your `.minecraft/mods/` folder.
5. Launch Minecraft using the **Fabric Loader** profile.
6. Enjoy! Press **U** to open the talents menu.

> **Important:** If **Fabric API** is not installed, the mod will not work correctly.

## 🔧 Requirements

| Requirement | Version / Note |
|---|---|
| Minecraft | 1.20.1 |
| Fabric Loader | Compatible with Minecraft 1.20.1 |
| Fabric API | **Required** — additional mod dependency |
| Forge | **Not required** |

### Dependencies

- **Fabric API**: required as an additional mod. It must be placed alongside BG Talents in the `mods` folder.

## 🌐 Languages

| Language | Status |
|---|---|
| 🇺🇸 English | ✅ Complete |
| 🇪🇸 Spanish | ✅ Complete |
| 🇲🇽 Spanish (MX) | ✅ Complete |

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs via Issues
- Suggest new features
- Submit pull requests

## 🔗 Links

- GitHub: https://github.com/AlVAR-4/BG-Talents
- Issue Tracker: https://github.com/AlVAR-4/BG-Talents/issues/5
- CurseForge: https://www.curseforge.com/minecraft/mc-mods/bgtalents
