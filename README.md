# game-mod-f22

<b>Magic Mod for Quake 4</b>


This mod aims to add a spellcasting system into Quake 4, letting the player cast combinations of elemental magic to create unique spell effects. 
Currently, there are four elements that will be implemented: rock, fire, ice, and lightning. 
Different inputs of these elements will produce unique combination spells - for example, rock and fire could make a meteor-like effect.
This system is inspired by another game called Magicka.
There will be a mana system, magical themed pickups that give certain effects (buffs, restore mana, etc.).
To add some difficulty into the game, enemies and players will have resistances and weaknesses to different types of magic. Enemies will also deal elemental damage.
The player will be able to have different kinds of robes, armor, etc. to change their affinities.
<br><br>

Planned features:

-Replace weapons with elemental casting system (10 spells/effects that can be cast through the system)

-Add elemental affinities to monsters

-Magical themed pickups

-Mana system (to replace ammo)

-Player gets affinities (armor, robes, cloaks, etc.)

<br> <i>how to test each deliverable</i>

-A desktop shortcut to automatically launch your mod: included in this repo, just download and run

-A README.md file in your github repository explaining what your mod is, what has been, and HOW to test each deliverable: this document

-Modified Main Menu: seen when game is launched

-Modified Heads Up Display (HUD) to reflect a key feature of your mod: seen when game is started

-An In-Game Help screen explaining your mod changes: press 'H' key when in game

<br><br>
-Replace weapons with elemental casting system (10 spells/effects that can be cast through the system): use 2, 3, 4, 5 number keys to cast different elements (2 = fire, 3 = ice, 4 = rock, 5 = lightning)

-Add elemental affinities to monsters: can spawn a monster_strogg_marine (or berserker, grunt, tank) and test different spells against it (fire-fire vs. ice-ice); difference is also displayed in console 

-Magical themed pickups: in console, type summonPickup x, where x can be one of the following: item_mana_pickup, item_rock_boost, item_ice_boost, item_lightning_boost, item_fire_boost; then, run over the spawned pickup

-Mana system (to replace ammo): change can be seen when using spells or equipping mana ring

-Player gets affinities (armor, robes, cloaks, etc.): use 'u', 'i', 'o', 'p' keys to switch between different equipment to give different boosts, resistances, weaknesses (u = mana ring, i = armor, o = robe, p = cloak)

