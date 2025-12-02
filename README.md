# Legends ZA Item Codes
These files represent individual Legends ZA item codes for use with cheat tools on Switch CFW. I have been told these are compatible with emulation tools as well, however I cannot confirm.

These codes can be used even if you have not found the item in question. We now have a better understanding of the internal inventory data, and as such these codes have been built to avoid inventory corruption in saves. Furthermore, I have tested each of these codes myself on switch hardware and can confirm they do not cause save corruption.

## How to Use
The provided files should not be used as is unless you only need a very specific set of items and only those items. Instead, pick and choose the codes you want and add them to your cheat file.

1. Open your cheat file in a text editor.
2. Copy the desired item codes from the text files in the root of this repository into the downloaded text file. Save the file when you are finished.
3. Copy the downloaded text file into the following directory on your Switch: `atmosphere/contents/0100F43008C44000/cheats/`
  If the directory does not exist, create it manually.
4. Launch the game and press `L + Down + Right Stick` to open the cheat menu.

If you are using Edizon overlay to manage your cheats, you can put cheats into subfolders in the cheat menu for better organization. I have included the section tags to make this work in the item code files. To use them in your cheat file, simply put section open and close tags around the codes you wish to put into a folder. For example:

```
[--SectionStart:XP/Leveling Items--]
00000000 00000000 00000000

[990x Rare Candy]
580F0000 041F0A60
780F0000 00000338
680F0000 000003DE 00000002

[990x Exp. Candy XL]
580F0000 041F0A60
780F0000 00004698
680F0000 000003DE 00000002

[--SectionEnd:XP/Leveling Items--]
00000000 00000000 00000000
```

The following will put the '990x Rare Candy' and '990x Exp. Candy XL' codes into a sub folder called "XP/Leveling Items" in the cheat menu. **This does not work on emulators**.

## Credits
[Stoned](https://gbatemp.net/members/stoned.347253/) - Created the original known-good item codes that these item codes are based on.

[dsrules](https://gbatemp.net/members/dsrules.31620/) - Provided the correct values for each category and provided the condensed code format for versions 1.0.0/1.0.1.

[azalea_](https://gbatemp.net/members/azalea_.771689/) - Provided an item list dumped directly from game files. This list has been used to verify that the item codes in this repo represent a complete collection of all items currently available in Legends ZA (as of version 1.0.1)

[Az91](https://gbatemp.net/members/az91.723200/) - Created the item codes for 1.0.3 which the version 1.0.3 item codes are based on.

[Patjenova](https://gbatemp.net/members/patjenova.459346/) - Created the original species spawn modifier codes and the encounter modifier codes that the ones in this repo are based on.

## Distribution
I am fine with these codes being posted elsewhere, however I ask that if you do so, please credit me (envyUK or entropiccodes) and/or link back to this repository.
