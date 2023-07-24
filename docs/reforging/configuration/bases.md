---
sidebar_position: 2
---

# Bases

## Dash

| Name | Type | Description |
| --- | --- | --- |
| velocity | `Vector` | The velocity |

## Pawn

| Name | Type | Description |
| --- | --- | --- |
| duration | `long` | How long the entities should exist, unlimited by default |
| entity | `EntityBuilder` | The entity |
| number | `int` | The number of entities |

## Thorns

| Name | Type | Description |
| --- | --- | --- |
| duration | `long` | The duration in ticks (1 second = 20 ticks) |
| multiplier | `double` | How much damage to reflect on the attacker |

## Rage

| Name | Type | Description |
| --- | --- | --- |
| duration | `int` | The duration in ticks (1 second = 20 ticks) |
| amplifier | `int` | The effect amplifier |
| multiplier | `double` | How much damage to reflect on the player |

## Effect

| Name | Type | Description |
| --- | --- | --- |
| type | `PotionEffectType` | The effect type |
| duration | `int` | The effect duration in ticks (1 second = 20 ticks) |
| amplifier | `int` | The effect amplifier |
| hideParticles | `boolean` | Whether to hide the effect particles |

## Throw

| Name | Type | Description |
| --- | --- | --- |
| duration | `long` | How long should the weapon fly in ticks (1 second = 20 ticks) |
| velocity | `Vector` | The velocity |
| damageMultiplier | `double` | How much of the actual weapon damage to deal |

## Fly

| Name | Type | Description |
| --- | --- | --- |
| duration | `int` | The duration in ticks (1 second = 20 ticks) |
| velocity | `Vector` | The velocity |

## Reveal

| Name | Type | Description |
| --- | --- | --- |
| range | `double` | The range |

## Fire

| Name | Type | Description |
| --- | --- | --- |
| function | `Function3` | The function describing the shape |
| particle | `Particle` | The particle used to create the shape |
| fireDuration | `int` | How long the entities should burn in ticks (1 second = 20 ticks) |

## Freeze

| Name | Type | Description |
| --- | --- | --- |
| projectileType | `EntityType` | The projectile type |
| projectileVelocity | `Vector` | The projectile velocity |
| duration | `int` | How long to freeze hit entity in ticks (1 second = 20 ticks) |

## Evoker

| Name | Type | Description |
| --- | --- | --- |
| number | `int` | The number of fangs |

## Cocoon

| Name | Type | Description |
| --- | --- | --- |
| block | `Material` | The block |

## Spectate

| Name | Type | Description |
| --- | --- | --- |
| duration | `long` | The duration in ticks (1 second = 20 ticks) |

## Explosion

| Name | Type | Description |
| --- | --- | --- |
| power | `double` | The explosion power |

## Projectile

| Name | Type | Description |
| --- | --- | --- |
| type | `EntityType` | The projectile type |
| velocity | `Vector` | The projectile velocity |

## Storm

| Name | Type | Description |
| --- | --- | --- |
| function | `Function2` | The function describing the shape |

## SeismicWave

| Name | Type | Description |
| --- | --- | --- |
| function | `Function2` | The function describing the shape |
| particle | `Particle` | The particle used to create the shape |
| knockback | `Vector` | How much to knock back the entities within range |
| height | `double` | How high to knock back the entities within range |
| damage | `double` | How much to damage the entities within range |
| range | `double` | The range |

## Shield

| Name | Type | Description |
| --- | --- | --- |
| duration | `long` | The duration in ticks (1 second = 20 ticks) |
| function | `Function3` | The function describing the shape |
| particle | `Particle` | The particle used to create the shape |
| disableAttack | `boolean` | Whether the player should not be able to attack other entities |

## Teleport

| Name | Type | Description |
| --- | --- | --- |
| distance | `int` | The maximum distance |

## Potion

| Name | Type | Description |
| --- | --- | --- |
| type | `PotionEffectType` | The effect type |
| duration | `int` | The effect duration in ticks (1 second = 20 ticks) |
| amplifier | `int` | The effect amplifier |
| hideParticles | `boolean` | Whether to hide the effect particles |
| velocity | `Vector` | The potion velocity |

## Command

| Name | Type | Description |
| --- | --- | --- |
| command | `String` | The command |
