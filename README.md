- https://github.com/Zoust/LOST-PATH-0.5.9.4330-Eng-Translation/tree/v0.2

# LOST-PATH-0.5.9.4330-Eng-Translation

-

Mod link : https://www.moddb.com/mods/lost-path

-

!! 			Put ALL content from archive in game ROOT folder, not in gamedata 		 !!

!!!								Overwrite files when prompted						!!!

!!						Don't use the old translation, just this one				 !!

!!!									Good hunting Stalker							!!!



Zoust
	
-

Made using Stalker Dialog 'XML' Helper, by Stalkerstein (on www.gsc-game.com forums)

-

Google translated readme files : 	

//-----------------------------------------
	  Lost Path 0.5.9.4330 	  by b4d1k
//-----------------------------------------

Please write to the group about the found bugs and exploits. The more information, the better.

You selected RePack without compression. The installation time is 1.5 - 5 minutes. Requires a minimum of resources, but the weight of 26GB makes itself felt.

After installing the repack, you must put the files from the Patch folder in the root of the game, so that the _mods folders merge.
For correct work, I advise you to install an update from the Update folder. Check the current version in the client's version.ini file
and updates, if not coincide - be updated!

I advise you not to use SWTC CoC, since this addon causes strong overexposures and distortion of normal colors of objects. how
the alternative is better to use "Skyboxes (put 1)" before the addon with the name "(put 3)" - this adaptation of SkyGod to Lost Path,
or any of the others provided in the _mods folder. Have a good game!

USE OF THIRD-GAME ARCHIVES IS PROHIBITED.
USE FILES THAT ARE EXTENDED BY THE AUTHOR.

[0.5.9.394]
- Added the ability to control AI hostile grouping using perk
- The ability to control the AI ​​of your grouping using perk is added
- Fixed simulation for new management, new algorithms for Alife.

[0.5.9.391]
- Created units are registered in smart and simulations
- Added the ability to initial group management * "Faction Commander" (using materials from FC 2.51 final for CHN)
- Added perks of perception "Your man" for the possibility of calling reinforcements. Each level raises the level of called squads **.

* - The mechanics of creating squads is similar to the Faction Commander for the Clear Sky. In a smart to the player, if possible, money and perk
the squad will spawn. And more than the capacity of a smart can not be ensured. Even if the smart does not belong to you, you can
cause reinforcements in the smart closest to you. If there are enemies there, reinforcements will help you. If you are waiting for reinforcements, then
reinforcement will reduce the waiting time for this very reinforcement.

** - Available levels give the opportunity to call beginners, experienced and veterans according to the level of perk.

[0.5.9.386]
- The caches created by the player do not have a loot

[0.5.9.385]
- Update "Flat UI" interface
- Fix the weapon's launch when hovering, if the slot of the weapon is empty
- New fonts electron_18, roboto_16, ui_font_arial_21
- Random filling of caches with loot *
- Increased the number of required points for pumping good luck. It was: 16. It became: 83. Points are bought and pay off from the caches.
- EFT-style inventory
- Small corrections in the behavior of AI NPC
- Volumetric light from NPS flashlights
- eft_inventory_items_using - number of items used
- eft_inventory_ammo_box_count - number of cartridges in packs

* - Loot is now generated not at the start of the game as it was before (initially counted the number of caches in the zone, after which the randomly filled 50%
from the caches when creating the game). Now, when creating a game, the caches are not created and the loot in them appears already when the hiding place is hidden. Capacity
(the quantity and quality of things inside) depends on the level of the player, the level of his luck (by default, luck = 0, so at least to level it
you just need to download) and some basic part (which is available immediately so that the caches are not empty). The higher the level and the luck the more things you
you can find. Plus, the more expensive things can come across.

[0.5.9.365]
- New "Flat UI" interface
- Automatically disable immortality when downloading saves

[0.5.9.360]
- Engine processing filters and backpacks
- Fixed a bug with the need to open and close inventory if the helmet was removed and the filter remained in the slot (similar situations with new slots are fixed)
- Test mode "after death" with zeroing of inventory
- Improved RPG interface

[0.5.9.354]
- Fixed growl of cats (sounds and config from LR)
- eft_inventory_name - display the name of the item
- eft_inventory_ammo - display the number of cartridges
- eft_inventory_ammo_type - display of type of cartridges

[0.5.9.345]
- Random bearing
- Horizontal recoil
- Display the number of cartridges in the store
- Display the number of cartridges in weapons
- Display of item names
- Displays the caliber of weapons
- Output of available add-ons in the description of weapons with icons
- Change of gun sights in inventory
- Change of sight even if some sight is already in place
- A new class for ADDON addons with a minimum number of parameters (as a universal one can be used)
- Redone simulation: units on vacation and not fighting with anyone can move to other smarts, if at the moment in the smart people more than half of the maximum number. The frequency of updating the units of new targets is adjusted from the settings. In doing so, they can go to any smart, check their own or go explore the Zone.
- Removed the error of launching the original launcher.

