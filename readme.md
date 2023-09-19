> This is a modification of Caligari87's [Ugly as Sin](https://github.com/caligari87/Ugly-as-Sin) medical module. All of the original code belongs to him.

side note: this is poorly fixed up, so do expect some weird bugs/inconsistency.

## Changes
 - You can now operate on unstable wounds with the Trauma Kit. (do note that you will still bleed out unless you seal the wound)
 - ~~Stabilised wounds can still be sealed up with Second Flesh. (might nerf/change this)~~
 - Removed autostrip, because it doesn't exist.
 - Trauma kit now has a tool list.
 - Fixed wounds will heal some tissue damage. (fixing with 2f will also do this)
 - **: W H E E L :** The trauma kit now has an item wheel for your tool switching needs.
 - ~~Wound Stabiliser now has an indicator to let you know if you're bleeding. (same as the bandage)~~

## Technical changes
 - `UaS_WoundInfo` now replaces `HDBleedingWound`.
 - also renamed `UaS_WoundInfo` to `UaS_Wound`.
 - Cavity is based on the width of your wound.


## Bandage changes (temporary list?)
 - Removed Wound Stabiliser, now wounds are stabilised through bandages.
 - Replaced vanilla self bandage with a somewhat more complex(?) self bandage.
 - Added bandages, used for bandaging wounds more efficiently.
 - Trauma kit can no longer operate on bandaged wounds. (this always bugged me lol)

## (planned) Bandage Overhaul
many changes, so this is getting its own section.

> NOTE: only the normal bandage is implemented right now, i'll just leave the contents here unchanged for now and modify it when i implement it
> please refer to the bandage changes to see what has been implemented

### Bandages
There are now 2 types of bandages: Improvised and Normal
Improvised is the default vanilla bandages. They are slow and not that great, and should be only used if you don't have any normal bandages to spare.
Normal is the new bandages that you have to find.

### Wound Dressings
Can be applied to wounds. Helps apply pressure to wounds, allowing them to stabilise faster.
Has to be bandaged up to actually work, and increases bandaging time.

## Credits
 - bunyear/Tapwave: Made the tool sprites
