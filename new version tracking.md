### WORK IN PROGRESS. THIS PAGE IS UPDATED AS THE NEW VERSION COMES TOGETHER

# Fallen World - New Version Tracking

The next version of Fallen World is being rebuilt from a clean base instead of being patched on top of the old install. Every mod is being checked before it goes in: is it still maintained, is there a better or newer version, does it work on the game version we run, and does it have serious open bug reports? Anything that doesn't hold up is replaced or left out.

The new version stays on the **Old-Gen (1.10.163)** version of Fallout 4.

**Nothing below has been playtested yet.** Once the build is complete, it goes through a full test pass before release.

---

## Coming Soon

### Workshop Rebuilt: Major Update

[Workshop Rebuilt](https://www.nexusmods.com/fallout4/mods/108055) is getting a new update packed with features. More details soon.

### Survival, Weather and Radiation Overhaul

Survival is getting a full overhaul built around my radiation mod. Weather and radiation will matter much more out in the wasteland, with new systems for:

* Temperature
* Wind
* Environmental conditions

More is planned on top of these.

---

## Done So Far

### Full Audit of the Modlist

* Compared the new build against the current Fallen World release and the in-development Alpha to find every missing mod, missing master file, outdated version, and file conflict.
* Went through every open issue on the modlist tracker to see which ones still apply and what fixes them.
* No active plugin is missing a master file, and every plugin loads after the files it depends on.

### Core Frameworks

Added the core frameworks that other mods depend on:

* [Papyrus Common Library](https://www.nexusmods.com/fallout4/mods/86222)
* [Lighthouse Papyrus Extender](https://www.nexusmods.com/fallout4/mods/71420)
* [Workshop Framework](https://www.nexusmods.com/fallout4/mods/35004) (with the Old-Gen script replacers)
* [Backported Archive2 Support System](https://www.nexusmods.com/fallout4/mods/81859)
* [Console Util](https://www.nexusmods.com/fallout4/mods/51951)
* [Console Commands Extender](https://www.nexusmods.com/fallout4/mods/47328)

### Duplicate Frameworks Cleaned Up

Several frameworks were installed twice, so the game was loading two copies of the same plugin. We now keep one copy of each:

* [RobCo Patcher](https://www.nexusmods.com/fallout4/mods/69798)
* [Commonwealth Camera](https://www.nexusmods.com/fallout4/mods/107225)
* [Pip-Boy Light Detection Fix](https://www.nexusmods.com/fallout4/mods/101467)
* [Pip-Boy Radio Detection](https://www.nexusmods.com/fallout4/mods/101682)

### Fixes and Patches

Added 33 bug fixes and compatibility patches, including:

* [NPC Drinking Fix](https://www.nexusmods.com/fallout4/mods/53980)
* [Outfit ReDress Fix](https://www.nexusmods.com/fallout4/mods/72657)
* [Sprint Jump AP Fix](https://www.nexusmods.com/fallout4/mods/73888)
* [Sighted Weapon Accuracy Fix](https://www.nexusmods.com/fallout4/mods/74004)
* [Overlay Framework Save Bug Fix](https://www.nexusmods.com/fallout4/mods/70251)
* [Fallout 4 Particle Patch - No More Glowing Objects](https://www.nexusmods.com/fallout4/mods/68599)
* [NPCs Travel - Fixes](https://www.nexusmods.com/fallout4/mods/89132)
* [Weapon Behavior Ironsights Movement Fixes](https://www.nexusmods.com/fallout4/mods/85053)
* [America Rising 2 - The Attachment Pack Compatibility Patch](https://www.nexusmods.com/fallout4/mods/80656)
* [XDI - America Rising 2 Patch](https://www.nexusmods.com/fallout4/mods/76204)
* [Vault Boy Coloured Animations](https://www.nexusmods.com/fallout4/mods/76518) (XDI patch)

Patches were only added when the mods they patch are actually in the list.

### Weapons and Armor: Complete

The full weapon and armor pass is done. 54 weapon and armor mods were added, including:

**Power Armor**

* [Hellfire X-03 Power Armor](https://www.nexusmods.com/fallout4/mods/26251)
* [MidWest Power Armor Revolution](https://www.nexusmods.com/fallout4/mods/79341)
* [T-65 Power Armor](https://www.nexusmods.com/fallout4/mods/49922) with the [East Brotherhood of Steel Paint](https://www.nexusmods.com/fallout4/mods/69532)
* [T-49 - Armor of the Storyteller](https://www.nexusmods.com/fallout4/mods/14581)
* [Children of Atom Power Armor](https://www.nexusmods.com/fallout4/mods/47586)
* [M150 Institute Power Armor HD Reboot](https://www.nexusmods.com/fallout4/mods/85947)
* [Tumbajamba's Raider Power Armor](https://www.nexusmods.com/fallout4/mods/68602)
* [Tumbajamba's Power Armor for Strong](https://www.nexusmods.com/fallout4/mods/10887)
* [Enemies Fear Power Armor](https://www.nexusmods.com/fallout4/mods/79662)
* [B-35C Heavy Brotherhood of Steel Armor](https://www.nexusmods.com/fallout4/mods/17247)

**Armor and Outfits**

* [America Rising 2 - Fashion of the Enclave](https://www.nexusmods.com/fallout4/mods/79886)
* [Tumbajamba's Railroad Heavy Armor](https://www.nexusmods.com/fallout4/mods/84146)
* [Tumbajamba's Gunner Armor Collection](https://www.nexusmods.com/fallout4/mods/87501)
* [Tumbajamba's Vault Leather Outfit](https://www.nexusmods.com/fallout4/mods/83151)
* A Fallen World backpack rebalance

**Weapons**

* [Pig's Wasteland Weaponry - A Best Of Pack](https://www.nexusmods.com/fallout4/mods/90801)
* [AKs of the Wasteland](https://www.nexusmods.com/fallout4/mods/94103)
* [The All American](https://www.nexusmods.com/fallout4/mods/85431)
* [AER15 Modern Laser Assault Rifle](https://www.nexusmods.com/fallout4/mods/47159)
* [Accelerator Plasma Energy Weapon](https://www.nexusmods.com/fallout4/mods/27127)
* [Glock 86 - Plasma Pistol](https://www.nexusmods.com/fallout4/mods/36358)
* [Laser RCW](https://www.nexusmods.com/fallout4/mods/92194)
* [Wattz 3000 mkII Laser Gun](https://www.nexusmods.com/fallout4/mods/87734)
* [X12 Plasmacaster](https://www.nexusmods.com/fallout4/mods/49918)
* [M72 Gauss Rifle](https://www.nexusmods.com/fallout4/mods/43442)
* [Cryolator Reworked](https://www.nexusmods.com/fallout4/mods/75764)
* [Flamer Resurgent](https://www.nexusmods.com/fallout4/mods/9049)
* [H and H Railway Rifle Redux](https://www.nexusmods.com/fallout4/mods/78302)
* [Modern Weapon Replacer - Combined Arms Expansion Pack](https://www.nexusmods.com/fallout4/mods/57157)

Also:

* [Bolt Actions of the Wasteland](https://www.nexusmods.com/fallout4/mods/102050) and [Pump Actions of the Wasteland](https://www.nexusmods.com/fallout4/mods/99991) now use their ESL versions to save plugin slots.
* The Vanilla Ammo Addon for [Munitions - Ammo Expansion Project](https://www.nexusmods.com/fallout4/mods/66051) is turned back on.
* Leftover plugin entries from weapon mods that are no longer installed have been removed.

### NPCs, Combat and Creatures

Added 45 mods covering combat, AI, companions, creatures and survival.

**Combat and AI**

* [Combat AI Empowered](https://www.nexusmods.com/fallout4/mods/72678)
* [Tactical Courser](https://www.nexusmods.com/fallout4/mods/43435), [Deadly Coursers](https://www.nexusmods.com/fallout4/mods/88843) and [CROSS Courser Strigidae](https://www.nexusmods.com/fallout4/mods/28009)
* [Improved Lighting Ballistics](https://www.nexusmods.com/fallout4/mods/47758)
* [Stealth and Detection System](https://www.nexusmods.com/fallout4/mods/62140) and [Stealth Effect Tune](https://www.nexusmods.com/fallout4/mods/59631)
* [AnotherOne Brutal Death](https://www.nexusmods.com/fallout4/mods/71356) and [EVB with Dismemberment](https://www.nexusmods.com/fallout4/mods/59143)
* [Distortion - Combat Music Replacer](https://www.nexusmods.com/fallout4/mods/54077)
* Fallen World Combat

**NPCs and Companions**

* [Heather Casdin - A Unique Companion Experience](https://www.nexusmods.com/fallout4/mods/23273)
* [Nick Valentine - Synthetic Facelift 2.0](https://www.nexusmods.com/fallout4/mods/74266) and [Valentine Jaw Sync](https://www.nexusmods.com/fallout4/mods/42985)
* [NPCs Use Items](https://www.nexusmods.com/fallout4/mods/73717) and [NPC Can Heal](https://www.nexusmods.com/fallout4/mods/72177)
* [Defective Synths](https://www.nexusmods.com/fallout4/mods/61040)
* [More Natural Idle Animation NPCs](https://www.nexusmods.com/fallout4/mods/88734)
* [Disable Companion Collision](https://www.nexusmods.com/fallout4/mods/76454)
* [KS Hairdos Conversions](https://www.nexusmods.com/fallout4/mods/45373)
* [CROSS Institute Expeditionary Suit](https://www.nexusmods.com/fallout4/mods/30857)

**Creatures**

* [FallEvil - Zombie Mega Pack](https://www.nexusmods.com/fallout4/mods/59293)
* [Feral Nights](https://www.nexusmods.com/fallout4/mods/52449) and [Feral Infestations](https://www.nexusmods.com/fallout4/mods/65406)
* [Monsterum - Deathclaw Sounds Rework](https://www.nexusmods.com/fallout4/mods/52771)
* [Bovine Intervention - Brahmin Overhaul](https://www.nexusmods.com/fallout4/mods/96476) and [Brahmin Variations](https://www.nexusmods.com/fallout4/mods/59130)
* [Friendly Radstags](https://www.nexusmods.com/fallout4/mods/76561)

### Survival

* The Fallen World radiation overhaul
* [Lucky 7 - Hardcore Start](https://www.nexusmods.com/fallout4/mods/69381)
* [Immersive Water Purification](https://www.nexusmods.com/fallout4/mods/17486) and [Drinking Water Retexture](https://www.nexusmods.com/fallout4/mods/81908)
* [Medical Asset Pack](https://www.nexusmods.com/fallout4/mods/53965), [Russian Stimpack Replacer](https://www.nexusmods.com/fallout4/mods/55170) and [Retextured Chems v.2](https://www.nexusmods.com/fallout4/mods/18867)
* [Less Food in Exteriors](https://www.nexusmods.com/fallout4/mods/69509)
* [No More Useless Beds](https://www.nexusmods.com/fallout4/mods/86751)
* [Running Breathing](https://www.nexusmods.com/fallout4/mods/59322) and [Better Low and Critical Health Heartbeat](https://www.nexusmods.com/fallout4/mods/53471)
* [No Water Jump](https://www.nexusmods.com/fallout4/mods/75100)
* [More Menacing Rad Thunder Sounds](https://www.nexusmods.com/fallout4/mods/79041)
* Fallen World flashlight disable for Metro and radiation gear

### World and Travel

* [Retro Aesthetics Institute Overhaul](https://www.nexusmods.com/fallout4/mods/87348)
* [Sailboat Abode - A Fast Travel Ship](https://www.nexusmods.com/fallout4/mods/64739)
* [Climbable Ladders](https://www.nexusmods.com/fallout4/mods/60143)

### Left Out on Purpose

We left these out because of serious open bug reports or known problems:

* [Super Mutant Equality](https://www.nexusmods.com/fallout4/mods/86503): reload loop bug
* [Militarized Minutemen](https://www.nexusmods.com/fallout4/mods/29853): open crash reports
* [Stimpaks Help You Breathe](https://www.nexusmods.com/fallout4/mods/46361): can stop healing from working
* [Radiant Clouds and Fogs](https://www.nexusmods.com/fallout4/mods/735): crash on launch reports
* [Deadlier Deathclaws](https://www.nexusmods.com/fallout4/mods/13822): deathclaws can become unkillable early on
* [True Grass](https://www.nexusmods.com/fallout4/mods/23469) and anything that depends on it

---

## In Progress

### Brand New Quests

Brand new Fallen World quests are in development. More details will be shared as they come together.

### Requested Additions

Mods are being added from the request list. These include a new HD texture pack that replaces the current 2K pack, a replacement for Uneducated Shooter, and new weather and world additions. Links will be added here once each one is in.

### UI and HUD

Reviewing the UI, HUD and economy mods, including the Fallen World Prisma UI systems.

---

## Planned

The goal for this version is to cover every part of Fallout 4. Here is the plan, area by area.

### Quests and Story

* [Lima Detachment](https://www.nexusmods.com/fallout4/mods/29042) with [America Rising 2 Integration](https://www.nexusmods.com/fallout4/mods/77581)
* [America Rising 2 - Delayed Start](https://www.nexusmods.com/fallout4/mods/92318)
* [CROSS Brotherhood Recon](https://www.nexusmods.com/fallout4/mods/27418)
* [CROSS Chosen of Atom](https://www.nexusmods.com/fallout4/mods/37820) and [Church of Atom Overhaul](https://www.nexusmods.com/fallout4/mods/26173)
* Fallen World's own new quests (see above)

### Settlements and Workshop

* The [Workshop Rebuilt](https://www.nexusmods.com/fallout4/mods/108055) update (see Coming Soon)
* [Settle Everywhere](https://www.nexusmods.com/fallout4/mods/37658)
* [Forgotten Pump House](https://www.nexusmods.com/fallout4/mods/84128)
* [The Top Floor Loft](https://www.nexusmods.com/fallout4/mods/19947) with [The Top Floor Loft Enhanced](https://www.nexusmods.com/fallout4/mods/87239)
* [The Rebuild Collection - Shared Resources](https://www.nexusmods.com/fallout4/mods/80606)

### Survival, Weather and Radiation

* The full survival overhaul built on the Fallen World radiation system, with temperature, wind and environmental conditions (see Coming Soon)

### World, Locations and Previs

* Set up the precombine and previs rules first, so that world mods don't hurt performance or cause flickering
* World additions and location overhauls that pass the previs check
* LOD improvements

### Visuals, Lighting and Characters

* Lighting and weather visuals
* Character visuals and hair, with Synthetic Facelift patches for companions and NPCs
* The new HD texture pack

### Weapons, Armor and Loot

* Add every new weapon and armor piece to the loot, vendor and NPC leveled lists so they actually appear in the world
* Balance pass on damage, armor values and ammo

### Economy and Progression

* Review of loot, vendors, caps and perk progression mods

### UI and HUD

* Finish the UI and HUD pass, including the Fallen World Prisma UI systems

### Stability and Performance

* Update core mods to their latest Old-Gen releases, including Workshop Framework, Prisma UI, High FPS Physics Fix, Addictol, and Pip-Boy Light Detection Fix
* Crash and stability review of the full load order

### Testing

* A full playthrough test before release
