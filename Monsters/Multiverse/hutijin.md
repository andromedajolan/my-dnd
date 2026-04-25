---
name: "Hutijin"
size: "Large"
monster_type: "fiend (devil)"
alignment: "Lawful Evil"
cr: "21"
ac: "19 (natural armor)"
hp: "200 (16d10 + 112)"
speed: "walk 30 ft., fly 60 ft."
str: 27
dex: 15
con: 25
int: 23
wis: 19
cha: 25
saves: "+9, +14, +11"
skills: "+14, +11"
immunities: "fire, poison"
resistances: "cold, bludgeoning, piercing, slashing (from nonmagical attacks that aren't silvered)"
vulnerabilities: ""
conditionImmunities: "charmed, exhaustion, frightened, poisoned"
senses: "truesight 120 ft."
languages: "all, telepathy 120 ft."
image: ""
source: "MPMM"
---

# Hutijin

*Large fiend (devil), Lawful Evil*

### Traits
***Infernal Despair.*** Each creature within 30 feet of Hutijin that isn't a devil makes saving throws with disadvantage.
***Legendary Resistance (3/Day).*** If Hutijin fails a saving throw, he can choose to succeed instead.
***Magic Resistance.*** Hutijin has advantage on saving throws against spells and other magical effects.
***Regeneration.*** Hutijin regains 20 hit points at the start of his turn. If he takes radiant damage, this trait doesn't function at the start of his next turn. Hutijin dies only if he starts his turn with 0 hit points and doesn't regenerate.

### Actions
***Multiattack.*** Hutijin makes one Bite attack, one Claw attack, one Mace attack, and one Tail attack.
***Bite.*** {@atk mw} {@hit 15} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d6 + 8}) fire damage. The target must succeed on a {@dc 22} Constitution saving throw or become {@condition poisoned}. While {@condition poisoned} in this way, the target can't regain hit points, and it takes 10 ({@damage 3d6}) poison damage at the start of each of its turns. The {@condition poisoned} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
***Claw.*** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d8 + 8}) cold damage.
***Mace.*** {@atk mw} {@hit 15} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d6 + 8}) force damage.
***Tail.*** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}19 ({@damage 2d10 + 8}) thunder damage.
***Teleport.*** Hutijin teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.

### Bonus Actions


### Reactions
***Fearful Voice {@recharge 5}.*** In response to taking damage, Hutijin utters a dreadful word of power. Each creature within 30 feet of him that isn't a devil must succeed on a {@dc 22} Wisdom saving throw or become {@condition frightened} of him for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature that saves against this effect is immune to his Fearful Voice for 24 hours.

### Legendary Actions
***Attack.*** Hutijin makes one Claw, Mace, or Tail attack.
***Teleport.*** Hutijin uses Teleport.
***Lightning Storm (Costs 2 Actions).*** Hutijin releases lightning in a 30-foot radius, blocked only by {@quickref Cover||3||total cover}. All other creatures in that area must each make a {@dc 22} Dexterity saving throw, taking 18 ({@damage 4d8}) lightning damage on a failed save, or half as much damage on a successful one.
