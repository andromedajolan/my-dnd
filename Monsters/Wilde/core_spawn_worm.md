---
name: "Core Spawn Worm"
size: "Gargantuan"
monster_type: "aberration"
alignment: "Chaotic Evil"
cr: "15"
ac: "18 (natural armor)"
hp: "279 (18d20 + 90)"
speed: "walk 60 ft., burrow 40 ft."
str: 26
dex: 5
con: 20
int: 6
wis: 8
cha: 4
saves: "+10, +4"
skills: "+4"
immunities: "fire, psychic"
resistances: ""
vulnerabilities: "cold"
conditionImmunities: "charmed, frightened"
senses: "blindsight 30 ft., tremorsense 60 ft."
languages: "understands Deep Speech but can't speak"
image: ""
source: "EGW"
---

# Core Spawn Worm

*Gargantuan aberration, Chaotic Evil*

### Traits
***Illumination.*** The worm sheds dim light in a 20-foot radius.
***Radiant Mirror.*** If the worm takes radiant damage, each creature within 20 feet of it takes that damage as well.
***Tunneler.*** The worm can burrow through solid rock at half its burrowing speed and leaves a 10-foot-diameter tunnel in its wake.

### Actions
***Multiattack.*** The worm makes two attacks: one with its barbed tentacles and one with its bite.
***Barbed Tentacles.*** {@atk mw} {@hit 13} to hit, reach 10 ft., one creature. {@h}25 ({@damage 5d6 + 8}) piercing damage, and the target is {@condition grappled} (escape {@dc 18}). Until this grapple ends, the target is {@condition restrained}. The tentacles can grapple only one creature at a time.
***Bite.*** {@atk mw} {@hit 13} to hit, reach 10 ft., one target. {@h}30 ({@damage 5d8 + 8}) piercing damage. If the target is a Large or smaller creature, it must succeed on a {@dc 18} Dexterity saving throw or be swallowed by the worm. A swallowed creature is {@condition blinded} and {@condition restrained}, has {@quickref Cover||3||total cover} against attacks and other effects outside the worm, and takes 21 ({@damage 6d6}) fire damage at the start of each of the worm's turns. If the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a {@dc 21} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the worm. If the worm dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse by using 20 feet of movement, exiting {@condition prone}.

### Bonus Actions


### Reactions


### Legendary Actions

