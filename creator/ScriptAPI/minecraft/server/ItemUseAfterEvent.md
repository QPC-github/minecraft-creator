---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.ItemUseAfterEvent Class
description: Contents of the @minecraft/server.ItemUseAfterEvent class.
---
# ItemUseAfterEvent Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend ItemUseAfterEvent
- [*ItemUseBeforeEvent*](ItemUseBeforeEvent.md)

Contains information related to an item being used. This event fires when an item is successfully used by a player.

## Properties

### **itemStack**
`itemStack: ItemStack;`

The impacted item stack that is being used.

Type: [*ItemStack*](ItemStack.md)

### **source**
`read-only source: Entity;`

Returns the source entity that triggered this item event.

Type: [*Entity*](Entity.md)
