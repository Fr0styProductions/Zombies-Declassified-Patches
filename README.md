# Zombies-Declassified-Patches
Zombies Declassified-Patches is a bug fix for the release of ZD/Zombies Declassified which is a bo2 dlc 5 port to black ops 2 plutonium this fixes most of the bugs in the current releases!

# Features:
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 - Kino Grief
 - Kino Turned
 - Bug Fixes For Multiple Maps
 - No Man's Land Gamemode on Moon
 - New Map Art for Kino
 - New Map Art for Five
 - Fixed Map art For Moon
 - Fixed Map art For Shangri-La
 - Fixed Map art For Ascension
 - Solo/Any Player EE on Moon
 - Solo/Any Player EE on Ascension
 - Solo/Any Player EE on Shangri-La
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Installation:
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. Close the game (if you have it opened already).
2. Open Run (Windows key + R), paste this in and press OK:   %LOCALAPPDATA%\Plutonium\storage\t6\
3. Copy the 3 folders inside the zip:  mods, raw, usermaps
4. Paste them into the folder that Run opened. Say YES to replace files.
5. Start the game and load DLC5 as normal.
# That's it. Zombies Declassified (Logo2K's DLC5) must already be installed - it is not included.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Uninstallation:
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. Close the game.
2. Open Run, paste this in and press OK:   %LOCALAPPDATA%\Plutonium\storage\t6\mods\dlc5\
   Delete:  mod.ff, mod_patch.ff, mod_patch.ipak,
            dlc5_bo1vox.english.sabs, dlc5_turnedvo.english.sabs, dlc5_ballista.all.sabl,
            ui_mp\t6\menus\privategamelobby_project.lua,
            clientscripts\mp\zombies\_zm_weap_black_hole_bomb.csc,
            maps\mp\zombies\_zm_weap_black_hole_bomb.gsc
   (Do NOT delete mod.json, mod_load.ff or mod_load.ipak - those are Logo2K's.)
3. Open Run, paste this in and press OK:   %LOCALAPPDATA%\Plutonium\storage\t6\raw\
   Delete every file from the zip's raw folder:
            raw\scripts\zm\  - all the zzz_ files from the zip
            raw\ui\t6\mainlobby.lua  and  raw\ui_mp\t6\hud\scoreboard.lua
            raw\maps\mp\gametypes_zm\  - zgrief.gsc, zmeat.gsc, zcleansed.gsc
            raw\maps\mp\zombies\  - _zm_game_module_meat.gsc, _zm_game_module_utility.gsc,
                                    _zm_game_module_meat_utility.gsc, _zm_turned.gsc
            raw\clientscripts\mp\gametypes\  - zgrief.csc, zcleansed.csc
4. Run the Zombies Declassified updater (or reinstall DLC5) to put back the map patch files the zip replaced
   (mods\dlc5\maps, mods\dlc5\scripts, the spikemore scripts, and the usermaps scripts).
# That's it, it should be finished!
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Made By Fr0sty/<https://guns.lol/fr0s_ty_>

# VIDEOS MADE WITH THESE PATCHES HAVE TO HAVE MY CREDITS IN THEM "@fr0sty_7952 on Youtube, @fr0s_ty_ on Discord, <https://guns.lol/fr0s_ty_>" OR THEY WILL BE TAKEN DOWN.
