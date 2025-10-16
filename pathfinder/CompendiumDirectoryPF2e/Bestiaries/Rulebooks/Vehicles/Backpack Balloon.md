---
title: Backpack Balloon
obsidianUIMode: preview
noteType: pf2eVehicle
cssClasses: pf2e
tags:
  - clockwork
  - pf2eVehicle

  - remaster
source: Pathfinder Battlecry!
aliases: "Compendium.pf2e.vehicles.Actor.c4wyqiRjepkHipZJ" 
level: 6
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Backpack Balloon"
level: "Vehicle 6"
rare_03: [[Uncommon]]

size: "Medium"
trait_01: [[clockwork]]
modifier: 
perception:
  - name: ""
  - name: "Price"
    desc: "750 gp\n* * *"
  - name: ""
    desc: "What appears to be a simple, if bulky, backpack conceals clockwork devices that can inflate two large balloons, carrying the backpack's wearer through the air for brief periods of time. In addition, propellers allow the pilot to move while airborne.\n* * *"
abilities_top:
  - name: ""
  - name: "Space"
    desc: "5 feet long, 5 feet wide, 5 feet high"
  - name: "Crew"
    desc: "1 pilot; **Passengers** "
  - name: "Piloting Check"
    desc: "Athletics (DC 24) or Piloting Lore (DC 22)"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +13"
hp: 80
health:
  - name: ""
  - name: "Hardness"
    desc: "5; **HP** 80 (BT 40); __Immunities__  object immunities; __Weaknesses__ fire 5"
speed: "fly 20 feet (alchemical, clockwork, wind)"
abilities_mid:
  - name: ""
attacks:
  - name: ""
  - name: "Collision"
    desc: "3d10 (DC 22)"

  - name: "Deploy Balloons"
    desc: "`pf2:3` (manipulate) The pilot engages a lever that activates the clockwork components to launch two large tethered balloons and fill them with lighter-than-air gas. On the outside of the backpack is a small clockwork propeller. This allows the wearer to wind up and pilot the vehicle.\n\nThis transformation lasts until the pilot disengages the balloons by using this activity again."

  - name: "Stowable"
    desc: " By spending 10 minutes repacking, the backpack balloons can be stowed after the pilot has disengaged them."

  - name: "Wind-Up"
    desc: " 10 minutes of wind-up, 30 minutes of operational time, [[Actions/disable-device dc=22|disable-device dc=22]]{DC 22}, standy\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."



sourcebook: "_Pathfinder Battlecry!_"
```

```encounter-table
name: Backpack Balloon
creatures:
  - 1: Backpack Balloon
```

