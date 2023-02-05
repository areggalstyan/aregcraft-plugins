---
sidebar_position: 7
title: candies.json
---

# `candies.json: List<Candy>`

| Name | Type | Description | Optional |
| --- | --- | --- | --- |
| id | `String` | The identifier | No |
| item | `ItemWrapper` | The item | No |
| recipe | `Recipe` | The recipe | Yes |
| experience | `double` | The number of levels to add | No |

```json
[
  {
    "id": "SMALL_CANDY",
    "item": {
      "material": "SUGAR",
      "name": "%green%Small Candy",
      "lore": [
        "%gray%Instantly adds two levels to your",
        "%gray%selected pet."
      ]
    },
    "recipe": {
      "shape": [
        "sgs",
        "gdg",
        "sgs"
      ],
      "ingredients": {
        "s": "SUGAR",
        "g": "GOLD_INGOT",
        "d": "DIAMOND"
      }
    },
    "experience": 2
  },
  {
    "id": "MEDIUM_CANDY",
    "item": {
      "material": "SUGAR",
      "name": "%blue%Medium Candy",
      "lore": [
        "%gray%Instantly adds four levels to your",
        "%gray%selected pet."
      ]
    },
    "recipe": {
      "shape": [
        "sgs",
        "gdg",
        "sgs"
      ],
      "ingredients": {
        "s": "SUGAR",
        "g": "GOLD_BLOCK",
        "d": "DIAMOND_BLOCK"
      }
    },
    "experience": 4
  },
  {
    "id": "BIG_CANDY",
    "item": {
      "material": "SUGAR",
      "name": "%red%Big Candy",
      "lore": [
        "%gray%Instantly adds eight levels to your",
        "%gray%selected pet."
      ]
    },
    "recipe": {
      "shape": [
        "sds",
        "dnd",
        "sds"
      ],
      "ingredients": {
        "s": "SUGAR",
        "d": "DIAMOND_BLOCK",
        "n": "NETHER_STAR"
      }
    },
    "experience": 8
  }
]
```
