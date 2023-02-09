---
sidebar_position: 3
title: Abilities
---

# `abilities/<name>.json`

| Name | Type | Description | Optional | Default |
| --- | --- | --- | --- | --- |
| base | `String` | The base from which to inherit other properties | No | N/A |
| id | `String` | The identifier | No | N/A |
| name | `String` | The name, can have colors | Yes | The identifier |
| description | `List<String>` | The description, can have colors | Yes | None |
| price | `Price` | The amount of health and hunger deducted from the player upon activation | No | N/A |
| cooldown | `long` | The cooldown in ticks (1 second = 20 ticks) | Yes | 0 |

```json
{
  "base": "Fire",
  "id": "FIRE",
  "name": "%gold%Fire",
  "description": [
    "%gray%Summons a vortex of fire that ignites",
    "%gray%everyone on its way for 5 seconds!"
  ],
  "price": {
    "health": 4,
    "food": 4
  },
  "cooldown": 100,
  "function": {
    "x": "0.5tcos(6t)",
    "y": "0.5tsin(6t)",
    "z": "t",
    "min": 0,
    "max": 3.14159265359,
    "delta": 0.09817477042
  },
  "particle": "FLAME",
  "fireDuration": 100
}
```
