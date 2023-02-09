---
sidebar_position: 2
---

# `armor.json`

| Name | Type | Description |
| --- | --- | --- |
| name | `String` | The names of all reforged armors, can have colors and placeholders |
| lore | `List<String>` | The lore attached to all reforged armors, can have colors and placeholders |

## Placeholders

| Name | Description | Example |
| --- | --- | --- |
| reforgeName | The name of the reforge | Withered |
| name | The name of the armor | Diamond Leggings |
| slot | The name of the slot | When on Body: |
| base_armor | The base armor the armor | 1.6 |
| base_armor_toughness | The base armor toughness of the armor | 7 |
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
    "%gray%%slot%",
    "%dark_green% %base_armor% (%generic_armor%) Armor",
    "%dark_green% %base_armor_toughness% (%generic_armor_toughness%) Armor Toughness",
    "%dark_green% %generic_attack_speed% Attack Speed",
    "%dark_green% %generic_attack_damage% Attack Damage",
    "%dark_green% %generic_max_health% Max Health",
    "%dark_green% %generic_knockback_resistance% Knockback Resistance",
    "%dark_green% %generic_movement_speed% Movement Speed",
    "%dark_green% %generic_attack_knockback% Attack Knockback"
  ]
}
```
