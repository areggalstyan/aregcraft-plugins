---
sidebar_position: 9
title: perks.json
---

# `perks.json: List<Perk>`

| Name | Type | Description |
| --- | --- | --- |
| base | `String` | The base from which to inherit other properties |
| id | `String` | The identifier |
| name | `String` | The name, can have colors |

```json
[
  {
    "base": "Effect",
    "id": "REGENERATION",
    "name": "%red%Regeneration",
    "description": [
      "%gray%Gives you regeneration 1!"
    ],
    "type": "minecraft:regeneration",
    "amplifier": 0,
    "hideParticles": true
  },
  {
    "base": "Experience",
    "id": "EXPERIENCE",
    "name": "%green%Experience",
    "description": [
      "%gray%Boosts your experience gain by 50%!"
    ],
    "bonus": "0.5x"
  },
  {
    "base": "Thorns",
    "id": "THORNS",
    "name": "%green%Thorns",
    "description": [
      "%gray%Reflects 12.5% of the damage you receive!"
    ],
    "reflect": "0.125x"
  },
  {
    "base": "Damage",
    "id": "DAMAGE_WITHER",
    "name": "%red%Wither Vanquisher",
    "description": [
      "%gray%Increases the amount of damage you deal",
      "%gray%to withers by 25% and wither skeletons",
      "%gray%by 50%!"
    ],
    "bonuses": {
      "WITHER": "0.25x",
      "WITHER_SKELETON": "0.5x"
    }
  },
  {
    "base": "KillEffect",
    "id": "KILL_STRENGTH",
    "name": "%gold%Strong Killer",
    "description": [
      "%gray%Gives you strength 2 for 5 seconds",
      "%gray%each time you kill a mob or player!"
    ],
    "type": "minecraft:strength",
    "duration": 100,
    "amplifier": 1,
    "hideParticles": true
  }
]
```