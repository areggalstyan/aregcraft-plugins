---
sidebar_position: 6
title: Candies
---

# `candies/<name>.json`

| Name | Type | Description | Optional |
| --- | --- | --- | --- |
| id | `String` | The identifier | No |
| item | `ItemWrapper` | The item | No |
| recipe | `Recipe` | The recipe | Yes |
| experience | `double` | The number of levels to add | No |

```json
{
  "id": "MEDIUM_CANDY",
  "item": {
    "material": "SUGAR",
    "name": "%blue%Medium Candy",
    "lore": [
      "%gray%Instantly adds four levels to your",
      "%gray%selected pet.",
      "%dark_gray%Right-click to use."
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
}
```
