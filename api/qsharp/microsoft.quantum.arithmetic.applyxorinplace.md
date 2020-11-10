---
uid: Microsoft.Quantum.Arithmetic.ApplyXorInPlace
title: ApplyXorInPlace operation
ms.date: 11/10/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Arithmetic
qsharp.name: ApplyXorInPlace
qsharp.summary: >-
  Applies a bitwise-XOR operation between a classical integer and an
  integer represented by a register of qubits.
---

# ApplyXorInPlace operation

Namespace: [Microsoft.Quantum.Arithmetic](xref:Microsoft.Quantum.Arithmetic)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Applies a bitwise-XOR operation between a classical integer and an

```qsharp
operation ApplyXorInPlace (value : Int, target : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit is Adj + Ctl
```


## Description

Applies `X` operations to qubits in a little-endian register based on

## Input

### value : [Int](xref:microsoft.quantum.lang-ref.int)

An integer which is assumed to be non-negative.


### target : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

A quantum register which is used to store `value` in little-endian encoding.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)
