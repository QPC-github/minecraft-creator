---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.ITripWireTripAfterEventSignal Class
description: Contents of the @minecraft/server.ITripWireTripAfterEventSignal class.
---
# ITripWireTripAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend ITripWireTripAfterEventSignal
- [*TripWireTripAfterEventSignal*](TripWireTripAfterEventSignal.md)

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: TripWireTripAfterEvent) => void): (arg: TripWireTripAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*TripWireTripAfterEvent*](TripWireTripAfterEvent.md)) => *void*

#### **Returns** (arg: [*TripWireTripAfterEvent*](TripWireTripAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: TripWireTripAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*TripWireTripAfterEvent*](TripWireTripAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
