# FE Homebrew
Heavily-modified setup for a cooperative, D&D-esque experience in Fire Emblem Fates.

Original concept by Zeoro, documentation and rules written mostly by Josue.

## Disclaimers
- We use `Fire Emblem Fates - Special Edition` as the base for these modification and rules, but a similar setup can be achieved in other versions of Fates
	- It is also possible to run this setup in Fire Emblem Awakening but would require some major modifications
- Dismounting is not a vanilla feature, it was modded into the game using paragon

## Links
- [Rules](./RULES.md)
- [Cheats Being Used](./CHEATS.md)
- [Character & Custom Weapon Creator](https://docs.google.com/spreadsheets/d/1xGSfxuuh6_xEI5TidIJ8dtZY9I_GhrJEe_qqwhvOJo0/edit?usp=sharing)
- [Blank Inventory Spreadsheet](https://docs.google.com/spreadsheets/d/11pNc7kBphGpPm-2IJ2guYXxa9ntc2QWtOJu4MTR6GIc/edit?usp=sharing)
- [Twitch Stream & Videos](https://www.twitch.tv/zeoro94)
- [Backups of Streams](https://www.youtube.com/@zeoro9497)
- [BGM Titles](https://www.reddit.com/r/fireemblem/comments/46c9bj/spoilers_fates_localization_dump_bgm_titles/)
	- A backup of this post can be found in the `preservation` folder which was scraped using [bdfr](https://github.com/aliparlakci/bulk-downloader-for-reddit).

## Software Being Used
Name|Purpose
---|---
[Citra](https://citra-emu.org/download/)|Emulating the game
[paragon](https://github.com/thane98/paragon/releases)|Editing the game
[FEFTwiddler](https://github.com/Soaprman/FEFTwiddler/releases)|Editing the save
[BCH-Texture-Editor](https://github.com/VelouriasMoon/BCH-Texture-Editor/releases)|Extracting the textures
[Clip Studio Paint](https://www.clipstudio.net/)|Editing the textures
[fe-conversation-editor](https://gitlab.com/secretivecactus/fe-conversation-editor/-/releases)|Creating support conversations
[CTR-Studio](https://github.com/MapStudioProject/CTR-Studio/releases)|Editing 3DS formats (not used but may be helpful)

## Setup for NPCs
Corrin is equipped with the following skills:
- Divine Shield
- Dragonskin
- Warp
- Locktouch

Corrin has a custom weapon called `Kill` that has the following settings in Paragon:
- Under the `Flags` tab, `Possession Bonuse` is turned on
- Under the `Stats` tab, under the `Extra Data` section, replace the text with: `00 99 99 99 99 99 99 99`

Jakob/Felicia is equipped with the following skills:
- Amaterasu
- Healing Descant
- Inspiration
- Quiet Strength
- Rallying Cry

## Other Modifications
- The cap stats of almost all classes were increased (too much to document)
- The base stats of some classes were modified (too much to document)
- The range of `Hexlock Spear` was changed from 1 to 1~2
- The durability of `Rescue` was changed from 2 to 4
- All S rank weapons have the flag `Halves Stats After Battle` enabled
- Various custom weapons were added (this is campaign-specific, will not document)
