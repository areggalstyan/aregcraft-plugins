---
sidebar_position: 3
title: Pets
---

# `pets/<name>.json`

| Name | Type | Description | Optional |
| --- | --- | --- | --- |
| id | `String` | The identifier | No |
| name | `String` | The name, can have colors and placeholders | No |
| item | `ItemWrapper` | The item | No |
| recipe | `Recipe` | The crafting recipe | Yes |
| level | `Expression` | How many levels the pet receives based on how many experience levels (x) its owner received | No |
| attributes | `Map<String, Map<Attribute, Expression>>` | The rarities with their attributes with their amounts based on the pet level (x) | No |
| perks | `Map<String, String>` | The rarities with their perks | Yes |
| maxCandies | `int` | The maximum number of candies | No |

## Placeholders

| Name | Description | Example |
| --- | --- | --- |
| level | The level | 5 |
| candies | The number of candies | 2 |
| maxCandies | The maximum number of candies | 4 |
| player | The owner | Aregcraft |
| perks | The perks with their names and descriptions | Regeneration<br/>Gives you regeneration 1!|
| experienceBooster | The experience booster | Decent Experience Booster |
| generic_max_health | The max health | 10 |
| generic_knockback_resistance | The knockback resistance | 1 |
| generic_movement_speed | The movement speed | 0.1 |
| generic_armor | The armor | 5 |
| generic_armor_toughness | The armor toughness | 3 |
| generic_attack_knockback | The attack knockback | 1 |

```json
{
  "id": "LION",
  "name": "%green%[%level%] %player%'s Lion",
  "head": "6b3a8ce66dc3927bb5482b29e936b39d24589f91e997bb3dfd567396e871120",
  "item": {
    "material": "PLAYER_HEAD",
    "name": "%green%[%level%] Lion",
    "lore": [
      "%dark_gray%Roar...",
      "",
      "%gray%%candies%/%maxCandies% candies used!",
      "",
      "%perks%",
      "",
      "%gray%When selected:",
      "%dark_green% %experienceBooster%",
      "%dark_green% %generic_max_health% Max Health",
      "%dark_green% %generic_attack_damage% Attack Damage",
      "%dark_green% %generic_armor% Armor",
      "",
      "%rarity%"
    ]
  },
  "recipe": {
    "shape": [
      "ggg",
      "geg",
      "ggg"
    ],
    "ingredients": {
      "g": "GOLD_BLOCK",
      "e": "EGG"
    }
  },
  "level": "x",
  "attributes": {
    "COMMON": {
      "GENERIC_MAX_HEALTH": "x",
      "GENERIC_ATTACK_DAMAGE": "x / 10",
      "GENERIC_ARMOR": "x / 10"
    },
    "RARE": {
      "GENERIC_MAX_HEALTH": "1.2x",
      "GENERIC_ATTACK_DAMAGE": "x / 8",
      "GENERIC_ARMOR": "x / 8"
    },
    "LEGENDARY": {
      "GENERIC_MAX_HEALTH": "1.4x",
      "GENERIC_ATTACK_DAMAGE": "x / 6",
      "GENERIC_ARMOR": "x / 6"
    }
  },
  "perks": {
    "COMMON": ["EXPERIENCE_1"],
    "RARE": ["EXPERIENCE_2"],
    "LEGENDARY": ["EXPERIENCE_3"]
  },
  "maxCandies": 3
}
```
