# Sonic Frontiers | Freezing & Stuttering Fix
Solves freezing and stuttering when running the game on certain hardware configurations, mainly on Windows 11 while paired with 8th or 9th-generation Intel CPUs though this has been reported on AMD CPUs and Windows 10 as well.

The source of these freezes seems to be two "lock bts" opcodes at 0x1503d8710 and 0x140c1df14 which are called hundreds of times per second. 

Installation:

1. Set up HedgeModManager. You should already have this if you play on PC with mods.
2. Download the ExtraCodes.hmm file from this repo and place it inside the  "mods" folder located where you installed HedgeModManager
3. Open HedgeModManager and go to the Codes tab. Then, expand the "Fixes" dropdown and check the box for the code called "Fix Freezes on Windows 11 Computers with 8th or 9th Gen Intel CPUs"
4. Press "Save" or "Save and Play" to apply the code.

We've tested this for a few hours and nothing out of the ordinary happened but if you do stumble upon something wrong or a crash please report it on the issues tab.
