# BG Talents

Forge mod for Minecraft 1.20.1 that adds an RPG-style talent system.

---

## License

This mod is All Rights Reserved.

You can download and use it. You cannot modify, decompile, redistribute modified versions, or use it commercially.

---

## Download

Get the latest version from the Releases page:
https://github.com/AlVAR-4/BG-Talents/releases

---

## What it does

The mod adds 11 talents split into two categories: Attack and Defense.

You unlock and upgrade them using Soul Stones, which drop from zombies, skeletons, spiders, and creepers with a 50% chance (1-5 stones per drop).

Press U to open the talent menu.

---

## Attack Talents (7)

1. Lifesteal – Steal up to 30% of damage dealt as health
2. Bloody Blade – Steal up to 5% of damage dealt as health
3. Ice – 30% chance to slow enemies by 30%
4. Blazing – 30% chance to set enemies on fire for 3 seconds
5. Attack Weakness – 20% chance to trigger a critical hit
6. Critical Hit – Critical hits deal up to 50% bonus damage
7. Thunder – 30% chance to strike with lightning, dealing 5 damage (ignores armor)

---

## Defense Talents (4)

1. Bedrock – 20% chance to block damage, reducing it by 50%
2. Health – Increases max health by up to 6.25 hearts
3. Tough – 20% universal damage resistance
4. Gold-Blood – Chance to generate absorption hearts when hit

Gold-Blood details:
- Levels 1-5: 2 hearts, 10s cooldown
- Levels 6-9: 2 hearts, cooldown scales from 9s to 6s
- Levels 10-14: 2 hearts, 5s cooldown
- Levels 15-20: 4 hearts, 5s cooldown

---

## Soul Stone Costs

- Unlock: 25 or 50 stones
- Upgrade levels 1-10: 20 stones each
- Upgrade levels 11-20: 30 stones each

If you reset a talent, the spent stones are returned as virtual balance. You can materialize them back into your inventory anytime.

---

## Installation

1. Download the .jar file from Releases
2. Put it in your mods folder
3. Launch Minecraft with Forge 1.20.1
4. Press U to open the talent menu

---

## Commands

- /bgtalents give <amount> – Gives Soul Stones
- /bgtalents reset attack – Resets attack talents (with refund)
- /bgtalents reset defense – Resets defense talents (with refund)
- /bgtalents admin wipe <player> – Resets all talents (no refund, OP)
- /bgtalents admin maxout <player> – Maxes all talents (with refund, OP)
- /bgtalents admin maxout-norefund <player> – Maxes all talents (no refund, OP)

---

## Requirements

- Minecraft 1.20.1
- Forge 47.4.10 or later
- No other dependencies

---

## Building from source

You can view the code but modification is not allowed.
