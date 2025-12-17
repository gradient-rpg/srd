# Gradient

>**Gradient** is an open-license, rules-lite, modular adventure game based on [Cairn by Yochai Gal](https://cairnrpg.com/), about exploring a world in movement, filled with strange folk, hidden treasure, and unspeakable monstrosities.
>
>**Gradient** aims to be setting agnostic, and its core rules do not assume a fantasy genre. **Settings** implement a specific fantasy genre, and reflects that into _Antagonists_, _Ambients_, Character's _Backgrounds_ and _Specializations_, _Inventory_ and _Marketplace_, _Currency_, and more.
>  
>**Characters**, **Antagonists**, and **Ambients** can be generated quickly and randomly. Adventures reward thoughtful exploration, while combat is often fast-paced and dangerous. The **Gradient Dice** provides an opportunity for narrative forward dice resolution.
>
>The goal is to offer a narrative-focused experience that welcomes any fantasy setting and any level of player familiarity, blending modern mechanics while remaining fairly rules-lite.

# Core Rules

## Setting Agnostic

**Gradient** separates its **Core** rules and mechanics from setting-specific rules and mechanics, to allow stories across any era or genre. 

The **Core Rules** provide what is universal: Player Characters mechanics such as _attributes_, _hit protection_, _armor_, _saves_; dice mechanics in the _Gradient of Grace and Grief_; and _Combat_ flow. These work whether you're wielding a sword, a pistol, or a plasma cannon.
However, every adventure needs concrete details: How do you manage _inventory, deprivation, fatigue_? What _equipment_ exists? What _currency_ do people use? What does _magic or power_ look like? A medieval fantasy world might handle these very differently than a steampunk future or a post-apocalyptic wasteland.
For this reason, **Gradient Settings** define inventory systems, equipment lists, currency, and the nature of magic or powers within their specific context. When you choose or create a setting, you're choosing how these essential elements manifest in your story. The core rules remain the same; the flavor of your world setting brings them to life.

A **Gradient Setting** should clearly identify what is overridden from the core rules, and implement setting-specific:
- Ambients
- Antagonists
- Character Creation Rules, Backgrounds, Traits
- Deprivation and Fatigue rules
- Inventory rules
- Power Systems

For a reference set of **Setting** rules, see [Gradient: Roots](settings/roots/setting-rules.md).

## Dice

**Gradient** uses **2d10** for most save rolls, but also uses smaller dice such as **1d8**, **1d6**, and **1d4** for weapon damage or random table rolls. We recommend having two of each.

## Player Characters

### Attributes

Player Characters (PCs) have three **Attributes**:

- **Strength (STR)**: Used for saves requiring physical power, like lifting gates, bending bars, resisting poison, etc.
- **Dexterity (DEX)**: Used for saves requiring poise, speed, reflexes, dodging, climbing, sneaking, balancing, etc.
- **Willpower (WIL)**: Used for saves to persuade, deceive, interrogate, intimidate, charm, provoke, manipulate spells or powers, etc.

> Attributes are not universal descriptors. A character with a low STR is not necessarily hopelessly weak; they can still attempt to lift a heavy door or survive a deadly fight! Their risk is simply higher. 

#### Attribute Loss

- If a PC takes damage outside of combat, they should instead receive damage to an Attribute, typically STR.
- If a PC's STR is reduced to 0, they die. If their DEX is reduced to 0, they are paralyzed. If their WIL is reduced to 0, they are delirious. Complete DEX and WIL loss renders the character unable to act until they are restored through extended rest or by extraordinary means.
  
### Hit Protection

- Hit Protection (HP) reflects a character's ability to avoid damage in combat. 
- This measurement does _not_ indicate a character’s health or fortitude, nor do they lose it for very long. See [Healing & Recovery](#healing--recovery).

#### Healing & Recovery

- Resting for a few moments and having a drink of water restores lost HP but may leave the party exposed. Bandages can stabilize a character that has taken critical damage.
- Attribute loss (see **Critical Damage**) can usually be restored with a week's rest, facilitated by a healer or other appropriate source of expertise. 
- Some healing services are free, while magical or more expedient means of recovery may come at a cost. 

### Character Creation

The first universal step of creating a new character, is rolling their **Attributes**:

>- Player Characters have just three **Attributes**: (_Strength (STR)_, _Dexterity (DEX)_, and _Willpower (WIL)_). 
>- Roll **3d6** for each of your character's **Attributes**, in order. You may then swap any two of the results. 

The second, is rolling their **Hit Protection**:

>- Roll 1d6 to determine your PC's starting **Hit Protection** (HP), which reflects their ability to avoid damage in combat. It does not indicate a character’s health or fortitude, nor do they lose it for very long. See [Healing & Recovery](#healing--recovery).
>- If an attack would take a PC's HP exactly to 0, the player must roll on the [**Scars**](#scars) table.

The third step is **Setting-Specific**. Follow the Settings' _Character Creation_ Rules to roll their _Backgrounds_, _Specialization_, _Traits_ and _Inventory_.

For a reference set of **Setting** character creation rules, see [Gradient: Roots](settings/roots/character-creation).

## Power Systems

**Gradient** has no universal magic system in its core rules. Instead, each setting defines its own **Power System** representing the extraordinary abilities, techniques, or forces that exist in that setting. In a medieval fantasy setting, this might be arcane spells and scrolls. In a steampunk world, it could be alchemical concoctions and experimental technology. A futurist setting might offer bio hacks or scavenged alien tech.

**Power Systems** aren't just reskinned magic, they're designed to reinforce the themes and feel of their setting. The cost, availability, and consequences of using power should reflect the world you're playing in. When you choose a setting, you're also choosing what "power" means and how it shapes the story the Player and the Warden are co-creating.

For a reference set of **Setting** power system rules, see [Gradient: Roots](settings/roots/power-system.md).

## Inventory

Most **Inventory** rules are going to be Setting-specific, but here is one rule that is universal:

### Inventory Slots

- Most items take up one slot unless otherwise indicated. 
- _Petty_ items do not take up any slots.
- _Bulky_ items take up **two** slots. 

For a reference set of **Setting** inventory rules, see [Gradient: Roots](settings/roots/setting-rules.md#inventory).

## Armor

- Before calculating damage to HP, subtract the target's **Armor** value from the result of damage rolls. 
- Shields and similar armor provide a bonus defense (e.g. +1 Armor), but only while the item is held or worn. Some may also provide additional benefits, depending on the fiction.
- A PC, NPC, or monster cannot have more than 3 Armor.  

## Saves & Risk

### Saves

- A save is a roll to avoid negative outcomes from risky choices. Characters roll **2d10**, and compare the summed results to the appropriate target attribute.
- If two opponents are each trying to overcome the other, whoever is most at risk should save.
- If two characters need to take an action together, whoever is most at risk should save (usually the character with the lowest relevant Attribute).

### Roll Under

To **succeed** on a [save](#saves), you need to roll **equal to or less** than the target number you're trying to beat. If you **roll above, you fail**. But the narrative result of such success or failure is not binary.

### The Gradient of Grace and Grief

In **Gradient**, every save roll uses **2d10** — with one die representing **Grace** and the other **Grief**. This system allows for a wider range of narrative outcomes for Successes and Failures.

To visually represent **Grace and Grief**, we suggest that each d10 dice have a **different color**.

#### Critical Success

Two equal dice are always a critical success.

#### Graceful Success
> You rolled the dice, and the summed result is equal to or less than the target you are trying to beat. The die representing Grace is higher than the die representing Grief.

The result is a successful save with its most optimal outcome.

#### Griefful Success
> You rolled the dice, and the summed result is equal to or less than the target you are trying to beat. The die representing Grief is higher than the die representing Grace.

A successful save, but with an undesired consequence.

#### Graceful Failure
> You rolled the dice, and the summed result is above the target you are trying to beat. The die representing Grace is higher than the die representing Grief.

A failed save, but with a less severe outcome than it could have been.

#### Griefful Failure (a.k.a. Critical Failure)
> You rolled the dice, and the summed result is above the target you are trying to beat. The die representing Grief is higher than the die representing Grace.

A failed save with the worst possible outcome.

### Save Roll Modifiers

- Certain conditions may require the Player Characters or the Warden to roll _enchanced_ or _impaired_ saves, adding or subtracting **1d4** to their roll result. 

## Non-Player Characters

### Hirelings

- Adventuring parties can recruit hirelings, relying on their unique skills, knowledge, and training to aid in expeditions. They are usually controlled by the **Warden**.
- Hirelings can be hired for currency, or they can be long-time, loyal companions.
- Hirelings are **Setting-Specific**.

For a reference set of **Setting** hireling rules, see [Gradient: Roots](settings/roots/setting-rules.md).

### Reactions

When the PCs encounter an NPC whose reaction to the party is not obvious, the Warden may roll 2d6 and consult the following table:

|         |      |         |      |         |
| :-----: | :--: | :-----: | :--: | :-----: |
|    2    | 3-5  |   6-8   | 9-11 |   12    |
| Hostile | Wary | Curious | Kind | Helpful |

## Combat

### Rounds

- A **Round** is roughly ten seconds of in-game time and and proceeds with each side taking turns. Each round starts with any PC that is able to act, followed by their opponents. _The result of each side's actions occur simultaneously_. 
- During the _first round of combat_, each PC must make a DEX save in order to act. Special circumstances, abilities, items, or skills may negate this requirement. PCs that fail their save _lose their turn_ for this round.
- Their opponents then take their turn, and the first round ends. The next round begins with the PCs taking their turn, followed by their opponents, and so on until combat has ended with one side defeated or fled.

### Actions

On their turn, a character may move up to 40ft and take up to one action. This may be casting a spell or using a power, attacking, moving for a second time, or some other reasonable action. Each round, the PCs declare what they are doing before dice are rolled. If a character attempts something risky, the Warden calls for a save for appropriate players or NPCs. 

### Attacking & Damage

- The attacker rolls their weapon die and subtracts the target's armor, then deals the remaining total to their opponent's HP. Attacks in combat automatically hit.
- If multiple attackers target the same foe, roll all damage dice and keep the single highest result. All actions are declared before being resolved.
- If an attack would take a PC's HP exactly to 0, refer to the [Scars](#scars-table) table to see how they are uniquely impacted.

### Attack Modifiers

- If fighting from a position of weakness (such as through cover or with bound hands), the attack is _Impaired_, and the attacker must roll 1d4 damage regardless of the attacks damage die. Unarmed attacks always do d4 damage.
- If fighting from a position of advantage (such as against a helpless foe or through a daring maneuver), the attack is _Enhanced_, allowing the attacker to roll **1d12** damage instead of their normal die.
- Attacks with the _Blast_ quality affect all targets in the noted area, rolling separately for each affected character. This can be anything from explosions to a dragon’s breath or the impact of a meteorite. If unsure how many targets can be affected, _roll the related damage die for a result_.
- If attacking with two weapons at the same time, roll both damage dice and keep the single highest result (denoted with a plus symbol, e.g. d8+d8).

### Critical Damage

- Damage that reduces a target's HP below zero is subtracted _from their STR_ by the amount of damage remaining. The target must then immediately make a STR save to avoid taking **Critical Damage**, using their _new STR score_. On a success, the target is still in the fight (albeit with a lower STR score) and must continue to make critical damage saves when incurring damage.
- Any PC that suffers Critical Damage cannot do anything but crawl weakly, grasping for life. If given aid (such as bandages), they will stabilize. If left untreated, they die within the hour. NPCs and monsters that fail a Critical Damage save are considered dead, per the **Warden's** discretion. Additionally, some enemies will have special abilities or effects that are triggered when their target fails a critical damage save. 

### Character Death

- When a character dies, the player should create a new character or take control of a hireling. They immediately join the party in order to reduce downtime.

### Detachments

- Large groups of similar combatants fighting together are treated as a single _Detachment_. When a _detachment_ takes **Critical Damage**, it is routed or significantly weakened. When it reaches 0 STR, it is destroyed.
- Attacks against detachments by individuals are _impaired_ (excluding _blast_ damage). Attacks against individuals by detachments are _enhanced_ and deal _blast_ damage.
  
### Retreat

- Running away from a dire situation always requires a successful DEX save, as well as a safe destination to run to.

### Morale

- Enemies must pass a WIL save to avoid fleeing when they take their first casualty and again when they lose half their number. 
- Some groups may use their leader's WIL in place of their own. Lone foes must save when they're reduced to 0 HP. 
- Morale does not affect PCs.

### Ranged Attacks

- Ranged weapons can target any enemy near enough to see the whites of their eyes. Attacks against especially distant targets are _Impaired_.
- Ammunition is not tracked unless otherwise specified. 

### Scars

If damage to a PC would reduce their HP to exactly 0, look up the result on the table below based on the _amount of HP lost in the attack_. For example, if a PC went from 3 HP to 0 HP, they would look at entry #3 (Walloped). 

#### Scars Table

|             |                                                                                                                                                                                                                           |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **HP Lost** | **Result**                                                                                                                                                                                                                |
| 1           | Lasting Scar: Roll 1d6. 1: Neck, 2: Hands, 3: Eye, 4: Chest, 5: Legs, 6: Ear. Roll 1d6. If the total is higher than your max HP, take the new result.                                                                     |
| 2           | Rattling Blow: You’re disoriented and shaken. Describe how you refocus. Roll 1d6. If the total is higher than your max HP, take the new result.                                                                           |
| 3           | Walloped: You’re sent flying and land flat on your face, winded. You are deprived until you rest for a few hours. Then, roll 1d6. Add that amount to your max HP.                                                         |
| 4           | Broken Limb: Roll 1d6. 1-2: Leg, 3-4: Arm, 5: Rib, 6: Skull. Once mended, roll 2d6. If the total is higher than your max HP, take the new result.                                                                         |
| 5           | Diseased: You’re afflicted with a gross, uncomfortable infection. When you get over it, roll 2d6. If the total is higher than your max HP, take the new result.                                                           |
| 6           | Reorienting Head Wound: Roll 1d6. 1-2: STR, 3-4: DEX, 5-6: WIL. Roll 3d6. If the total is higher than your current attribute, take the new result.                                                                        |
| 7           | Hamstrung: You can barely move until you get serious help and rest. After recovery, roll 3d6. If the total is higher than your max DEX, take the new result.                                                              |
| 8           | Deafened: You cannot hear anything until you find extraordinary aid. Regardless, make a WIL save. If you pass, increase your max WIL by 1d4.                                                                              |
| 9           | Re-brained: Some hidden part of your psyche is knocked loose. Roll 3d6. If the total is higher than your max WIL, take the new result.                                                                                    |
| 10          | Sundered: An appendage is torn off, crippled, or useless. (The Warden will tell you which.) Then make a WIL save. If you pass, increase your max WIL by 1d6.                                                              |
| 11          | Mortal Wound: You are deprived and out of action. You die in one hour unless healed. Upon recovery, roll 2d6. Take the new result as your max HP.                                                                         |
| 12          | Doomed: Death seemed ever so close, but somehow you survived. If your next save against critical damage is a fail, you die horribly. If you pass, roll 3d6. If the total is higher than your max HP, take the new result. |