### WORK IN PROGRESS. THIS PAGE IS UPDATED AS THE NEW VERSION COMES TOGETHER

# Fallen World - New Version Tracking

The next version of Fallen World is being rebuilt from a clean base instead of being patched on top of the old install. Every mod is being checked before it goes in: is it still maintained, is there a better or newer version, does it work on the game version we run, and does it have serious open bug reports? Anything that doesn't hold up is replaced or left out.

The new version stays on the **Old-Gen (1.10.163)** version of Fallout 4.

**Nothing below has been playtested yet.** Once the build is complete, it goes through a full test pass before release.

---

## Done So Far

### Full Audit of the Modlist

* Compared the new build against the current Fallen World release and the in-development Alpha to find every missing mod, missing master file, outdated version, and file conflict.
* Went through every open issue on the modlist tracker to see which ones still apply and what fixes them.
* No active plugin is missing a master file, and every plugin loads after the files it depends on.

### Core Frameworks

Added the core frameworks that other mods depend on:

* Papyrus Common Library
* Lighthouse Papyrus Extender
* Workshop Framework (with the Old-Gen script replacers)
* Backported Archive2 Support System
* Console Util
* Console Commands Extender

### Duplicate Frameworks Cleaned Up

Several frameworks were installed twice, so the game was loading two copies of the same plugin. We now keep one copy of each:

* RobCo Patcher
* Commonwealth Camera
* Pip-Boy Light Detection Fix
* Pip-Boy Radio Detection (the remaining copy is the Old-Gen build)

### Mods That Were Silently Not Loading

Ten mods in the list were Next-Gen builds that never load on Old-Gen, so the game was quietly skipping them. They have all been replaced with the correct Old-Gen builds:

* LooksMenu and LooksMenu Player Rotation (character creation)
* Base Object Swapper
* Spell Perk Item Distributor
* Baka Framework
* Crafting Highlight Fix
* Encounter Zone Recalculation
* Remove Ammo from Dropped Guns
* Perk Points Per Level
* Pipboy Tabs

### Fixes and Patches

Added 33 bug fixes and compatibility patches, including:

* NPC Drinking Fix, Outfit ReDress Fix, Sprint Jump AP Fix, and Sighted Weapon Accuracy Fix
* Overlay Framework Save Bug Fix
* Fallout 4 Particle Patch (no more glowing objects)
* Godrays Performance Fix Redux
* NPCs Travel fixes
* Weapon behavior ironsights movement fixes
* America Rising 2 compatibility patches for the Attachment Pack and XDI
* Vault Boy Coloured Animations XDI patch

Patches were only added when the mods they patch are actually in the list.

### Weapons and Armor

Added 54 weapon and armor mods, including:

* **Power Armor:** Hellfire X-03, MidWest Power Armor, T-65 (with East Brotherhood paint), T-49, Children of Atom Power Armor, M150 Institute Power Armor, Tumbajamba's Raider Power Armor, B-35C Heavy Brotherhood of Steel armor, and more
* **Armor and outfits:** America Rising 2 Enclave uniforms, Tumbajamba's Railroad Heavy, Gunner and Vault Leather armor, and a backpack rebalance
* **Weapons:** Pig's Wasteland Weaponry Best Of pack, AKs of the Wasteland, The All American, AER15, Accelerator, Glock 86, Laser RCW, Wattz 3000, X12 Plasmacaster, M72 Gauss Rifle, reworked Cryolator and Flamer, H&H Railway Rifle, Radium Rifle improvements, T6M launchers, and the Modern Weapon Replacer expansion

Also:

* Bolt Actions and Pump Actions now use their ESL versions to save plugin slots.
* Munitions Vanilla Ammo Addon is turned back on.
* Leftover plugin entries from weapon mods that are no longer installed have been removed.

### Left Out on Purpose

We left these out because of serious open bug reports or known problems:

* Super Mutant Equality (reload loop bug)
* Militarized Minutemen (open crash reports)
* Stimpaks Help You Breathe (can stop healing from working)
* Radiant Clouds and Fogs (crash on launch reports)
* Deadlier Deathclaws (deathclaws can become unkillable early on)
* True Grass and anything that depends on it

---

## In Progress

### NPCs, Combat and Survival

* Combat, AI, and companion improvements
* Fallen World Hardcore
* The in-house radiation overhaul

### Requested Additions

Mods are being added from the request list. These include a new HD texture pack that replaces the current 2K pack, a replacement for Uneducated Shooter, and new weather and world additions.

### UI and HUD

Reviewing the UI, HUD and economy mods, including the Fallen World Prisma UI systems.

---

## Planned

* **Precombines and Previs:** set up the previs rules first, so that world and visual mods don't break performance or cause flickering
* **World and Visuals:** world additions, lighting, weather, character visuals, and Synthetic Facelift patches
* **Leveled Lists:** add the new weapons and armor to the loot and vendor lists so they actually appear in the world
* **Version Updates:** move core mods to their latest Old-Gen releases, including Workshop Framework, Prisma UI, High FPS Physics Fix, Addictol, and Pip-Boy Light Detection Fix
* **Full Test Pass:** a full playthrough test before release
