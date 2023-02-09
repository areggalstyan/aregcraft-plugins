---
sidebar_position: 4
title: Reforges
---

# `reforges/<name>.json`

| Name | Type | Description | Optional |
| --- | --- | --- | --- |
| id | `String` | The identifier | No |
| name | `String` | The name | No |
| attributes | `Map<Attribute, double>` | The attributes with their amounts | No |
| ability | `String` | The identifier of the ability | Yes |
| targets | `List<Target>` | The targets | Yes |

```json
{
  "id": "WITHERED",
  "name": "%light_purple%Withered",
  "attributes": {
    "GENERIC_MAX_HEALTH": 10,
    "GENERIC_ATTACK_DAMAGE": 10,
    "GENERIC_ATTACK_SPEED": 0.2,
    "GENERIC_ARMOR": 4,
    "GENERIC_ARMOR_TOUGHNESS": 2
  },
  "ability": "WITHER",
  "targets": ["SWORD", "AXE"]
}
```
