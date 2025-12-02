# Frequently Asked Questions

## 1 - Do these codes work on 1.0.0?
The build ID for 1.0.0 is identical to 1.0.1, so the codes for 1.0.1 will work on 1.0.0.

## 2 - Do these codes work on emulator?
While I have not directly confirmed myself, many others have reported these codes working as intended on multiple different emulators.

## 3 - Can I use these codes if I don't already have the item? Will these corrupt my save?
Yes, you can use these codes even if you do not have the item already, and no, they will not corrupt your save.

Legends ZA has a specific method of handling and storing inventory data which early item codes created shortly after the game was leaked did not take into account. As such, those codes quite often corrupted saves after use. Fortunately we now understand the inventory logic far better and why those corruptions were happening. These item codes are designed to properly write items to your inventory, regardless of whether or not you already possess the item in question.

## 4 - My save got corrupted, can you help me?
Backup your save and run it through the PLZA Recovery Tool here: https://pl.azalea.sh/  

Credits to [@azalea-w](https://github.com/azalea-w) for their amazing work on this.

## 5 - How do I use the item codes?
These instructions are for those running Atmosphere CFW on Switch hardware with Tesla/UltraHand with the EdiZon overlay.

1 - **BACKUP YOUR SAVE!** This is something you should be doing any time you are trying new codes. While I can verify the safety of codes from this repo, this is a good habit to have regardless.

2 - Copy and paste the desired cheat codes into a text file. The filename of the text file should match the build ID of the version of the game you are playing.

| Version | build ID |
|:-------:|:--------:|
| 1.0.0 / 1.0.1 | 7222E13ECF6ADB32 |
| 1.0.2 | 7FC4289C78877148 |
| 1.0.3 | 179C3843B984F878 |

For this example, I will setup a 1.0.1 cheat file (7222E13ECF6ADB32.txt) like so:

```
[990x Rare Candy]
580F0000 041F0A60
780F0000 00000338
680F0000 000003DE 00000002

[990x Master Ball]
580F0000 041F0A60
780F0000 00000028
680F0000 000003DE 00000001

[990x Big Nugget]
580F0000 041F0A60
780F0000 00002468
680F0000 000003DE 00000003
```

3 - Copy the text file to your switch, placing it in the following folder: `/atmosphere/contents/0100F43008C44000/cheats/`
If any of the folders do not exist, create them.

4 - Launch the game, and progress past the title screen into the game itself.

5 - Press `L + Down + Right Stick/R3`. This is the default key-combination to open the Tesla/Ultrahand menu: ![Overlay Menu](img/step_5.jpg)

6 - Open the EdiZon menu, then open Cheats. If you put the cheat file in the correct place, the cheats added to the file will be visible here: ![Cheats](img/step_6.jpg)

7 - Toggle the cheats on by pressing `A` while the cheat is selected: ![Cheats Active](img/step_7.jpg)

You can turn the cheats off after enabling them if you choose, keeping them on simply means the count of those items will not decrease when used.

8 - Close the Tesla/Ultrahand overlay by repeatedly pressing `B` or `L + Down + Right Stick/R3` again.

9 - Open your satchel, and enjoy your items: ![Items Added](img/step_9.jpg)

## 6 - I cheated in Poke Balls but I don't see them in the throwing menu?
Save and reload, and the Poke Balls will appear.

## 7 - Help, I soft-locked myself because I gave myself a key item, and now the game is trying to give it to me but I can't take it!
Please refer to the `remove_key_items.txt` file for the version of the game you are playing to find the code to remove the item in question.

## 8 - I added some items via cheat, why can't I see them?
There are several item categories in the satchel, and most of them are not available at the start. If you cheat in an item for a category you have not yet unlocked, the cheat will not work. This most commonly affects Mega Stones, as you do not get the Mega Stone bag category until you have unlocked your first Mega Stone through story progression, but can affect Berries, Other Items, TMs and Treasures, depending on how early you attempt to cheat in items.

## 9 - I don't see my cheats in the cheat menu?
Your cheat file is in the wrong location, or has the wrong file name. On Switch hardware, the cheat file should be named after the build ID for the version you are playing, and be in this folder: `/atmosphere/contents/0100F43008C44000/cheats/`

For emulation, please refer to documentation for your chosen emulator.

## 10 - How do I use the Pokemon Encounter Codes? I put one in my cheat file and it isn't working!
The encounter codes provided in this repo are designed to be used with another set of codes, which can be found in the cheat file here: https://gbatemp.net/threads/pokemon-legends-z-a-cheat-database.675579/#post-10732980

Grab the 'Recovery Code' and 'Always Encounter Pokemon' codes from the cheat file matching the version you are playing, along with any others you wish to use. To spawn Pokemon of your choosing, activate the 'Always Encounter Pokemon' code first, and then activate the encounter code of your choosing. Following this, teleport to a new location to refresh spawns. You should now be seeing the Pokemon of your choosing.

Once you are finished, disable the encounter code and 'Always Encounter Pokemon' code, then enable the 'Recovery Code' to reset the memory values back to normal. This will disable the encounter codes and eliminate the possibility of long term problems caused by memory editing.
