---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IItemStartUseOnAfterEventSignal Class
description: Contents of the @minecraft/server.IItemStartUseOnAfterEventSignal class.
---
# IItemStartUseOnAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IItemStartUseOnAfterEventSignal
- [*ItemStartUseOnAfterEventSignal*](ItemStartUseOnAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires when an item item is starting to be used on a block.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ItemStartUseOnAfterEvent) => void): (arg: ItemStartUseOnAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ItemStartUseOnAfterEvent*](ItemStartUseOnAfterEvent.md)) => *void*

#### **Returns** (arg: [*ItemStartUseOnAfterEvent*](ItemStartUseOnAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ItemStartUseOnAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ItemStartUseOnAfterEvent*](ItemStartUseOnAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
