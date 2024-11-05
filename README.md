# Sonic Frontiers | Windows 11 Freeze Fix
Solves freezing and stuttering when running the game on Windows 11 while paired with 8th or 9th-generation Intel CPUs.

Their source seems to be two "lock bts" opcodes at 0x1503d8710 and 0x140c1df14, which both lead into a jump loop. I'm not sure why these chips struggle with them. The second address is related to the freezes in Cyberspace and I haven't been able to get around it without the game crashing, so it's on the To-Do list for now. Stutters in the open world should be all fixed though.

Installation:

1. Set up HedgeModManager. You should already have this if you play on PC with mods.
2. Download the ExtraCodes.hmm file from this repo and place it inside the  "mods" folder located where you installed HedgeModManager
3. Open HedgeModManager and go to the Codes tab. Then, expand the "Fixes" dropdown and check the box for the code called "Fix Freezes on Windows 11 Computers with 8th or 9th Gen Intel CPUs"
4. Press "Save" or "Save and Play" to apply the code.

Enjoy!

To-do:
Fix the freezes that only happen in Cyberspace.
