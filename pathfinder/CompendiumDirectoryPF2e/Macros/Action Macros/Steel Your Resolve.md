---
title: "Steel Your Resolve"
icon: ":file-question:"
aliases: "Steel Your Resolve"
foundryId: Compendium.pf2e.action-macros.Macro.oxowCzHbxSGOWRke
tags:
  - Macro
---

# Steel Your Resolve
![[icons/skills/social/intimidation-impressing.webp|150]]

```Macro
author: 7rBRoXLPb5I767rN
command: |-
  const tokens = canvas.tokens.controlled;
  if (tokens.length != 1) {
      ui.notifications.error(`You must select one pc token`);
  } else {
      game.pf2e.actions.steelYourResolve({ actors: [token.actor ?? actor].filter((actor) => actor !== null) });
  }
img: icons/skills/social/intimidation-impressing.webp
name: Steel Your Resolve
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
