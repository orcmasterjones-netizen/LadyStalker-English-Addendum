Lady Stalker English Translation Addendum v1.1
================================================

This hack is an addendum to RetchErezzed's English machine-translation
patch for Lady Stalker: Kako kara no Chousen.

Version 1.1 revises the eight torn-page story fragments used by the library
ordering puzzle. The new English preserves the Japanese story while making
the intended order logically deducible. It also renames the library book item
from "Baron-kun 4" to "Little Baron 4" so it matches the bookshelf clue.
The slot-machine prize message now displays "COINS WON!" in English.
No gameplay behavior, audio, spell names, or unrelated text was changed.

No ROM image is included.


PATCHING
========

Use exactly one of the two included IPS patches:

1. LadyStalker_Patch_for_Japanese_ROM.ips
   Apply this directly to the original headerless Japanese ROM.

   Expected source:
     Size:    2,621,440 bytes
     SHA-256: d0275f6fdc38f26b53b017bdd7fe26e13b9871a93671c76f48800e4f733b2385

2. LadyStalker_Patch_for_ENG_v1.0_Rom.ips
   Apply this to a ROM already patched with RetchErezzed's ENG v1.0 patch.

   Expected source:
     Size:    4,194,304 bytes
     SHA-256: 3a698798b844e248cd3cf612941d18d1837bc6af1805df18b6eff609bc97e3cf

Do not apply both patches, and do not apply either patch over an earlier
version of this addendum.

Expected patched v1.1 ROM:
  Size:    4,194,304 bytes
  SHA-256: 08579800e5c7386ea52e2511145c6ee44f893f3c24c26e909ff990dfbf95d086


VERSION HISTORY
===============

v1.1 - 3 September 2026
  - Rewrote the eight library story-puzzle fragments so their correct order
    can be inferred from the English text.
  - Renamed the library book item "Baron-kun 4" to "Little Baron 4" to match
    the bookshelf clue.
  - Translated the slot-machine prize message as "COINS WON!" while retaining
    the game's dynamically generated prize amount.

v1.0 - 29 August 2026
  - Initial release.
  - Cleaned up menus and restored important English text.
  - Added Landstalker-style dialogue font and proportional item-menu text.
  - Restored the original NPC voice sounds.


CREDITS
=======

Original English machine-translation patch: RetchErezzed
English Translation Addendum: OrcMasterJones

RetchErezzed's translation:
https://www.romhacking.net/translations/7687/

Addendum page:
https://www.romhacking.net/hacks/9938/
