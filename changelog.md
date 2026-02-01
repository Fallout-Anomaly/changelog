
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


