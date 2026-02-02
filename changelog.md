# 🚀 Fallout Anomaly – Launcher Update  
**HOTFIX • SAVE SAFE • 2/2/2026**

![Launcher Update](https://github.com/user-attachments/assets/403c1c67-f50c-4c18-a8c3-6f30cfc640f1)

---

## ⚠️ Important
The launcher now runs as **Administrator by default**.  
This is **intentional and required** to ensure all plugins load correctly.

---

## 🔧 What Changed
- **🛠 Self-Repair System**  
  The launcher can now automatically restore missing files.  
  **DO NOT delete the `enbseries` folder** in the launcher directory — it contains the master backups.

- **🎯 Zero-Touch Path Detection**  
  The launcher automatically finds your Fallout 4 install. No setup required.

- **🔇 Silent Shutdown**  
  Exit cleanup has been optimized. No more temporary directory error popups.

---

## 🚀 Fallout Anomaly v0.5.9.1 — Hotfix

### 🛠 Critical Fixes
- **Launcher Stability**  
  Fixed cases where the Anomaly Launcher failed to start for some users.

- **Weapon Damage Scaling**  
  Damage values now scale correctly. Combat balance should feel normal again.

- **Guide Update**  
  The **First Steps** page has been updated.  
  **YOU MUST READ THIS** to ensure scripts initialize correctly (save/load procedure).

---

### 🎨 Wasteland Graffiti Added
Lore-friendly graffiti added across the Commonwealth to improve environmental storytelling.  
🔗 https://www.nexusmods.com/fallout4/mods/74482

---

### ⚠️ Mod Changes
- **Animated World — DISABLED**  
  Conflicts with MAIM caused issues. Temporarily removed until patched.

- **Equipment Slot Limits**  
  Still optional/disabled while fixes are pending.

---

## 🐛 Bug Tracker
View resolved and tracked issues here:  
🔗 https://github.com/orgs/Fallout-Anomaly/projects/50/views/1

---

## ❤️ Consider Endorsing
If you're enjoying the list, please endorse it on Nexus:  
🔗 https://www.nexusmods.com/fallout4/mods/74075  

> You must download the file and wait **15 minutes** before endorsing  
> *(unless you downloaded it in the past).*

---

## 📦 Wabbajack Notice
**@Stalkers** — allow **~10 minutes** for this update to appear in Wabbajack.

If you don’t see it:
1. Close Wabbajack
2. Wait a few minutes
3. Relaunch and try again

---

## ❗ READ THIS
**EVERYTHING ABOVE MUST BE READ.**  
**YOU MUST COMPLETE THE FIRST STEPS IN THE MCM GUIDE BEFORE PLAYING.**


## Fallout Anomaly Update v0.5.9.1 – System Overhaul  
**February 2, 2026**

---

## ✨ Major Mod Additions

### **Boon Island – Isles of New England**  
A hauntingly atmospheric addition to the New England coastline. Explore a desolate lighthouse island featuring unique quests, environmental storytelling, and challenges built for hardcore exploration.  
🔗 https://www.nexusmods.com/fallout4/mods/84449

### **Misery Island – Isles of New England**  
A massive expansion to the *Isles of New England* series. Introduces a large new worldspace with fully voiced quests, lore-driven settlements, and dense environmental storytelling that expands late-game content significantly.  
🔗 https://www.nexusmods.com/fallout4/mods/87983

### **Animated World Framework**  
Adds pre-placed, context-aware animations for NPCs and environmental objects. The Commonwealth now feels more reactive and alive as characters naturally interact with their surroundings.  
🔗 https://www.nexusmods.com/fallout4/mods/100946

### **Feral Nights (SKK)**  
Nighttime is now far more dangerous. Feral ghouls dynamically form hunting packs after dark and actively track the player. Night travel now demands preparation, stealth, and awareness.  
🔗 https://www.nexusmods.com/fallout4/mods/52449

### **Feral Infestations (FlashyJoeR)**  
Ghoul infestations are no longer static encounters. These dynamic hotzones grow in intensity if ignored and must be actively cleared to maintain safe routes and settlement stability.  
🔗 https://www.nexusmods.com/fallout4/mods/65406

---

## 🚀 New Tools & Features

### **Anomaly Launcher v0.0.1 (Alpha)**  
The first public build of the **Anomaly Launcher** is now included. This lightweight tool lives in your root directory and acts as a bridge between the modlist and update infrastructure.

- **Auto-Update Check** – Scans for modlist updates and patches on launch  
- **Smart Sync** – Verifies your local setup against the official Anomaly baseline before play

### **Master Guide & Mod Settings Overhaul**  
The in-game configuration hub has been fully rebuilt for clarity and stability.

- **Centralized Configuration**  
  All master toggles for **Combat Damage**, **Medical Healing**, and **Core Survival** are now grouped into high-priority pages.
- **AN76 Integration**  
  Redundant Advanced Needs 76 menus have been removed. All system toggles (Needs, Hygiene, Takedowns, etc.) are now controlled directly through the Master Guide.

---

## 🗑️ Cleanup & Optimization

- **Redundancy Pass**  
  **True Damage** and **Scourge** have been removed. Combat remains lethal and high-stakes, but is now fully controlled through streamlined sliders within Anomaly’s core configuration.
- **Equipment Slot Limits**  
  Moved to **Optional**. Disabled by default while we coordinate with the mod author to resolve potential slot conflicts.

---

## 🐞 Bug Tracking

View all resolved issues and fixes for this release on the official tracker:  
https://github.com/orgs/Fallout-Anomaly/projects/50/views/1

---

## ❤️ Consider Endorsing

If you’re enjoying **Fallout Anomaly**, please consider endorsing the modlist on Nexus:  
🔗 https://www.nexusmods.com/fallout4/mods/74075  

*Note: Nexus requires downloading the file and waiting at least 15 minutes before endorsing.*





# Fallout Anomaly 0.5.9 — Full Changelog  2/1/2026

## Overview

Fallout Anomaly 0.5.9 is a major systems update focused on long-term stability, survival depth, and player agency. This version removes several legacy or problematic systems and replaces them with more robust, configurable frameworks. Progression, survival, inventory management, and world interaction have all been reworked to better support extended playthroughs and a harsher, more deliberate experience.

---

## Core Progression Changes

### S7 Skyrim-Style Leveling System

* Replaced the **Exceptional Perks** system with the **S7 Skyrim-style leveling framework**.
* Player progression is now driven by **skill usage** rather than traditional XP sources.
* Skills increase through use, and character levels are earned through skill growth.
* Optional **True Skyrim Mode** removes XP gain from quests, kills, crafting, and settlement building.
* Tagged skills receive improved starting values and faster early progression.
* Designed to slow overall progression and encourage specialization and planning.
* **S7 must be configured manually during startup prompts**. MCM Manager cannot apply these settings.

---

## Survival System Overhaul

### Removal of Damn Apocalypse

* **Damn Apocalypse has been fully removed** from the modlist.
* This decision was made due to complexity, instability, and overlap with newer systems.

### Advanced Needs Integration

* **Advanced Needs** is now the primary survival framework.
* Handles hunger, thirst, fatigue, and other survival mechanics.
* Modular design allows players to enable or disable individual systems.
* Survival mechanics have a much stronger impact on pacing, preparation, and risk management.
* **Manual configuration is required**:

  * Open the Advanced Needs MCM under the **Survival** category.
  * At minimum, the **Needs** module must be enabled.
  * Other modules are optional but strongly encouraged.
* Advanced Needs does **not** support automatic configuration via MCM Manager.

---

## Economy Changes

### Currency Rework

* **Removed military-grade cartridges as a currency system**.
* Reverted the economy back to **vanilla caps**.
* This change improves compatibility, balance, and long-term economic stability.

---

## Inventory & Carry Limits

### Weapon Slot Limit System

* Added a **slot-based inventory limit system** for:

  * Rifles
  * Pistols
  * Melee weapons
  * Grenades
  * Ammo
* Prevents hoarding by **blocking pickups** once slot limits are reached instead of forcing encumbrance micromanagement.
* If added mid-playthrough and the player is already over limits:

  * The player will be encumbered **only until brought back under the limits**.
* Items picked up past the limit are automatically dropped or returned to their source container.
* Vendor purchases that exceed slot limits remain on the counter until space is freed.
* Encourages deliberate loadouts and meaningful gear choices.
* Tutorial video for this system:
  [https://www.youtube.com/watch?v=iylPHK8kXvU&t=142s](https://www.youtube.com/watch?v=iylPHK8kXvU&t=142s)

---

## Hacking & Lockpicking Overhauls

### Hacking Changes

* Hacking is now **soft-gated** instead of perk-locked.
* You can attempt any terminal regardless of perks.
* Default settings make hacking difficult without perks.
* Players are expected to use:

  * Deduction
  * Dud removal
  * Attempt resets
* Resetting the minigame now has penalties.
* Terminal password count, lockout time, number of guesses, and reset behavior are fully configurable via MCM.
* Requires **F4SE and MCM**.

### Lockpicking Changes

* Lockpicking is now **progression-based** instead of hard-gated.
* You can attempt any lock regardless of Locksmith perks.
* Without perks:

  * Locks are harder to pick
  * Bobby pins break more often
* As Locksmith perks are acquired:

  * Locks become easier
  * Bobby pin break chance is reduced
* Optional setting to have **Locksmith01 govern Novice locks**.
* Affects:

  * Sweet spot size
  * Partial pick behavior
  * Break chance
* Includes presets and full MCM customization.
* Requires **F4SE and MCM**.

---

## Gas Mask System Changes

### Removal of Gas Mask of the Wasteland

* **Gas Mask of the Wasteland has been removed** due to excessive bugs and instability.
* Permission has been granted by the original author to reuse the **gas mask overlays**.
* A **new in-house gas mask overlay mod** is currently in development.
* This custom solution will be introduced in a future update once completed.

---

## Alternate Start System

### New Alternate Start

* Added a **brand new alternate start system**.
* Players can skip the vanilla intro and begin elsewhere in the Commonwealth.
* After selecting a start location, the player may briefly freeze.

  * This is expected behavior while scripts and injections finish loading.

---

## Optional Mods & Quality of Life

### Silent Protagonist

* **Silent Protagonist added**, enabled by default.
* Can be disabled at any time via the **MO2 Optional** section.

### Leaning

* Leaning is available as an optional feature.
* **Must only be enabled after leaving the starting area** to avoid issues.

---

## Stability & Fixes

* Large round of **bug fixes and stability improvements**.
* Removed or reworked systems that caused instability in long playthroughs.
* Improved script injection and startup handling.
* General balance cleanup across combat, progression, and survival systems.
* Focus on improving reliability for extended saves.

---

## Setup Notes & Requirements

* **S7 and Advanced Needs must be configured manually**.
* MCM Manager cannot apply these settings automatically.
* At minimum, the **Needs** module in Advanced Needs must be enabled.
* Other Advanced Needs modules are optional but strongly encouraged.
* Brief freezes during startup or teleport are expected while scripts load.

---
Test Updater

Test Updater 2

