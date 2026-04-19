# MobHealth3: Kronos Edition (1.12)
### Updated for Kronos 4 by Mirasu

The original Kronos Mob DB was lost, so it was recreated from scratch via the Twinstar DB. 
The DB file is now nested into the addon.

## Features:
The included DB contains every mob in the game with Kronos values. It only contains the max level version of that specific npc and its max health since that is known. I have improved the original calculation method for lower level versions of a mob using a guestimator that has been thoroughly tested. The original version of this addon only had recording logic that would record and keep the lower level version of that mobs health once hit. These two now work in conjunction to provide a completely accurate health value. 

## Compatibility & Setup:
* **pfUI** - To use this with pfUI you must disable Health Point Estimation in Settings
* **Luna** - Use the `[smarthealth]` Tag in the Target Health Bar 
* **Blizzard Frames** - This is now baked in and does not require a separate file.
* **Compatible with SuperWoW:** It was causing some issues.
* **Nameplate Compatibility:** Tested on my fork of Kui Nameplates

---

## MobHealth3: Kronos 4 Edition - Major Update in v2.0.0
This update fundamentally rebuilds the dynamic health estimation engine to provide the most mathematically accurate, responsive, and stable health tracking possible within the limitations of the Vanilla 1.12 WoW client.

## Please see Release v2.0.0 for full changelog 
