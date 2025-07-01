# 2025-06-27
v1.2.0-beta-branch

- Removed "buffs" from melee damage types
    - Concerns of it affecting the warpfire and bleed counts
- Added ammo pickup modifiers from Havoc (pickups give less)
    - Check if mission is Havoc when starting a mission
    - If so, set the ammo modifier from the Havoc settings template
- Some code reorganizing to make it easier for me to read
- Moved some units and damage types around
    - Mutator disablers (Grandfather's Gifts) from specialists to disablers. Thanks Tunnfisk!
    - Fix for bleed and warpfire damage counting as melee (removing buff from melee type. thanks syllogism!)
    - Moved shockmaul_stun to dog damage type, since shock maul electricity damage is less important than dog shocks (thanks for the suggestion syllogism!). Planning on a "cleaner" solution to this later