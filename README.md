# Macha-Server

Pack version: 3.0.0
Minecraft version: 1.16.5
Forge version: 36.0.46

   

Stability Notice ⚠️
I think it's only fair to warn everyone that modded minecraft is volatile and prone to breaking.

This is a WIP, so there are going to be some bumps along the way. As much as possible I'm going to try to preserve the world and mods that are in the pack when updating MC/Mod versions. But, there is a chance there will be world resets, or mods that break / aren't updated so they are removed. The idea is to keep the modlist minimal and on the latest version of MC as fast as possible.

That being said I don't want people to put in a bunch of work for nothing so there is the possibility of extended or experimental branches.

   

Getting Started
If you haven't already, download Minecraft from Mojang and install it.
Download the specified version of Forge Mod Loader for Minecraft
If you encounter issues try using 8 JDK.
For M1 Macs: I reccomend using Zulu OpenJDK. There aren't many (if any) other compiled versions of OpenJDK for ARMx64 Macs right now.
Run the installed profile so it can perform initial setup
You'll know you have the right one as it should be an anvil icon / forge version to the left of the Play button.
Once you get to the main menu you can close the game
Download the latest release of Valleycraft
Back in the Minecraft Launcher, in the top navigation select Installations
Select the Ellipsis (...) icon and select Edit for the forge installation
Rename the pack to "Valleycraft"
Expand More Options and remove the current -Xmx property from JVM Arguements
Add -Xms7G -Xmx7G to the beginning to give the installation more memory
7 is just a recomendation. You can adjust as needed, but I'd reccomend at least 6 GB.
For M1 Macs: Also add -Dfml.earlyprogresswindow=false (This is a temp fix as Forge seems to crash on boot without it)
Select the Folder icon for "Valleycraft" to open the installation location
Remove the existing mods folder and replace it with mods folder from the Valleycraft ZIP
Close the folder and return to the launcher
Launch and enjoy!
   

Updating
Download the latest release of Valleycraft
Note: If forge needs to be updated, update Forge first!
Open the Minecraft Launcher
From the top navigation select Installations
Select the Folder icon for "Valleycraft" to open the installation location
Remove the existing mods folder and replace it with mods folder from the Valleycraft ZIP
Close the folder and return to the launcher
Launch and enjoy!
   

Updating Forge
Under the forge subfolder for the current version you'll find the current version of forge for the pack
e.g. forge-<$MC_VERSION>-<$FORGE_VERSION>-installer.jar
Double-click the jar file and run the installer
Make sure you install to the same location as your previous install (unless you know what you are doing)
Make sure when you boot the launcher, the listed forge version matches that listed in the readme
   

Connecting
From Multiplayer, select Add Server
Enter the following:
Server Name: Valleycraft
Server Address: valley.hearth.adam.wtf
No port is required!
As long as the server is up you should see the icon populate and version populate (e.g., Valleycraft 2.x.y )
   

