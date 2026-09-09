Lady Stalker English Translation Addendum v1.2.9
===============================================

This hack is an addendum to RetchErezzed's English machine-translation
patch for Lady Stalker: Kako kara no Chousen.

Version 1.2.9 fixes the reproduced HUD-background flashes when using
Medicine and confirming Spring destinations, including Lady alone. It also
fixes the corresponding pulse when a full Battle Items bag opens.
The local menu-upload repairs preserve native item effects, quantities,
party selection, and frame pacing. No global interrupt hook was added.

Shopkeepers retain their full introductory greeting and conversational
confirmations. Three repeated purchase prompts are shorter, bringing the
measured repeated-purchase text time closer to the Japanese version.

All earlier addendum improvements are included: menu and HUD repairs,
cursed-status icons and equipment messages, native quantity presentation,
battle healing-target windows, connected K/Z glyphs, shorter battle notices,
and the agreed enemy-name and matching dialogue corrections.

Controlled emulator regression checks cover all four party configurations,
small and full varied bags, field and battle targeting, menu transitions,
Storage/Retrieval, cursed gear, usable items, complete Spring warps, and
all 124 item entries in the affected battle-name slots. Test methods and
measurement limits are documented in the separate Source and QA archive.
This is not a new full story playthrough or real-hardware certification.

Both patches below include the complete addendum. No ROM image is included.


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

Apply the appropriate patch with an IPS-compatible patcher. Both patches
produce the same complete v1.2.9 ROM.

Do not apply both patches, and do not apply either patch over an earlier
version of this addendum. To upgrade, patch a fresh copy of one of the two
supported sources above.

Expected patched v1.2.9 ROM:
  Size:    4,194,304 bytes
  SHA-256: ed72ad227207fb65ad8d3cdd8cfe0a8c21564d7ca147d090670b48d3ae15bfe4

Existing in-game saves remain compatible. Back up your save, boot the new
ROM, and load it through the game's Continue menu. If your emulator matches
saves by filename, give the .srm file the same basename as the new ROM.
Use an in-game save when upgrading; old emulator savestates can retain
graphics and menu data from the previous patch.


VERSION HISTORY
===============

v1.2.9 - 9 September 2026 (HUD polish and shop cadence)
  - Remove Medicine/Spring HUD-background flashes and the full-bag battle pulse.
  - Preserve the native battle-name renderer CPU budget and sound timing.
  - Retain conversational shop text while shortening repeated purchases.
  - Recheck the affected menu, item, warp, audio, and party-size paths.

v1.2.8 - 9 September 2026 (release)
  - Restore exact original field-popup audio timing.
  - Preserve battle target repair and its existing sound timing.
  - Full controlled menu/HUD regression repeated on this build.

v1.2.7 - 9 September 2026 (target-window repair)
  - Battle healing-recipient separators and caption repaired.
  - Full controlled menu/HUD regression repeated on this build.

v1.2.6 - 9 September 2026 (enemy names)
  - Six agreed names and their three dialogue references updated.

v1.2.5 - 9 September 2026 (battle text)
  - Applied the seven approved message changes listed above.

v1.2.4 - 9 September 2026 (name polish)
  - Applied five agreed names in both text tables and updated Full Heal art.

v1.2.3 - 8 September 2026
  - Filled missing pixels in narrow capital K and Z across pre-rendered
    spell and item names, retaining the same widths, spacing, and wording.

v1.2.2 - 8 September 2026
  - Restored the Gear bottom edge in the same upload that closes a cursed
    item message, eliminating the briefly missing strip.

v1.2.1 - 8 September 2026
  - Fixed the remaining one-frame black strip when Retrieval redraws after
    taking an item while stored entries remain.
  - Protected the native cursed-status graphic in Battle Magic lists.
  - Verified Lady-and-Yosh menus and actions with distinct small/full bags,
    and checked the Retrieval correction with all four party combinations.

v1.2 - 8 September 2026
  - Fixed intermittent black-line flashes during menu transitions, including
    Battle Items and Storage/Retrieval paths.
  - Fixed HUD health-bar graphics during health changes.
  - Fixed long-name Gear rendering and menu transitions with full inventories.
  - Fixed equipment preview text, including DEF and Can't Equip, after cursed
    equipment and failed removal attempts.
  - Restored native item-quantity presentation through menu actions.
  - Fixed Give so a newly received item's name and quantity appear together.
  - Restored the original cursed-status graphic in the HUD and party selector
    after closing and reopening menus, including full Battle Items lists.
  - Shortened critical-hit notices to "[Name] lands a crit!" and
    "[Name] takes a crit!".

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
