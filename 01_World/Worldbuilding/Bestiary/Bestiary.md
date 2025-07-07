
## Blighted and Cursed
### Blighted Dryads 
Once benevolent tree spirits corrupted by dark magic. Blighted Dryads have become twisted and malevolent. They manipulate the forest itself causing plants to wither and decay, they unleash spells of decay and despair upon those who intrude upon their territory.  Blighted Dryads are most common within the [[Whispering Vale]], but can also be found in the [[Ethereal Veil]].
```statblock 
layout: Basic 5e Layout
name: "Blighted Dryads"
image: [[image]]
size: "Medium"
type: "Fey"
subtype: "Blightborn"
ac: "11 (16 With Barkskin)"
hp: "22"
hit_dice: 5d8
speed: "30 ft."
stats: [10,12,11,14,15,18]
skillsaves: 
 - perception: +4
 - stealth: +5
senses: "Darkvision 60ft Passive Perception 14"
languages: "Elvish, Sylvan"
cr: 1
traits:
 - name: Magic Resistance 
   desc: Has advantage on saving throws against spells and other magical effects.
 - name: "Blighted Constitution"
   desc: "Advantage on saving throws against being charmed, poisoned, or diseased."
 - name: Tree Stride
   desc: Once on turn can cuse 10 ft of movement to step magically into one living tree within her reach and emerge from a second living tree within 60ft of the first, appearing in an unoccupies space within 5ft. of the second tree. both trees must be large or bigger.
 - name: "Blighted Magic"
   desc: "Spare the dying cantrip. 3rd level, can cast the false life spell as a 2nd level spell once with this trait and regain the abilith to do so when after long rest. 5th level, can cast blooming death once with this trait and regain the ability to do so after a long rest. Charisma is spell casting ability,"
actions: 
 - name: "Club"
   desc: "Melee Weapon attack: +2 to hit, reach 5 ft., one target. Hit: (1d4) bludgeoning damage"
 - name: "Club (with shillelagh)"
   desc: "Melee Weapon attack: +6 to hit, reach 5 ft., one target. Hit: (1d8+4) bludgeoning damage"
 - name: "Fey Charm"
   desc: Targets 1 humanoid or beast that they can see within 30 ft. If they can see the dryad, make DC 14 WIS saving throw or be [[Conditions#Charmed | charmed]] . Each time the dryad of its allies do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise the effect lasts 24 hrs or until the dryad dies, is on another plane, or ends the effects as a bonus action. If the target's saving throw is successful, the target is immune to the Fey Charm for 24 hrs. Cannot have more than 1 homanoid and 3 beasts charmed at a time.

column: 2
forceColumns: true
```

### Corrupt Fey
These once beautiful and benevolent creatures have been corrupted by the dark forces that dwell deep within the Whispering Vale. From years or neglect or the dark nature of the forest itself, no one is quite sure what has ruined these creatures. Corrupt Fey use their innate magical abilities to manipulate the mist that surrounds every crevice of the Whispering Vale. They are able to ensnare travelers and manipulate the mist into leading them into traps or luring them into despair.



```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Corrupt Fey"
size: "Medium"
type: "fey"
alignment: "chaotic evil"
ac: "15 (natural armor)"
hp: "65 (10d8 + 20)"
hit_dice: "10d8 + 20"
speed: "30 ft."
stats: [12, 16, 14, 13, 14, 18]
saves:
  - wisdom: "4"
  - charisma: "6"
skillsaves:
  - deception: "6"
  - perception: "4"
  - stealth: "5"
damage_resistances: "bludgeoning, piercing, and slashing from nonmagical attacks"
damage_vulnerabilities: "cold iron"
condition_immunities: "charmed"
senses: "darkvision 60 ft., passive Perception 14"
languages: "Common, Sylvan"
cr: "3"
traits:
  - name: "Fey Ancestry"
    desc: "The corrupt fey has advantage on saving throws against being charmed, and magic can't put it to sleep."
  - name: "Magic Resistance"
    desc: "The corrupt fey has advantage on saving throws against spells and other magical effects."
  - name: "Mist Dependency"
    desc: "If the mist within 30 feet of the corrupt fey is dispersed (such as by a strong wind or magic), the fey becomes vulnerable to all damage types until the end of its next turn."
actions:
  - name: "Corrupted Touch"
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6 + 3) necrotic damage, and the target must succeed on a DC 14 Constitution saving throw or be poisoned until the end of its next turn."
  - name: "Haunting Whispers"
    desc: "The corrupt fey targets one creature it can see within 60 feet. The target must succeed on a DC 14 Wisdom saving throw or take 10 (3d6) psychic damage and become frightened of the fey until the end of the fey's next turn. <br> *Cold mist swirls around the target, engulfing them.* "
  - name: "Mist Manipulation"
    desc: "The corrupt fey manipulates the surrounding mist. It can use this ability in one of two ways:<br>- Restrain: One creature the fey can see within 30 feet must succeed on a DC 14 Strength saving throw or be restrained by tendrils of mist until the end of the fey's next turn.<br>- Illusory Path: The fey creates an illusory path up to 60 feet long and 10 feet wide. Any creature that can see the path must succeed on a DC 14 Intelligence (Investigation) check to recognize it as an illusion. A creature that fails this check believes the path is real and safe to traverse, potentially leading them into danger."
```





### Cursed Treant
Once guardians of the forest, these ancient treants have been consumed by malevolent forces. Cursed Treants wield powerful nature-based magic to unleash devastating spells and summon corrupted creatures to aid them in their dark purpose. Faces seem to form and dissolve against the bark.


```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Cursed Treant"
size: "Huge"
type: "plant"
alignment: "chaotic evil"
ac: "16 (natural armor)"
hp: "138 (12d12 + 60)"
hit_dice: "12d12 + 60"
speed: "30 ft."
stats: [23, 8, 21, 12, 16, 12]
damage_resistances: "bludgeoning, piercing"
damage_vulnerabilities: "fire"
condition_immunities: "charmed, frightened"
senses: "darkvision 60 ft., passive Perception 13"
languages: "Common, Druidic, Elvish, Sylvan"
cr: "7"
traits:
  - name: "False Appearance"
    desc: "While the treant remains motionless, it is indistinguishable from a normal tree."
  - name: "Siege Monster"
    desc: "The treant deals double damage to objects and structures."
actions:
  - name: "Multiattack"
    desc: "The treant makes two slam attacks."
  - name: "Slam"
    desc: "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 19 (3d8 + 6) bludgeoning damage."
  - name: "Rock"
    desc: "Ranged Weapon Attack: +9 to hit, range 60/180 ft., one target. Hit: 28 (4d10 + 6) bludgeoning damage."
  - name: "Corrupting Aura (Recharge 5-6)"
    desc: "The treant releases a pulse of corrupting energy. Each creature within 30 feet must make a DC 15 Constitution saving throw. On a failed save, a creature takes 18 (4d8) necrotic damage and is poisoned until the end of its next turn. On a successful save, the creature takes half as much damage and isn't poisoned."
  - name: "Animate Corrupted Plants (1/Day)"
    desc: "The treant magically animates one or two trees it can see within 60 feet of it. These trees have the same statistics as a corrupted awakened tree (use awakened tree stats, but change alignment to chaotic evil and add 7 (2d6) necrotic damage to its slam attack). An animated tree acts as an ally of the treant. The tree remains animate for 1 day or until it dies; until the treant dies or is more than 120 feet from the tree; or until the treant takes a bonus action to turn it back into an inanimate tree. The tree then takes root if possible."
bonus_actions:
  - name: "Summon Corrupt Creatures (1/Day)"
    desc: "The treant summons 1d4 + 1 corrupted woodland creatures. These can be wolves, bears, or other appropriate CR 1 or lower beasts, twisted by the forest's corruption. The summoned creatures appear in unoccupied spaces within 60 feet of the treant and act as its allies. They remain for 1 minute, until the treant dies, or until the treant dismisses them as an action."
```

## Dryads
### Base Dryads
Characters may encounter a powerful dryad residing in a grand ancient tree who shares ancient knowledge about the forest's secrets or provides magical boons to those deemed worthy.
## Golems 
### Celestial Golem
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Celestial Golem"
size: "Large"
type: "Construct"
alignment: "Lawful Good"
ac: "18 (Natural Armor)"
hp: "136 (16d10 + 48)"
hit_dice: "16d10 + 48"
speed: "30 ft."
stats: [20, 12, 18, 10, 16, 12]
saves:
  - Str: "8"
  - Con: "7"
  - Wis: "6"
skillsaves:
  - Perception: "13"
damage_vulnerabilities: “Bludgeoning”
damage_resistances: "Radiant, Force, Necrotic, Piercing, and Slashing from Nonmagical Attacks"
damage_immunities: "Poison, Disease, Psychic, Blight"
condition_immunities: "Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 13"
languages: "Understands Celestial, Primordial, and the languages of its creator but cannot speak, except for a rare few"
cr: "7"
traits:
  - name: "Sunfire Core (Regeneration)"
    desc: "The [[Sunfire Crystal]]s embedded in the golem's chest grants it the ability to regenerate. The Celestial Golem regains 10 hit points at the start of its turn if it has at least 1 hit point and isn't in an area of magical darkness. If the golem takes necrotic damage, this trait doesn't function at the start of the golem's next turn."
  - name: "Erosion"
    desc: "The Celestial Golem is subject to gradual erosion over time. For every month without maintenance, it loses 1 point of its maximum hit points. These lost hit points can be restored through special repairs involving [[Sunfire Crystal]]s and stardust."
  - name: "Celestial Fragments"
    desc: "The floating meteorite fragments surrounding the golem provide it with additional power:<br>**Temporal Displacement**: Once per day, the golem can shift itself 5 feet in any direction as a reaction, avoiding an attack that would hit it.<br>**Stardust Shield**: The golem can use an action to create a radiant shield of stardust, granting itself and all allies within 10 feet a +2 bonus to AC for 1 minute."
  - name: "Immutable Form"
    desc: "The Celestial Golem is immune to any spell or effect that would alter its form."
  - name: "Magic Resistance"
    desc: "The Celestial Golem has advantage on saving throws against spells and other magical effects."
  - name: "Magic Weapons"
    desc: "The Celestial Golem’s weapon attacks are magical."
actions:
  - name: "Multiattack"
    desc: "The Celestial Golem makes two attacks with its Celestial Slam."
  - name: "Celestial Slam"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 19 (3d8 + 5) bludgeoning damage plus 7 (2d6) radiant damage."
  - name: "Temporal Stasis (Recharge 5-6)"
    desc: "The golem targets one creature it can see within 30 feet of it. The target must succeed on a DC 16 Wisdom saving throw or be frozen in time for 1 minute. While frozen, the target is incapacitated and immune to all damage. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
  - name: "Meteoric Strike (Recharge 6)"
    desc: "The golem channels the power of the floating meteorites and hurls them at a point within 60 feet. Each creature in a 15-foot-radius sphere centered on that point must make a DC 16 Dexterity saving throw, taking 27 (6d8) bludgeoning damage and 13 (3d8) radiant damage on a failed save, or half as much damage on a successful one."
reactions:
  - name: "Celestial Reprisal"
    desc: "When the Celestial Golem is hit by a melee attack, it can use its reaction to release a burst of radiant energy. The attacker must make a DC 16 Constitution saving throw or take 14 (4d6) radiant damage and be blinded until the end of their next turn."
column: 2
forceColumns: true

```
### Etheric Warden Golem 

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Etheric Warden Golem"
size: "Large"
type: "Construct"
alignment: "Lawful Neutral"
ac: "17 (Natural Armor)"
hp: "102 (12d10 + 36)"
hit_dice: "12d10 + 36"
speed: "30 ft., Fly 30 ft. (Hover)"
stats: [18, 14, 16, 10, 12, 10]
saves:
  - Str: "8"
  - Dex: "6"
  - Con: "7"
  - Wis: "5"
skillsaves:
  - Perception: "11"
damage_vulnerabilities: “Bludgeoning”
damage_resistances: "Piercing, and Slashing from Nonmagical Attacks"
damage_immunities: "Poison, Psychic"
condition_immunities: "Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 11"
languages: "Understands the languages of its creator but cannot speak"
cr: "6"
traits:
  - name: "Anti-Gravity Field"
    desc: "The Etheric Warden Golem generates a 20-foot radius anti-gravity field centered on itself. This field affects the following:<br>**Flight Restriction**: Flying creatures within this field must succeed on a DC 15 Dexterity saving throw or have their flight reduced to 0 feet until the end of their next turn.<br>**Weight Manipulation**: Large or smaller creatures within the field have disadvantage on Strength checks and saving throws."
  - name: "Ethereal Fragments"
    desc: "The floating, ethereal fragments surrounding the golem provide it with the following benefits:<br>**Ethereal Resilience**: The golem has resistance to force damage.<br>**Displacement**: The golem’s form is partially insubstantial, granting it advantage on Dexterity saving throws against attacks that rely on sight."
  - name: "Immutable Form"
    desc: "The Etheric Warden Golem is immune to any spell or effect that would alter its form."
  - name: "Magic Resistance"
    desc: "The Etheric Warden Golem has advantage on saving throws against spells and other magical effects."
  - name: "Magic Weapons"
    desc: "The Etheric Warden Golem’s weapon attacks are magical."
actions:
  - name: "Multiattack"
    desc: "The Etheric Warden Golem makes two attacks with its Crystalline Slam."
  - name: "Crystalline Slam"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 22 (3d10 + 4) bludgeoning damage."
  - name: "Gravity Pulse (Recharge 5-6)"
    desc: "The golem emits a pulse of anti-gravity energy in a 20-foot radius. Each creature of its choice within that area must make a DC 15 Constitution saving throw, taking 27 (6d8) force damage on a failed save, or half as much damage on a successful one. Additionally, affected creatures are pushed 10 feet away from the golem and are restrained until the end of their next turn."
  - name: "Meteoric Barrage (Recharge 6)"
    desc: "The golem summons fragments of floating rock to pelt enemies. Each creature in a 15-foot-radius sphere centered on a point within 60 feet of the golem must make a DC 15 Dexterity saving throw. On a failed save, a creature takes 22 (5d8) bludgeoning damage and is knocked prone. On a successful save, the creature takes half damage and is not knocked prone."
reactions:
  - name: "Gravitational Deflection"
    desc: "When the Etheric Warden Golem is hit by an attack, it can use its reaction to create a gravitational distortion field, imposing disadvantage on the attack roll."
```
### Solar Golem
**Behavior and Tactics**
Solar Golems are resolute guardians, designed to protect and alert. When reduced to half health, they will activate their siren to call for reinforcements. If other golems are in the area, they will converge on the location to provide aid. Players will need to act quickly to disable the siren or risk facing multiple golems at once. This makes encounters with Solar Golems more tactical, encouraging players to think creatively about how to handle the situation. The Golem fights fiercely to protect its charges, using its radiant aura to weaken enemies while shielding allies. If confronted in sunlight, it becomes even more formidable, but its vulnerabilities to dark magic and non-magical attacks give clever opponents an opportunity to bring it down.
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Solar Golem"
size: "Large"
type: "Construct"
alignment: "Lawful Neutral"
ac: "19 (Natural Armor)"
hp: "152 (16d10 + 64)"
hit_dice: "16d10 + 64"
speed: "30 ft."
stats: [22, 12, 18, 6, 14, 10]
saves:
  - Str: "10"
  - Con: "8"
  - Wis: "6"
skillsaves:
  - Perception: "12"
damage_resistances: "Fire, Radiant"
damage_vulnerabilities: "Necrotic, Bludgeoning, Piercing, and Slashing from Nonmagical Attacks"
condition_immunities: "Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 12"
languages: "Understands the languages of its creator but cannot speak"
cr: "10 (5,900 XP)"
traits:
  - name: "Radiant Aura"
    desc: "The Solar Golem emits an aura of radiant energy in a 15-foot radius around it. Any hostile creature that starts its turn within the aura must succeed on a DC 16 Constitution saving throw or take 10 (3d6) radiant damage. Additionally, allies within the aura gain 5 temporary hit points at the start of their turn."
  - name: "Sunlight Absorption"
    desc: "When the Solar Golem is in direct sunlight, it regenerates 10 hit points at the start of its turn. If the Golem takes necrotic damage, this trait doesn’t function at the start of the Golem’s next turn."
  - name: "Immutable Form"
    desc: "The Solar Golem is immune to any spell or effect that would alter its form."
  - name: "Magic Resistance"
    desc: "The Solar Golem has advantage on saving throws against spells and other magical effects."
  - name: "Magic Weapons"
    desc: "The Solar Golem’s weapon attacks are magical."
  - name: "Siren Alert"
    desc: "When the Solar Golem drops below half of its maximum hit points (76 HP), it emits a loud, piercing siren. All constructs within a 60-foot radius are alerted to its distress and will begin moving toward the Solar Golem's location. These constructs will arrive at the start of the Solar Golem's next turn if they are within range. The siren can be heard clearly up to 300 feet away, and muffled up to 600 feet away. <br>**Countering the Siren**: A creature can use an action to make a DC 18 Intelligence (Arcana) or Wisdom (Insight) check to identify the mechanism producing the siren. If successful, the creature can attempt to disable it by making a DC 18 Dexterity (Thieves' Tools) check as an action. If successful, the siren is disabled, and no alert is sent."