Mod list
Mod	Description
Abnormal's Core	Shared lib for mods
AIOT Botania	All-in-one Tools for Botania
AppleSkin	QOL mod, adds useful info such as food saturation and exhaustion
Applied Energistics 2	Automated storage and crafting (Most high-tech mod in the pack)
Architectury API	Shared lib for mods
Attribute Fix	Shared fix to Vanilla (removes attribute caps) for other mods
AutoRegLib	Shared lib for mods
BadMobs	Limit spawning of problematic mobs
Better End	Adds new biomes and mobs to post-end end.
Biomes O' Plenty	Adds new biomes to Overworld / Nether / End
Biomes You'll Go	Adds over 80 new magical biomes to explore
Botania	Mana, Magic, and Flowers
Bookshelf	Shared lib for mods
Buzzier Bees	Adds more blocks for Bees!
Chisel & Bits	Adds micro-blocks for more creative building
Citadel	Shared lib for mods
Chicken Chunks	Adds an item that allows fro chunk loading (Since FTB is removed)
Chocolate Fix	Shared fixes to Vanilla for other mods
Cloth Config	Shared lib for mods
CodeChicken Core	Shared lib for mods (Chicken Chunks)
Corail Tombstone	Adds tombstones and handles player deaths (so you don't lose your stuff)
Create	Mechanical tech mod adds power/processing via pulley's gears, windmills, etc. (Main tech insparion for the pack)
Culinary Construct	Custom sandwiches? Let's go.
Cucumber	Shared lib for mods
Curios API	Shared lib for mods
Dynamic View	OTF adjustments to chunk view distance based on server performance
Emojiful	Adds emoji to chat 👌
Engineer's Decor	Adds decorative industrial blocks. It's the server's aesthetic
Engineer's Tools	Adds early game tools to help with getting started
Farming for Blockheads	QOL Farming Mod
Fast Furnace	Shared fixes to Vanilla furnaces (improves performance)
Fast Workbench	Shared fixes to Vanilla crafting benches (improves performance)
Fast Leaf Decay	Speeds up the decay of leaves after a tree is cut. Nobody likes floating blocks.
Flat Bedrock	QOL mod, flattens out bedrock
FlickerFix	Fixes potion expiry effect, because we don't need seizures
Flux Networks	QOL mod for transferring energing through dimensions (doesn't quite fit the aesthetic but it's useful)
FTB Backups	Removed 2.1.0
FTB Chunks	Removed 3.0.0
FTB Essentials	Removed 3.0.0
FTB GUI Library	Removed 3.0.0
FTB Ranks	Removed 3.0.0
FTB Teams	Removed 3.0.0
FTB Ultimine	Adds ability to harvest entire trees/ore veins by holding ~ when mining
HWYLA	Adds tooltips to viewing blocks, since there are so many new ones
Immersive Engineering	Other main tech mod, it fits the server's aesthetic
Immersive Petroleum	Expands on IE's fuel systems
Inventory Tweaks Renewed	QOL mod for inventory sorting
JEI	Adds searchable interface for items and crafting recipes
JEI Integration	Shared lib for mods to add items to JEI
Journeymap	Adds a much prettier map with mob/player support
Mahou Tsukai	Adds magic and spellcrafting 👀
Macaw's Bridges	Adds beautiful bridges
Macaw's Doors	Adds beautiful doors
Macaw's Furniture	Adds beautiful furniture
Macaw's Paintings	Adds beautiful paintings
Macaw's Roofs	Adds beautiful roofs
Macaw's Trapdoors	Adds beautiful trapdoors
Macaw's Windows	Adds beautiful windows
Modular Routers	Adds item routing and sorter (just another option)
Mouse Tweaks	QOL mod for easier crafting and dragging with the mouse
Mystical Aggradditions	Removed 2.1.0
Mystical Agriculture	Removed 2.1.0
Mystical Customization	Removed 2.1.0
Pam's HC2 - Crops	Adds an adundance of additional crops
Pam's HC2 - Food Core	Adds an abundance of new foods and cooking tools
Pam's HC2 - Food Extended	Adds even more foods and recipes
Pam's HC2 - Trees	Adds food/ingredients spawning to trees 🥑🍞
Patchouli	Shared lib for mods, adds documentation for players
Pickle Tweaks	Removed 2.1.0
Placebo	Shared lib for mods
Quark	Adds a ton of QOL tweaks (https://quark.vazkii.net/#features)
Quark Oddities	Additional QOL tweaks for Quark
Rats	Adds fancy rats
Ratlantis	Unlocks the mystery of a forgotten realm
Resourceful Bees	Adds more bee types, such as coal or redstone
Serene Seasons	Removed 2.1.0
Shutup Experimental Settings	QOL mod that disables the silly warning about custom world-gen
Spice of Life: Carrot Ed.	Rewards players for trying different foods. And there is a ton in this pack
Storage Drawers	Adds an efficient and nicer looking storage system
Switches and Gauges	Adds more buttons / pressure plates and prettier redstone switches. It's the server's aesthetic
Tool Belt	QOL mod that combines your tools to save inveotry space
Trample Stopper	QOL mod that prevents trampling crops
TrashSlot	QOL mod that adds a trash slot to your inventory to dump uneeded items (without making lag!)
U Team Core	Shared lib for mods
Useful Backpacks	Adds backpacks so your inventory isn't always full
WAWLA	Adds extra useful info to HWYLA
Waystones	Adds an obelisk network that you can teleport around with
