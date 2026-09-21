Lady Stalker English Translation Addendum v1.4
By OrcMasterJones, building on RetchErezzed's English translation

This cumulative release includes all earlier Addendum improvements, plus
full-name battle and warp menus, clearer secondary Status pages, event-flash
repairs, and reviewed translation and message-layout improvements.

PATCHING
--------
Use a fresh copy of ONE of the two supported source ROMs below. Both must
be headerless (no 512-byte copier header).

1. Original Japanese ROM:
   Apply LadyStalker_Patch_for_Japanese_ROM.ips
   Size: 2,621,440 bytes
   CRC32: 4390D719
   SHA-256:
   d0275f6fdc38f26b53b017bdd7fe26e13b9871a93671c76f48800e4f733b2385

2. Original English translation v1.0 ROM:
   Apply LadyStalker_Patch_for_ENG_v1.0_Rom.ips
   Size: 4,194,304 bytes
   CRC32: 3A59468A
   SHA-256:
   3a698798b844e248cd3cf612941d18d1837bc6af1805df18b6eff609bc97e3cf

Apply exactly one patch with an IPS-compatible patcher. Do not stack the
two patches or apply either one over an earlier Addendum ROM. IPS does not
check the source for you, so verify the size and hash before patching.

Both routes produce the same v1.4 ROM:
   Suggested filename: LadyStalker_English_Addendum_v1.4.sfc
   Size: 4,194,304 bytes
   CRC32: 7C236DBA
   SHA-256:
   e8490da4e6e0cc5681ebe0e9c566471d989a24489867785765ef5f22440443cd

This archive contains patches and documentation. Supply your own source
ROM. SHA256SUMS.txt lists the hashes of the five package payload files.

WHAT'S NEW
----------
- Full item names in the two-column Battle Items menu, with all 12 slots
  and native quantities retained.
- Full learned abilities and spells in secondary Status, including Lady
  Special, with Field Spells and Battle Spells inside a complete border.
- Full destination names in Spring and Zap, with consistent Death Vegas
  spelling, King Baron's Manor, and improved V/v lettering.
- Full Double Up in Battle Magic and several item-lettering refinements.
- Connect the diagonal leg of narrow capital R letters in item, spell and
  destination names without changing their width or spacing.
- Repairs for several key-item event flashes, including the bookcase and
  both investigated Baron's Eye platform flashes.
- Reviewed translation corrections, restored ancient-name symbols, shorter
  battle notices, and cleaner line breaks where the English text fits.
- Keeps Spring/Zap names and dialogue clean through opening, cancellation,
  casting and closing; retains the original two-line action messages.
- Preserves the question mark in the shop Sell prompt with full inventories.
- Clears stale text-cache data after canceling Spring/Zap, preventing blank
  Sell item names and subsequent screen corruption.

See CHANGELOG.txt for details, verification limits and earlier history.

EXISTING SAVES
--------------
Keep a backup of your save. The battery-save format (.srm) is unchanged.
Copy or rename the save to match the new ROM's filename, then boot the new
ROM and use the game's Continue option. Some emulators manage save names
or locations differently.

Use a battery save when moving between versions. Older emulator save
states can retain graphics, text pointers and menu data from the previous
build. A new game is not required.

NOTES AND FEEDBACK
------------------
Component validation includes broad emulator regression runs, per-frame menu
checks and native save/reload tests. The final shop repair has additional
cross-menu, continuous-session and warp comparisons. Both supported patch
routes reconstruct the exact author-approved ROM. Expanded menu rendering
and revised text can change fine timing; this version does not promise
identical audio samples or RNG sequences to previous builds. Some visual
quirks shared with the Japanese game remain unchanged.

This package does not claim a new complete playthrough or certification
on physical hardware. If you find a problem, include the version, emulator,
steps to reproduce it, a screenshot, and a nearby battery save or save state.

Credits and project links are in CREDITS.txt.