[0.5.9.301]
1. New strong impact (beta version)
2. Very accurate weapons (offset by strong returns)
3. Glock 18C (in the spa wpn_glock_auto)

[0.5.9.300]
1. Fixed a critical engine error causing the weather to crash.
2. Added quests from PM (working only a couple of pieces, killing stalkers in development).
3. Fixed issuance of the award from Sidorovich, receiving now immediately.
4. Fires stories have been fixed, now stalkers began to tell jokes, complain about life or entertain with songs.
5. Added addon TRX - Global Weather 2.0 from throbits.
6. Added addon OL Addon (Oblivion Lost Style) from bloodshot12.
7. Added rollback to version 0.5.007 through the manager.
8. Added a script that verifies that the tagged NPS is on and loads the desired config when the game is loaded.

[0.5.9.299]
- New icons for RPG system
- Added 5 perks for perception
- Named NPCs added to the most active members of the group

[0.5.9.284]
Editing changes:
1. Changing artifact stats through engine commands
2. Restoration of old stats from PM (not used in calculating stat GG)
3. Saving changed stats to no packages (only artifacts)
4. The ability to write to the configuration of the artifact only the required parameters
5. Partially cleaned network code and checks for a single
6. HitType synchronization with the display of the stats
7. Output of stats with 2 decimal places
8. Fix the statues of artifact stats
9. Displaying the properties of the character is not from 0 to 99, but from -999 to +999
10. The player's weight is taken into account only from the backpack, in the slots the gear is not counted.
11. Carrying out a separate variable of the number of rounds and adding to it, if an upgrade is made (needed for the feature "+1 cartridge")
12. Correct weight calculation for trunks with stropping sights (slider, not config)
13. Disconnection of the truck during the ejection
14. Console commands:
- hud_shoc (the little man's image)
- hud_slots_info (infa about backpack and other slots)
- hud_crosshair_circle (enable / disable round sight)
- csky_rank (displaying rank by a picture or text after restarting the game)
15. +1 cartridge, if the weapon is loaded (alya battles, you need to register one_plus_ammo for the operation)
16. 20 slots for artifacts
17. A separate class for a backpack
18. Reading ONLY the necessary parameters from sections of artifacts, armor, helmets:
If the parameter is zero, you can not write it, the engine will nullify it. Now only non-zero parameters are written.
Plus, a complete rejection of the absorber sections, since the parameters of the art are written in the artifact section.
19. Dilated slots for batteries and filters
20. Batteries through the engine
21. Backpacks through the engine
22. Working gears in the menu
23. Optional thin from PM
24. Fix the duplication of music in the main menu
25. Fix the preservation of client objects (Shoker)
26. Fix the blurry fonts on DX10 + (Forser)
27. Shadow from the grass (KD & nikira_nz1986 & Forser)
28. Correction of grenade scrolling (Nanobot)
29. Edit the position of fire for the actor (v2v3v4)
30. Fix effector recharge (SkyLoader)
31. Calculation of the weight of the weapon in the light of the current sight (scopes_name is entered for the scopes of the sights, counting goes on it).
32. If the sound has a bad ogg comment (! Invalid ogg comment), then it will be assigned a basic set of parameters for the ability to play the sound (there will be no more entries in the log).
33. If the game does not find a sound, then it writes to the console like textures, but does not crash.
34. Added busting over the backpack iterate_ruck similar to iterate_inventory
35. Added a search for the belt iterate_belt similar to iterate_inventory
36. Added functions that return the coordinates of the item's icon (Works only for CInventoryItem):
- inv_grid_x
- inv_grid_y
37. Added function for NPC set_money (), which allows the script to set a certain amount of money for it (it closes the exploit with endless loot of money from traders.) Call: npc: set_money (int money))

Gameplay:
1. Weapons become more accurate
2. Different exoskeletons have different protection parameters
3. The zuma became more realistic, so for some weapons, they may be absent or very insignificant
4. Changed the inventory of the protagonist
5. Fixed a bug with the quest to search for several items (you could lay out all the items except one as soon as the task went into the phase of the assignment and did not pass all the items)
6. Added addon TRX Dynamic News [need translation] (Tronex)
7. Added addon TRX FM (Tronex)
8. Displaying information about pumping on the screen
9. Mnogogvladkovaya pumping system GG (5 characteristics, 23 perks). Now without pumping certain skills you can not use some items, weapons and armor samples ...


This repack includes a fully working client
with version 0.5.007 without having to patch it
separately.

Also in this repack there is an OVT version of the next
update under the working title "build 296".
You can see the list of changes below.

The _mods folder contains optional additions to the
game. Also do not forget to visit the tab
"Mod settings", where you can more flexibly configure
game process. I advise not to use SWTC CoC because
that there wild outbreaks sometimes happen + it is necessary through
console configure lumscale.

More details about the modifications in the official group:
vk.com/lost_pafos

Using all my know-how in a supporter
projects is prohibited. Any attempt to copy or
"pizdings" will be regarded as theft.

