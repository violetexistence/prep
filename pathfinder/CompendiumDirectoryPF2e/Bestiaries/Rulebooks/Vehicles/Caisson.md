---
title: Caisson
obsidianUIMode: preview
noteType: pf2eVehicle
cssClasses: pf2e
tags:
  - clockwork
  - pf2eVehicle

  - remaster
source: Pathfinder Battlecry!
aliases: "Compendium.pf2e.vehicles.Actor.AexJwHcCnOxnbcro" 
level: 4
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Caisson"
level: "Vehicle 4"
rare_03: [[Uncommon]]

size: "Large"
trait_01: [[clockwork]]
modifier: 
perception:
  - name: ""
  - name: "Price"
    desc: "240 gp\n* * *"
  - name: ""
    desc: "This heavily armored wagon is designed to transport black powder and other flammable munitions in and around combat zones. It has extra armor plating that increases its weight to several times that of an ordinary wagon. Due to this extra weight, the armored wagon is quite slow.\n* * *"
abilities_top:
  - name: ""
  - name: "Space"
    desc: "10 feet long, 10 feet wide, 10 feet high"
  - name: "Crew"
    desc: "1 pilot; **Passengers** 1"
  - name: "Piloting Check"
    desc: "Driving Lore (DC 19) or Crafting (DC 21)"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +11"
hp: 50
health:
  - name: ""
  - name: "Hardness"
    desc: "5; **HP** 50 (BT 25); __Immunities__  object immunities"
speed: "15 feet (clockwork)"
abilities_mid:
  - name: ""
attacks:
  - name: ""
  - name: "Collision"
    desc: "3d8 (DC 19)"

  - name: "Sluggish"
    desc: " This vehicle must move twice its length for each 90-degree turn it makes."

  - name: "Wind-Up"
    desc: " 1 hour of wind-up, 6 hours of operational time, [[Actions/disable-device dc=19|disable-device dc=19]]{DC 19}, standy\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

  - name: "Space"
    desc: " 10 feet long, 10 feet wide, 8 feet high"



sourcebook: "_Pathfinder Battlecry!_"
```

```encounter-table
name: Caisson
creatures:
  - 1: Caisson
```

