---
title: "Rest for the Night"
icon: ":file-question:"
aliases: "Rest for the Night"
foundryId: Compendium.pf2e.pf2e-macros.Macro.0GU2sdy3r2MeC56x
tags:
  - Macro
---

# Rest for the Night
![[icons/svg/sleep.svg|150]]

```Macro
author: 4rlSA43v1xPa1vsy
command: >-
  game.pf2e.actions.restForTheNight({ actors: [game.user.character ??
  canvas.tokens.controlled.map((t) => t.actor)].flat().filter((a) => a?.type ===
  "character") })
img: icons/svg/sleep.svg
name: Rest for the Night
scope: global
type: script
_stats:
  coreVersion: '13.345'
  systemId: pf2e
  systemVersion: 7.3.1
  lastModifiedBy: null
folder: null
flags: {}
```
