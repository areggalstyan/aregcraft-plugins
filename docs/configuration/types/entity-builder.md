---
sidebar_position: 7
---

# `EntityBuilder`

| Name | Type | Description | Optional | Default |
| --- | --- | --- | --- | --- |
| attributeModifiers | `Multimap<Attribute, AttributeModifiers>` | The attribute modifiers | Yes | None |
| persistentData | `Map<String, Object>` | The persistent data | Yes | None |
| type | `EntityType` | The type  | No | N/A |
| name | `String` | The name, can have colors | Yes | `""` |
| health | `double` | The health  | Yes | Maximum |
| nameVisible | `boolean` | Whether the name should be visible | Yes | `false` |
| gravity | `boolean` | Whether the entity should be affected by gravity | Yes | `true` |
| ai | `boolean` | Whether the entity should have AI | Yes | `true` |
| invisible | `boolean` | Whether the entity should be invisible | Yes |`false` |
| glowing | `boolean` | Whether the entity should glow | Yes | `false` |
| canPickupItems | `boolean` | Whether the entity should be able to pick up items | Yes | `false` |
| visualFire | `boolean` | Whether the entity should look as if it is on fire | Yes | `false` |
| adult | `boolean` | Whether the entity should be an adult | Yes | `false` |
| helmet | `ItemWrapper` | The helmet | Yes | None |
| chestplate | `ItemWrapper` | The chestplate | Yes | None |
| leggings | `ItemWrapper` | The leggings | Yes | None |
| boots | `ItemWrapper` | The boots | Yes | None |
| itemInMainHand | `ItemWrapper` | The item in the main hand | Yes | None |
| itemInOffHand | `ItemWrapper` | The item in the offhand | Yes | None |

```json
{
  "type": "ZOMBIE",
  "name": "%blue%Frozen Baby Zombie",
  "nameVisible": true,
  "gravity": false,
  "ai": false,
  "glowing": true,
  "adult": false,
  "helmet": {
    "material": "LEATHER_HELMET"
  }
}
```
