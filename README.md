# UT3-DM_Dungeon
Unreal Tournament 3 custom map, single player vs AI; build in Unreal Editor 3, Kismet &amp; UnrealScript

[Demo](https://www.youtube.com/watch?v=HS1OGlrDK3g)
###FILES

**CustomMaps**

 - DM-a3v03.ini               //General map info for UT3 to display (name, author, gamemodes, image, etc..)
 - DM-a3v03.ut3               //Level
 - DM-a3v03_LOC_int.upk       //Localization file
 - DM-Dungeon.upk             //Custom model
 - DM-a3v03 Central Hall.bmp  //Screenshot

**Script**

 - credits.txt	            //Referenced scripts
 - FirstMutator.u             //Custom pawn
 - SeqAction_LevelComplete.u  //Game Ended kismet action

###INSTALLATION and SETUP
To install, move the CustomMaps and Script folders to:
Documents\My Games\Unreal Tournament 3\UTGame\Published\CookedPC\

To play->open the game->instant action-> DM-a3v03->setup a team deathmatch with 1 player(you)

*Note: This was developed on UT3 - Patch 4 + Titan pack, because of this, there may
be problems opening in the editor or launching in game if you have a different version of UT3

*The game plays better in the editor. However in the editor, the bots' ai is constrained to DeathMatch AI, so they
will kill each other (since there are no teams in death match)

*You may need to recompile the scripts to get them working, in which case follow the instructions here for both 
.u files
http://forums.epicgames.com/showthread.php?t=724098
