# BG Talents

[![Forge](https://img.shields.io/badge/Forge-1.20.1-important)](https://files.minecraftforge.net/)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)](LICENSE)

RPG-style talent system for Minecraft 1.20.1 Forge.

---

## ⚠️ LICENSE NOTICE

**This mod is All Rights Reserved.**

You are **allowed** to:
- ✅ Download and use the mod
- ✅ Share the mod with others (unmodified)

You are **NOT allowed** to:
- ❌ Modify, decompile, or reverse engineer the code
- ❌ Redistribute modified versions
- ❌ Claim ownership of the mod
- ❌ Use the mod for commercial purposes without explicit permission

For details, see the [LICENSE](LICENSE) file.

---

## 📦 Download

Download the latest version from the [Releases](https://github.com/AlVAR-4/BG-Talents/releases) page.

---

## 📖 Features

- **11 unique talents** (7 Attack / 4 Defense)
- **Soul Stone system** with virtual balance
- **Multiplayer support** (full client-server sync)
- **Custom sounds and particle effects**
- **World-specific save data**
- **Scrollable talent menu** (press `U` to open)

---

## ⚔️ Attack Talents

| Talent | Effect (Max Level 20) |
|--------|----------------------|
| **Lifesteal** | Steal up to **30%** of damage dealt as health |
| **Bloody Blade** | Steal up to **5%** of damage dealt as health |
| **Ice** | **30%** chance to slow enemies by 30% |
| **Blazing** | **30%** chance to set enemies on fire (3s) |
| **Attack Weakness** | **20%** chance to trigger a critical hit |
| **Critical Hit** | Critical hits deal **+50%** bonus damage |
| **Thunder** | **30%** chance to strike with lightning (4 damage, ignores armor) |

---

## 🛡️ Defense Talents

| Talent | Effect (Max Level 20) |
|--------|----------------------|
| **Bedrock** | **20%** chance to block damage, reducing it by **50%** |
| **Health** | Increases max health by up to **+6.25 hearts** |
| **Tough** | **20%** universal damage resistance |
| **Gold-Blood** | **20%** chance to generate **2-3 absorption hearts** (10s duration, cooldown 5-10s) |

### Gold-Blood Cooldown Scaling

| Level Range | Cooldown | Absorption Hearts |
|-------------|----------|-------------------|
| 1–5 | 10s | 2 hearts |
| 6–9 | 9s → 6s | 2 hearts |
| 10–14 | 5s | 2 hearts |
| **15–20** | **5s** | **3 hearts** |

---

## 💎 Soul Stone System

| Feature | Detail |
|---------|--------|
| **Obtained from** | Zombies, Skeletons, Spiders, Creepers |
| **Drop chance** | 50% chance, 1-5 stones per drop |
| **Unlock cost** | 25 or 50 Soul Stones |
| **Upgrade cost (1–10)** | 20 Soul Stones |
| **Upgrade cost (11–20)** | 30 Soul Stones |
| **Refund** | Stones returned as virtual balance when resetting |

---

## 🎮 Installation

1. Download the `.jar` file from [Releases](https://github.com/AlVAR-4/BG-Talents/releases)
2. Place it in your `mods` folder
3. Launch Minecraft with Forge 1.20.1
4. Press `U` to open the talent menu (configurable)

---

## ⌨️ Commands

| Command | Description | Permission |
|---------|-------------|------------|
| `/bgtalents give <amount>` | Gives Soul Stones to the player | None |
| `/bgtalents reset attack` | Resets all attack talents (with refund) | None |
| `/bgtalents reset defense` | Resets all defense talents (with refund) | None |
| `/bgtalents admin wipe <player>` | Resets ALL talents (no refund) | OP Level 2 |
| `/bgtalents admin maxout <player>` | Maxes ALL talents (with refund) | OP Level 2 |
| `/bgtalents admin maxout-norefund <player>` | Maxes ALL talents (no refund) | OP Level 2 |

---

## 🖼️ Screenshots

*(Add screenshots here)*

---

## 📋 Requirements

| Requirement | Detail |
|-------------|--------|
| **Minecraft** | 1.20.1 |
| **Mod Loader** | Forge 47.4.10+ |
| **Dependencies** | None |

---

## 🛠️ Building from Source

If you just want to view the source code (modification is not permitted):

```bash
git clone https://github.com/AlVAR-4/BG-Talents.git
cd BG-Talents
./gradlew build
