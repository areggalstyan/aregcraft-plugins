---
sidebar_position: 5
---

# `reforging_anvil.json`

| Name | Type | Description |
| --- | --- | --- |
| item | `ItemWrapper` | The item |
| recipe | `Recipe` | The crafting recipe |
| sound | `PlayableSound` | The sound played during reforging |
| price | `int` | The number of ingredients consumed during reforging |

```json
{
  "item": {
    "material": "ANVIL",
    "name": "%green%Reforging Anvil",
    "lore": [
      "%gray%Place this anvil anywhere in the world",
      "%gray%to start reforging items!",
      "",
      "%dark_gray%Use /reforginginfo or /ri for details!"
    ]
  },
  "recipe": {
    "shape": [
      "ooo",
      "dad",
      "iii"
    ],
    "ingredients": {
      "o": "OBSIDIAN",
      "d": "DIAMOND",
      "a": "ANVIL",
      "i": "IRON_BLOCK"
    }
  },
  "sound": {
    "type": "BLOCK_ANVIL_USE",
    "volume": 1,
    "pitch": 0
  },
  "price": 2
}
```
