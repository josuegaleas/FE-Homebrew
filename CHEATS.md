## Cheats Being Used
Go into the `Cheats` folder in this [repository](https://github.com/iSharingan/CTRPF-AR-CHEAT-CODES) and search up your version of Fates. In our case, we use these [codes](https://github.com/iSharingan/CTRPF-AR-CHEAT-CODES/blob/master/Cheats/Fire%20Emblem%20Fates%20-%20Special%20Edition%20(USA)/0004000000179800.txt). For preservation's sake, a backup of this file can also be found in `preservation` folder.

Always Enabled|Enabled When Needed
---|---
Able to control enemy|Get Exp 100
Infinite Movement|Able to attack an ally
Anywhere starting position in preparations (including enemy)|All class selectable in Heart Seal (or Dread Scroll)
(SELECT+Y)Max Money|More than 1% of growth rates don't fail to stat increases
(SELECT+Y)Dragon Point99|Supports fast
(SELECT+Y)Gems & Foodstuff x99|Able to take the Rage & Breath from Convoy
(SELECT+Y)All items in convoy to x95 Fix|All Weapon & Staves & Batons equipment possible
Able to item trade with the enemy|
Able to use convoy anyone|
Free change difficult|
Able to set all skills(Include Personal skills)|
(SELECT+Y)Enable All City Item|
Can battle again not waiting in Arena|

---
We are also using a custom-made cheat from [here](https://gbatemp.net/threads/gateway-cheats.402900/post-8620212) that enables us to forge:
- All dragonstone weapons
- All beaststones weapons
- All breath weapons (including Draconic Rage)
- All fist weapons
- All rock weapons
- All saw weapons

For preservation's sake, the code is as follows and was made by `ymyn`:
```
[Forge is possible from 0 to 63 v1.0]
005287C8 EA000009
00528830 E3A00063
003C1180 E3A01000
003C1338 E351003F
003C133C C3A0103F
003C1344 E5841044
003C3ABC E1A00000
00610F18 E1A06000
00610F1C E5941000
00610F20 E1A00004
00610F24 E591106C
00610F28 E12FFF31
00610F2C E1D000B0
00610F30 E3A01001
00610F34 EBF6FFDC
00610F38 EBFC6089
00610F3C E3500000
00610F40 0AFC5E3C
00610F44 E3A05000
00610F48 E5C65003
00610F4C EAFC5E33
0052881C BA03A1BD
```

For our setup, this cheat is always enabled. The cheat is based on the `Forge is possible from 0 to 63  v1.0` cheat listed in the repository. The cheat normally only lets you forge all the other weapons not listed above like swords, but this custom-made one extends it. Unfortunately this cheat was made with `Special Edition` in mind and may not work with other versions of Fates.

---
We are also using a slightly modified version of the `More than 1% of growth rates don't fail to stat increases` cheat that makes it into a 0% growth rate cheat. To achieve this, you just have to change the last two 0's of the second line to F's.
For example, since we are using Special Edition, we changed the following cheat:
```
[More than 1% of growth rates don't fail to stat increases v1.0]
D3000000 00000000
003D8218 E3A00000
```
To this:
```
[0% growth rate]
D3000000 00000000
003D8218 E3A000FF
```
For our setup, this cheat is enabled when needed.

---
We are also using a cheat from [here](https://gamebanana.com/mods/51424) that alleviates a ghosting effect that occurs when increasing the resolution in Citra. It is not necessary to install the mod so no need to download it, the codes are as follows and were made by `Moonling`:
```
Fates Shader Ghosting Fix for Citra

USA SE
[Ghosting Shader Fix]
D3000000 00000000
001EE42C E3A01002

USA CQ/BR
[Ghosting Shader Fix]
D3000000 00000000
001EE444 E3A01002

EU SE
[Ghosting Shader Fix]
D3000000 00000000
001EE8E8 E3A01002

USA CQ/BR
[Ghosting Shader Fix]
D3000000 00000000
001EE900 E3A01002

JPN SE/CQ/BR
[Ghosting Shader Fix]
D3000000 00000000
001EFA3C E3A01002
```
For our setup, this cheat is always enabled.
