---
sidebar_position: 5
title: pets.json
---

# `pets.json: List<Pet>`

| Name | Type | Description | Optional |
| --- | --- | --- | --- |
| id | `String` | The identifier | No |
| name | `String` | The name, can have colors and placeholders | No |
| item | `ItemWrapper` | The item | No |
| recipe | `Recipe` | The crafting recipe | Yes |
| level | `Expression` | How many levels the pet receives based on how many experience levels (x) its owner received | No |
| attributes | `Map<Attribute, Expression>` | The attributes with their amounts based on the pet level (x) | No |
| perk | `String` | The identifier of the perk | Yes |
| maxCandies | `int` | The maximum number of candies | No |

## Placeholders

| Name | Description | Example |
| --- | --- | --- |
| level | The level | 5 |
| candies | The number of candies | 2 |
| maxCandies | The maximum number of candies | 4 |
| player | The owner | Aregcraft |
| perk | The name of the perk | Regeneration |
| perkDescription | The description of the perk | Gives you regeneration 1! |
| experienceBooster | The experience booster | Decent Experience Booster |
| generic_max_health | The max health | 10 |
| generic_knockback_resistance | The knockback resistance | 1 |
| generic_movement_speed | The movement speed | 0.1 |
| generic_armor | The armor | 5 |
| generic_armor_toughness | The armor toughness | 3 |
| generic_attack_knockback | The attack knockback | 1 |

```json
[
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
        "%perk% Perk",
        "%perkDescription%",
        "",
        "%gray%When selected:",
        "%dark_green% %experienceBooster%",
        "%dark_green% %generic_max_health% Max Health",
        "%dark_green% %generic_attack_damage% Attack Damage",
        "%dark_green% %generic_armor% Armor"
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
      "GENERIC_MAX_HEALTH": "x",
      "GENERIC_ATTACK_DAMAGE": "x / 10",
      "GENERIC_ARMOR": "x / 10"
    },
    "perk": "EXPERIENCE",
    "maxCandies": 3
  },
  {
    "id": "ELEPHANT",
    "name": "%gray%[%level%] %player%'s Elephant",
    "head": "7071a76f669db5ed6d32b48bb2dba55d5317d7f45225cb3267ec435cfa514",
    "item": {
      "material": "PLAYER_HEAD",
      "name": "%gray%[%level%] Elephant",
      "lore": [
        "%dark_gray%Trumpet...",
        "",
        "%gray%%candies%/%maxCandies% candies used!",
        "",
        "%perk% Perk",
        "%perkDescription%",
        "",
        "%gray%When selected:",
        "%dark_green% %experienceBooster%",
        "%dark_green% %generic_max_health% Max Health",
        "%dark_green% %generic_armor% Armor",
        "%dark_green% %generic_attack_speed% Attack Speed"
      ]
    },
    "recipe": {
      "shape": [
        "odo",
        "ded",
        "odo"
      ],
      "ingredients": {
        "o": "OBSIDIAN",
        "d": "DIAMOND_BLOCK",
        "e": "EGG"
      }
    },
    "level": "x / 2",
    "attributes": {
      "GENERIC_MAX_HEALTH": "x",
      "GENERIC_ATTACK_SPEED": "x / 100",
      "GENERIC_ARMOR": "x / 5"
    },
    "perk": "REGENERATION",
    "maxCandies": 4
  },
  {
    "id": "CHEETAH",
    "name": "%yellow%[%level%] %player%'s Cheetah",
    "head": "1553f8856dd46de7e05d46f5fc2fb58eafba6829b11b160a1545622e89caaa33",
    "item": {
      "material": "PLAYER_HEAD",
      "name": "%yellow%[%level%] Cheetah",
      "lore": [
        "%dark_gray%Chirrs...",
        "",
        "%gray%%candies%/%maxCandies% candies used!",
        "",
        "%perk% Perk",
        "%perkDescription%",
        "",
        "%gray%When selected:",
        "%dark_green% %experienceBooster%",
        "%dark_green% %generic_movement_speed% Movement Speed",
        "%dark_green% %generic_attack_damage% Attack Damage",
        "%dark_green% %generic_attack_speed% Attack Speed"
      ]
    },
    "recipe": {
      "shape": [
        "igi",
        "geg",
        "igi"
      ],
      "ingredients": {
        "i": "IRON_BLOCK",
        "g": "GOLD_BLOCK",
        "e": "EGG"
      }
    },
    "level": "x / 2",
    "attributes": {
      "GENERIC_MOVEMENT_SPEED": "x / 1000",
      "GENERIC_ATTACK_SPEED": "x / 100",
      "GENERIC_ATTACK_DAMAGE": "x / 5"
    },
    "perk": "THORNS",
    "maxCandies": 4
  },
  {
    "id": "WITHER",
    "name": "%red%[%level%] %player%'s Wither",
    "head": "cdf74e323ed41436965f5c57ddf2815d5332fe999e68fbb9d6cf5c8bd4139f",
    "item": {
      "material": "PLAYER_HEAD",
      "name": "%red%[%level%] Wither",
      "lore": [
        "%dark_gray%Hush...",
        "",
        "%gray%%candies%/%maxCandies% candies used!",
        "",
        "%perk% Perk",
        "%perkDescription%",
        "",
        "%gray%When selected:",
        "%dark_green% %experienceBooster%",
        "%dark_green% %generic_max_health% Max Health",
        "%dark_green% %generic_attack_damage% Attack Damage",
        "%dark_green% %generic_armor% Armor",
        "%dark_green% %generic_armor_toughness% Armor Toughness"
      ]
    },
    "recipe": {
      "shape": [
        "dwd",
        "wnw",
        "dwd"
      ],
      "ingredients": {
        "d": "DIAMOND_BLOCK",
        "w": "WITHER_SKELETON_SKULL",
        "n": "NETHER_STAR"
      }
    },
    "level": "x / 3",
    "attributes": {
      "GENERIC_MAX_HEALTH": "2x",
      "GENERIC_ATTACK_DAMAGE": "x / 3",
      "GENERIC_ARMOR": "x / 3",
      "GENERIC_ARMOR_TOUGHNESS": "x / 5"
    },
    "perk": "DAMAGE_WITHER",
    "maxCandies": 2
  },
  {
    "id": "TIGER",
    "name": "%gold%[%level%] %player%'s Tiger",
    "head": "3bddf5bae3af592858df9a150109e88c1caed8ba51e793c25aa03ca1b25db",
    "item": {
      "material": "PLAYER_HEAD",
      "name": "%gold%[%level%] Tiger",
      "lore": [
        "%dark_gray%Growl...",
        "",
        "%gray%%candies%/%maxCandies% candies used!",
        "",
        "%perk% Perk",
        "%perkDescription%",
        "",
        "%gray%When selected:",
        "%dark_green% %experienceBooster%",
        "%dark_green% %generic_max_health% Max Health",
        "%dark_green% %generic_attack_damage% Attack Damage",
        "%dark_green% %generic_armor% Armor"
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
        "e": "EGG"
      }
    },
    "level": "x / 2",
    "attributes": {
      "GENERIC_MAX_HEALTH": "2x / 5",
      "GENERIC_ATTACK_DAMAGE": "x / 5",
      "GENERIC_ARMOR": "x / 5"
    },
    "perk": "KILL_STRENGTH",
    "maxCandies": 3
  }
]
```
