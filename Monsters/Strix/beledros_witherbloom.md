---
name: "Beledros Witherbloom"
size: "Gargantuan"
monster_type: "dragon (druid)"
alignment: "Neutral Good"
cr: "24"
ac: "22 (natural armor)"
hp: "444 (24d20 + 192)"
speed: "walk 40 ft., fly 80 ft., swim 40 ft."
str: 28
dex: 14
con: 27
int: 18
wis: 28
cha: 17
saves: "+9, +15, +16, +10"
skills: "+18, +16, +18, +16"
immunities: "necrotic, poison"
resistances: ""
vulnerabilities: ""
conditionImmunities: "poisoned"
senses: "blindsight 120 ft."
languages: "Common, Draconic, Druidic, Sylvan"
image: ""
source: "SCC"
---

# Beledros Witherbloom

*Gargantuan dragon (druid), Neutral Good*

### Traits
***Legendary Resistance (3/Day).*** If Beledros fails a saving throw, she can choose to succeed instead.
***Unusual Nature.*** Beledros doesn't require air, food, or drink.

### Actions
***Multiattack.*** Beledros makes one Bite attack and two Claw attacks.
***Bite.*** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}14 ({@damage 1d10 + 9}) piercing damage plus 6 ({@damage 1d12}) necrotic damage.
***Claw.*** {@atk mw} {@hit 16} to hit, reach 10 ft., one target. {@h}12 ({@damage 1d6 + 9}) slashing damage. If the target is a Huge or smaller creature, it is knocked {@condition prone}.
***Decaying Breath {@recharge 5}.*** Beledros exhales decaying energy in a 90-foot cone. Each creature in that area must make a {@dc 23} Constitution saving throw, taking 39 ({@damage 6d12}) necrotic damage and 39 ({@damage 6d12}) poison damage on a failed save, or half as much damage on a successful one. A creature that takes damage from the breath can't regain hit points until the start of Beledros's next turn.
***Miasmal Flow.*** Beledros becomes a swirling cloud of green mist and can move up to half her flying speed without provoking opportunity attacks, then resumes her true form. During this movement, she can move through creatures and objects as if they were {@quickref difficult terrain||3}. If she moves through a creature, it must succeed on a {@dc 23} Constitution saving throw or become {@condition poisoned} until the end of its next turn. If Beledros ends this move inside an object, she takes 5 ({@damage 1d10}) force damage and is shunted to the nearest unoccupied space.

### Bonus Actions


### Reactions


### Legendary Actions
***Claw.*** Beledros makes one Claw attack.
***Miasmal Flow (Costs 2 Actions).*** Beledros uses Miasmal Flow.
***Teeming with Life (Costs 3 Actions).*** Beledros magically summons {@dice 1d4} {@creature pest mascot|SCC|pest mascots} in unoccupied spaces she can see within 60 feet of herself. The pests obey her commands and take their turns immediately after hers. Any creature, other than a pest, takes 9 ({@damage 2d8}) poison damage if it starts its turn within 5 feet of one or more of these pests. When one of these pests drops to 0 hit points, Beledros regains 9 hit points. These pests disappear after 10 minutes, when Beledros dies, or when she uses this action again.
