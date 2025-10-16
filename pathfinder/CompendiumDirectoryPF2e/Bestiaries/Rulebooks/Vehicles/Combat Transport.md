---
title: Combat Transport
obsidianUIMode: preview
noteType: pf2eVehicle
cssClasses: pf2e
tags:
  - clockwork
  - pf2eVehicle

  - remaster
source: Pathfinder Battlecry!
aliases: "Compendium.pf2e.vehicles.Actor.UUN41cEHd23gbS2j" 
level: 15
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Combat Transport"
level: "Vehicle 15"


size: "Gargantuan"
trait_01: [[clockwork]]
modifier: 
perception:
  - name: ""
  - name: "Price"
    desc: "20000 gp\n* * *"
  - name: ""
    desc: "These massive vehicles incorporate multiple gas filled bladders and clockwork technology to quickly deploy troops in battle. With a large fuselage bracketed by equally large gas bladders, combat transports utilize both aft-mounted and bottom-mounted clockwork fans to move and hover.\n* * *"
abilities_top:
  - name: ""
  - name: "Space"
    desc: "50 feet long, 50 feet wide, 30 feet high"
  - name: "Crew"
    desc: "1 pilot, 3 crew; **Passengers** 40"
  - name: "Piloting Check"
    desc: "Crafting (DC 36) or Piloting Lore (DC 34)"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26"
hp: 230
health:
  - name: ""
  - name: "Hardness"
    desc: "20; **HP** 230 (BT 115); __Immunities__  precision,  object immunities"
speed: "fly 40 feet (alchemical, clockwork, wind)"
abilities_mid:
  - name: ""
attacks:
  - name: ""
  - name: "Collision"
    desc: "9d12 (DC 34)"

  - name: "Space"
    desc: " 80 feet long, 60 feet wide, 30 feet high"

  - name: "Hover"
    desc: " Combat transports have a series of six large clockwork fans built into their flat under body. These fans can be activated when Stopping the vehicle to allow it to hover within 5 feet of the surface so that troops can be quickly deployed via forward and aft ramps, regardless of the nature of the terrain."

  - name: "Sluggish"
    desc: " This vehicle must move twice its length for each 90-degree turn it makes."

  - name: "Wind-Up"
    desc: " 30 minutes of wind-up, 3 hours of operational time, [[Actions/disable-device dc=34|disable-device dc=34]]{DC 34}, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."



sourcebook: "_Pathfinder Battlecry!_"
```

```encounter-table
name: Combat Transport
creatures:
  - 1: Combat Transport
```

