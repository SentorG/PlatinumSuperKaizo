# Platinum Super Kaizo IronMON
A big thanks to PyroMike for all his help throughout this project, Arex for initially making the first changes and Champred for creating the modifications to the Great Marsh Binoculars and applying the smart AI flags. Many thanks to Toxxxyn for his help and support and devbotman for their contributions to the friendship-increasing NPC in Sandgem Town.
<br><br>
Check out the releases page [**here**](https://github.com/SentorG/PlatinumSuperKaizo/releases).
<br><br>
To patch your legally acquired Pokémon Platinum ROM, go to **https://www.marcrobledo.com/RomPatcher.js/** and use the .xDelta patch of your choice provided in the release section.

### **Please note:** this patch requires the **1.0 Version** of Platinum to work correctly.<br>If you find anything wrong with my patches, or have any suggestions for improvements, please let me know through my DMs on Discord. You can find me in the **[IronMON Discord server](https://discord.com/invite/jFPYsZAhjX) (user ID: sentor_g)**.

## The Great Marsh Pivot:
I have created a [**Google Sheets spreadsheet**](https://docs.google.com/spreadsheets/d/17ogpFOxqWgTNwNOs4q2Gda6FU8mMM-UHDDz_XMbYpbw/edit?usp=sharing) for you to use when tracking the species and levels of Pokémon inside the Great Marsh area. There are a total of 8 days contained within the spreadsheet, but I highly doubt you'll need all of them.<br>To make your own copy: go to the linked page and click "File" > "Make a copy" for you to be able to input your Marsh Area data.<br>You can refer to the [**Platinum IronMON guide**](https://docs.google.com/document/d/1Qd4mbwQxreLnbRLA5tWRjsZPlCUlWVMjBvNjI9tu7gs/edit?tab=t.0#heading=h.qsa502koukjk) for detailed information pertaining to the Great Marsh area.

### Which three TMs am I allowed for my pivot? -
**The three "Safari TMs" are:**
<br>- **TM 51**, obtainable by talking to the NPC nearest to the honey tree on [**Route 210 South.**](https://bulbapedia.bulbagarden.net/wiki/Appendix:Platinum_walkthrough/Section_7#Route_210_(south))
<br>- **TM 66**, obtainable by talking to the NPC next to the second bridge on [**Route 215.**](https://bulbapedia.bulbagarden.net/wiki/Appendix:Platinum_walkthrough/Section_8#Route_215)
<br>- **TM 63**, obtainable by talking to the NPC below Veilstone Gym in [**Veilstone city.**](https://bulbapedia.bulbagarden.net/wiki/Appendix:Platinum_walkthrough/Section_8#Veilstone_City)

### How does the Great Marsh area work? -
There exists "static" Pokémon encounters (stay in the same area regardless of the day) and "rotating" Pokémon encounters (a list of 15 Pokémon which can enter or exit the Great Marsh when the game crosses over into a new day). Rotating Pokémon have a selection % chance assigned to each one.<br>The Great Marsh Binoculars have been modified to allow the player to view every single encounter in each area through one view, using the A button to cycle to the next Pokémon. The first area will be displayed twice and we cannot fix that fact, apologies.<br>**For areas 1 and 2, the rotating Pokémon is the 3rd to last which was shown and for areas 3-6 it is the 2nd to last Pokémon.**
## Patch Contents List:
The Platinum Super Kaizo patch is derived from the [**GIGA Patch 3**](https://github.com/SentorG/NewPlatPatch/releases/tag/v3.0), but is also completely separate. To include the modifications made to the Great Marsh Binoculars, the patch needed to be built again from scratch.

### **WARNING:** Through testing, we have experienced infrequent, random crashing of the game when loading a new area (when the screen goes black to load a new area). It is therefore heavily advised to frequently save your game **AND** understand how to use the trackers' "Restore Point" function to reload the game without losing too much of your progress. Due to the random nature of the crashes, we have not been able to precisely pinpoint the reason for this occurring. I wanted to include a disclaimer here, just in case anyone else experiences this issue.

## Patch Modification List:
| **Update** | **Details** |
|:-:|:-|
| **Smart AI** | All trainers have Champion-level “smart” AI flags set. This removes the need to use the smart AI randomizer fork. |
| **Intro Skip** | Bedroom, Mom, Twinleaf, Route 201, Lake Verity, Sandgem, Jubilife and Oreburgh. Many other sections of cutscenes/dialogue have been trimmed significantly. |
| **Dialogue Skip** | Massive dialogue overhaul from the moment you start to the Hall of Fame. Less yapping, faster battling. |
| **Options QoL** | Set mode on by default. |
| **Custom Maps** | Created custom map edits to remove trees and rocks for easy pathing. (Lake Verity, Route 201, Sandgem, Route 219 (north), Oreburgh (south) and Oreburgh Mine. |
| **Name Raters** | Name rater NPC Psyducks in all Pokémon Centers. |
| **Friendship NPC (Sandgem)** | Added a friendship-increasing NPC (now with no limitations). |
| **Expanded Pokétch** | Extra Pokétch applications (Memo Pad, Pedometer, Pokémon List, Chain Counter, Color Changer). |
| **Faster Fishing** | Early pivot fishing spots have a 100% encounter rate. |
| **Moved NPCs** | Minor specific NPC repositioning to minimize movement for the player. |
| **Faster HMs** | All HM moves no longer require a Yes/No input from the player to use in the overworld. |
| **Honey Pivots** | Honey trees now no longer require a 6-hour in-game wait to encounter and are instead instantaneous. |
| **All-day Trainers** | Removed limitations on trainers who battle at specific times of the day. The Seven Stars Restaurant is now open 24-hours. |
| **Great Marsh Binoculars** | This function has now been updated to show every single Pokémon in the Great Marsh on that day. Placed a Piplup NPC which allows the player to access the binoculars while inside the Great Marsh. The first area will be shown twice (we know) and the order areas are shown in is random - but you will see all of them. Now only costs $1. |
| **No Sinking** | Removed sinking tiles in the marshy areas and deep snow where applicable. |
| **Iron Island * Trainer** | Spinning trainer made static in Iron Island. This is to guarantee avoiding the in-dungeon battle before being allowed to do so (no battles before mandatory continuous NPC healing). |

### I have added snow falling in Twinleaf town (because it's a vibe) but this does technically give an IronMON runner a slight advantage if the fishing pivot has Magic Guard, Ice Body or Snow Cloak. As there might be some controversy over whether this should be included, I have created a snowy version AND a clean version.

## File names breakdown:
- **FLX** - The frame limiter has been turned off. The game runs smoothly but faster.
- Snowy - Adds slow, falling snow to Twinleaf Town.

