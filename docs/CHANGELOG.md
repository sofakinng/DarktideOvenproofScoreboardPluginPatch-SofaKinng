# 2025-07-01
v1.2.1-beta

- Added localizations for new settings
    - I don't know who added these so I can't credit :(
    - Russian, Simplified Mandarin, and Traditional Mandarin

# 2025-06-27
v1.2.0-beta-branch

- Moved some units and damage types around
    - Mutator disablers (Grandfather's Gifts) from specialists to disablers. **Thanks Tunnfisk!**
    - Fix for bleed and warpfire damage counting as melee (removing buff from melee type. **thanks syllogism!**)
    - Moved `shockmaul_stun`` to dog damage type, since shock maul electricity damage is less important than dog shocks (thanks for the suggestion syllogism!). Planning on a "cleaner" solution to this later
- Added ammo pickup modifiers from Havoc (pickups give less)
    - Check if mission is Havoc when starting a mission
    - If so, set the ammo modifier from the Havoc settings template
- Some code reorganizing to make it easier for me to read
- Coding style for the localizations