---
sidebar_position: 2
---

# Bases

## KillEffect

| Name | Type | Description |
| --- | --- | --- |
| type | `PotionEffectType` | The effect type |
| duration | `int` | The effect duration in ticks (1 second = 20 ticks) |
| amplifier | `int` | The effect amplifier |
| hideParticles | `boolean` | Whether to hide the effect particles |
| onlyPlayers | `boolean` | Whether to add the effect only when killing players |

## Effect

| Name | Type | Description |
| --- | --- | --- |
| type | `PotionEffectType` | The effect type |
| amplifier | `int` | The effect amplifier |
| hideParticles | `boolean` | Whether to hide the effect particles |

## Thorns

| Name | Type | Description |
| --- | --- | --- |
| reflect | `Expression` | How much damage to reflect on the attacker based on the received damage (x) |

## Damage

| Name | Type | Description |
| --- | --- | --- |
| bonuses | `Expression>` | The damage bonuses based on the dealt damage (x) with entities |

## Experience

| Name | Type | Description |
| --- | --- | --- |
| bonus | `Expression` | The amount of experience to add to the earned ones (x) |

## KillCommand

| Name | Type | Description |
| --- | --- | --- |
| type | `EntityType` | The entity type |
| command | `String` | The command |
