# Mechanics

## Ability Score System
Ability scores should represent have some correspondence to reality but be optimized for gameplay.

We have the following three categories, each of which hold a set of 6 scores each.

  * Physical
  * Spirit
  * Arcane

The six scores that each category holds are:

  * Might -- damage
  * Prowess -- hit points, power points, divine points
  * Focus -- crit %
  * Sense -- detect divine, detect magic
  * Haste -- movement speed, attack speed
  * Reaction -- dodge %

Some species, such as the ghostly ones, would derive their character movement speed from their Spirit Haste stat. Others, such as the golems, would derive their movement speed from their Arcane Haste stat.

### Skills
All skills are individually leveled. Each skill also has an Efficiency %. This % decreases when the skill is not used to a minimum value determined by the total level in the skill.

Melee, Arcane, and Spirit skills are all divided into major groups with focuses within.

#### Non-combat

`*` denotes multiple uses.
`P` nenotes passive.

  * Dungeoneering skills
    * Disarm trap
    * Trapfinding (detect traps) P
    * Detect Arcane P
    * Detect Divine P
  * Resource-acquiring skills
    * Woodcutting?
    * Farming (maybe)
    * Mining
    * Fishing
    * Herbalism *
  * "Crafting" skills
    * Smithing *
    * Fletching
    * Trapmaking (are there arcane and/or divine traps?)
    * Herbalism *
    * Alchemy *
    * Endow (apply magic effects to items)
  * Knowledge skills
    * Jeweler (ability to identify magic rings, etc?)
    * Smithing * (ability to identify arms and armor)
    * Herbalism * (ability to identify components)
    * Alchemy * (ability to identify potions)
    * Arcane Literacy (ability to learn from spellbooks)
    * Divine Literacy (ability to learn from divine books)

#### Combat
Combat style has a primary category that corresponds to the type of motion used:

  * Swinging
    * Swords
    * Hammers
    * Flails
  * Thrusting
    * Daggers
    * Javelins
    * Rapiers
  
In addition to this, there are these additional skills:

  * Two-handed Weapons - generally heavy weapons that receive bonus effects from Might.
  * Shield use (adds to defense - can potential use shield bashing?)
  * Two-weapon Fighting - can be light weapons or heavy weapons. Generally best for high crits.

Ranged
  * Drawn (Might)
    * Bow (pierce)
  * Thrown (Might)
    * Rocks (impact)
    * Axes (slash)
    * Darts (pierce)
  * Aimed
    * Crossbow (pierce)
    * Handcannons (impact)
    * Wand(?)

Arcane
  * Ray
  * Cone
  * Explosion
  * Channel

  * Kinetic (force effects)
  * Temperature (freeze&fire)
  * Materialize (creation, summoning)

Spirit
  * Lifeforce
    * Heal
    * Harm
  * Mental Guidance
    * Bless (bonus to hit, etc.)
    * Confuse (reduction of skills, etc.)
  * Imbue (physically changing effects)
    * Protect (damage absorption, etc.)
    * Weaken (reduce armor, etc.)

  * Heal/Harm
  * Bless/Curse
  * Protect

#### Attack Rolls
Skill cap = Level*2?

  * Might -- damage
  * Prowess -- hit points, power points, divine points
  * Focus -- crit %
  * Sense -- detect divine, detect magic
  * Haste -- movement speed, attack speed
  * Reaction -- dodge %

~~To Hit: (Skill * Efficiency) + Skill Focus~~
~~To Hit: (4 * 0.80%) + 2~~
Damage: Sword Damage + (Skill + Skill Focus) * Efficiency + Might * 2
Damage: 1d6(x1.5) + (4+2) * 0.80% + 3 = 4 + 3 = (1 to 6) + 7
Crit: Focus * 2
Crit: 4 * 2 = 8%
Dodge: Reaction * 2 + Haste
Dodge: 4 * 2 + 4 = 12%
Armor: Armor Vs. AttackType + (Skill + Skill Focus) * Efficiency
Armor: 6 + (4 + 2 * 0.80%) = 10
On Hit: 0 to -4 hp, potentially -3 to -10

HP: Prowess * 16
HP: 4 * 16 = 64 hp

Statistics start at 1 per default. Minimum damages:
Damage: 1d6(x1.5) + (1+0) * 80% + 1*2 = (1 to 6) + 2
Crit: 1 * 2 = 2%
Dodge: 1*2 + 1 = 3%
Armor: 2 + (1+0) * 80% = 3
On Hit: 0 to -4 hp, potentially 0 to -9

HP: 1 * 16 = 16

What if armor was a bit more complex and had its own damaged percentage that would reduce its armor values by the given %?

What if armor, in terms of damage reduction, was % based?

Level 4-ish:
Armor: Armor% + ((Skill + Skill Focus) * Efficiency * Armor%)
Armor: 30% + 1% = 31% damage reduction
On Hit: -4 to -8 hp, potentially -8 to -13

Level 1:
Armor: 20% + 0% = 20% damage reduction
On Hit: -2 to -6 hp, potentially -3 to -9 hp

----

Damage: Weapon + ((Skill + Skill Focus) * Efficiency) + Might
Crit: Focus * 2 = % chance to multiple Damage by Weapon's crit
Armor%: Base Armor% * (100% - Damaged%)
Armor: Armor% + ((Skill + Skill Focus) * Efficiency * Armor%)

Potentially Dodge should also use a skill that provides bonuses at a rate similar to Armor %. Criticals should also be trainable in a similar fashion.

Maybe:
Crit: (Focus*2/100) + ( (Crit Skill + Weapon Focus) * Efficiency * (Focus*2/100) )
Dodge: (Reaction*2/100) + ( (Dodge Skill + ???) * Efficiency * (Reaction*2/100) )
