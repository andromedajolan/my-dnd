---
name: "Daemogoth Titan"
size: "Gargantuan"
monster_type: "fiend"
alignment: "Chaotic Evil"
cr: "16"
ac: "17 (natural armor)"
hp: "203 (11d20 + 88)"
speed: "walk 40 ft."
str: 26
dex: 10
con: 26
int: 24
wis: 18
cha: 20
saves: "+12, +9, +10"
skills: "+17, +15, +12, +9"
immunities: "psychic"
resistances: ""
vulnerabilities: ""
conditionImmunities: "charmed, frightened"
senses: "truesight 120 ft."
languages: "Abyssal, Infernal, telepathy 120 ft."
image: ""
source: "SCC"
---

# Daemogoth Titan

*Gargantuan fiend, Chaotic Evil*

### Traits
***Legendary Resistance (3/Day).*** If the titan fails a saving throw, it can choose to succeed instead.
***Pact of Suffering.*** Using a 10-minute long ritual, the titan can forge a magical bond with a willing creature it touches throughout the ritual. The creature becomes bound by the pact until it dies, the titan dies, or the pact is broken by a {@spell wish} spell. The titan chooses one spell from the {@filter necromancy or enchantment school that is 8th level or lower|spells|level=0;1;2;3;4;5;6;7;8|school=N;E}. The bound creature can cast that spell using this pact, requiring no material components and using Intelligence as the spellcasting ability. When it casts the spell, the creature takes 21 ({@damage 6d6}) psychic damage, which can't break the creature's {@status concentration} on a spell. Once the bound creature casts the spell in this way, it can't do so again until it finishes a long rest.

### Actions
***Multiattack.*** The titan makes two Agonizing Burst attacks.
***Agonizing Burst.*** {@atk ms,rs} {@hit 12} to hit, reach 15 ft. or range 120 ft., one target. {@h}17 ({@damage 3d6 + 7}) force damage. If the target is a creature, the titan regains 5 hit points.
***Teleport.*** The titan teleports to an unoccupied space it can see within 120 feet of itself.

### Bonus Actions


### Reactions


### Legendary Actions
***Attack.*** The titan makes one Agonizing Burst attack.
***Stalking Nightmare (Costs 2 Actions).*** The titan uses Teleport, after which it can target one creature within 20 feet of itself that it can see. The target must make a {@dc 20} Constitution saving throw. On a failed save, the target takes 22 ({@damage 4d10}) necrotic damage, and the titan regains 10 hit points. On a successful save, the target takes half as much damage, and the titan doesn't heal.
***Terrorize (Costs 3 Actions).*** The titan targets one creature it can see within 120 feet of itself. The target must make a {@dc 20} Wisdom saving throw. On a failed save, the target takes 38 ({@damage 7d10}) psychic damage and is {@condition frightened} of the titan until the end of the target's next turn, and the titan regains 15 hit points. On a successful save, the target takes half as much damage and isn't {@condition frightened}, and the titan doesn't heal.
