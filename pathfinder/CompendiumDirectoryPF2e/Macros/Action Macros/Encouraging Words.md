---
title: "Encouraging Words"
icon: ":file-question:"
aliases: "Encouraging Words"
foundryId: Compendium.pf2e.action-macros.Macro.I6MMTpk9faBOHb2T
tags:
  - Macro
---

# Encouraging Words
![[icons/svg/dice-target.svg|150]]

```Macro
author: 7rBRoXLPb5I767rN
command: |-
  const tokens = canvas.tokens.controlled;
  if (tokens.length != 1) {
      ui.notifications.error(`You must select one pc token`);
  } else {
      game.pf2e.actions.encouragingWords({ actors: [token.actor ?? actor].filter((actor) => actor !== null) });
  }
img: icons/svg/dice-target.svg
name: Encouraging Words
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