actions:
  - name: "Multiattack"
    desc: "The Solar Golem makes two attacks with its Radiant Strike."
  - name: "Radiant Strike"
    desc: "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 22 (3d10 + 6) bludgeoning damage plus 10 (3d6) radiant damage."
  - name: "Solar Beam (Recharge 5-6)"
    desc: "The Solar Golem releases a concentrated beam of solar energy in a 60-foot line that is 5 feet wide. Each creature in that line must make a DC 18 Dexterity saving throw, taking 49 (11d8) radiant damage on a failed save, or half as much damage on a successful one. This beam counts as sunlight for the purposes of creatures with sunlight sensitivity or sunlight vulnerability."
  - name: "Blinding Flash (Recharge 6)"
    desc: "The Solar Golem emits a burst of intense light. Each creature within 30 feet of the golem that can see it must succeed on a DC 16 Constitution saving throw or be blinded for 1 minute. A blinded creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
legendary_actions:
  - name: "Solar Shield"
    desc: "When the Solar Golem is hit by an attack, it can use its reaction to create a shield of radiant energy, granting it a +4 bonus to AC until the start of its next turn, including against the triggering attack."
```
## Legendary
### Glacier Serpent
This beast is not awoken until after all the groves have been healed. 
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Glacier Serpent"
size: "Colossal"
type: "Monstrosity"
alignment: "Neutral"
ac: "18 (Natural Armor)"
hp: "325 (25d20 + 150)"
hit_dice: "25d20 + 150"
speed: "20 ft., climb 20 ft., swim 40 ft."
stats: [30, 8, 25, 10, 16, 14]
saves:
  - Con: "14"
  - Wis: "10"
skillsaves:
  - Perception: "10"
  - Stealth: "11"
damage_resistances: "Cold, Bludgeoning from nonmagical attacks"
damage_immunities: "Poison"
condition_immunities: "[[Mechanics#Frightened|Frightened]], [[Mechanics#Paralyzed|Paralyzed]], [[Mechanics#Exhaustion|Exhaustion]]"
senses: "[[Mechanics#Blindsight|Blindsight]] 120 ft., [[Mechanics#Tremorsense|Tremorsense]] 240 ft., Passive Perception 20"
languages: "Primordial (understands but cannot speak)"
cr: "18"
traits:
  - name: "Living Landscape"
    desc: "The Glacier Serpent's massive body is covered in a thick layer of snow and ice, forming a deceptive landscape. Creatures can unknowingly walk on its surface without realizing they're on a living being. The serpent can sense all creatures on its body and can choose to ignore or interact with them. Small settlements or structures built on the serpent remain undisturbed unless it chooses to move."
  - name: "Frozen Ecosystem"
    desc: "The Glacier Serpent's body hosts a unique ecosystem of ice-adapted flora and fauna. These creatures are considered part of the serpent and can act independently to defend it. As a bonus action, the serpent can awaken 1d4 + 2 Ice Guardians (use [[Mechanics#Animated Armor|Animated Armor]] stats with cold immunity) within 120 feet of it."
  - name: "Thawed Memories"
    desc: "Ancient creatures and artifacts are sometimes frozen within the Glacier Serpent's body. When the serpent takes fire damage, roll a d20. On a 18-20, a random effect occurs: a creature or object emerges from the ice, potentially aiding or hindering nearby creatures."
  - name: "Shifting Terrain"
    desc: "The area within 60 feet of the Glacier Serpent is considered difficult terrain due to the constantly shifting ice and snow. Additionally, at the start of each of the serpent's turns, the terrain within this area changes. Creatures in the area must succeed on a DC 18 Dexterity saving throw or fall [[Mechanics#Prone|prone]]."
actions:
  - name: "Multiattack"
    desc: "The Glacier Serpent makes two attacks: one with its Bite and one with its Tail Swipe."
  - name: "Bite"
    desc: "Melee Weapon Attack: +17 to hit, reach 20 ft., one target. Hit: 36 (4d12 + 10) piercing damage plus 18 (4d8) cold damage. If the target is Huge or smaller, it must succeed on a DC 22 Strength saving throw or be swallowed. A swallowed creature is [[Mechanics#Blinded|blinded]] and [[Mechanics#Restrained|restrained]], has total cover against attacks from outside the serpent, and takes 36 (8d8) cold damage at the start of each of the serpent's turns.<br>If the Glacier Serpent takes 60 damage or more on a single turn from a creature inside it, it must succeed on a DC 22 Constitution saving throw or regurgitate all swallowed creatures, which fall [[Mechanics#Prone|prone]] in a space within 30 feet of the serpent. If the serpent dies, a swallowed creature is no longer [[Mechanics#Restrained|restrained]] by it and can escape from the corpse by using 60 feet of movement, exiting [[Mechanics#Prone|prone]]."
  - name: "Tail Swipe"
    desc: "Melee Weapon Attack: +17 to hit, reach 40 ft., all creatures in a 40-foot line. Hit: 28 (4d8 + 10) bludgeoning damage plus 18 (4d8) cold damage. All creatures hit by the Tail Swipe must succeed on a DC 22 Strength saving throw or be knocked [[Mechanics#Prone|prone]] and pushed 20 feet away from the serpent."
  - name: "Glacial Maw (Recharge 5-6)"
    desc: "The Glacier Serpent opens its massive maw, creating a swirling vortex of icy wind and sharp ice shards in a 90-foot cone. Each creature in that area must make a DC 22 Dexterity saving throw. On a failed save, a creature takes 56 (16d6) cold damage and becomes [[Mechanics#Restrained|restrained]] by ice until the end of its next turn. On a successful save, the creature takes half as much damage and isn't [[Mechanics#Restrained|restrained]]. The area within the cone becomes difficult terrain until the end of the serpent's next turn."
legendary_actions:
  - name: "The Glacier Serpent can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature's turn. The Glacier Serpent regains spent legendary actions at the start of its turn."
  - name: "Tail Lash"
    desc: "The Glacier Serpent makes a Tail Swipe attack."
  - name: "Glacial Shift (Costs 2 Actions)"
    desc: "The Glacier Serpent subtly moves its body, causing the icy landscape to shift dramatically. Each creature within 60 feet of the serpent must succeed on a DC 18 Dexterity saving throw or fall 60 feet into a suddenly-opened crevasse, taking 21 (6d6) bludgeoning damage and becoming [[Mechanics#Restrained|restrained]]. A [[Mechanics#Restrained|restrained]] creature can use its action to make a DC 18 Strength (Athletics) or Dexterity (Acrobatics) check to escape."
  - name: "Awaken Frozen Horror (Costs 3 Actions)"
    desc: "The Glacier Serpent expels a long-frozen creature from its icy body. An Ice Golem (use [[Mechanics#Stone Golem|Stone Golem]] stats with cold immunity instead of poison) emerges in an unoccupied space within 60 feet of the serpent and acts immediately on the serpent's initiative. The Ice Golem crumbles after 1 minute or when reduced to 0 hit points."
```

### Magma Sentinel
Huge gate-keeper esque golem made of stone and magma. Has 3-4 arms, and a large almost mechanical looking head. This creature lives deep within an active volcano. It sits, constantly submerged within a large molten lake and will protect the sanctity of the volcano. They act as guardians. For the most part things that are smaller than them they ignore unless they are annoyed. This is considered a legendary creature. It probably has a cr of around 10-13

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Magma Sentinel"
size: "Huge"
type: "Construct"
alignment: "Lawful Neutral"
ac: "21 (Enhanced Natural Armor)"
hp: "276 (24d12 + 120)"
hit_dice: "24d12 + 120"
speed: "30 ft."
stats: [26, 12, 22, 12, 18, 11]
saves:
  - Str: "13"
  - Con: "11"
  - Wis: "9"
skillsaves:
  - Perception: "14"
  - Insight: "9"
damage_resistances: "Lightning; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks"
damage_immunities: "Fire, Poison, Psychic"
condition_immunities: "[[Mechanics#Charmed|Charmed]], [[Mechanics#Exhaustion|Exhaustion]], [[Mechanics#Frightened|Frightened]], [[Mechanics#Paralyzed|Paralyzed]], [[Mechanics#Petrified|Petrified]], [[Mechanics#Poisoned|Poisoned]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 120 ft., [[Mechanics#Tremorsense|Tremorsense]] 60 ft., Passive Perception 14"
languages: "Ignan, Terran, Primordial; understands but cannot speak"
cr: "15"
traits:
  - name: "Legendary Resistances (3/Day)"
    desc: "If the Magma Sentinel fails a saving throw, it can choose to succeed instead."
  - name: "Magma Submersion"
    desc: "While submerged in molten lava, the Magma Sentinel gains the following benefits:<br>**Damage Reduction**: The Magma Sentinel gains resistance to all damage except force and psychic while submerged.<br>**Regeneration**: The Magma Sentinel regains 20 hit points at the start of its turn if it has at least 1 hit point and is fully submerged in lava.<br>**Blazing Aura**: Any creature that starts its turn within 20 feet of the Sentinel while it is submerged in lava takes 21 (6d6) fire damage."
  - name: "Immutable Form"
    desc: "The Magma Sentinel is immune to any spell or effect that would alter its form."
  - name: "Magic Resistance"
    desc: "The Magma Sentinel has advantage on saving throws against spells and other magical effects."
  - name: "Magic Weapons"
    desc: "The Magma Sentinel's weapon attacks are magical."
  - name: "Ancestral Whispers"
    desc: "The Magma Sentinel is connected to the ancient spirits of the volcano. As a bonus action, it can gain [[Mechanics#Truesight|truesight]] out to a range of 30 feet until the start of its next turn."
actions:
  - name: "Multiattack"
    desc: "The Magma Sentinel makes three attacks: one with its Molten Slam and two with its Magma Fist."
  - name: "Molten Slam"
    desc: "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 39 (6d10 + 8) bludgeoning damage plus 21 (6d6) fire damage."
  - name: "Magma Fist"
    desc: "Melee Weapon Attack: +13 to hit, reach 15 ft., one target. Hit: 29 (4d10 + 8) bludgeoning damage plus 17 (5d6) fire damage."
  - name: "Erupting Flame (Recharge 5-6)"
    desc: "The Magma Sentinel causes magma to erupt in a 60-foot cone. Each creature in that area must make a DC 20 Dexterity saving throw, taking 72 (16d8) fire damage on a failed save, or half as much damage on a successful one. The area becomes difficult terrain for 1 minute as magma cools and solidifies."
  - name: "Volcanic Rune Activation (1/Day)"
    desc: "The Magma Sentinel activates one of the ancient runes etched into its body. Choose one of the following effects:<br>• **Searing Glyph**: Fiery symbols appear on the ground in a 30-foot radius around the Sentinel. Any creature that enters the area or starts its turn there must make a DC 18 Intelligence saving throw. On a failed save, the creature takes 36 (8d8) psychic damage and is [[Mechanics#Stunned|stunned]] until the end of its next turn.<br>• **Ember Eyes**: The Sentinel's eyes glow with an otherworldly light. Each creature within 60 feet that can see the Sentinel must succeed on a DC 18 Wisdom saving throw or be [[Mechanics#Frightened|frightened]] for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
legendary_actions:
  - name: "The Magma Sentinel can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The Magma Sentinel regains spent legendary actions at the start of its turn."
  - name: "Magma Swipe"
    desc: "The Magma Sentinel makes a Magma Fist attack."
  - name: "Molten Shield (Costs 2 Actions)"
    desc: "The Magma Sentinel envelops itself in molten lava, gaining temporary hit points equal to 40 + its Constitution modifier (6). Until the start of its next turn, any creature that hits the Magma Sentinel with a melee attack takes 21 (6d6) fire damage."
  - name: "Lava Surge (Costs 3 Actions)"
    desc: "The Magma Sentinel causes magma to surge from the ground in a 30-foot radius centered on a point it can see within 60 feet. Each creature in that area must make a DC 20 Dexterity saving throw, taking 63 (14d6) fire damage on a failed save, or half as much damage on a successful one. The area remains hot, and creatures that start their turn there take an additional 10 (3d6) fire damage until the end of their turn."
  - name: "Whisper of the Ancients (Costs 2 Actions)"
    desc: "The Magma Sentinel channels the whispers of ancient spirits. Each creature within 30 feet must succeed on a DC 18 Wisdom saving throw or take 22 (4d10) psychic damage and have [[Mechanics#Disadvantage|disadvantage]] on its next attack roll or ability check."
```
## Melusines 
The Melusine, also known as the Sorrowful Siren, is a tragic creature born from the depths of human longing and aquatic mysteries. Its upper body resembles a hauntingly beautiful humanoid, with skin that seems to shift between flesh and iridescent scales. Bioluminescent patterns pulse across its body, mimicking the movement of deep-sea creatures. Its lower half is a long, sinuous tail covered in scales that reflect light in hypnotic patterns.

The Melusine's face is a masterpiece of sorrow, with large, expressive eyes that seem to hold centuries of loneliness. Its mouth, when open, reveals rows of needle-like teeth behind full, alluring lips. Long, kelp-like hair flows around its head, moving as if constantly underwater.

In its humanoid form, the Melusine appears as a breathtakingly beautiful individual, but always with an air of profound sadness that draws others to it. This form retains subtle aquatic features, such as slightly webbed fingers or faint scale patterns visible in certain lights.

The Melusine is driven by an insatiable longing for companionship and a desperate fear of solitude. It lures victims with its beauty and song, not out of malice, but from a deep-seated need to share its eternal sorrow. Those who fall victim to its curse are slowly transformed, joining the Melusine in its tragic existence.

Melusine's are able to see the memories of those who ***fail*** and tend to portray themselves as their loved ones as a way to trick them.


```statblock
layout: Basic 5e Layout
name: "Melusine, the Sorrowful Siren"
image: [[melusine]]
size: "Medium"
type: "Fey"
subtype: "Shapechanger"
alignment: "Chaotic Neutral"
ac: "14 (natural armor)"
hp: "58 (9d8 + 18)"
hit_dice: "9d8 + 18"
speed: "15 ft., swim 50 ft."
stats: [14, 16, 14, 12, 14, 18]
saves:
  - Dex: "6"
  - Con: "4"
  - Cha: "7"
skillsaves:
  - Deception: "7"
  - Perception: "5"
  - Performance: "7"
  - Stealth: "6"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., Passive Perception 15"
languages: "Sylvan, Common"
cr: "5"
traits:
  - name: "Amphibious"
    desc: "The Melusine can breathe air and water."
  - name:"Melusine's Curse" 
    desc: "A creature afflicted by Melusine's Curse begins to slowly transform, their skin becoming pallid and scaly, their eyes growing large and sorrowful. At the end of each long rest, the cursed creature must succeed on a DC 14 Constitution saving throw or its Constitution score is reduced by 1d4. If a creature's Constitution is reduced to 0 by this curse, the creature dies and transforms into a new Melusine. The curse can be removed by a [[Mechanics#Remove Curse|Remove Curse]] spell or similar magic." 
  - name: "Sorrow's Embrace"
    desc: "The Melusine exudes an aura of melancholy within 30 feet of it. Any creature that starts its turn in this aura must succeed on a DC 15 Wisdom saving throw or be [[Mechanics#Charmed|charmed]] by the Melusine until the start of the creature's next turn. While [[Mechanics#Charmed|charmed]] in this way, the creature is [[Mechanics#Incapacitated|incapacitated]] and has a speed of 0, overcome by a sense of deep longing and sadness."
actions:
  - name: "Multiattack"
    desc: "The Melusine makes two attacks: one with its claws and one with its tail."
  - name: "Claws"
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12 (2d8 + 3) slashing damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or be afflicted with Melusine's Curse."
  - name: "Tail"
    desc: "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 10 (2d6 + 3) bludgeoning damage. If the target is a creature, it is [[Mechanics#Grappled|grappled]] (escape DC 14) on a failed save the grappled creature is pulled . Until this grapple ends, the target is [[Mechanics#Restrained|restrained]], and the Melusine can't use its tail on another target. "
  - name: "Sorrowful Song (1/Day)"
    desc: "The Melusine sings a haunting melody. Each creature within 60 feet of the Melusine that can hear the song must succeed on a DC 15 Wisdom saving throw or be [[Mechanics#Charmed|charmed]] for 1 minute. While [[Mechanics#Charmed|charmed]], the creature is [[Mechanics#Incapacitated|incapacitated]] and has a speed of 0. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the Melusine's Sorrowful Song for the next 24 hours."
