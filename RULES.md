# Rules for FE Homebrew
These are the rules for the setup described [here](https://github.com/josuegaleas/FE-Homebrew).

## Table of Contents
- [Character](#character)
- [Turn Order](#turn-order)
- [Movement & Action Costs](#movement--action-costs)
	- [Attack Costs](#attack-costs)
	- [Item Usage Costs](#item-usage-costs)
	- [Weapon Switching Costs](#weapon-switching-costs)
	- [Convoy Access Costs](#convoy-access-costs)
	- [Other Costs](#other-costs)
	- [Movement Assists](#movement-assists)
- [Pair-Up's](#pair-ups)
	- [Player Phase Pair-Up's](#player-phase-pair-ups)
	- [Enemy Phase Pair-Up's](#enemy-phase-pair-ups)
- [Supports](#supports)
- [Capture](#capture)
- [Shopping](#shopping)
	- [Eternal & Pseudo Skills](#eternal--pseudo-skills)
	- [Forging](#forging)
	- [Donation Pools](#donation-pools)
	- [Jakob/Felicia's Taco Truck](#jakobfelicias-taco-truck)
- [Dismounting](#dismounting)
- [Mission Checkpoints](#mission-checkpoints)
- [Mission Failure](#mission-failure)
- [Mission Success](#mission-success)
	- [Rewards](#rewards)
	- [Special Chapter Rewards](#special-chapter-rewards)
- [Skill Modifications/Restrictions](#skill-modificationsrestrictions)
- [Weapon Restrictions](#weapon-restrictions)
	- [Staff Restrictions](#staff-restrictions)

## Character
- You start with a default weapon that can not be lost
	- Either Bronze or Brass based on your class's faction
- You start with your custom weapon in the convoy until you have the rank to use it
- You start with 10k gold and three silver cards
- You start with three vulneraries and two keys
- If you die in a mission, then you lose the weapon you last had equipped that is **not** your default weapon

## Turn Order
- Roll a `d100` to determine turn order from greatest to least
- You can "pass" your turn and go last
	- You can **not** pass twice
	- Multiple units are allowed to pass their turn
- You may also "ponder" to temporarily suspend your turn
	- This lets the person after you do their turn, after which you get **two minutes** to do the rest of your turn
	- You can ponder in the middle of your turn but not while paired-up
- Each player gets **three minutes** to do their turn

## Movement & Action Costs
- Roll a `XdY` where `X` is the number of dice and `Y` is your movement stat
- Maximum movement is capped at `10` at Tier 1 and `15` at Tier 2
- What you roll is used for both movement, attacking, and other actions
- You may use "Anankos' Blessing" to add 3 to your roll's results
	- Must have rolled 6 or lower
	- Can only be used once every **five** turns
	- Charge resets automatically on turns that are multiples of five

### Attack Costs
- Only **three** attacks are allowed per turn
- The cost to attack is: `number of dice` + `number of attacks done this turn`
	- Example: If you have two dice, your first attack costs `2`, your second attack costs `3`, etc.

### Item Usage Costs
- Only **three** item uses are allowed per turn
- The cost to use an item is: `1` + `number of items used this turn`
- If your weapon has a "use" effect, it is considered an item usage and therefore increases your item use count

### Weapon Switching Costs
- The cost to switch weapons **outside** of initiating combat during your turn is `1`
- You may switch weapons at the end of your turn but you must deduct `1` from your next roll
- You may switch weapons before the enemy phase but you must deduct `4` from your next roll

### Convoy Access Costs
- Corrin and Jakob/Felicia will serve as the convoy
- The cost to access convoy is `0` when adjacent to them, otherwise it costs `2`

### Other Costs
- Only **one** chest or door can be opened per turn
	- Requires a key; the key does not have to be in your inventory
- Only **one** town/house visit is allowed per turn
- You may stand on "sparkles" at the end of your turn for no cost, otherwise it costs `1` to check
- The cost of breaking objects (such as walls) scales the same as using items
- The cost of using a rally skill scales the same way as using items
- The cost of using a staff/rod scales the same way as using items
- The cost of using a ballista/turret scales the same way as using items
- The cost to start a trade with an ally is `1`
	- Must be adjacent to the ally and can trade freely with no limits
- The cost to dismount is `1` and can only be done once per turn

### Movement Assists
- All movement assists cost `2`, except for your chosen assist during the mission
- Can only perform **one** movement assist per turn
- If you have a skill that gives you a movement assist, then that assist will also be free
	- Although it is free, you are still restricted to one movement assist per turn
- Can be done through flier-only terrain, such as smiting over a gap
- Can **not** be done through impassable terrain, such as fire or walls
- Can **not** be done with non-player-controlled units, such as Corrin

Name|Action
---|---
Swap|Unit and target ally swap spaces
Reposition|Target ally moves to opposite side of unit
Shove|Pushes target ally 1 space away
Smite|Pushes target ally 2 spaces away
Draw Back|Unit moves 1 space away from target ally, ally moves to unit's previous space
Pivot|Unit moves to opposite side of target ally

## Pair-Up's
- Everyone starts with `3` pair-up charges every mission
- The unit **supporting** the lead unit will consume the pair-up charge
- Can be done through flier-only terrain, such as water
- Can **not** be done through impassable terrain, such as fire or walls
- Can **not** be done with non-player-controlled units, such as Corrin
- Can **not** preview combat forecast for when splitting off from a pair-up

### Player Phase Pair-Up's
- The supporting unit must be within **three** spaces of the lead unit before they move or attack
- After combat, or if the lead unit ends their turn, the supporting unit will be separated and will choose where to stand

### Enemy Phase Pair-Up's
- The supporting unit must be **adjacent** to the lead unit
- At the start of the next player phase, the supporting unit will be separated and will choose where to stand

## Supports
- You can have up to three C supports, two B support, and one A support (your partner)
- You can build up support by:
	- Fighting an enemy while being supported (either in a pair-up or by simply being adjacent)
	- Fighting an enemy while adjacent to an ally (if not in the above situation)
	- Using a staff/rod on an ally
	- Activating dual-strike or dual-guard (only once per combat)
- You get the following perks with your partner:
	- Once per turn, you may flip a coin to **not** consume a pair-up charge
		- If you get `Heads` then the pair-up is free but the gold gained from pairing up is reduced to 500 from 1k
		- If you get `Tails` then the pair-up is **not** free and gameplay continues as normal
		- You do not have to commit to the pair-up in either outcome, but you can not "save" a `Heads` pair-up
		- Not available if the supporting unit has no pair-up's left
	- You can inherit **one** skill from your partner (except Eternal skills)
	- You can use other movement assists on your partner (that are not your chosen assist) for free
		- Although it is free, you are still restricted to one movement assist per turn

## Capture
- Once per mission, we may surround a hurt enemy enemy to "capture" them
	- The skill `Kidnap` could also be used to capture an enemy more easily
- Captured enemies can be sold off to grant everyone 2k gold
- Captured enemies can also serve as the supporting unit in a pair-up lasting the whole mission
	- Pairing-up with a captured enemy like this must be decided at the start of the mission
	- The supporting unit can use any skills the lead unit owns, except for Eternal and Pseudo skills
	- If the lead unit dies, the supporting unit runs away and is lost permanently

## Shopping
- Silver cards can be used to get 50% off any weapon (except Legendaries) or 5k gold off any Eternal skill
- Silver cards can also be used to restore lost forged weapons after one mission
- Silver cards can **not** be sold or traded
- All `Tier 2` skills are locked until you are Tier 2
- All `Other` or `Personal` skills worth 15k or more gold are locked until you are Tier 2
- You can **not** unequip your lottery skills until you are level 10
- You can **not** equip skills from the same family
	- Example: You can **not** have both `Swordbreaker` and `Lancebreaker` equipped
- The group is limited to three purchases of each skill
	- Consult the list in the `Skill Counter` tab in the Inventory spreadsheet
- You can **not** use an 'Arms Scroll' until you are Tier 2 and level 10
- You can **not** purchase `enemy only` weapons until you are Tier 2
- You can **not** purchase your second pair of boots until you are Tier 2
- You can only purchase **one** seal
	- The purchasable options are: `Battle Seal`, `Visitation Seal`, `Master Emblem`
- There can only be **one** of each Legendary weapon
	- Any found in a mission do **not** count towards this limit
	
### Eternal & Pseudo Skills
- Eternal skills require using an `Eternal Seal` to be unlocked and only **one** can be equipped
	- If learned naturally, then the skill must be put away until the above condition is met
- Pseudo skills can **not** be equipped if an Eternal skill is equipped

Eternal|Pseudo
---|---
Wary Fighter|`x`-taker skills
Aggressor|Lifetaker
Aether|Galeforce
Awakening|Warp
Divine Shield|Toxic Brew
Immune Status|Hit/Avo +20
Staff Savant|Resist Status
Immobilize|Point Blank
Inevitable End|

### Forging
- You can have up to two forged weapons
- You can **not** forge a weapon that you can not use
- Your default weapon can **not** be forged
- Custom weapons can be forged up to +7, regular weapons up to +4, and Legendary weapons up to +1
	- Can only forge up to +3 until the group finishes the chapter in which they get their second die
- Lost forged weapons can be re-purchased at a cost or you can use a silver card to get it back after one mission
	- Forged Legendary weapons are an exception and can be re-purchased for free
- Non-custom weapons that have been forged can be sold-off
	- Example: You get 24k gold for selling off a `Silver Sword +3`
- Forged weapons can **not** be used on bosses unless they have the skill `Dragonskin` equipped
	- This includes retaliating and hitting during the enemy phase or dual-striking in either phase
	- Players that break this rule will get a penalty seal until the next mission and must participate in three fights

Forge Count|Must Have|Cost|Re-purchase|Sell-off
---|---|---|---|---
+1|Base|Base Cost + 5k|Base Cost|5k
+2|Base +1|Base Cost + 8k|Base Cost|13k
+3|Base +2|Base Cost + 11k|Base Cost + 1k|24k
+4|Base +3|Base Cost + 14k|Base Cost + 2k|38k
+5|Base +4|Base Cost + 17k|Base Cost + 3k|N/A
+6|Base +5|Base Cost + 20k|Base Cost + 4k|N/A
+7|Base +6|Base Cost + 23k|Base Cost + 5k|N/A

- Example #1: `Silver Sword +1` = `Silver Sword` (already owned) + `Silver Sword` (5k) + `Add. Cost` (5k) --> 10k
- Example #2: `Silver Sword +2` = `Silver Sword +1` (already owned) + `Silver Sword` (5k) + `Add. Cost` (8k) --> 13k

### Donation Pools
- There are three pools to donate towards:
	- Señor Jakob/Señorita Felicia for 10k gold
	- Bifröst for 40k gold
	- Food Buff for 5k gold
- When the `Señor Jakob/Señorita Felicia` pool is funded, Jakob/Felicia becomes available to provide support and sell staff/rod services
	- Jakob/Felicia will provide +4 damage and -4 damage received if within two spaces of them
	- Jakob/Felicia will also provide a 30% heal if within two spaces of them at the start of the player phase
	- If Jakob/Felicia perishes in a mission, the pool will have to be funded again to bring them back
- When the `Bifröst` pool is funded, a fallen unit can be revived during the mission
	- The revived unit will not get their lost weapon back and any subsequent deaths will lead to more lost weapons
	- Jakob/Felicia must be present to cast this Bifröst charge
	- This Bifröst charge can only be used once per mission
- When the `Food Buff` pool is funded, the entire party gets two temporary stat boosts
	- The two stats are selected through a group vote
	- The food is obtained through the Mess Hall
	
### Jakob/Felicia's Taco Truck
Service|Cost
---|---
Physic|2k
Recover|3k
Bloom Festal|1k
Rescue|3k

## Dismounting
- Requires being Tier 2 and owning one of the purchasable seals
- The penalties of being dismounted:
	- Movement is reduced (varies based on class)
	- Current stats are reduced (varies based on class)
	- Caps for stats are reduced (varies based on class)
	- Caps for weapon ranks are reduced by 1 rank
	- Terrain effects become relevant again
- The bonuses of being dismounted:
	- Negates effective damage from being mounted
	- Avoid +10, Hit +5, and Dodge +5
	- Additional 3% growth rate to all stat growth rates

## Mission Checkpoints
- Two checkpoints are allowed per mission but require a majority vote
- Can only be done at the start of the player phase
- Any rolls done before making a checkpoint can **not** be rerolled

## Mission Failure
- If half the group dies (round up, minimum 3) then the mission is a failure and must restart from the beginning or the last checkpoint
- If any unit in the group dies in the first turn then the mission is a failure and must restart
- If the GM had presented a challenge for additional rewards and the mission is a failure, then the challenge is nullified

## Mission Success
- At the end of every successful mission, everyone votes on who to give a free level up to
	- If there is no winner then no level up is distributed
- If you did **not** participate in a successful main, paralogue, or invasion mission, then add `0.50` to your exp bank
- If you did **not** participate in a successful scout mission, then add `0.25` to your exp bank
- If you participated in an ongoing mission but missed a part of it, then add `0.25` to your exp bank
- At Tier 1, `1.00` from your exp bank can be used for a level up before the start of a mission
- At Tier 2, `2.00` from your exp bank can be used for a level up before the start of a mission

### Rewards
- The GM announces an amount of gold that everyone gets for the mission
- The game automatically selects MVP(s); they receive an additional 3k gold
	- The same unit can **not** be MVP for four consecutive missions (excluding scout missions)
- The GM distributes an `Underdog Seal` to one or two players that need it
	- Grants Str/Mag +5 and Def/Res +10
	- Does not conflict with any of the purchasable seals and can be equipped together
	- Can **not** be received for two consecutive missions
- 500 gold gets added to the `Señor Jakob/Señorita Felicia` pool
- 1k gold gets added to the `Bifröst` pool
- `0.50` gets added to the group exp bank which players can take from with group consent
- When pairing-up, the supporting unit earns 1k gold
- When supporting while dual-striking, 100 gold is earned per successful attack
- When supporting while dual-guarding, 500 gold is earned per successful block
- When using a rally skill, 50 gold is earned per unit rallied (excludes none-player-controlled units)
- When using a ballista/turret, 50 gold is earned per enemy hit

### Special Chapter Rewards
- After completing Chapter 13, everyone gets to roll two dice
- After completing the Rainbow Sage chapter, everyone gets a choice between:
	- +1 forge to their custom weapon
	- +2 to all stats (excluding HP)

## Skill Modifications/Restrictions
- `Movement +1`, `Surefooted`, `Pass`, and `Galeforce` can **not** be equipped together
- `Supportive` and `Miraculous Save` can **not** be equipped together
- `Divine Shield` can **not** be equipped with either `Aegis` or `Pavise`
- `Shelter` (aka Reposition), `Shove`, and `Swap` can be used on **non-boss** enemies
- `Quick Salve`
	- You get a free use out of a healing item (only once per turn)
- `Lifetaker`
	- Can not receive healing or use healing items
	- Max attack limit is reduced to **two** from three
- `Galeforce`
	- Your movement stat increases by **two**
	- You get a free hit if you kill an enemy (only once per turn)
- `Pass`
	- Your movement stat increases by **one**
	- Tiles with an enemy have **no cost** to walk through
- `Spendthrift`
	- Can only be used **three** times per mission
	- Costs 1k gold to use (based on money **before** the start of the mission)
- `Supportive`
	- Pair-up charge limit increases by **one**
	- Can enter an **enemy phase** pair-up from three spaces away
- `Miraculous Save`
	- Pair-up charge limit increases by **one**
- `Warp`
	- Costs `1` to use and can only be done once per turn
	- Can **not** use movement assists nor skills that grant movement assists (except with partner)
- `Lunge`
	- Adds `1` to your current attack cost to use
- `Shove`
	- Can choose to shove one space away or smite two spaces away
- `Replicate`
	- Both units will share the same pool of movement
	- If you pair-up with yourself, you can **not** separate for the rest of the mission
- `Solidarity`
	- Gain 100 gold when an adjacent ally lands a critical hit
	- Gain an additional 200 gold when successfully supporting while dual-striking
- `Bold Stance`
	- While paired-up and dual-strike is successful, lead unit gains 200 gold
	- While paired-up, supporting unit gains an additional 100 gold when successfully supporting while dual-striking
	- Does **not** apply if pairing-up with yourself
- `Dual Striker`
	- Gain an additional 200 gold when successfully supporting while dual-striking
- `Dual Guardsman`
	- Gain an additional 300 gold when successfully supporting while dual-guarding
- `Nohrian Trust`
	- If lead unit has this skill, can pair-up at **no cost** to the supporting unit (once per **mission**)
	- May flip a coin to enter an enemy phase pair-up from **three spaces** away if you get `Heads`
	- If lead unit successfully uses a skill from the supporting unit, the supporting unit gets 1k gold
- `Locktouch`
	- Can attempt to steal a weapon from the enemy at the cost of your current attack cost
	- Can **not** steal weapons from bosses
	- Must have an open slot in your inventory
	- Must roll a `d10`, and if the steal is a success, you gain 10 exp
		- Must be `7` or greater for equipped weapons
		- Must be `4` or greater for unequipped weapons
	- If Tier 2, stealing counts as an attack and therefore increases your attack count

## Weapon Restrictions
- After using a Brave weapon, you can **not** change to another weapon nor unequip that Brave weapon
	- Custom weapons with the `Brave` unique effect are exempt from this restriction
- Crit weapons can not be equipped during the enemy phase
	- Default weapon will be used if there are no other options
	- Custom weapons with the `Killer` unique effect are exempt from this restriction
- After using a Legendary weapon, you can **not** change to another weapon nor unequip that Legendary weapon

### Staff Restrictions
- The `Enfeeble` staff can be used on bosses only **once** per mission
- The `Entrap` and `"Super" Entrap` staves can **not** be used on bosses
- The `Bifröst` staff will only cost `1` to use but will use up **all three** of your staff uses for that turn
