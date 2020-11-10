---
uid: Microsoft.Quantum.Canon.Delay
title: Delay operation
ms.date: 11/10/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: Delay
qsharp.summary: Applies a given operation with a delay.
---

# Delay operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Applies a given operation with a delay.

```qsharp
operation Delay<'T, 'U> (op : ('T => 'U), arg : 'T, aux : Unit) : 'U
```


## Description

Given an operation and an input to that operation, applies

## Input

### op : 'T => 'U 

An operation to be applied.


### arg : 'T

The input to which the operation is applied.


### aux : [Unit](xref:microsoft.quantum.lang-ref.unit)

Argument used to delay the application of operation by using



## Output : 'U



## Type Parameters

### 'T

The input type of the operation to be delayed.
### 'U

The return type of the operation to be delayed.

## See Also

- [Microsoft.Quantum.Canon.DelayC](xref:Microsoft.Quantum.Canon.DelayC)
- [Microsoft.Quantum.Canon.DelayA](xref:Microsoft.Quantum.Canon.DelayA)
- [Microsoft.Quantum.Canon.DelayCA](xref:Microsoft.Quantum.Canon.DelayCA)
- [Microsoft.Quantum.Canon.Delayed](xref:Microsoft.Quantum.Canon.Delayed)