bonus_actions:
  - name: "Mournful Whisper"
    desc: "The Melusine whispers a secret sorrow to a [[Mechanics#Charmed|charmed]] creature within 5 feet of it. The target must succeed on a DC 15 Wisdom saving throw or take 10 (3d6) psychic damage and become [[Mechanics#Frightened|frightened]] of the Melusine for 1 minute."
```
## Serpents
### Flamevine Serpent
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Flamevine Serpent"
size: "Large"
type: "Monstrosity"
alignment: "Neutral Evil"
ac: "15 (Natural Armor)"
hp: "85 (10d10 + 30)"
hit_dice: "10d10 + 30"
speed: "40 ft., climb 30 ft."
stats: [18, 16, 16, 8, 14, 12]
saves:
  - Dex: "6"
  - Con: "6"
skillsaves:
  - Stealth: "6"
  - Perception: "5"
damage_immunities: "Fire"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., Passive Perception 15"
languages: "Understands Draconic but can't speak"
cr: "5"
spells:
  - 3rd Level (3): "Fireball"
  - 4th Level (1): "Wall of Fire"
traits:
  - name: "Blazing Infusion"
    desc: "The Flamevine Serpent's body is infused with the essence of fire, allowing it to cast Fireball 3/day and Wall of Fire 1/day."
  - name: "Burning Vine Trail"
    desc: "As the Flamevine Serpent moves, it leaves a trail of fire. Any creature that ends its turn in a space within 5 feet of the Serpent takes 7 (2d6) fire damage."
  - name: "Fiery Glow"
    desc: "The Flamevine Serpent's body emits bright, fiery light in a 15-foot radius and dim light for an additional 15 feet. As a bonus action, the serpent can cause the light to flare, [[Mechanics#Blinded|blinding]] any creature within 10 feet that fails a DC 15 Constitution saving throw until the start of the serpent's next turn."
  - name: "Pack Behavior"
    desc: "The Flamevine Serpent is often accompanied by 1d6 Flamevine Spawnlings. If any of the Spawnlings are threatened or injured, the Flamevine Serpent becomes highly aggressive, gaining advantage on attack rolls against any creature that has harmed its Spawnlings. The Serpent will fight fiercely to protect them, using its Flame Surge and Fiery Glow abilities more strategically in defense of its young."
actions:
  - name: "Multiattack"
    desc: "The Flamevine Serpent makes two attacks: one with its Vine Bite and one with its Tail Swipe."
  - name: "Vine Bite"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 12 (2d6 + 5) piercing damage plus 9 (2d8) fire damage. The target must also succeed on a DC 15 Constitution saving throw or take 7 (2d6) fire damage at the start of each of its turns for the next minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on a success."
  - name: "Tail Swipe"
    desc: "Melee Weapon Attack: +8 to hit, reach 15 ft., one target. Hit: 15 (2d8 + 6) bludgeoning damage."
  - name: "Flame Surge"
    desc: "The Flamevine Serpent releases a surge of fiery energy. Each creature within a 15-foot cone must make a DC 15 Dexterity saving throw, taking 27 (6d8) fire damage on a failed save, or half as much on a successful one. (Recharge 5-6)"
column: 2
forceColumns: true

```


#### Flamevine Spawnling
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Flamevine Spawnling"
size: "Medium"
type: "Monstrosity"
alignment: "Neutral Evil"
ac: "13 (Natural Armor)"
hp: "34 (6d8 + 6)"
hit_dice: "6d8 + 6"
speed: "30 ft., climb 20 ft."
stats: [14, 16, 12, 6, 12, 10]
saves:
  - Dex: "5"
skillsaves:
  - Stealth: "5"
  - Perception: "3"
damage_immunities: "Fire"
senses: "[[Mechanics#Darkvision|Darkvision]] 30 ft., Passive Perception 13"
languages: "Understands Draconic but can't speak"
cr: "1"
traits:
  - name: "Burning Bite"
    desc: "The Flamevine Spawnling's bite carries a lesser version of the adult's fire power. A creature bitten by the Spawnling must succeed on a DC 11 Constitution saving throw or take 4 (1d8) fire damage at the start of each of its turns for the next minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on a success."
  - name: "Fiery Trail"
    desc: "The Flamevine Spawnling leaves a faint trail of embers as it moves. Any creature that ends its turn in a space within 5 feet of the Spawnling takes 3 (1d6) fire damage."
  - name: "Defensive Aggression"
    desc: "If a Flamevine Spawnling is injured, it becomes highly aggressive. The Spawnling gains advantage on attack rolls against any creature that has damaged it. This aggression lasts until the end of the Spawnling's next turn, or until it is no longer injured."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d6 + 2) piercing damage plus 4 (1d8) fire damage."
  - name: "Flame Flicker"
    desc: "The Spawnling can release a small burst of flame. Each creature within 5 feet of the Spawnling must make a DC 11 Dexterity saving throw, taking 7 (2d6) fire damage on a failed save, or half as much on a successful one. (Recharge 6)"
column: 2
forceColumns: true
```
### Golden Serpents
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Golden Serpent"
size: "Large"
type: "Monstrosity"
alignment: "Neutral"
ac: "17 (Natural Armor)"
hp: "95 (10d10 + 40)"
hit_dice: "10d10 + 40"
speed: "35 ft., climb 20 ft."
stats: [18, 16, 18, 10, 14, 16]
saves:
  - Dex: "6"
  - Con: "7"
  - Wis: "5"
skillsaves:
  - Stealth: "9"
  - Perception: "5"
damage_resistances: "Nonmagical bludgeoning, piercing, and slashing"
damage_immunities: "Poison"
condition_immunities: "[[Mechanics#Poisoned|Poisoned]], [[Mechanics#Petrified|Petrified]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., [[Mechanics#Tremorsense|Tremorsense]] 30 ft., Passive Perception 15"
languages: "Understands Draconic but can't speak"
cr: "6"
traits:
  - name: "Gleaming Camouflage"
    desc: "The Golden Serpent's scales shimmer with a golden hue, blending seamlessly with the golden fields of Lumina. The serpent has advantage on Dexterity (Stealth) checks made to hide in areas with golden or yellowish vegetation."
  - name: "Golden Venom"
    desc: "The Golden Serpent's bite is imbued with a potent venom that slowly petrifies its victims, turning them into solid gold over time. A creature bitten by the serpent must succeed on a DC 15 Constitution saving throw or become [[Mechanics#Poisoned|poisoned]]. While [[Mechanics#Poisoned|poisoned]] in this way, the creature's speed is reduced by 10 feet, and it takes 7 (2d6) necrotic damage at the start of each of its turns.<br>This effect lasts until the creature succeeds on a DC 15 Constitution saving throw at the end of one of its turns. After failing three saving throws, the creature begins to turn to gold, becoming [[Mechanics#Petrified|petrified]]. The creature is fully [[Mechanics#Petrified|petrified]] into gold after one hour, but this effect can be reversed by *Greater Restoration* or *Wish* before the transformation is complete."
  - name: "Golden Sheen"
    desc: "As a bonus action, the Golden Serpent can cause its scales to flash brightly, creating a dazzling effect. Each creature within 10 feet of the serpent that can see it must succeed on a DC 15 Wisdom saving throw or be [[Mechanics#Blinded|blinded]] until the start of the serpent's next turn."
  - name: "Pack Behavior"
    desc: "The Golden Serpent is often accompanied by 1d4 Golden Spawnlings. If any of the Spawnlings are threatened or injured, the Golden Serpent becomes extremely aggressive, gaining advantage on attack rolls against any creature that has harmed its Spawnlings. The Serpent will use its Golden Sheen and Golden Gaze abilities more frequently in defense of its young."
actions:
  - name: "Multiattack"
    desc: "The Golden Serpent makes two attacks: one with its Bite and one with its Constrict."
  - name: "Bite"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 14 (2d8 + 5) piercing damage plus 10 (3d6) poison damage. The target must succeed on a DC 15 Constitution saving throw or be affected by the Golden Venom."
  - name: "Constrict"
    desc: "Melee Weapon Attack: +8 to hit, reach 15 ft., one target. Hit: 16 (2d10 + 5) bludgeoning damage. The target is [[Mechanics#Grappled|grappled]] (escape DC 16) if the target is Large or smaller, and until this grapple ends, the target is [[Mechanics#Restrained|restrained]]."
  - name: "Golden Gaze"
    desc: "The Golden Serpent can focus its gaze on a creature within 30 feet that it can see. The target must make a DC 15 Wisdom saving throw. On a failed save, the creature begins to hallucinate, seeing visions of wealth and gold, becoming [[Mechanics#Charmed|charmed]] by the serpent for 1 minute. While [[Mechanics#Charmed|charmed]] in this way, the creature is [[Mechanics#Incapacitated|incapacitated]] and has a speed of 0. The effect ends early if the creature takes damage or another creature uses an action to shake it out of its stupor. (Recharge 5-6)"
column: 2
forceColumns: true
```



#### Golden Spawnling

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Golden Spawnling"
size: "Small"
type: "Monstrosity"
alignment: "Neutral"
ac: "14 (Natural Armor)"
hp: "28 (4d8 + 10)"
hit_dice: "4d8 + 10"
speed: "30 ft., climb 20 ft."
stats: [12, 16, 14, 6, 12, 14]
saves:
  - Dex: "5"
  - Con: "4"
skillsaves:
  - Stealth: "7"
  - Perception: "3"
damage_resistances: "Nonmagical bludgeoning, piercing, and slashing"
damage_immunities: "Poison"
condition_immunities: "[[Mechanics#Poisoned|Poisoned]], [[Mechanics#Petrified|Petrified]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 30 ft., [[Mechanics#Tremorsense|Tremorsense]] 15 ft., Passive Perception 13"
languages: "Understands Draconic but can't speak"
cr: "1"
traits:
  - name: "Gleaming Hide"
    desc: "The Golden Spawnling's scales shimmer with a golden hue, allowing it to blend into golden fields. It has advantage on Dexterity (Stealth) checks made to hide in areas with golden or yellowish vegetation."
  - name: "Golden Bite"
    desc: "The Golden Spawnling's bite delivers a weaker form of the venom its adult counterpart carries. A creature bitten by the Spawnling must succeed on a DC 12 Constitution saving throw or become [[Mechanics#Poisoned|poisoned]]. While [[Mechanics#Poisoned|poisoned]] in this way, the creature's speed is reduced by 5 feet, and it takes 3 (1d6) necrotic damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on a success."
  - name: "Defensive Aggression"
    desc: "If a Golden Spawnling is injured, it becomes highly aggressive. The Spawnling gains advantage on attack rolls against any creature that has damaged it. This aggression lasts until the end of the Spawnling's next turn, or until it is no longer injured."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 8 (2d4 + 3) piercing damage plus 4 (1d8) poison damage."
  - name: "Golden Flash"
    desc: "The Spawnling can cause its scales to emit a sudden flash of light. Each creature within 5 feet of the Spawnling that can see it must succeed on a DC 12 Wisdom saving throw or be [[Mechanics#Blinded|blinded]] until the start of the Spawnling's next turn. (Recharge 6)"
```


### Radiant Serpent


```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Radiant Serpent"
size: "Medium"
type: "Monstrosity"
alignment: "Neutral"
ac: "14 (Natural Armor)"
hp: "52 (8d8 + 16)"
hit_dice: "8d8 + 16"
speed: "30 ft., climb 20 ft., swim 20 ft."
stats: [12, 18, 14, 6, 14, 10]
saves:
  - Dex: "6"
  - Con: "4"
skillsaves:
  - Stealth: "6"
  - Perception: "4"
damage_immunities: "Fire, Radiant"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., Passive Perception 14"
languages: "Understands Draconic but can't speak"
cr: "3"
spells:
  - 1st Level (3): "Burning Hands"
  - 2nd Level (1): "Scorching Ray"
traits:
  - name: "Sunfyre Infusion"
    desc: "The Radiant Serpent has absorbed the magical essence of [[Sunfire Crystal]]s, giving it access to the following abilities: Innate Spellcasting: The Radiant Serpent's innate spellcasting ability is Wisdom (spell save DC 14). It can innately cast Burning Hands 3/day and Scorching Ray 1/day."
  - name: "Blistering Venom"
    desc: "The Radiant Serpent's bite injects a venom that causes intense burns and pain. When the serpent bites a creature, it must succeed on a DC 13 Constitution saving throw or take an additional 7 (2d6) fire damage at the start of each of its turns for the next minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
  - name: "Radiant Glow"
    desc: "The Radiant Serpent emits a faint light, shedding bright light in a 10-foot radius and dim light for an additional 10 feet. As a bonus action, it can intensify this glow, [[Mechanics#Blinded|blinding]] a creature within 5 feet that fails a DC 12 Constitution saving throw until the start of the serpent's next turn."
  - name: "Pack Behavior"
    desc: "The Radiant Serpent is often accompanied by 1d6 Radiant Spawnlings. If any of the Spawnlings are threatened or attacked, the Radiant Serpent becomes extremely aggressive, gaining advantage on attack rolls against any creature that has harmed its Spawnlings. The Serpent will fight fiercely to protect them, often displaying increased ferocity and using its Radiant Burst and Radiant Glow abilities more strategically to defend its young."
