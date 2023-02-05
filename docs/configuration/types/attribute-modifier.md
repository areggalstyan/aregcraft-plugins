---
sidebar_position: 5
---

# `AttributeModifier`

| Name | Type | Description | Optional | Default |
| --- | --- | --- | --- | --- |
| uuid | `UUID` | The unique identifier  | Yes | Random |
| name | `String` | The name | No | N/A |
| amount | `double` | The amount  | No | N/A |
| operation | `AttributeModifier.Operation` | The operation | Yes | `ADD_NUMBER` |
| slot | `EquipmentSlot` | The equipment slot | Yes | All |

```json
{
  "uuid": "b74413ae-d8a7-4025-8dc7-60ca8b65f979",
  "name": "generic_max_health",
  "amount": 0.5,
  "operation": "MULTIPLY_SCALAR_1",
  "slot": "CHEST"
}
```
