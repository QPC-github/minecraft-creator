---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IEntityDieAfterEventSignal Class
description: Contents of the @minecraft/server.IEntityDieAfterEventSignal class.
---
# IEntityDieAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IEntityDieAfterEventSignal
- [*EntityDieAfterEventSignal*](EntityDieAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires when an entity dies.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: EntityDieAfterEvent) => void, options?: EntityEventOptions): (arg: EntityDieAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*EntityDieAfterEvent*](EntityDieAfterEvent.md)) => *void*
- **options**?: [*EntityEventOptions*](EntityEventOptions.md) = `null`

#### **Returns** (arg: [*EntityDieAfterEvent*](EntityDieAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: EntityDieAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*EntityDieAfterEvent*](EntityDieAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
