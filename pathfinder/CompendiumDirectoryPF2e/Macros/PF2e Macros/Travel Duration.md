---
title: "Travel Duration"
icon: ":file-question:"
aliases: "Travel Duration"
foundryId: Compendium.pf2e.pf2e-macros.Macro.NQkc5rKoeFemdVHr
tags:
  - Macro
---

# Travel Duration
![[systems/pf2e/icons/equipment/adventuring-gear/cartographers-kit.webp|150]]

```Macro
author: ru9MkwAaWXaeSZph
command: |-
  const tokens = canvas.tokens.controlled;
  if (tokens.length === 0) {
      ui.notifications.error(`You must select at least one pc token`);
  } else {
      game.pf2e.gm.launchTravelSheet(tokens.map((p) => p.actor));
  }
img: systems/pf2e/icons/equipment/adventuring-gear/cartographers-kit.webp
name: Travel Duration
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
