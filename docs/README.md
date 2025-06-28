# Ovenproof's Scoreboard Plugin (OSP) Patch
Since OvenProofMars is no longer working on their [Scoreboard plugin](nexusmods.com), the Darktide community and I have been maintaining it to include enemies and damage types added by game updates. 

Originally it was stored in the posts on the mod page, but the project has grown enough that this is no longer viable. This mod is also hosted on [NexusMods](nexusmods.com), thanks to Sai.

# Installation
I have assumed your copy of Darktide is ready to load mods
## Manual
1) Install OSP, following [standard mod installation procedures](dmf.darkti.de)
2) Install the OSP Patch, overwriting OSP
    - Archive contains `mods\ovenproof_scoreboard_plugin\...`
    - Make sure you are installing the `ovenproof_scoreboard_plugin` folder into your Darktide mods directory
    - It should NOT end up being like `mods\mods\ovenproof_scoreboard_plugin`
## Vortex
1) Install OSP through Vortex
2) Install the OSP patch through Vortex (recommended: download it off the Nexus page)
3) Set loading rules so the OSP patch overwrites OSP
## Mod Organizer 2
1) Install OSP through MO2
2) Install the OSP patch through MO2 (recommended: download it off the Nexus page)
3) Order them in the left panel so OSP comes *before* the OSP patch
    - Set them in this order when the left panel is sorted by priority, with 0 at the top of the list
    - You may then filter the left panel's sorting however you wish
4) Enable both OSP and the OSP patch
    - You should see lightning bolt icons on each, with a red minus and a green plus for OSP and the patch, respectively
    - This means the contents of the OSP patch will overwrite OSP when loading into the virtual file system