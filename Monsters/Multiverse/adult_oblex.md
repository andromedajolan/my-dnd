---
name: "Adult Oblex"
size: "Medium"
monster_type: "ooze"
alignment: "Lawful Evil"
cr: "5"
ac: "14"
hp: "75 (10d8 + 30)"
speed: "walk 20 ft."
str: 8
dex: 19
con: 16
int: 19
wis: 12
cha: 15
saves: "+7, +5"
skills: "+5, +4, [{'oneOf': {'arcana': '+7', 'history': '+7', 'nature': '+7', 'religion': '+7'}}]"
immunities: ""
resistances: ""
vulnerabilities: ""
conditionImmunities: "blinded, charmed, deafened, exhaustion, prone"
senses: "blindsight 60 ft. (blind beyond this distance)"
languages: "Common plus two more languages"
image: ""
source: "MPMM"
---

# Adult Oblex

*Medium ooze, Lawful Evil*

### Traits
***Amorphous.*** The oblex can move through a space as narrow as 1 inch wide without squeezing.
***Aversion to Fire.*** If the oblex takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.
***Unusual Nature.*** The oblex doesn't require sleep.

### Actions
***Multiattack.*** The oblex makes two pseudopod attacks, and it uses Eat Memories.
***Pseudopod.*** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) bludgeoning damage plus 7 ({@damage 2d6}) psychic damage.
***Eat Memories.*** The oblex targets one creature it can see within 5 feet of it. The target must succeed on a {@dc 15} Wisdom saving throw or take 18 ({@damage 4d8}) psychic damage and become memory drained until it finishes a short or long rest or until it benefits from the {@spell greater restoration} or {@spell heal} spell. Constructs, Oozes, Plants, and Undead succeed on the save automatically. While memory drained, the target must roll a {@dice d4} and subtract the number rolled from its ability checks and attack rolls. Each time the target is memory drained beyond the first, the die size increases by one: the {@dice d4} becomes a {@dice d6}, the {@dice d6} becomes a {@dice d8}, and so on until the die becomes a {@dice d20}, at which point the target becomes {@condition unconscious} for 1 hour. The effect then ends. The oblex learns all the languages a memory-drained target knows and gains all its skill proficiencies.

### Bonus Actions
***Sulfurous Impersonation.*** The oblex extrudes a piece of itself that assumes the appearance of one Medium or smaller creature whose memories it has stolen. This simulacrum appears, feels, and sounds exactly like the creature it impersonates, though it smells faintly of sulfur. The oblex can impersonate {@dice 1d4 + 1} different creatures, each one tethered to its body by a strand of slime that can extend up to 120 feet away. The simulacrum is an extension of the oblex, meaning that the oblex occupies its space and the simulacrum's space simultaneously. The tether is immune to damage, but it is severed if there is no opening at least 1 inch wide between the oblex and the simulacrum. The simulacrum disappears if the tether is severed.

### Reactions


### Legendary Actions

