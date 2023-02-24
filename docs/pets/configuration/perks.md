---
sidebar_position: 3
title: Perks
---

# `perks/<name>.json`

| Name | Type | Description |
| --- | --- | --- |
| base | `String` | The base from which to inherit other properties |
| id | `String` | The identifier |
| name | `String` | The name, can have colors |

```json
{
  "base": "Damage",
  "id": "DAMAGE_WITHER_2",
  "name": "%red%Wither Vanquisher",
  "description": [
    "%gray%Increases the amount of damage you deal",
    "%gray%to withers by 37.5% and wither skeletons",
    "%gray%by 62.5%!"
  ],
  "bonuses": {
    "WITHER": "0.375x",
    "WITHER_SKELETON": "0.625x"
  }
}
```