Collaboration with third-party developers on
mutually beneficial soil is only welcomed.

With Respect, Draco.


//-----------------------------------------
  LIST OF CHANGES	BUILD 296
//-----------------------------------------


1. Changing artifact stats
set_af_additional_weight 
set_af_rank 
set_af_cost 
set_af_inv_weight 
set_af_inv_x 
set_af_inv_y 
get_af_level 
get_af_type 
get_af_anom 
set_af_level 
set_af_type 
set_af_anom 
set_af_name 
set_af_name_short 
set_af_descr 
set_art_radiation 
set_art_burn 
set_art_strike 
set_art_shock 
set_art_wound 
set_art_telepation 
set_art_chemistry 
set_art_explosion 
set_art_fire_wound 
get_art_radiation 
get_art_burn 
get_art_strike 
get_art_shock 
get_art_wound 
get_art_telepation 
get_art_chemistry 
get_art_explosion 
get_art_fire_wound 

2. Restoration of old stats from PM (not used in calculating stat GG)
3. Saving changed stats to no packages (only artifacts)
4. The ability to write to the configuration of the artifact only the required parameters
5. Partially cleaned network code and checks for a single
6. HitType synchronization with the display of the stats
7. Output of stats with 2 decimal places
8. Fix the statues of artifact stats
9. Displaying the properties of the character is not from 0 to 99, but from -999 to +999
10. The player's weight is taken into account only from the backpack, in the slots the gear is not counted.
11. Carrying out a separate variable of the number of rounds and adding to it, if an upgrade is made (needed for the feature "+1 cartridge")
12. Correct weight calculation for trunks with stropping sights (slider, not config)
13. Disconnection of the truck during the ejection
14. Console commands:
- hud_shoc (the little man's image)
- hud_slots_info (infa about backpack and other slots)
- hud_crosshair_circle (enable / disable round sight)
- csky_rank (displaying rank by a picture or text after restarting the game)
15. +1 cartridge, if the weapon is loaded (alya battles, you need to register one_plus_ammo for the operation)
16. 20 slots for artifacts
17. A separate class for a backpack
18. Reading ONLY the necessary parameters from sections of artifacts, armor, helmets:
If the parameter is zero, you can not write it, the engine will nullify it. Now only non-zero parameters are written.
Plus, a complete rejection of the absorber sections, since the parameters of the art are written in the artifact section.
19. Dilated slots for batteries and filters
20. Batteries through the engine
21. Backpacks through the engine
22. Working gears in the menu
23. Optional thin from PM
24. Fix the duplication of music in the main menu
25. Fix the preservation of client objects (Shoker)
26. Fix the blurry fonts on DX10 + (Forser)
27. Shadow from the grass (KD & nikira_nz1986 & Forser)
28. Correction of grenade scrolling (Nanobot)
29. Edit the position of fire for the actor (v2v3v4)
30. Fix effector recharge (SkyLoader)
31. Calculation of the weight of the weapon in the light of the current sight (scopes_name is entered for the scopes of the sights, counting goes on it).
32. If the sound has a bad ogg comment (! Invalid ogg comment), then it will be assigned a basic set of parameters for the ability to play the sound (there will be no more entries in the log).
33. If the game does not find a sound, then it writes to the console like textures, but does not crash.
34. Added busting over the backpack iterate_ruck similar to iterate_inventory
35. Added a search for the belt iterate_belt similar to iterate_inventory
36. Added functions that return the coordinates of the item's icon (Works only for CInventoryItem):
- inv_grid_x
- inv_grid_y
37. Added function for NPC set_money (), which allows the script to set a certain amount of money for it (it closes the exploit with endless loot of money from traders.) Call: npc: set_money (int money))

Launcher:
1. Preparation for the selection of the renderer in the launcher launch phase
2. If you put the key in the start line -r2a -r3 -r4, then the game will start in the selected renderer.

Gameplay:
1. Weapons become more accurate
2. Different exoskeletons have different protection parameters
3. The zuma became more realistic, so for some weapons, they may be absent or very insignificant
4. Changed the inventory of the protagonist
5. Fixed a bug with the quest to search for several items (you could lay out all the items except one as soon as the task went into the phase of the assignment and did not pass all the items)
6. Added addon TRX Dynamic News [need translation] (Tronex)
7. Added addon TRX FM (Tronex)
8. Displaying information about pumping on the screen
9. Mnogogvladkovaya pumping system GG (5 characteristics, 23 perks). Now without pumping certain skills you can not use some items, weapons and armor samples ...

Tinctures:
- You can change the icons on the map in the mod settings -> Old map display, after which you need to make a save-load
- You can change NPC activity in the mod settings -> Spawn attack / defense time in games. min, 1 game minute = 6 real seconds, save-load.
- Customize the thinness with the following commands:
- hud_shoc (the little man's image)
- hud_slots_info (infa about backpack and other slots)
- hud_crosshair_circle (enable / disable round sight)
- csky_rank (displaying rank by a picture or text after restarting the game)

Notes:
- Awards are taken from mentors at any base
