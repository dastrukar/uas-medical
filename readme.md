> This is a modification of Caligari87's [Ugly as Sin](https://github.com/caligari87/Ugly-as-Sin) medical module. All of the original code belongs to him.

side note: this is poorly fixed up, so do expect some weird bugs/inconsistency.

## Changes
 - You can now operate on not stabilised wounds with the Trauma Kit. (do note that you will still bleed out unless you seal the wound)
 - Stabilised wounds can still be sealed up with Second Flesh. (might nerf/change this)
 - Removed autostrip, because it doesn't exist.
 - Trauma kit now has a tool list.
 - Fixed wounds will heal some tissue damage. (fixing with 2f will also do this, so i might have to change that)

## Technical changes
 - `UaS_WoundInfo` now replaces `HDBleedingWound`.
 - also renamed `UaS_WoundInfo` to `UaS_Wound`.
 - Cavity is based on the width of your wound.

## Credits
 - bunyear/Tapwave: Made the tool sprites
