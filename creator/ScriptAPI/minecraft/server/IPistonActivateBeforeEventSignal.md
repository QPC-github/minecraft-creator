---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IPistonActivateBeforeEventSignal Class
description: Contents of the @minecraft/server.IPistonActivateBeforeEventSignal class.
---
# IPistonActivateBeforeEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IPistonActivateBeforeEventSignal
- [*PistonActivateBeforeEventSignal*](PistonActivateBeforeEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires before a piston is activated.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: PistonActivateBeforeEvent) => void): (arg: PistonActivateBeforeEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*PistonActivateBeforeEvent*](PistonActivateBeforeEvent.md)) => *void*

#### **Returns** (arg: [*PistonActivateBeforeEvent*](PistonActivateBeforeEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: PistonActivateBeforeEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*PistonActivateBeforeEvent*](PistonActivateBeforeEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