actions:
  - name: "Multiattack"
    desc: "The Radiant Serpent makes two attacks: one with its Bite and one with its Tail."
  - name: "Bite"
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8 + 4) piercing damage plus 5 (1d10) fire damage. The target must also succeed on a DC 13 Constitution saving throw or be [[Mechanics#Poisoned|poisoned]] by the Blistering Venom (as described above)."
  - name: "Tail Whip"
    desc: "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 9 (1d10 + 4) bludgeoning damage."
  - name: "Radiant Burst"
    desc: "The Radiant Serpent can release a burst of radiant energy absorbed from [[Sunfire Crystal]]s. Each creature within 10 feet of the serpent must make a DC 13 Dexterity saving throw, taking 14 (4d6) radiant damage on a failed save, or half as much on a successful one. (Recharge 5-6)"
```




#### Radiant Spawnling
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Radiant Spawnling"
size: "Small"
type: "Monstrosity"
alignment: "Neutral"
ac: "12 (Natural Armor)"
hp: "22 (4d6 + 8)"
hit_dice: "4d6 + 8"
speed: "25 ft., climb 10 ft., swim 10 ft."
stats: [8, 14, 14, 4, 12, 10]
saves:
  - Dex: "4"
skillsaves:
  - Stealth: "4"
  - Perception: "3"
damage_immunities: "Fire"
condition_immunities: ""
senses: "[[Mechanics#Darkvision|Darkvision]] 30 ft., Passive Perception 13"
languages: "Understands Draconic but can't speak"
cr: "1"
traits:
  - name: "Blistering Bite"
    desc: "The Radiant Spawnling's bite, while not as potent as an adult's, still carries a hint of its future power. A creature bitten by the Spawnling must succeed on a DC 11 Constitution saving throw or take 3 (1d6) fire damage at the start of each of its turns for the next minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
  - name: "Faint Glow"
    desc: "The Radiant Spawnling emits a soft light, shedding dim light in a 5-foot radius. This glow is harmless and primarily serves to illuminate its surroundings, but it hints at the creature's growing connection to the [[Sunfire Crystal]]s."
  - name: "Defensive Aggression"
    desc: "If a Radiant Spawnling is injured, it becomes highly aggressive. The Spawnling gains advantage on attack rolls against any creature that has damaged it. This aggressive behavior persists until the end of the Spawnling's next turn, or until it is no longer injured."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage plus 3 (1d6) fire damage."
  - name: "Radiant Flicker"
    desc: "As a fledgling ability, the Spawnling can attempt to release a small burst of radiant energy. Each creature within 5 feet of the Spawnling must make a DC 11 Dexterity saving throw, taking 7 (2d6) radiant damage on a failed save, or half as much damage on a successful one. (Recharge 6)"
column: 2
forceColumns: true
```


### Rustwyrm

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Rustwyrm"
size: "Large"
type: "Monstrosity"
alignment: "Neutral"
ac: "16 (Natural Armor)"
hp: "102 (12d10 + 36)"
hit_dice: "12d10 + 36"
speed: "40 ft., swim 30 ft."
stats: [19, 14, 17, 8, 12, 10]
saves:
  - Dex: "5"
  - Con: "6"
skillsaves:
  - Stealth: "7"
  - Perception: "4"
damage_resistances: "Acid, Poison"
condition_immunities: "[[Mechanics#Poisoned|Poisoned]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., [[Mechanics#Tremorsense|Tremorsense]] 30 ft., Passive Perception 14"
languages: "Understands Draconic but can't speak"
cr: "7"
traits:
  - name: "Iron Stomach"
    desc: "The Rustwyrm can consume and digest metal and stone, which it uses to aid in the consumption of its prey. It gains temporary hit points equal to the amount of metal ingested in pounds."
  - name: "Sulfurous Emission"
    desc: "The Rustwyrm can emit a cloud of sulfurous gas from its mouth to disorient and weaken its prey. The cloud fills a 20-foot radius centered on the Rustwyrm and lasts for 1 minute or until a strong wind disperses it. The area is heavily obscured, and any creature that starts its turn in the cloud must succeed on a DC 16 Constitution saving throw or be [[Mechanics#Poisoned|poisoned]] for 1 minute.<br>While [[Mechanics#Poisoned|poisoned]] this way, a creature is [[Mechanics#Incapacitated|incapacitated]] and cannot take actions, bonus actions, or reactions. The creature can repeat the saving throw at the end of each of its turns, ending the effect on a success."
actions:
  - name: "Multiattack"
    desc: "The Rustwyrm makes two attacks: one with its Bite and one with its Tail Swipe."
  - name: "Bite"
    desc: "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 18 (3d8 + 5) piercing damage. The Rustwyrm can then attempt to swallow a creature of Medium size or smaller that it has [[Mechanics#Grappled|grappled]]. The swallowed target is [[Mechanics#Blinded|blinded]] and [[Mechanics#Restrained|restrained]], has total cover against attacks and other effects outside the Rustwyrm, and takes 10 (3d6) acid damage at the start of each of the Rustwyrm's turns.<br>If the Rustwyrm takes 30 damage or more on a single turn from a creature inside it, the Rustwyrm must succeed on a DC 15 Constitution saving throw or regurgitate the swallowed creature, which falls [[Mechanics#Prone|prone]] in a space within 10 feet of the Rustwyrm."
  - name: "Tail Swipe"
    desc: "Melee Weapon Attack: +7 to hit, reach 15 ft., one target. Hit: 14 (2d8 + 5) bludgeoning damage. The target must succeed on a DC 15 Strength saving throw or be knocked [[Mechanics#Prone|prone]]."
  - name: "Rock Crusher (Recharge 5-6)"
    desc: "The Rustwyrm can perform a powerful crushing attack by rolling over its prey. Each creature within 10 feet of the Rustwyrm must make a DC 16 Dexterity saving throw, taking 27 (6d8) bludgeoning damage on a failed save, or half as much damage on a successful one. Creatures that fail the save are also [[Mechanics#Restrained|restrained]] as the Rustwyrm rolls over them."
  - name: "Pack Behavior"
    desc: "The Rustwyrm is often accompanied by 1d4 Rust-wyrmlings. If any of the Rust-wyrmlings are threatened or injured, the Rustwyrm becomes extremely aggressive, gaining advantage on attack rolls against any creature that has harmed its Rustlings. It will use its Rock Crusher and Sulfurous Emission abilities more frequently in defense of its young."
```
#### Rust-Wyrmlings
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Rust-Wyrmling"
size: "Small"
type: "Monstrosity"
alignment: "Neutral"
ac: "13 (Natural Armor)"
hp: "32 (5d8 + 10)"
hit_dice: "5d8 + 10"
speed: "30 ft., swim 20 ft."
stats: [14, 14, 14, 6, 10, 8]
saves:
  - Dex: "4"
  - Con: "4"
skillsaves:
  - Stealth: "6"
  - Perception: "2"
damage_resistances: "Acid, Poison"
condition_immunities: "[[Mechanics#Poisoned|Poisoned]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 30 ft., [[Mechanics#Tremorsense|Tremorsense]] 15 ft., Passive Perception 12"
languages: "Understands Draconic but can't speak"
cr: "1"
traits:
  - name: "Iron Belly"
    desc: "The Rust-Wyrmling consumes small stones and minerals, which help it digest tougher prey. It can bite through non-magical metal and stone as though it were soft material."
  - name: "Sulfuric Spit (Recharge 6)"
    desc: "The Wyrmling can spit a small glob of sulfuric acid at a creature within 10 feet. The target must make a DC 12 Dexterity saving throw, taking 7 (2d6) acid damage on a failed save, or half as much damage on a successful one. Creatures that fail the save are also [[Mechanics#Poisoned|poisoned]] until the end of their next turn."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 8 (2d6 + 2) piercing damage."
  - name: "Defensive Aggression"
    desc: "If a Rust-Wyrmling is injured, it becomes highly aggressive. The Wyrmling gains advantage on attack rolls against any creature that has damaged it. This aggression lasts until the end of the Wyrmling's next turn, or until it is no longer injured."
```
## Spiders
### Base Spiders 
```statblock 
creature: Giant Spider

```
### Shadow Weaver Spider
A large, jet-black spider  with an iridescent sheen that blends into the darkness. It's webs are nearly invisible and exude a paralyzing toxin. These spiders often will inhabit dark caves, abandoned ruins, and shadowy forests.
```statblock 
name: Shadow Weaver
source: 5e SRD
size: Large
type: beast
subtype: ""
alignment: unaligned
ac: 14
hp: 26
hit_dice: 4d10 + 4
speed: 30 ft., climb 30 ft.
stats:
  - 14
  - 16
  - 12
  - 2
  - 11
  - 4
skillsaves:
  - stealth: 7
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: blindsight 10 ft., darkvision 60 ft., passive Perception 10
languages: ""
cr: "1"
bestiary: true
traits:
  - name: Spider Climb
    desc: The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.
    attack_bonus: 0
  - name: Web Sense
    desc: While in contact with a web, the spider knows the exact location of any other creature in contact with the same web.
    attack_bonus: 0
  - name: Web Walker
    desc: The spider ignores movement restrictions caused by webbing.
    attack_bonus: 0
actions:
  - name: Bite
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 7 (1d8 + 3) piercing damage, and the target must make a DC 11 Constitution saving throw, taking 9 (2d8) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hit points, the target is stable but poisoned for 1 hour, even after regaining hit points, and is paralyzed while poisoned in this way."
    attack_bonus: 5
    damage_dice: 1d8
    damage_bonus: 3
  - name: Web (Recharge 5-6)
    desc: "Ranged Weapon Attack: +5 to hit, range 30/60 ft., one creature. Hit: The target is restrained by webbing. As an action, the restrained target must make a DC14 CON or be [[mechanics.md#Paralyzed| paralyzed]], then can make a DC 11 Strength check, bursting the webbing on a success. . The webbing can also be attacked and destroyed (AC 10; hp 5; vulnerability to fire damage; immunity to bludgeoning, poison, and psychic damage)."
    attack_bonus: 5
column: 2
forceColumns: true
```



## Treants 
### Crimson Mangrove Treants
Found in the mangrove forests of [[Crimson Shores]]. These Treants use their long roots to traverse through the high waters. They are able to use their roots to latch onto creatures large and smaller and restrain them. The roots seem to resemble writhing tentacles and it's eye-like knots seem to follow it's potential prey. 

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Crimson Mangrove Treant"
size: "Huge"
type: "plant"
alignment: "neutral"
ac: "16 (natural armor)"
hp: "126 (12d12 + 48)"
hit_dice: "12d12 + 48"
speed: "30 ft., swim 30 ft."
stats: [21, 10, 19, 12, 16, 12]
damage_resistances: "bludgeoning, piercing"
damage_vulnerabilities: "fire"
condition_immunities: "[[Mechanics#Charmed|charmed]], [[Mechanics#Frightened|frightened]]"
senses: "[[Mechanics#Blindsight|blindsight]] 60 ft. (blind beyond this radius), passive Perception 13"
languages: "Common, Sylvan"
cr: "6"
traits:
  - name: "Amphibious"
    desc: "The treant can breathe air and water."
  - name: "Iron Absorption"
    desc: "The treant has advantage on Constitution saving throws while in contact with iron-rich water."
  - name: "False Appearance"
    desc: "While the treant remains motionless, it is indistinguishable from a normal mangrove tree."
actions:
  - name: "Multiattack"
    desc: "The treant makes two root lash attacks."
  - name: "Root Lash"
    desc: "Melee Weapon Attack: +8 to hit, reach 15 ft., one target. Hit: 16 (3d6 + 6) bludgeoning damage. If the target is Large or smaller, it must succeed on a DC 16 Strength saving throw or be [[Mechanics#Grappled|grappled]] (escape DC 16). Until this grapple ends, the target is [[Mechanics#Restrained|restrained]], and the treant can't use this root to attack another target."
  - name: "Rock"
    desc: "Ranged Weapon Attack: +8 to hit, range 60/180 ft., one target. Hit: 26 (4d8 + 8) bludgeoning damage."
  - name: "Crimson Mist (Recharge 5-6)"
    desc: "The treant releases a cloud of iron-rich mist in a 30-foot radius. Each creature in that area must make a DC 15 Constitution saving throw. On a failure, the creature takes 18 (4d8) poison damage and is [[Mechanics#Poisoned|poisoned]] for 1 minute. On a success, the creature takes half damage and isn't [[Mechanics#Poisoned|poisoned]]. A [[Mechanics#Poisoned|poisoned]] creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
bonus_actions:
  - name: "Root Network"
    desc: "The treant can move up to its speed without provoking opportunity attacks by submerging its roots and resurfacing them. During this movement, it can pass through spaces as narrow as 1 foot wide without squeezing."
```

## Basilisk
### Blazehorn Basilisk
A multi-legged, reptilian horror with fiery scales and glowing red eyes. [[Sunfire Crystal]] s protrude outwards from it's body, they glow with the beasts inner fire.  Its deadly gaze transforms victims into obsidian with veins of ember. With its strong jaws, the creature will shatter and consume the stone, which returns to organic form in its gullet. This breed of Basilisk is found in the [[Ember Caverns]] and [[Emberfall Gorge]]. They have developed an immunity to fire and the ability to cause fire damage due to consuming large amounts of [[Sunfire Crystal]]s in their raw form. Additionally, they are able to exhale a cone of sulfuric, acidic breath, a byproduct of their volcanic habitat. 
```statblock 
layout: Basic 5e Layout
image: [[image]]
name: "Blazehorn Basilisk"
size: "Medium"
type: "monstrosity"
alignment: "unaligned"
ac: "15 (natural armor)"
hp: "52 (8d8 + 16)"
hit_dice: "8d8 + 16"
speed: "20 ft."
stats: [16, 8, 15, 2, 8, 7]
saves:
  - constitution: "4"
damage_immunities: "fire"
senses: "[[Mechanics#Darkvision|darkvision]] 60 ft., passive Perception 9"
languages: "-"
cr: "4"
traits:
  - name: "[[Sunfire Crystal]] Protrusions"
    desc: "The basilisk's body is covered in protruding [[Sunfire Crystal]]s. Any creature that touches the basilisk or hits it with a melee attack while within 5 feet of it takes 3 (1d6) fire damage."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6 + 3) piercing damage plus 3 (1d6) fire damage from its magma-like venom."
  - name: "Petrifying Gaze"
    desc: "The basilisk targets one creature it can see within 30 feet. If the target can see the basilisk's eyes, the target must succeed on a DC 12 Constitution saving throw or begin to turn into obsidian with veins of ember and be [[Mechanics#Restrained|restrained]]. The [[Mechanics#Restrained|restrained]] target must repeat the saving throw at the end of its next turn. On a success, the effect ends. On a failure, the target is [[Mechanics#Petrified|petrified]] into obsidian with veins of ember. This petrification can be removed by the greater restoration spell or similar magic.<br><br>A creature that isn't [[Mechanics#Surprised|surprised]] can avert its eyes to avoid the saving throw at the start of its turn. If it does so, it can't see the basilisk until the start of its next turn, when it can avert its eyes again. If it looks at the basilisk in the meantime, it must immediately make the save."
  - name: "Sulfuric Acid Breath (Recharge 5-6)"
    desc: "The basilisk exhales a cone of sulfuric, acidic breath in a 15-foot cone. Each creature in that area must make a DC 12 Dexterity saving throw, taking 21 (6d6) acid damage on a failed save, or half as much damage on a successful one."
```


## Blighted and Cursed
### Blighted Dryads 
Once benevolent tree spirits corrupted by dark magic. Blighted Dryads have become twisted and malevolent. They manipulate the forest itself causing plants to wither and decay, they unleash spells of decay and despair upon those who intrude upon their territory.  Blighted Dryads are most common within the [[Whispering Vale]], but can also be found in the [[Ethereal Veil]].
```statblock 
layout: Basic 5e Layout
name: "Blighted Dryads"
image: [[image]]
size: "Medium"
type: "Fey"
subtype: "Blightborn"
ac: "11 (16 With Barkskin)"
hp: "22"
hit_dice: 5d8
speed: "30 ft."
stats: [10,12,11,14,15,18]
skillsaves: 
 - perception: +4
 - stealth: +5
senses: "Darkvision 60ft Passive Perception 14"
languages: "Elvish, Sylvan"
cr: 1
traits:
 - name: Magic Resistance 
   desc: Has advantage on saving throws against spells and other magical effects.
 - name: "Blighted Constitution"
   desc: "Advantage on saving throws against being charmed, poisoned, or diseased."
 - name: Tree Stride
   desc: Once on turn can cuse 10 ft of movement to step magically into one living tree within her reach and emerge from a second living tree within 60ft of the first, appearing in an unoccupies space within 5ft. of the second tree. both trees must be large or bigger.
 - name: "Blighted Magic"
   desc: "Spare the dying cantrip. 3rd level, can cast the false life spell as a 2nd level spell once with this trait and regain the abilith to do so when after long rest. 5th level, can cast blooming death once with this trait and regain the ability to do so after a long rest. Charisma is spell casting ability,"
actions: 
 - name: "Club"
   desc: "Melee Weapon attack: +2 to hit, reach 5 ft., one target. Hit: (1d4) bludgeoning damage"
 - name: "Club (with shillelagh)"
   desc: "Melee Weapon attack: +6 to hit, reach 5 ft., one target. Hit: (1d8+4) bludgeoning damage"
 - name: "Fey Charm"
   desc: Targets 1 humanoid or beast that they can see within 30 ft. If they can see the dryad, make DC 14 WIS saving throw or be [[Conditions#Charmed | charmed]] . Each time the dryad of its allies do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise the effect lasts 24 hrs or until the dryad dies, is on another plane, or ends the effects as a bonus action. If the target's saving throw is successful, the target is immune to the Fey Charm for 24 hrs. Cannot have more than 1 homanoid and 3 beasts charmed at a time.

column: 2
forceColumns: true
```

### Corrupt Fey
These once beautiful and benevolent creatures have been corrupted by the dark forces that dwell deep within the Whispering Vale. From years or neglect or the dark nature of the forest itself, no one is quite sure what has ruined these creatures. Corrupt Fey use their innate magical abilities to manipulate the mist that surrounds every crevice of the Whispering Vale. They are able to ensnare travelers and manipulate the mist into leading them into traps or luring them into despair.



```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Corrupt Fey"
size: "Medium"
type: "fey"
alignment: "chaotic evil"
ac: "15 (natural armor)"
hp: "65 (10d8 + 20)"
hit_dice: "10d8 + 20"
speed: "30 ft."
stats: [12, 16, 14, 13, 14, 18]
saves:
  - wisdom: "4"
  - charisma: "6"
skillsaves:
  - deception: "6"
  - perception: "4"
  - stealth: "5"
damage_resistances: "bludgeoning, piercing, and slashing from nonmagical attacks"
damage_vulnerabilities: "cold iron"
condition_immunities: "charmed"
senses: "darkvision 60 ft., passive Perception 14"
languages: "Common, Sylvan"
cr: "3"
traits:
  - name: "Fey Ancestry"
    desc: "The corrupt fey has advantage on saving throws against being charmed, and magic can't put it to sleep."
  - name: "Magic Resistance"
    desc: "The corrupt fey has advantage on saving throws against spells and other magical effects."
  - name: "Mist Dependency"
    desc: "If the mist within 30 feet of the corrupt fey is dispersed (such as by a strong wind or magic), the fey becomes vulnerable to all damage types until the end of its next turn."
actions:
  - name: "Corrupted Touch"
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6 + 3) necrotic damage, and the target must succeed on a DC 14 Constitution saving throw or be poisoned until the end of its next turn."
  - name: "Haunting Whispers"
    desc: "The corrupt fey targets one creature it can see within 60 feet. The target must succeed on a DC 14 Wisdom saving throw or take 10 (3d6) psychic damage and become frightened of the fey until the end of the fey's next turn. <br> *Cold mist swirls around the target, engulfing them.* "
  - name: "Mist Manipulation"
    desc: "The corrupt fey manipulates the surrounding mist. It can use this ability in one of two ways:<br>- Restrain: One creature the fey can see within 30 feet must succeed on a DC 14 Strength saving throw or be restrained by tendrils of mist until the end of the fey's next turn.<br>- Illusory Path: The fey creates an illusory path up to 60 feet long and 10 feet wide. Any creature that can see the path must succeed on a DC 14 Intelligence (Investigation) check to recognize it as an illusion. A creature that fails this check believes the path is real and safe to traverse, potentially leading them into danger."
```





### Cursed Treant
Once guardians of the forest, these ancient treants have been consumed by malevolent forces. Cursed Treants wield powerful nature-based magic to unleash devastating spells and summon corrupted creatures to aid them in their dark purpose. Faces seem to form and dissolve against the bark.


```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Cursed Treant"
size: "Huge"
type: "plant"
alignment: "chaotic evil"
ac: "16 (natural armor)"
hp: "138 (12d12 + 60)"
hit_dice: "12d12 + 60"
speed: "30 ft."
stats: [23, 8, 21, 12, 16, 12]
damage_resistances: "bludgeoning, piercing"
damage_vulnerabilities: "fire"
condition_immunities: "charmed, frightened"
senses: "darkvision 60 ft., passive Perception 13"
languages: "Common, Druidic, Elvish, Sylvan"
cr: "7"
traits:
  - name: "False Appearance"
    desc: "While the treant remains motionless, it is indistinguishable from a normal tree."
  - name: "Siege Monster"
    desc: "The treant deals double damage to objects and structures."
actions:
  - name: "Multiattack"
    desc: "The treant makes two slam attacks."
  - name: "Slam"
    desc: "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 19 (3d8 + 6) bludgeoning damage."
  - name: "Rock"
    desc: "Ranged Weapon Attack: +9 to hit, range 60/180 ft., one target. Hit: 28 (4d10 + 6) bludgeoning damage."
  - name: "Corrupting Aura (Recharge 5-6)"
    desc: "The treant releases a pulse of corrupting energy. Each creature within 30 feet must make a DC 15 Constitution saving throw. On a failed save, a creature takes 18 (4d8) necrotic damage and is poisoned until the end of its next turn. On a successful save, the creature takes half as much damage and isn't poisoned."
  - name: "Animate Corrupted Plants (1/Day)"
    desc: "The treant magically animates one or two trees it can see within 60 feet of it. These trees have the same statistics as a corrupted awakened tree (use awakened tree stats, but change alignment to chaotic evil and add 7 (2d6) necrotic damage to its slam attack). An animated tree acts as an ally of the treant. The tree remains animate for 1 day or until it dies; until the treant dies or is more than 120 feet from the tree; or until the treant takes a bonus action to turn it back into an inanimate tree. The tree then takes root if possible."
bonus_actions:
  - name: "Summon Corrupt Creatures (1/Day)"
    desc: "The treant summons 1d4 + 1 corrupted woodland creatures. These can be wolves, bears, or other appropriate CR 1 or lower beasts, twisted by the forest's corruption. The summoned creatures appear in unoccupied spaces within 60 feet of the treant and act as its allies. They remain for 1 minute, until the treant dies, or until the treant dismisses them as an action."
```

## Drakes
Drakes are believed to be the unwanted offspring of dragons. They are anomalies that can occur within a dragon's brood, and are usually derided as failures due to their lack of wings and their smaller size. Drakes are often left to die of exposure when their birth is discovered. Drakes are often not feared as dragons due to their size which they use to their advantage, utilizing their intelligence to assimilate and coexist within other societies. Not many Drakes can reproduce due to their ecology and abnormal birth, though some are able to.
Drakes will bond to whoever feeds it within it's first 3 weeks of life. Very territorial, being very protective of possessions and their bonded, but can be seen as obedient to those who have bonded or to those who are natural leaders. Drakes vary wildly in size from under 6 feet to well over 7 feet tall.

| Dragon         | Damage Type |     | Base Height | Height Mod* | Base Weight | Weight Mod** |
| -------------- | ----------- | --- | ----------- | ---------- | ----------- | ---------- |
| Black/Copper   | Acid        |     | 6'4"        | +1d12      | 230 lbs     | *1d6 lbs   |
| Blue/Bronze    | Lightning   |     |       Height *   | =   base height +        |         height mod    |            |
| Brass/Gold/Red | Fire        |     |         Weight  **  |    = base weight +        |       weight mod      |            |
| Green          | Poison      |     |             |            |             |            |
| Silver/White   | Cold        |     |             |            |             |            |
|                |             |     |             |            |             |            |
### Dazzlewing_Drake
These Drakes are quite a bit smaller than others and are able to reproduce organically. These stunted dragons possess iridescent scales that shimmer in various colors. Dazzlewings Drakes are highly agile and have a mesmerizing ability to emit dazzling bursts of light, which they use to disorient and confuse their adversaries. #Lumina #bioluminescent #Whispering_Vale #Ethereal_Veil 
```statblock 
layout: Basic 5e Layout
name: "Dazzlewing Drake"
image: [[Blighted Drake]]
size: “Small"
type: "Stunted Dragon"
alignment: "Unaligned"
ac: "14 (natural armor)"
hp: "22"
hit_dice: 3d8+6
speed: "30ft, climb 10ft, fly 50ft"
stats: [12,18,14,4,11,6]
skillsaves: 
 - perception: 4
 - stealth: 4
senses: "Passive Perception 14"
languages: "Undercommon"
damage_resistances: "poison"
damage_immunities: "damage immunities"
condition_immunities: "condition immunities"
cr: 1
traits:
 - name: "Pack Tactics"
   desc: "Has advantage on an attack roll against a creature if at least one ally is within 5ft. of the creature and the ally is not [[Mechanics#Incapacitated|incapacitated]]"
 - name: "Suprise Attack"
   desc: "If the drake suprises a creature and hits it with an attack during the first round of combat, the target takes an extra 9 (2d8) damage"
actions: 
 - name: "Mesmerizing Patterns" 
 - desc: "The Dazzlewing Drake's wings display hypnotic, ever-shifting patterns. Each creature within 30 feet that can see the Mothdrake must succeed on a DC 13 Wisdom saving throw or be [[Mechanics#Charmed|charmed]] for 1 minute. While [[Mechanics#Charmed|charmed]] by this effect, the creature is [[Mechanics#Incapacitated|incapacitated]] and has a speed of 0. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success." 
 - name: "Memory Drain" 
 - desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one [[Mechanics#Charmed|charmed]] creature. Hit: 7 (1d6 + 4) psychic damage, and the target must succeed on a DC 13 Wisdom saving throw or lose one memory of the Dazzlewing Drake's choice. The creature can regain the lost memory after a long rest or through magical means such as the greater restoration spell."
 - name: "Bite"
   desc: "Melee Weaon Attack: +4 to hit, reach 5ft., one target. Hit 6 (1d8+1) piercing damage"
column: 2
forceColumns: true
```

### Drake
```statblock 
layout: Basic 5e Layout
name: "Drake"
image: [[drake]]
size: "Medium"
type: "dragon"
subtype: "stunted"
alignment: "unaligned"
ac: "14 (natural armor)"
hp: "28 (4d8 + 8)"
hit_dice: "4d8 + 8"
speed: "30 ft."
stats: [13, 15, 14, 4, 11, 6]
skillsaves:
  - perception: "4"
  - stealth: "4"
senses: "[[Mechanics#Blindsight|blindsight]] 30 ft. or 10 ft. while [[Mechanics#Deafened|deafened]] ([[Mechanics#Blinded|blinded]] beyond this radius), passive Perception 14"
languages: "understands Undercommon but can't speak"
damage_resistances: "poison"
cr: "1"
traits:
  - name: "Pack Tactics"
    desc: "The drake has advantage on an attack roll against a creature if at least one of the drake's allies is within 5 feet of the creature and the ally isn't [[Mechanics#Incapacitated|incapacitated]]."
  - name: "Surprise Attack"
    desc: "If the drake surprises a creature and hits it with an attack during the first round of combat, the target takes an extra 9 (2d8) damage from the attack."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8 + 2) piercing damage."
```
## Dryads
### Base Dryads
Characters may encounter a powerful dryad residing in a grand ancient tree who shares ancient knowledge about the forest's secrets or provides magical boons to those deemed worthy.











## Foxes 
### Base Foxes
Foxes are renowned as clever animals, able to avoid the hunters hounds which seek them for their valuable furs. They are most active at night but can sometimes be seen during the day as well. #Lumina #Whispering_Vale #no_show 

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Fox"
size: "Tiny"
type: "Beast"
alignment: "Unaligned"
ac: "12"
hp: "3 (1d6)"
hit_dice: "1d6"
speed: "40 ft."
stats: [3, 15, 10, 4, 14, 7]
skillsaves:
  - Perception: "+3"
  - Stealth: "+4"
  - Survival: "+2"
senses: "[[Mechanics#Darkvision|Darkvision]] 30 ft., Passive Perception 15"
languages: "—"
cr: "0"
traits:
  - name: "Keen Hearing and Smell"
    desc: "The fox has advantage on Wisdom (Perception) checks that rely on hearing or smell."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 1 piercing damage."
```

### Dawn Foxes
These elusive creatures are known for their beautiful coats, which range from pale gold to fiery orange. Their fur appears to catch and reflect the sunlight, making them blend seamlessly with the surroundings. They are often associated with dawn and are considered to be harbingers of good fortune. 

## Golems 
### Celestial Golem
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Celestial Golem"
size: "Large"
type: "Construct"
alignment: "Lawful Good"
ac: "18 (Natural Armor)"
hp: "136 (16d10 + 48)"
hit_dice: "16d10 + 48"
speed: "30 ft."
stats: [20, 12, 18, 10, 16, 12]
saves:
  - Str: "8"
  - Con: "7"
  - Wis: "6"
skillsaves:
  - Perception: "13"
damage_vulnerabilities: “Bludgeoning”
damage_resistances: "Radiant, Force, Necrotic, Piercing, and Slashing from Nonmagical Attacks"
damage_immunities: "Poison, Disease, Psychic, Blight"
condition_immunities: "Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 13"
languages: "Understands Celestial, Primordial, and the languages of its creator but cannot speak, except for a rare few"
cr: "7"
traits:
  - name: "Sunfire Core (Regeneration)"
    desc: "The [[Sunfire Crystal]]s embedded in the golem's chest grants it the ability to regenerate. The Celestial Golem regains 10 hit points at the start of its turn if it has at least 1 hit point and isn't in an area of magical darkness. If the golem takes necrotic damage, this trait doesn't function at the start of the golem's next turn."
  - name: "Erosion"
    desc: "The Celestial Golem is subject to gradual erosion over time. For every month without maintenance, it loses 1 point of its maximum hit points. These lost hit points can be restored through special repairs involving [[Sunfire Crystal]]s and stardust."
  - name: "Celestial Fragments"
    desc: "The floating meteorite fragments surrounding the golem provide it with additional power:<br>**Temporal Displacement**: Once per day, the golem can shift itself 5 feet in any direction as a reaction, avoiding an attack that would hit it.<br>**Stardust Shield**: The golem can use an action to create a radiant shield of stardust, granting itself and all allies within 10 feet a +2 bonus to AC for 1 minute."
  - name: "Immutable Form"
    desc: "The Celestial Golem is immune to any spell or effect that would alter its form."
  - name: "Magic Resistance"
    desc: "The Celestial Golem has advantage on saving throws against spells and other magical effects."
  - name: "Magic Weapons"
    desc: "The Celestial Golem’s weapon attacks are magical."
actions:
  - name: "Multiattack"
    desc: "The Celestial Golem makes two attacks with its Celestial Slam."
  - name: "Celestial Slam"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 19 (3d8 + 5) bludgeoning damage plus 7 (2d6) radiant damage."
  - name: "Temporal Stasis (Recharge 5-6)"
    desc: "The golem targets one creature it can see within 30 feet of it. The target must succeed on a DC 16 Wisdom saving throw or be frozen in time for 1 minute. While frozen, the target is incapacitated and immune to all damage. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
  - name: "Meteoric Strike (Recharge 6)"
    desc: "The golem channels the power of the floating meteorites and hurls them at a point within 60 feet. Each creature in a 15-foot-radius sphere centered on that point must make a DC 16 Dexterity saving throw, taking 27 (6d8) bludgeoning damage and 13 (3d8) radiant damage on a failed save, or half as much damage on a successful one."
reactions:
  - name: "Celestial Reprisal"
    desc: "When the Celestial Golem is hit by a melee attack, it can use its reaction to release a burst of radiant energy. The attacker must make a DC 16 Constitution saving throw or take 14 (4d6) radiant damage and be blinded until the end of their next turn."
column: 2
forceColumns: true

```
### Etheric Warden Golem 

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Etheric Warden Golem"
size: "Large"
type: "Construct"
alignment: "Lawful Neutral"
ac: "17 (Natural Armor)"
hp: "102 (12d10 + 36)"
hit_dice: "12d10 + 36"
speed: "30 ft., Fly 30 ft. (Hover)"
stats: [18, 14, 16, 10, 12, 10]
saves:
  - Str: "8"
  - Dex: "6"
  - Con: "7"
  - Wis: "5"
skillsaves:
  - Perception: "11"
damage_vulnerabilities: “Bludgeoning”
damage_resistances: "Piercing, and Slashing from Nonmagical Attacks"
damage_immunities: "Poison, Psychic"
condition_immunities: "Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 11"
languages: "Understands the languages of its creator but cannot speak"
cr: "6"
traits:
  - name: "Anti-Gravity Field"
    desc: "The Etheric Warden Golem generates a 20-foot radius anti-gravity field centered on itself. This field affects the following:<br>**Flight Restriction**: Flying creatures within this field must succeed on a DC 15 Dexterity saving throw or have their flight reduced to 0 feet until the end of their next turn.<br>**Weight Manipulation**: Large or smaller creatures within the field have disadvantage on Strength checks and saving throws."
  - name: "Ethereal Fragments"
    desc: "The floating, ethereal fragments surrounding the golem provide it with the following benefits:<br>**Ethereal Resilience**: The golem has resistance to force damage.<br>**Displacement**: The golem’s form is partially insubstantial, granting it advantage on Dexterity saving throws against attacks that rely on sight."
  - name: "Immutable Form"
    desc: "The Etheric Warden Golem is immune to any spell or effect that would alter its form."
  - name: "Magic Resistance"
    desc: "The Etheric Warden Golem has advantage on saving throws against spells and other magical effects."
  - name: "Magic Weapons"
    desc: "The Etheric Warden Golem’s weapon attacks are magical."
actions:
  - name: "Multiattack"
    desc: "The Etheric Warden Golem makes two attacks with its Crystalline Slam."
  - name: "Crystalline Slam"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 22 (3d10 + 4) bludgeoning damage."
  - name: "Gravity Pulse (Recharge 5-6)"
    desc: "The golem emits a pulse of anti-gravity energy in a 20-foot radius. Each creature of its choice within that area must make a DC 15 Constitution saving throw, taking 27 (6d8) force damage on a failed save, or half as much damage on a successful one. Additionally, affected creatures are pushed 10 feet away from the golem and are restrained until the end of their next turn."
  - name: "Meteoric Barrage (Recharge 6)"
    desc: "The golem summons fragments of floating rock to pelt enemies. Each creature in a 15-foot-radius sphere centered on a point within 60 feet of the golem must make a DC 15 Dexterity saving throw. On a failed save, a creature takes 22 (5d8) bludgeoning damage and is knocked prone. On a successful save, the creature takes half damage and is not knocked prone."
reactions:
  - name: "Gravitational Deflection"
    desc: "When the Etheric Warden Golem is hit by an attack, it can use its reaction to create a gravitational distortion field, imposing disadvantage on the attack roll."
```
### Solar Golem
**Behavior and Tactics**
Solar Golems are resolute guardians, designed to protect and alert. When reduced to half health, they will activate their siren to call for reinforcements. If other golems are in the area, they will converge on the location to provide aid. Players will need to act quickly to disable the siren or risk facing multiple golems at once. This makes encounters with Solar Golems more tactical, encouraging players to think creatively about how to handle the situation. The Golem fights fiercely to protect its charges, using its radiant aura to weaken enemies while shielding allies. If confronted in sunlight, it becomes even more formidable, but its vulnerabilities to dark magic and non-magical attacks give clever opponents an opportunity to bring it down.
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Solar Golem"
size: "Large"
type: "Construct"
alignment: "Lawful Neutral"
ac: "19 (Natural Armor)"
hp: "152 (16d10 + 64)"
hit_dice: "16d10 + 64"
speed: "30 ft."
stats: [22, 12, 18, 6, 14, 10]
saves:
  - Str: "10"
  - Con: "8"
  - Wis: "6"
skillsaves:
  - Perception: "12"
damage_resistances: "Fire, Radiant"
damage_vulnerabilities: "Necrotic, Bludgeoning, Piercing, and Slashing from Nonmagical Attacks"
condition_immunities: "Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned"
senses: "Darkvision 60 ft., Passive Perception 12"
languages: "Understands the languages of its creator but cannot speak"
cr: "10 (5,900 XP)"
traits:
  - name: "Radiant Aura"
    desc: "The Solar Golem emits an aura of radiant energy in a 15-foot radius around it. Any hostile creature that starts its turn within the aura must succeed on a DC 16 Constitution saving throw or take 10 (3d6) radiant damage. Additionally, allies within the aura gain 5 temporary hit points at the start of their turn."
  - name: "Sunlight Absorption"
    desc: "When the Solar Golem is in direct sunlight, it regenerates 10 hit points at the start of its turn. If the Golem takes necrotic damage, this trait doesn’t function at the start of the Golem’s next turn."
  - name: "Immutable Form"
    desc: "The Solar Golem is immune to any spell or effect that would alter its form."
  - name: "Magic Resistance"
    desc: "The Solar Golem has advantage on saving throws against spells and other magical effects."
  - name: "Magic Weapons"
    desc: "The Solar Golem’s weapon attacks are magical."
  - name: "Siren Alert"
    desc: "When the Solar Golem drops below half of its maximum hit points (76 HP), it emits a loud, piercing siren. All constructs within a 60-foot radius are alerted to its distress and will begin moving toward the Solar Golem's location. These constructs will arrive at the start of the Solar Golem's next turn if they are within range. The siren can be heard clearly up to 300 feet away, and muffled up to 600 feet away. <br>**Countering the Siren**: A creature can use an action to make a DC 18 Intelligence (Arcana) or Wisdom (Insight) check to identify the mechanism producing the siren. If successful, the creature can attempt to disable it by making a DC 18 Dexterity (Thieves' Tools) check as an action. If successful, the siren is disabled, and no alert is sent."
actions:
  - name: "Multiattack"
    desc: "The Solar Golem makes two attacks with its Radiant Strike."
  - name: "Radiant Strike"
    desc: "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 22 (3d10 + 6) bludgeoning damage plus 10 (3d6) radiant damage."
  - name: "Solar Beam (Recharge 5-6)"
    desc: "The Solar Golem releases a concentrated beam of solar energy in a 60-foot line that is 5 feet wide. Each creature in that line must make a DC 18 Dexterity saving throw, taking 49 (11d8) radiant damage on a failed save, or half as much damage on a successful one. This beam counts as sunlight for the purposes of creatures with sunlight sensitivity or sunlight vulnerability."
  - name: "Blinding Flash (Recharge 6)"
    desc: "The Solar Golem emits a burst of intense light. Each creature within 30 feet of the golem that can see it must succeed on a DC 16 Constitution saving throw or be blinded for 1 minute. A blinded creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
legendary_actions:
  - name: "Solar Shield"
    desc: "When the Solar Golem is hit by an attack, it can use its reaction to create a shield of radiant energy, granting it a +4 bonus to AC until the start of its next turn, including against the triggering attack."
```
## Legendary
### Glacier Serpent
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Glacier Serpent"
size: "Colossal"
type: "Monstrosity"
alignment: "Neutral"
ac: "18 (Natural Armor)"
hp: "325 (25d20 + 150)"
hit_dice: "25d20 + 150"
speed: "20 ft., climb 20 ft., swim 40 ft."
stats: [30, 8, 25, 10, 16, 14]
saves:
  - Con: "14"
  - Wis: "10"
skillsaves:
  - Perception: "10"
  - Stealth: "11"
damage_resistances: "Cold, Bludgeoning from nonmagical attacks"
damage_immunities: "Poison"
condition_immunities: "[[Mechanics#Frightened|Frightened]], [[Mechanics#Paralyzed|Paralyzed]], [[Mechanics#Exhaustion|Exhaustion]]"
senses: "[[Mechanics#Blindsight|Blindsight]] 120 ft., [[Mechanics#Tremorsense|Tremorsense]] 240 ft., Passive Perception 20"
languages: "Primordial (understands but cannot speak)"
cr: "18"
traits:
  - name: "Living Landscape"
    desc: "The Glacier Serpent's massive body is covered in a thick layer of snow and ice, forming a deceptive landscape. Creatures can unknowingly walk on its surface without realizing they're on a living being. The serpent can sense all creatures on its body and can choose to ignore or interact with them. Small settlements or structures built on the serpent remain undisturbed unless it chooses to move."
  - name: "Frozen Ecosystem"
    desc: "The Glacier Serpent's body hosts a unique ecosystem of ice-adapted flora and fauna. These creatures are considered part of the serpent and can act independently to defend it. As a bonus action, the serpent can awaken 1d4 + 2 Ice Guardians (use [[Mechanics#Animated Armor|Animated Armor]] stats with cold immunity) within 120 feet of it."
  - name: "Thawed Memories"
    desc: "Ancient creatures and artifacts are sometimes frozen within the Glacier Serpent's body. When the serpent takes fire damage, roll a d20. On a 18-20, a random effect occurs: a creature or object emerges from the ice, potentially aiding or hindering nearby creatures."
  - name: "Shifting Terrain"
    desc: "The area within 60 feet of the Glacier Serpent is considered difficult terrain due to the constantly shifting ice and snow. Additionally, at the start of each of the serpent's turns, the terrain within this area changes. Creatures in the area must succeed on a DC 18 Dexterity saving throw or fall [[Mechanics#Prone|prone]]."
actions:
  - name: "Multiattack"
    desc: "The Glacier Serpent makes two attacks: one with its Bite and one with its Tail Swipe."
  - name: "Bite"
    desc: "Melee Weapon Attack: +17 to hit, reach 20 ft., one target. Hit: 36 (4d12 + 10) piercing damage plus 18 (4d8) cold damage. If the target is Huge or smaller, it must succeed on a DC 22 Strength saving throw or be swallowed. A swallowed creature is [[Mechanics#Blinded|blinded]] and [[Mechanics#Restrained|restrained]], has total cover against attacks from outside the serpent, and takes 36 (8d8) cold damage at the start of each of the serpent's turns.<br>If the Glacier Serpent takes 60 damage or more on a single turn from a creature inside it, it must succeed on a DC 22 Constitution saving throw or regurgitate all swallowed creatures, which fall [[Mechanics#Prone|prone]] in a space within 30 feet of the serpent. If the serpent dies, a swallowed creature is no longer [[Mechanics#Restrained|restrained]] by it and can escape from the corpse by using 60 feet of movement, exiting [[Mechanics#Prone|prone]]."
  - name: "Tail Swipe"
    desc: "Melee Weapon Attack: +17 to hit, reach 40 ft., all creatures in a 40-foot line. Hit: 28 (4d8 + 10) bludgeoning damage plus 18 (4d8) cold damage. All creatures hit by the Tail Swipe must succeed on a DC 22 Strength saving throw or be knocked [[Mechanics#Prone|prone]] and pushed 20 feet away from the serpent."
  - name: "Glacial Maw (Recharge 5-6)"
    desc: "The Glacier Serpent opens its massive maw, creating a swirling vortex of icy wind and sharp ice shards in a 90-foot cone. Each creature in that area must make a DC 22 Dexterity saving throw. On a failed save, a creature takes 56 (16d6) cold damage and becomes [[Mechanics#Restrained|restrained]] by ice until the end of its next turn. On a successful save, the creature takes half as much damage and isn't [[Mechanics#Restrained|restrained]]. The area within the cone becomes difficult terrain until the end of the serpent's next turn."
legendary_actions:
  - name: "The Glacier Serpent can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature's turn. The Glacier Serpent regains spent legendary actions at the start of its turn."
  - name: "Tail Lash"
    desc: "The Glacier Serpent makes a Tail Swipe attack."
  - name: "Glacial Shift (Costs 2 Actions)"
    desc: "The Glacier Serpent subtly moves its body, causing the icy landscape to shift dramatically. Each creature within 60 feet of the serpent must succeed on a DC 18 Dexterity saving throw or fall 60 feet into a suddenly-opened crevasse, taking 21 (6d6) bludgeoning damage and becoming [[Mechanics#Restrained|restrained]]. A [[Mechanics#Restrained|restrained]] creature can use its action to make a DC 18 Strength (Athletics) or Dexterity (Acrobatics) check to escape."
  - name: "Awaken Frozen Horror (Costs 3 Actions)"
    desc: "The Glacier Serpent expels a long-frozen creature from its icy body. An Ice Golem (use [[Mechanics#Stone Golem|Stone Golem]] stats with cold immunity instead of poison) emerges in an unoccupied space within 60 feet of the serpent and acts immediately on the serpent's initiative. The Ice Golem crumbles after 1 minute or when reduced to 0 hit points."
```

### Magma Sentinel
Huge gate-keeper esque golem made of stone and magma. Has 3-4 arms, and a large almost mechanical looking head. This creature lives deep within an active volcano. It sits, constantly submerged within a large molten lake and will protect the sanctity of the volcano. They act as guardians. For the most part things that are smaller than them they ignore unless they are annoyed. This is considered a legendary creature. It probably has a cr of around 10-13

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Magma Sentinel"
size: "Huge"
type: "Construct"
alignment: "Lawful Neutral"
ac: "21 (Enhanced Natural Armor)"
hp: "276 (24d12 + 120)"
hit_dice: "24d12 + 120"
speed: "30 ft."
stats: [26, 12, 22, 12, 18, 11]
saves:
  - Str: "13"
  - Con: "11"
  - Wis: "9"
skillsaves:
  - Perception: "14"
  - Insight: "9"
damage_resistances: "Lightning; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks"
damage_immunities: "Fire, Poison, Psychic"
condition_immunities: "[[Mechanics#Charmed|Charmed]], [[Mechanics#Exhaustion|Exhaustion]], [[Mechanics#Frightened|Frightened]], [[Mechanics#Paralyzed|Paralyzed]], [[Mechanics#Petrified|Petrified]], [[Mechanics#Poisoned|Poisoned]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 120 ft., [[Mechanics#Tremorsense|Tremorsense]] 60 ft., Passive Perception 14"
languages: "Ignan, Terran, Primordial; understands but cannot speak"
cr: "15"
traits:
  - name: "Legendary Resistances (3/Day)"
    desc: "If the Magma Sentinel fails a saving throw, it can choose to succeed instead."
  - name: "Magma Submersion"
    desc: "While submerged in molten lava, the Magma Sentinel gains the following benefits:<br>**Damage Reduction**: The Magma Sentinel gains resistance to all damage except force and psychic while submerged.<br>**Regeneration**: The Magma Sentinel regains 20 hit points at the start of its turn if it has at least 1 hit point and is fully submerged in lava.<br>**Blazing Aura**: Any creature that starts its turn within 20 feet of the Sentinel while it is submerged in lava takes 21 (6d6) fire damage."
  - name: "Immutable Form"
    desc: "The Magma Sentinel is immune to any spell or effect that would alter its form."
  - name: "Magic Resistance"
    desc: "The Magma Sentinel has advantage on saving throws against spells and other magical effects."
  - name: "Magic Weapons"
    desc: "The Magma Sentinel's weapon attacks are magical."
  - name: "Ancestral Whispers"
    desc: "The Magma Sentinel is connected to the ancient spirits of the volcano. As a bonus action, it can gain [[Mechanics#Truesight|truesight]] out to a range of 30 feet until the start of its next turn."
actions:
  - name: "Multiattack"
    desc: "The Magma Sentinel makes three attacks: one with its Molten Slam and two with its Magma Fist."
  - name: "Molten Slam"
    desc: "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 39 (6d10 + 8) bludgeoning damage plus 21 (6d6) fire damage."
  - name: "Magma Fist"
    desc: "Melee Weapon Attack: +13 to hit, reach 15 ft., one target. Hit: 29 (4d10 + 8) bludgeoning damage plus 17 (5d6) fire damage."
  - name: "Erupting Flame (Recharge 5-6)"
    desc: "The Magma Sentinel causes magma to erupt in a 60-foot cone. Each creature in that area must make a DC 20 Dexterity saving throw, taking 72 (16d8) fire damage on a failed save, or half as much damage on a successful one. The area becomes difficult terrain for 1 minute as magma cools and solidifies."
  - name: "Volcanic Rune Activation (1/Day)"
    desc: "The Magma Sentinel activates one of the ancient runes etched into its body. Choose one of the following effects:<br>• **Searing Glyph**: Fiery symbols appear on the ground in a 30-foot radius around the Sentinel. Any creature that enters the area or starts its turn there must make a DC 18 Intelligence saving throw. On a failed save, the creature takes 36 (8d8) psychic damage and is [[Mechanics#Stunned|stunned]] until the end of its next turn.<br>• **Ember Eyes**: The Sentinel's eyes glow with an otherworldly light. Each creature within 60 feet that can see the Sentinel must succeed on a DC 18 Wisdom saving throw or be [[Mechanics#Frightened|frightened]] for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
legendary_actions:
  - name: "The Magma Sentinel can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The Magma Sentinel regains spent legendary actions at the start of its turn."
  - name: "Magma Swipe"
    desc: "The Magma Sentinel makes a Magma Fist attack."
  - name: "Molten Shield (Costs 2 Actions)"
    desc: "The Magma Sentinel envelops itself in molten lava, gaining temporary hit points equal to 40 + its Constitution modifier (6). Until the start of its next turn, any creature that hits the Magma Sentinel with a melee attack takes 21 (6d6) fire damage."
  - name: "Lava Surge (Costs 3 Actions)"
    desc: "The Magma Sentinel causes magma to surge from the ground in a 30-foot radius centered on a point it can see within 60 feet. Each creature in that area must make a DC 20 Dexterity saving throw, taking 63 (14d6) fire damage on a failed save, or half as much damage on a successful one. The area remains hot, and creatures that start their turn there take an additional 10 (3d6) fire damage until the end of their turn."
  - name: "Whisper of the Ancients (Costs 2 Actions)"
    desc: "The Magma Sentinel channels the whispers of ancient spirits. Each creature within 30 feet must succeed on a DC 18 Wisdom saving throw or take 22 (4d10) psychic damage and have [[Mechanics#Disadvantage|disadvantage]] on its next attack roll or ability check."
```
## Melusines 
The Melusine, also known as the Sorrowful Siren, is a tragic creature born from the depths of human longing and aquatic mysteries. Its upper body resembles a hauntingly beautiful humanoid, with skin that seems to shift between flesh and iridescent scales. Bioluminescent patterns pulse across its body, mimicking the movement of deep-sea creatures. Its lower half is a long, sinuous tail covered in scales that reflect light in hypnotic patterns.

The Melusine's face is a masterpiece of sorrow, with large, expressive eyes that seem to hold centuries of loneliness. Its mouth, when open, reveals rows of needle-like teeth behind full, alluring lips. Long, kelp-like hair flows around its head, moving as if constantly underwater.

In its humanoid form, the Melusine appears as a breathtakingly beautiful individual, but always with an air of profound sadness that draws others to it. This form retains subtle aquatic features, such as slightly webbed fingers or faint scale patterns visible in certain lights.

The Melusine is driven by an insatiable longing for companionship and a desperate fear of solitude. It lures victims with its beauty and song, not out of malice, but from a deep-seated need to share its eternal sorrow. Those who fall victim to its curse are slowly transformed, joining the Melusine in its tragic existence.

Melusine's are able to see the memories of those who ***fail*** and tend to portray themselves as their loved ones as a way to trick them.


```statblock
layout: Basic 5e Layout
name: "Melusine, the Sorrowful Siren"
image: [[melusine]]
size: "Medium"
type: "Fey"
subtype: "Shapechanger"
alignment: "Chaotic Neutral"
ac: "14 (natural armor)"
hp: "58 (9d8 + 18)"
hit_dice: "9d8 + 18"
speed: "15 ft., swim 40 ft."
stats: [14, 16, 14, 12, 14, 18]
saves:
  - Dex: "6"
  - Con: "4"
  - Cha: "7"
skillsaves:
  - Deception: "7"
  - Perception: "5"
  - Performance: "7"
  - Stealth: "6"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., Passive Perception 15"
languages: "Sylvan, Common"
cr: "5"
traits:
  - name: "Amphibious"
    desc: "The Melusine can breathe air and water."
  - name:"Melusine's Curse" 
    desc: "A creature afflicted by Melusine's Curse begins to slowly transform, their skin becoming pallid and scaly, their eyes growing large and sorrowful. At the end of each long rest, the cursed creature must succeed on a DC 14 Constitution saving throw or its Constitution score is reduced by 1d4. If a creature's Constitution is reduced to 0 by this curse, the creature dies and transforms into a new Melusine. The curse can be removed by a [[Mechanics#Remove Curse|Remove Curse]] spell or similar magic." 
  - name: "Sorrow's Embrace"
    desc: "The Melusine exudes an aura of melancholy within 30 feet of it. Any creature that starts its turn in this aura must succeed on a DC 15 Wisdom saving throw or be [[Mechanics#Charmed|charmed]] by the Melusine until the start of the creature's next turn. While [[Mechanics#Charmed|charmed]] in this way, the creature is [[Mechanics#Incapacitated|incapacitated]] and has a speed of 0, overcome by a sense of deep longing and sadness."
actions:
  - name: "Multiattack"
    desc: "The Melusine makes two attacks: one with its claws and one with its tail."
  - name: "Claws"
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12 (2d8 + 3) slashing damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or be afflicted with Melusine's Curse."
  - name: "Tail"
    desc: "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 10 (2d6 + 3) bludgeoning damage. If the target is a creature, it is [[Mechanics#Grappled|grappled]] (escape DC 14). Until this grapple ends, the target is [[Mechanics#Restrained|restrained]], and the Melusine can't use its tail on another target."
  - name: "Sorrowful Song (1/Day)"
    desc: "The Melusine sings a haunting melody. Each creature within 60 feet of the Melusine that can hear the song must succeed on a DC 15 Wisdom saving throw or be [[Mechanics#Charmed|charmed]] for 1 minute. While [[Mechanics#Charmed|charmed]], the creature is [[Mechanics#Incapacitated|incapacitated]] and has a speed of 0. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the Melusine's Sorrowful Song for the next 24 hours."
bonus_actions:
  - name: "Mournful Whisper"
    desc: "The Melusine whispers a secret sorrow to a [[Mechanics#Charmed|charmed]] creature within 5 feet of it. The target must succeed on a DC 15 Wisdom saving throw or take 10 (3d6) psychic damage and become [[Mechanics#Frightened|frightened]] of the Melusine for 1 minute."
```
## Serpents
### Flamevine Serpent
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Flamevine Serpent"
size: "Large"
type: "Monstrosity"
alignment: "Neutral Evil"
ac: "15 (Natural Armor)"
hp: "85 (10d10 + 30)"
hit_dice: "10d10 + 30"
speed: "40 ft., climb 30 ft."
stats: [18, 16, 16, 8, 14, 12]
saves:
  - Dex: "6"
  - Con: "6"
skillsaves:
  - Stealth: "6"
  - Perception: "5"
damage_immunities: "Fire"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., Passive Perception 15"
languages: "Understands Draconic but can't speak"
cr: "5"
spells:
  - 3rd Level (3): "Fireball"
  - 4th Level (1): "Wall of Fire"
traits:
  - name: "Blazing Infusion"
    desc: "The Flamevine Serpent's body is infused with the essence of fire, allowing it to cast Fireball 3/day and Wall of Fire 1/day."
  - name: "Burning Vine Trail"
    desc: "As the Flamevine Serpent moves, it leaves a trail of fire. Any creature that ends its turn in a space within 5 feet of the Serpent takes 7 (2d6) fire damage."
  - name: "Fiery Glow"
    desc: "The Flamevine Serpent's body emits bright, fiery light in a 15-foot radius and dim light for an additional 15 feet. As a bonus action, the serpent can cause the light to flare, [[Mechanics#Blinded|blinding]] any creature within 10 feet that fails a DC 15 Constitution saving throw until the start of the serpent's next turn."
  - name: "Pack Behavior"
    desc: "The Flamevine Serpent is often accompanied by 1d6 Flamevine Spawnlings. If any of the Spawnlings are threatened or injured, the Flamevine Serpent becomes highly aggressive, gaining advantage on attack rolls against any creature that has harmed its Spawnlings. The Serpent will fight fiercely to protect them, using its Flame Surge and Fiery Glow abilities more strategically in defense of its young."
actions:
  - name: "Multiattack"
    desc: "The Flamevine Serpent makes two attacks: one with its Vine Bite and one with its Tail Swipe."
  - name: "Vine Bite"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 12 (2d6 + 5) piercing damage plus 9 (2d8) fire damage. The target must also succeed on a DC 15 Constitution saving throw or take 7 (2d6) fire damage at the start of each of its turns for the next minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on a success."
  - name: "Tail Swipe"
    desc: "Melee Weapon Attack: +8 to hit, reach 15 ft., one target. Hit: 15 (2d8 + 6) bludgeoning damage."
  - name: "Flame Surge"
    desc: "The Flamevine Serpent releases a surge of fiery energy. Each creature within a 15-foot cone must make a DC 15 Dexterity saving throw, taking 27 (6d8) fire damage on a failed save, or half as much on a successful one. (Recharge 5-6)"
column: 2
forceColumns: true

```


#### Flamevine Spawnling
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Flamevine Spawnling"
size: "Medium"
type: "Monstrosity"
alignment: "Neutral Evil"
ac: "13 (Natural Armor)"
hp: "34 (6d8 + 6)"
hit_dice: "6d8 + 6"
speed: "30 ft., climb 20 ft."
stats: [14, 16, 12, 6, 12, 10]
saves:
  - Dex: "5"
skillsaves:
  - Stealth: "5"
  - Perception: "3"
damage_immunities: "Fire"
senses: "[[Mechanics#Darkvision|Darkvision]] 30 ft., Passive Perception 13"
languages: "Understands Draconic but can't speak"
cr: "1"
traits:
  - name: "Burning Bite"
    desc: "The Flamevine Spawnling's bite carries a lesser version of the adult's fire power. A creature bitten by the Spawnling must succeed on a DC 11 Constitution saving throw or take 4 (1d8) fire damage at the start of each of its turns for the next minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on a success."
  - name: "Fiery Trail"
    desc: "The Flamevine Spawnling leaves a faint trail of embers as it moves. Any creature that ends its turn in a space within 5 feet of the Spawnling takes 3 (1d6) fire damage."
  - name: "Defensive Aggression"
    desc: "If a Flamevine Spawnling is injured, it becomes highly aggressive. The Spawnling gains advantage on attack rolls against any creature that has damaged it. This aggression lasts until the end of the Spawnling's next turn, or until it is no longer injured."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d6 + 2) piercing damage plus 4 (1d8) fire damage."
  - name: "Flame Flicker"
    desc: "The Spawnling can release a small burst of flame. Each creature within 5 feet of the Spawnling must make a DC 11 Dexterity saving throw, taking 7 (2d6) fire damage on a failed save, or half as much on a successful one. (Recharge 6)"
column: 2
forceColumns: true
```
### Golden Serpents
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Golden Serpent"
size: "Large"
type: "Monstrosity"
alignment: "Neutral"
ac: "17 (Natural Armor)"
hp: "95 (10d10 + 40)"
hit_dice: "10d10 + 40"
speed: "35 ft., climb 20 ft."
stats: [18, 16, 18, 10, 14, 16]
saves:
  - Dex: "6"
  - Con: "7"
  - Wis: "5"
skillsaves:
  - Stealth: "9"
  - Perception: "5"
damage_resistances: "Nonmagical bludgeoning, piercing, and slashing"
damage_immunities: "Poison"
condition_immunities: "[[Mechanics#Poisoned|Poisoned]], [[Mechanics#Petrified|Petrified]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., [[Mechanics#Tremorsense|Tremorsense]] 30 ft., Passive Perception 15"
languages: "Understands Draconic but can't speak"
cr: "6"
traits:
  - name: "Gleaming Camouflage"
    desc: "The Golden Serpent's scales shimmer with a golden hue, blending seamlessly with the golden fields of Lumina. The serpent has advantage on Dexterity (Stealth) checks made to hide in areas with golden or yellowish vegetation."
  - name: "Golden Venom"
    desc: "The Golden Serpent's bite is imbued with a potent venom that slowly petrifies its victims, turning them into solid gold over time. A creature bitten by the serpent must succeed on a DC 15 Constitution saving throw or become [[Mechanics#Poisoned|poisoned]]. While [[Mechanics#Poisoned|poisoned]] in this way, the creature's speed is reduced by 10 feet, and it takes 7 (2d6) necrotic damage at the start of each of its turns.<br>This effect lasts until the creature succeeds on a DC 15 Constitution saving throw at the end of one of its turns. After failing three saving throws, the creature begins to turn to gold, becoming [[Mechanics#Petrified|petrified]]. The creature is fully [[Mechanics#Petrified|petrified]] into gold after one hour, but this effect can be reversed by *Greater Restoration* or *Wish* before the transformation is complete."
  - name: "Golden Sheen"
    desc: "As a bonus action, the Golden Serpent can cause its scales to flash brightly, creating a dazzling effect. Each creature within 10 feet of the serpent that can see it must succeed on a DC 15 Wisdom saving throw or be [[Mechanics#Blinded|blinded]] until the start of the serpent's next turn."
  - name: "Pack Behavior"
    desc: "The Golden Serpent is often accompanied by 1d4 Golden Spawnlings. If any of the Spawnlings are threatened or injured, the Golden Serpent becomes extremely aggressive, gaining advantage on attack rolls against any creature that has harmed its Spawnlings. The Serpent will use its Golden Sheen and Golden Gaze abilities more frequently in defense of its young."
actions:
  - name: "Multiattack"
    desc: "The Golden Serpent makes two attacks: one with its Bite and one with its Constrict."
  - name: "Bite"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 14 (2d8 + 5) piercing damage plus 10 (3d6) poison damage. The target must succeed on a DC 15 Constitution saving throw or be affected by the Golden Venom."
  - name: "Constrict"
    desc: "Melee Weapon Attack: +8 to hit, reach 15 ft., one target. Hit: 16 (2d10 + 5) bludgeoning damage. The target is [[Mechanics#Grappled|grappled]] (escape DC 16) if the target is Large or smaller, and until this grapple ends, the target is [[Mechanics#Restrained|restrained]]."
  - name: "Golden Gaze"
    desc: "The Golden Serpent can focus its gaze on a creature within 30 feet that it can see. The target must make a DC 15 Wisdom saving throw. On a failed save, the creature begins to hallucinate, seeing visions of wealth and gold, becoming [[Mechanics#Charmed|charmed]] by the serpent for 1 minute. While [[Mechanics#Charmed|charmed]] in this way, the creature is [[Mechanics#Incapacitated|incapacitated]] and has a speed of 0. The effect ends early if the creature takes damage or another creature uses an action to shake it out of its stupor. (Recharge 5-6)"
column: 2
forceColumns: true
```



#### Golden Spawnling

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Golden Spawnling"
size: "Small"
type: "Monstrosity"
alignment: "Neutral"
ac: "14 (Natural Armor)"
hp: "28 (4d8 + 10)"
hit_dice: "4d8 + 10"
speed: "30 ft., climb 20 ft."
stats: [12, 16, 14, 6, 12, 14]
saves:
  - Dex: "5"
  - Con: "4"
skillsaves:
  - Stealth: "7"
  - Perception: "3"
damage_resistances: "Nonmagical bludgeoning, piercing, and slashing"
damage_immunities: "Poison"
condition_immunities: "[[Mechanics#Poisoned|Poisoned]], [[Mechanics#Petrified|Petrified]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 30 ft., [[Mechanics#Tremorsense|Tremorsense]] 15 ft., Passive Perception 13"
languages: "Understands Draconic but can't speak"
cr: "1"
traits:
  - name: "Gleaming Hide"
    desc: "The Golden Spawnling's scales shimmer with a golden hue, allowing it to blend into golden fields. It has advantage on Dexterity (Stealth) checks made to hide in areas with golden or yellowish vegetation."
  - name: "Golden Bite"
    desc: "The Golden Spawnling's bite delivers a weaker form of the venom its adult counterpart carries. A creature bitten by the Spawnling must succeed on a DC 12 Constitution saving throw or become [[Mechanics#Poisoned|poisoned]]. While [[Mechanics#Poisoned|poisoned]] in this way, the creature's speed is reduced by 5 feet, and it takes 3 (1d6) necrotic damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on a success."
  - name: "Defensive Aggression"
    desc: "If a Golden Spawnling is injured, it becomes highly aggressive. The Spawnling gains advantage on attack rolls against any creature that has damaged it. This aggression lasts until the end of the Spawnling's next turn, or until it is no longer injured."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 8 (2d4 + 3) piercing damage plus 4 (1d8) poison damage."
  - name: "Golden Flash"
    desc: "The Spawnling can cause its scales to emit a sudden flash of light. Each creature within 5 feet of the Spawnling that can see it must succeed on a DC 12 Wisdom saving throw or be [[Mechanics#Blinded|blinded]] until the start of the Spawnling's next turn. (Recharge 6)"
```


### Radiant Serpent


```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Radiant Serpent"
size: "Medium"
type: "Monstrosity"
alignment: "Neutral"
ac: "14 (Natural Armor)"
hp: "52 (8d8 + 16)"
hit_dice: "8d8 + 16"
speed: "30 ft., climb 20 ft., swim 20 ft."
stats: [12, 18, 14, 6, 14, 10]
saves:
  - Dex: "6"
  - Con: "4"
skillsaves:
  - Stealth: "6"
  - Perception: "4"
damage_immunities: "Fire, Radiant"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., Passive Perception 14"
languages: "Understands Draconic but can't speak"
cr: "3"
spells:
  - 1st Level (3): "Burning Hands"
  - 2nd Level (1): "Scorching Ray"
traits:
  - name: "Sunfyre Infusion"
    desc: "The Radiant Serpent has absorbed the magical essence of [[Sunfire Crystal]]s, giving it access to the following abilities: Innate Spellcasting: The Radiant Serpent's innate spellcasting ability is Wisdom (spell save DC 14). It can innately cast Burning Hands 3/day and Scorching Ray 1/day."
  - name: "Blistering Venom"
    desc: "The Radiant Serpent's bite injects a venom that causes intense burns and pain. When the serpent bites a creature, it must succeed on a DC 13 Constitution saving throw or take an additional 7 (2d6) fire damage at the start of each of its turns for the next minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
  - name: "Radiant Glow"
    desc: "The Radiant Serpent emits a faint light, shedding bright light in a 10-foot radius and dim light for an additional 10 feet. As a bonus action, it can intensify this glow, [[Mechanics#Blinded|blinding]] a creature within 5 feet that fails a DC 12 Constitution saving throw until the start of the serpent's next turn."
  - name: "Pack Behavior"
    desc: "The Radiant Serpent is often accompanied by 1d6 Radiant Spawnlings. If any of the Spawnlings are threatened or attacked, the Radiant Serpent becomes extremely aggressive, gaining advantage on attack rolls against any creature that has harmed its Spawnlings. The Serpent will fight fiercely to protect them, often displaying increased ferocity and using its Radiant Burst and Radiant Glow abilities more strategically to defend its young."
actions:
  - name: "Multiattack"
    desc: "The Radiant Serpent makes two attacks: one with its Bite and one with its Tail."
  - name: "Bite"
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8 + 4) piercing damage plus 5 (1d10) fire damage. The target must also succeed on a DC 13 Constitution saving throw or be [[Mechanics#Poisoned|poisoned]] by the Blistering Venom (as described above)."
  - name: "Tail Whip"
    desc: "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 9 (1d10 + 4) bludgeoning damage."
  - name: "Radiant Burst"
    desc: "The Radiant Serpent can release a burst of radiant energy absorbed from [[Sunfire Crystal]]s. Each creature within 10 feet of the serpent must make a DC 13 Dexterity saving throw, taking 14 (4d6) radiant damage on a failed save, or half as much on a successful one. (Recharge 5-6)"
```




#### Radiant Spawnling
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Radiant Spawnling"
size: "Small"
type: "Monstrosity"
alignment: "Neutral"
ac: "12 (Natural Armor)"
hp: "22 (4d6 + 8)"
hit_dice: "4d6 + 8"
speed: "25 ft., climb 10 ft., swim 10 ft."
stats: [8, 14, 14, 4, 12, 10]
saves:
  - Dex: "4"
skillsaves:
  - Stealth: "4"
  - Perception: "3"
damage_immunities: "Fire"
condition_immunities: ""
senses: "[[Mechanics#Darkvision|Darkvision]] 30 ft., Passive Perception 13"
languages: "Understands Draconic but can't speak"
cr: "1"
traits:
  - name: "Blistering Bite"
    desc: "The Radiant Spawnling's bite, while not as potent as an adult's, still carries a hint of its future power. A creature bitten by the Spawnling must succeed on a DC 11 Constitution saving throw or take 3 (1d6) fire damage at the start of each of its turns for the next minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
  - name: "Faint Glow"
    desc: "The Radiant Spawnling emits a soft light, shedding dim light in a 5-foot radius. This glow is harmless and primarily serves to illuminate its surroundings, but it hints at the creature's growing connection to the [[Sunfire Crystal]]s."
  - name: "Defensive Aggression"
    desc: "If a Radiant Spawnling is injured, it becomes highly aggressive. The Spawnling gains advantage on attack rolls against any creature that has damaged it. This aggressive behavior persists until the end of the Spawnling's next turn, or until it is no longer injured."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage plus 3 (1d6) fire damage."
  - name: "Radiant Flicker"
    desc: "As a fledgling ability, the Spawnling can attempt to release a small burst of radiant energy. Each creature within 5 feet of the Spawnling must make a DC 11 Dexterity saving throw, taking 7 (2d6) radiant damage on a failed save, or half as much damage on a successful one. (Recharge 6)"
column: 2
forceColumns: true
```


### Rustwyrm

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Rustwyrm"
size: "Large"
type: "Monstrosity"
alignment: "Neutral"
ac: "16 (Natural Armor)"
hp: "102 (12d10 + 36)"
hit_dice: "12d10 + 36"
speed: "40 ft., swim 30 ft."
stats: [19, 14, 17, 8, 12, 10]
saves:
  - Dex: "5"
  - Con: "6"
skillsaves:
  - Stealth: "7"
  - Perception: "4"
damage_resistances: "Acid, Poison"
condition_immunities: "[[Mechanics#Poisoned|Poisoned]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., [[Mechanics#Tremorsense|Tremorsense]] 30 ft., Passive Perception 14"
languages: "Understands Draconic but can't speak"
cr: "7"
traits:
  - name: "Iron Stomach"
    desc: "The Rustwyrm can consume and digest metal and stone, which it uses to aid in the consumption of its prey. It gains temporary hit points equal to the amount of metal ingested in pounds."
  - name: "Sulfurous Emission"
    desc: "The Rustwyrm can emit a cloud of sulfurous gas from its mouth to disorient and weaken its prey. The cloud fills a 20-foot radius centered on the Rustwyrm and lasts for 1 minute or until a strong wind disperses it. The area is heavily obscured, and any creature that starts its turn in the cloud must succeed on a DC 16 Constitution saving throw or be [[Mechanics#Poisoned|poisoned]] for 1 minute.<br>While [[Mechanics#Poisoned|poisoned]] this way, a creature is [[Mechanics#Incapacitated|incapacitated]] and cannot take actions, bonus actions, or reactions. The creature can repeat the saving throw at the end of each of its turns, ending the effect on a success."
actions:
  - name: "Multiattack"
    desc: "The Rustwyrm makes two attacks: one with its Bite and one with its Tail Swipe."
  - name: "Bite"
    desc: "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 18 (3d8 + 5) piercing damage. The Rustwyrm can then attempt to swallow a creature of Medium size or smaller that it has [[Mechanics#Grappled|grappled]]. The swallowed target is [[Mechanics#Blinded|blinded]] and [[Mechanics#Restrained|restrained]], has total cover against attacks and other effects outside the Rustwyrm, and takes 10 (3d6) acid damage at the start of each of the Rustwyrm's turns.<br>If the Rustwyrm takes 30 damage or more on a single turn from a creature inside it, the Rustwyrm must succeed on a DC 15 Constitution saving throw or regurgitate the swallowed creature, which falls [[Mechanics#Prone|prone]] in a space within 10 feet of the Rustwyrm."
  - name: "Tail Swipe"
    desc: "Melee Weapon Attack: +7 to hit, reach 15 ft., one target. Hit: 14 (2d8 + 5) bludgeoning damage. The target must succeed on a DC 15 Strength saving throw or be knocked [[Mechanics#Prone|prone]]."
  - name: "Rock Crusher (Recharge 5-6)"
    desc: "The Rustwyrm can perform a powerful crushing attack by rolling over its prey. Each creature within 10 feet of the Rustwyrm must make a DC 16 Dexterity saving throw, taking 27 (6d8) bludgeoning damage on a failed save, or half as much damage on a successful one. Creatures that fail the save are also [[Mechanics#Restrained|restrained]] as the Rustwyrm rolls over them."
  - name: "Pack Behavior"
    desc: "The Rustwyrm is often accompanied by 1d4 Rust-wyrmlings. If any of the Rust-wyrmlings are threatened or injured, the Rustwyrm becomes extremely aggressive, gaining advantage on attack rolls against any creature that has harmed its Rustlings. It will use its Rock Crusher and Sulfurous Emission abilities more frequently in defense of its young."
```
#### Rust-Wyrmlings
```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Rust-Wyrmling"
size: "Small"
type: "Monstrosity"
alignment: "Neutral"
ac: "13 (Natural Armor)"
hp: "32 (5d8 + 10)"
hit_dice: "5d8 + 10"
speed: "30 ft., swim 20 ft."
stats: [14, 14, 14, 6, 10, 8]
saves:
  - Dex: "4"
  - Con: "4"
skillsaves:
  - Stealth: "6"
  - Perception: "2"
damage_resistances: "Acid, Poison"
condition_immunities: "[[Mechanics#Poisoned|Poisoned]]"
senses: "[[Mechanics#Darkvision|Darkvision]] 30 ft., [[Mechanics#Tremorsense|Tremorsense]] 15 ft., Passive Perception 12"
languages: "Understands Draconic but can't speak"
cr: "1"
traits:
  - name: "Iron Belly"
    desc: "The Rust-Wyrmling consumes small stones and minerals, which help it digest tougher prey. It can bite through non-magical metal and stone as though it were soft material."
  - name: "Sulfuric Spit (Recharge 6)"
    desc: "The Wyrmling can spit a small glob of sulfuric acid at a creature within 10 feet. The target must make a DC 12 Dexterity saving throw, taking 7 (2d6) acid damage on a failed save, or half as much damage on a successful one. Creatures that fail the save are also [[Mechanics#Poisoned|poisoned]] until the end of their next turn."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 8 (2d6 + 2) piercing damage."
  - name: "Defensive Aggression"
    desc: "If a Rust-Wyrmling is injured, it becomes highly aggressive. The Wyrmling gains advantage on attack rolls against any creature that has damaged it. This aggression lasts until the end of the Wyrmling's next turn, or until it is no longer injured."
```
## Spiders
### Base Spiders 
```statblock 
creature: Giant Spider

```
### Shadow Weaver
A large, jet-black spider  with an iridescent sheen that blends into the darkness. It's webs are nearly invisible and exude a paralyzing toxin. These spiders often will inhabit dark caves, abandoned ruins, and shadowy forests.
```statblock 
name: Shadow Weaver
source: 5e SRD
size: Large
type: beast
subtype: ""
alignment: unaligned
ac: 14
hp: 26
hit_dice: 4d10 + 4
speed: 30 ft., climb 30 ft.
stats:
  - 14
  - 16
  - 12
  - 2
  - 11
  - 4
skillsaves:
  - stealth: 7
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: blindsight 10 ft., darkvision 60 ft., passive Perception 10
languages: ""
cr: "1"
bestiary: true
traits:
  - name: Spider Climb
    desc: The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.
    attack_bonus: 0
  - name: Web Sense
    desc: While in contact with a web, the spider knows the exact location of any other creature in contact with the same web.
    attack_bonus: 0
  - name: Web Walker
    desc: The spider ignores movement restrictions caused by webbing.
    attack_bonus: 0
actions:
  - name: Bite
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 7 (1d8 + 3) piercing damage, and the target must make a DC 11 Constitution saving throw, taking 9 (2d8) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hit points, the target is stable but poisoned for 1 hour, even after regaining hit points, and is paralyzed while poisoned in this way."
    attack_bonus: 5
    damage_dice: 1d8
    damage_bonus: 3
  - name: Web (Recharge 5-6)
    desc: "Ranged Weapon Attack: +5 to hit, range 30/60 ft., one creature. Hit: The target is restrained by webbing. As an action, the restrained target must make a DC14 CON or be [[mechanics.md#Paralyzed| paralyzed]], then can make a DC 11 Strength check, bursting the webbing on a success. . The webbing can also be attacked and destroyed (AC 10; hp 5; vulnerability to fire damage; immunity to bludgeoning, poison, and psychic damage)."
    attack_bonus: 5
column: 2
forceColumns: true
```


## Stags and Deer
### Celestial Deer
A creature with warm golden coat. They will often be seen around a Stag of some sort. 
```statblock
layout: Basic 5e Layout
name: "Celestial Deer"
image: [[celestial_deer.jpg]]
size: "Medium"
type: "Beast"
alignment: "Neutral Good"
ac: "13 (natural armor)"
hp: "12 (2d8 + 3)"
hit_dice: "2d8 + 3"
speed: "50 ft."
stats: [11, 16, 11, 2, 14, 5]
senses: "Passive Perception 12"
cr: "1"
traits:
  - name: "Forest Stride"
    desc: "Difficult terrain doesn't slow the Celestial Deer's travel while in a forest."
  - name: "Running Leap"
    desc: "With a 10-foot running start, the Celestial Deer can long jump up to 25 feet."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 5 (2d4) piercing damage."
  - name: "Hooves"
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (3d4) bludgeoning damage."
column: 2
forceColumns: true
```
### Celestial Stags
Celestial Stags are majestic creatures with  shimmering, silvery-white antlers. They possess  the ability to channel celestial energy, creating a protective barrier and guiding lost wanderers to safety. 
*Beloved by the Gods*: When a stag is killed, the deity that created it curses the creature that dealt the killing blow. The cursed creature finds the natural world working against them. Roots randomly rise up to trip the creature when it walks past a tree (5% chance per mile traveled in forest terrain). Animals are more reluctant to obey (disadvantage on [[Animal Handling]] checks). The wind seems to always be blowing in the least favorable direction for the creature (scattering papers, sending the creatures scent towards creatures tracking it, etc.) The curse lasts until lifted by a [[remove curse]] spell or after the cursed creature completes a task for the deity or its temple.
*Divine Messengers*. When pious elves die and their spirits journey to the Outer Planes, some are accorded the honor of spending a year and a day serving the elven gods as a white stag before moving on to enjoy the afterlife. A deity will dispatch a white stag to the Material Plane when it wants to send a group of mortals on a divine quest, or it needs to give them a nudge in the right direction.
```statblock 
layout: Basic 5e Layout
name: "Celestial Stag"
image: [[celestial_stag.jpg]]
size: "Large"
type: "Beast"
alignment: "Neutral Good"
ac: "14 (natural armor)"
hp: "62"
hit_dice: 7d12+12
speed: "60 ft"
stats: [18,15,13,10,15,14]
skillsaves: 
 - athletics: +5
 - insight: +4
 - perception: +5
senses: "Passive Perception 14"
languages: "Understands, Giant elk, sylvan, and Elvish"
cr: 3
traits:
 - name: "Forest Stride"
   desc: "Difficult terrain doesnt slow the stag' travel while in a forest."
 - name: "Running Leap"
   desc: "With a 10-foot running start, the stag can long jump up to 25 feet."
actions: 
 - name: "Multiattack"
   desc: "The stag makes one gore attack and one hooves attack."
 - name: "Gore"
   desc: "Melee Weapon Attack: +7 to hit, reach 5 ft. one target. Hit: 15 (2d8+5) piercing damage."
 - name: "Hooves"
   desc: "Melee Weapon Attack: +7 to hit, reach 5ft. one target. Hit: 25 (4d8+5) bludgeoning damage."
column: 2
forceColumns: true
```
----
### Radiant Deer
A creature with warm golden coat. They will often be seen around a Stag of some sort. 
```statblock
layout: Basic 5e Layout
name: "Radiant Deer"
image: [[radiant_deer.jpg]]
size: "Medium"
type: "Beast"
alignment: "Neutral Good"
ac: "13 (natural armor)"
hp: "12 (2d8 + 2)"
hit_dice: "2d8 + 2"
speed: "50 ft."
stats: [11, 16, 11, 2, 14, 5]
senses: "[[Mechanics#Darkvision|Darkvision]] 60 ft., Passive Perception 12"
damage_resistances: "Fire"
languages: "—"
cr: "1"
traits:
  - name: "Forest Stride"
    desc: "Difficult terrain doesn't slow the Radiant Deer's travel while in a forest."
  - name: "Running Leap"
    desc: "With a 10-foot running start, the Radiant Deer can long jump up to 25 feet."
actions:
  - name: "Bite"
    desc: "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 5 (2d4) piercing damage."
  - name: "Hooves"
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (3d4 + 1) bludgeoning damage."
column: 2
forceColumns: true
```
----

### Radiant Stags 
Creature with shimmering, golden antlers. 
Radiant stags are considered good omens, especially when seen in regions other than [[Lumina]]. 
*Forest Chase*: These stags will often lead adventurers on a chase through the forest through a number of obstacles, if the adventurers can keep up and not lose sight of the stag they are likely to find a useful clue or item. Sometimes the pursuers may experience a vision.
*Dying Curse*: A radiant stag always runs when attacked. If cornered, it defends itself to the best of its ability. Killing a radiant stag angers the gods who created it. When the stag dies, its body vanishes in a puff of golden smoke, and the person who slew the creature is subject to a curse that can only be removed with magic or by performing a quest on behalf of the gods- sometimes both.
*Mystical Favor*: If you come upon an injured radiant stag and are able to heal it and/or care for it. The stag will allow you to collect it's tears, which can be used to reincarnate a slain creature within 24 hrs after the death. However the creatures alignment is changed to be within 2 blocks of the stag's. 

```statblock
statblock
layout: Basic 5e Layout
name: "Celestial Stag"
image: [[celestial_stag.jpg]]
size: "Large"
type: "Beast"
alignment: "Neutral Good"
ac: "14 (natural armor)"
hp: "62 (7d12 + 12)"
hit_dice: "7d12 + 12"
speed: "60 ft."
stats: [18, 15, 13, 10, 15, 14]
skillsaves:
  - athletics: "5"
  - insight: "4"
  - perception: "5"
senses: "Passive Perception 15"
languages: "Understands Giant elk, Sylvan, and Elvish but can't speak"
cr: "3"
traits:
  - name: "Forest Stride"
    desc: "Difficult terrain doesn't slow the stag's travel while in a forest."
  - name: "Running Leap"
    desc: "With a 10-foot running start, the stag can long jump up to 25 feet."
actions:
  - name: "Multiattack"
    desc: "The stag makes one gore attack and one hooves attack."
  - name: "Gore"
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 15 (2d8 + 5) piercing damage."
  - name: "Hooves"
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 25 (4d8 + 5) bludgeoning damage."
column: 2
forceColumns: true
```
## Treants 
### Crimson Mangrove Treants
Found in the mangrove forests of [[Crimson Shores]]. These Treants use their long roots to traverse through the high waters. They are able to use their roots to latch onto creatures large and smaller and restrain them. The roots seem to resemble writhing tentacles and it's eye-like knots seem to follow it's potential prey. 

```statblock
layout: Basic 5e Layout
image: [[image]]
name: "Crimson Mangrove Treant"
size: "Huge"
type: "plant"
alignment: "neutral"
ac: "16 (natural armor)"
hp: "126 (12d12 + 48)"
hit_dice: "12d12 + 48"
speed: "30 ft., swim 30 ft."
stats: [21, 10, 19, 12, 16, 12]
damage_resistances: "bludgeoning, piercing"
damage_vulnerabilities: "fire"
condition_immunities: "[[Mechanics#Charmed|charmed]], [[Mechanics#Frightened|frightened]]"
senses: "[[Mechanics#Blindsight|blindsight]] 60 ft. (blind beyond this radius), passive Perception 13"
languages: "Common, Sylvan"
cr: "6"
traits:
  - name: "Amphibious"
    desc: "The treant can breathe air and water."
  - name: "Iron Absorption"
    desc: "The treant has advantage on Constitution saving throws while in contact with iron-rich water."
  - name: "False Appearance"
    desc: "While the treant remains motionless, it is indistinguishable from a normal mangrove tree."
actions:
  - name: "Multiattack"
    desc: "The treant makes two root lash attacks."
  - name: "Root Lash"
    desc: "Melee Weapon Attack: +8 to hit, reach 15 ft., one target. Hit: 16 (3d6 + 6) bludgeoning damage. If the target is Large or smaller, it must succeed on a DC 16 Strength saving throw or be [[Mechanics#Grappled|grappled]] (escape DC 16). Until this grapple ends, the target is [[Mechanics#Restrained|restrained]], and the treant can't use this root to attack another target."
  - name: "Rock"
    desc: "Ranged Weapon Attack: +8 to hit, range 60/180 ft., one target. Hit: 26 (4d8 + 8) bludgeoning damage."
  - name: "Crimson Mist (Recharge 5-6)"
    desc: "The treant releases a cloud of iron-rich mist in a 30-foot radius. Each creature in that area must make a DC 15 Constitution saving throw. On a failure, the creature takes 18 (4d8) poison damage and is [[Mechanics#Poisoned|poisoned]] for 1 minute. On a success, the creature takes half damage and isn't [[Mechanics#Poisoned|poisoned]]. A [[Mechanics#Poisoned|poisoned]] creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
bonus_actions:
  - name: "Root Network"
    desc: "The treant can move up to its speed without provoking opportunity attacks by submerging its roots and resurfacing them. During this movement, it can pass through spaces as narrow as 1 foot wide without squeezing."
```
