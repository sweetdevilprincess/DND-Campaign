---
tags:
  - location
  - difficulty/easy
  - enviroment/area
  - time/time
  - conditions/conditions when found
  - type/creature type
  - behavior/behavior
---
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

### Statblock
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



#no_show