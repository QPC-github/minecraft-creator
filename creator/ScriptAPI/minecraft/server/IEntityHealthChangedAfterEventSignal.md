---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IEntityHealthChangedAfterEventSignal Class
description: Contents of the @minecraft/server.IEntityHealthChangedAfterEventSignal class.
---
# IEntityHealthChangedAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IEntityHealthChangedAfterEventSignal
- [*EntityHealthChangedAfterEventSignal*](EntityHealthChangedAfterEventSignal.md)

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: EntityHealthChangedAfterEvent) => void, options?: EntityEventOptions): (arg: EntityHealthChangedAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*EntityHealthChangedAfterEvent*](EntityHealthChangedAfterEvent.md)) => *void*
- **options**?: [*EntityEventOptions*](EntityEventOptions.md) = `null`

#### **Returns** (arg: [*EntityHealthChangedAfterEvent*](EntityHealthChangedAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: EntityHealthChangedAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*EntityHealthChangedAfterEvent*](EntityHealthChangedAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
