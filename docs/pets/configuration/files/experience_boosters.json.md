---
sidebar_position: 6
title: experience_boosters.json
---

# `experience_boosters.json: List<ExperienceBooster>`

| Name | Type | Description | Optional |
| --- | --- | --- | --- |
| id | `String` | The identifier | No |
| item | `ItemWrapper` | The item | No |
| recipe | `Recipe` | The recipe | Yes |
| boost | `Expression` | The number of levels to add to the earned ones (x) | No |

```json
[
  {
    "id": "WEAK_EXPERIENCE_BOOSTER",
    "item": {
      "material": "EXPERIENCE_BOTTLE",
      "name": "%green%Weak Experience Booster",
      "lore": [
        "%gray%Increases the amount of pet experience",
        "%gray%you receive by 50%."
      ]
    },
    "recipe": {
      "shape": [
        "gdg",
        "ded",
        "gdg"
      ],
      "ingredients": {
        "g": "GOLD_INGOT",
        "d": "DIAMOND",
        "e": "EMERALD"
      }
    },
    "boost": "0.5x"
  },
  {
    "id": "DECENT_EXPERIENCE_BOOSTER",
    "item": {
      "material": "EXPERIENCE_BOTTLE",
      "name": "%blue%Decent Experience Booster",
      "lore": [
        "%gray%Increases the amount of pet experience",
        "%gray%you receive by 100%."
      ]
    },
    "recipe": {
      "shape": [
        "gdg",
        "ded",
        "gdg"
      ],
      "ingredients": {
        "g": "GOLD_BLOCK",
        "d": "DIAMOND_BLOCK",
        "e": "EMERALD_BLOCK"
      }
    },
    "boost": "x"
  },
  {
    "id": "STRONG_EXPERIENCE_BOOSTER",
    "item": {
      "material": "EXPERIENCE_BOTTLE",
      "name": "%red%Strong Experience Booster",
      "lore": [
        "%gray%Increases the amount of pet experience",
        "%gray%you receive by 200%."
      ]
    },
    "recipe": {
      "shape": [
        "ded",
        "ene",
        "ded"
      ],
      "ingredients": {
        "d": "DIAMOND_BLOCK",
        "e": "EMERALD_BLOCK",
        "n": "NETHER_STAR"
      }
    },
    "boost": "2x"
  }
]
```
