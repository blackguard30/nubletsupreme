Small gameplay, utility, and development support mods for SC:FA, SC2, and Demigod.

##  ##
####  ####
# Supreme Commander 2 #

---

## SC2: Mod Support Minimod ##
[Download Version 7](http://nubletsupreme.googlecode.com/files/_modsupport_v7.scd)

Allows any number of mods to co-exist by enabling non-destructive hooking of original game files.  Supports campaign mods.  Requires the DLC for skirmish/multiplayer mods, although campaign mods will work without the DLC.

See the [thread](http://forums.gaspowered.com/viewtopic.php?f=19&t=50454) on the GPG forums for more information.

---

## SC2: Campaign Research Unlock ##
[Download](http://nubletsupreme.googlecode.com/files/_campaign_unlock.scd)

Unlocks all non-objective research in the single-player campaign missions.  Requires the Mod Support Minimod to function, but works without the DLC.

See the [thread](http://forums.gaspowered.com/viewtopic.php?f=7&t=50993) on the GPG forums for more information.

---

## SC2: Slow Research ##
[Download Version 1](http://nubletsupreme.googlecode.com/files/_slowresearch.scd)

Reduces all sources of research income and production, including combat experience, by roughly 1/2.  Provides a framework for easy customization.
Requires the SC2 DLC and the Mod Support Minimod to function. Fully compatible with all other mods, including destructive or exclusive mods.

See the [thread](http://forums.gaspowered.com/viewtopic.php?f=7&t=50473) on the GPG forums for more information.

---

## SC2: Massive Conversion ##
[Download Version 3](http://nubletsupreme.googlecode.com/files/_massiveconversion_v3.scd)

Doubles the size, cooldown, and explosion damage of Mass Convertors, quadruples their cost and build time, and expands their explosion blast radius by 50%, and lowers their output to 50 mass for 1000 energy (from 250 for 2500).

To soften the blow of these changes and reduce needed micromanagement with the longer cooldown and lower payoff, Mass Converters now have an automatic conversion mode that can be toggled off and on at will.

Requires the Mod Support Minimod v4 or later to function.  It is compatible with almost all other mods, although it will override the Mass Conversion ability settings of the Community Balance Patch.

See the [thread](http://forums.gaspowered.com/viewtopic.php?f=7&t=50475) on the GPG forums for more information.

---


##  ##
####  ####
# Forged Alliance #

---

## FA: Rock, Paper, Scissors ##
[Download Version 1.1](http://nubletsupreme.googlecode.com/files/RockPaperScissors_1.1.zip)

A support mod that enables complex per-armortype and per-category damage multipliers on a weapon by weapon basis, providing a robust framework for creating a rock-paper-scissors balance mod for FA with minumum effort and maximum precision.

See the included readme for much more detailed information.

---

## FA: SafeReload ##
[Download Version 2.0](http://nubletsupreme.googlecode.com/files/SafeReload2.0.zip)

Enables better, faster mod development by fixing many problems with blueprint reloading.

  * Prevents ModBlueprints from crashing the game or rendering blueprints/objects unusable during a reload.

  * Enables successful reloads of single- and multi-blueprint merge files with /EnableDiskWatch by pre-loading their originals.

  * Re-applies other mods' merges to blueprint(s) you're editing and reloading in mod load order, whether an original or a merge.

  * Filters out orphaned blueprint merges during the initial loading process, and logs their bpids and file paths.

---

## FA: Mod Script Hooking ##
[Download Version 2.0](http://nubletsupreme.googlecode.com/files/Modhook2.0.zip)

Not so much a mod itself as a script for use in other mods, this hook allows the import function to hook mod-specific files that did not exist in FA - something that is otherwise impossible.

This allows for all manner of mod-on-top-of-mod scripting possibilities, and opens some new script compatibility avenues as well.  See the [thread](http://forums.gaspowered.com/viewtopic.php?t=41379) on the GPG forums for a better explanation.

---

## FA: No Allied Collision ##
[Download Version 1](http://nubletsupreme.googlecode.com/files/NoAlliedCollision.zip)

Causes weapons with CollideFriendly off to pass through allied shields and units just as they pass through your own.  Does not affect weapons with CollideFriendly on, which will already impact your own shields/units.

---

## FA: No Engineers ##
[Download Version 1.1](http://nubletsupreme.googlecode.com/files/NoEngineers_1.1.zip)

Makes all mobile engineering units other than ACUs and SCUs unbuildable, and allows ACUs to construct all T1 structures.

---

## FA: Double Strength ##
[Download Version 1.1](http://nubletsupreme.googlecode.com/files/DoubleStrength_1.1.zip)

Multiplies all T1-T3 unit costs, hitpoints, regen, and shield stats by 2.  ACUs, SCUs, Experimentals, and enhancement costs are excepted by default, but can be enabled by changing flags at the top of hook\lua\system\Blueprints.lua.

---

## FA: Buildable ACUs ##
[Download Version 1.3](http://nubletsupreme.googlecode.com/files/BuildableACUs_1.3.zip)

  * **Allows ACUs to be constructed at Quantum Gates.**  Build time and energy cost are tweaked slightly for gameplay and cosmetic purposes, and can be adjusted easily by editing the values at the top of /BuildableACUs/hook/lua/system/Blueprints.lua.
  * **Compatible with any version of Blackops ACUs.**  If present, only Blackops ACUs units will be constructable.

---


##  ##
####  ####
# Demigod #

---

## DG: Tower Rewards ##
[Download Version 1](http://nubletsupreme.googlecode.com/files/TowerRewards.zip)

Awards experience and gold for destroyed structures.

---
