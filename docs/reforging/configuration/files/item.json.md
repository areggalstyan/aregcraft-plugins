---
sidebar_position: 1
---

# `item.json`

| Name | Type | Description |
| --- | --- | --- |
| name | `String` | The names of all reforged weapons, can have colors and placeholders |
| lore | `List<String>` | The lore attached to all reforged weapons, can have colors and placeholders |

## Placeholders

| Name | Description | Example |
| --- | --- | --- |
| reforgeName | The name of the reforge | Withered |
| name | The name of the weapon | Diamond Sword |
| ability | The name of the ability | Throw |
| abilityDescription | The description of the ability | Shoots wither skulls! |
| priceHealth | The amount of health deducted from the player upon activation of the ability | 4 |
| priceFood | The amount of hunger deducted from the player upon activation of the ability | 8 |
| cooldown | The cooldown of the ability in seconds | 3 |
| base_attack_speed | The base attack speed of the weapon | 1.6 |
| base_attack_damage | The base attack damage of the weapon | 7 |
| generic_max_health | The max health provided by the reforge | 10 |
| generic_knockback_resistance | The knockback resistance provided by the reforge | 1 |
| generic_movement_speed | The movement speed provided by the reforge | 0.1 |
| generic_armor | The armor provided by the reforge | 5 |
| generic_armor_toughness | The armor toughness provided by the reforge | 3 |
| generic_attack_knockback | The attack knockback provided by the reforge | 1 |

```json
{
  "name": "%reforgeName% %name%",
  "lore": [
    "",
    "%ability% Ability %yellow%%bold%RIGHT CLICK",
    "%abilityDescription%",
    "%dark_aqua% -%priceHealth% Health",
    "%dark_aqua% -%priceFood% Food",
    "%dark_aqua% %cooldown%s Cooldown",
    "",
    "%gray%When in Main Hand:",
    "%dark_green% %base_attack_speed% (%generic_attack_speed%) Attack Speed",
    "%dark_green% %base_attack_damage% (%generic_attack_damage%) Attack Damage",
    "%dark_green% %generic_max_health% Max Health",
    "%dark_green% %generic_knockback_resistance% Knockback Resistance",
    "%dark_green% %generic_movement_speed% Movement Speed",
    "%dark_green% %generic_armor% Armor",
    "%dark_green% %generic_armor_toughness% Armor Toughness",
    "%dark_green% %generic_attack_knockback% Attack Knockback"
  ]
}
```
