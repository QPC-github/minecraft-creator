---
author: mammerla
ms.author: v-jimseaman
title: Entity Documentation - minecraft:movement.skip
ms.prod: gaming
---

# Entity Documentation - minecraft:movement.skip

`minecraft:movement.skip` compels the entity to hop as it moves.

## Parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
| max_turn| 30.0| Decimal| The maximum number in degrees the entity can turn per tick. |

## Example

```json
"minecraft:movement.skip":{
    "max_turn": 30.0
}
```

## Vanilla entities examples

### rabbit

```json
"minecraft:movement.skip": {
      }
```

## Vanilla entities using `minecraft:movement.skip`

- [rabbit](../../../../Source/VanillaBehaviorPack_Snippets/entities/rabbit.md)