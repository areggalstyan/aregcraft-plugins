---
sidebar_position: 5
title: Experience Boosters
---

# `experience_boosters/<name>.json`

| Name | Type | Description | Optional |
| --- | --- | --- | --- |
| id | `String` | The identifier | No |
| item | `ItemWrapper` | The item | No |
| recipe | `Recipe` | The recipe | Yes |
| boost | `Expression` | The number of levels to add to the earned ones (x) | No |

```json
{
  "id": "DECENT_EXPERIENCE_BOOSTER",
  "item": {
    "material": "EXPERIENCE_BOTTLE",
    "name": "%blue%Decent Experience Booster",
    "lore": [
      "%gray%Increases the amount of pet experience",
      "%gray%you receive by 100%.",
      "%dark_gray%Right-click to use."
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
}
```
