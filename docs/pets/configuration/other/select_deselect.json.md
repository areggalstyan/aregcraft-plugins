---
sidebar_position: 3
---

# `select_deselect.json`

| Name | Type | Description |
| --- | --- | --- |
| select | `Feedback` | The select feedback |
| deselect | `Feedback` | The deselect feedback |

```json
{
  "select": {
    "sound": {
      "type": "ITEM_ARMOR_EQUIP_LEATHER",
      "volume": 1,
      "pitch": 0
    },
    "message": "%name% %green%selected!"
  },
  "deselect": {
    "sound": {
      "type": "ITEM_ARMOR_EQUIP_LEATHER",
      "volume": 1,
      "pitch": 1
    },
    "message": "%name% %red%deselected!"
  }
}
```
