# VMaNGOS Arena Patch
VMaNGOS Arena Patch Client Side (WoW Client 1.12.1 mpq file).

Features:
  - Solo queue & Group queue.
  - Crossfaction support.
  - Spectator support.
  - Disabled Item switching during the battle (even out of combat) except Weapons of course.
  - Disabled custom items.
  - Disabled most Consumables and Buffs, adjustable in the "arena_disabled_spells" table. (![List of disabled Consumables](https://raw.githubusercontent.com/Oroxzy/vmangos_arena_patch/master/disabled_consumables.txt)).
  - Damage & healing done on Scoreboard added, this feature is new and not available in Classic for BGs. Also it does count Pet damage too and not count over damage (So if you kill a Player with 4k hp with a 6k Shadowbolt it adds only 4k damage)
  - Pet commands are disabled until door opens to avoid attacking your enemies before the battle starts.
   
 Todo:
  - Fix Scoreboard for same Faction games (maybe edit */Interface/FrameXML/WorldStateFrame.lua*). (edit: not possible i think)
  
 Try it:
  - Goto (http://uterusone.net) and create your Account.

All 3 TBC Arenas & Dalaran Arena from WotLK available to play as 1v1, 2v2, 3v3, 5v5:
![TBC Arena](https://i.imgur.com/p5IVD1l.jpg)

Damage & healing done:
![Damage & healing done](https://i.imgur.com/eL6kHXH.png)

Remaining players:
![Alive players left](https://i.imgur.com/5zCC4aA.png)
