---
uid: Microsoft.Quantum.Arithmetic.IncrementByModularInteger
title: IncrementByModularInteger operation
ms.date: 11/10/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Arithmetic
qsharp.name: IncrementByModularInteger
qsharp.summary: Performs a modular increment of a qubit register by an integer constant.
---

# IncrementByModularInteger operation

Namespace: [Microsoft.Quantum.Arithmetic](xref:Microsoft.Quantum.Arithmetic)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Performs a modular increment of a qubit register by an integer constant.

```qsharp
operation IncrementByModularInteger (increment : Int, modulus : Int, target : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit is Adj + Ctl
```


## Description

Let us denote `increment` by $a$, `modulus` by $N$ and integer encoded in `target` by $y$.

## Input

### increment : [Int](xref:microsoft.quantum.lang-ref.int)

Integer increment $a$ to be added to $y$.


### modulus : [Int](xref:microsoft.quantum.lang-ref.int)

Integer $N$ that mods $y + a$.


### target : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

Integer $y$ in `LittleEndian` format that `increment` $a$ is added to.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

Assumes that the initial value of target is less than $N$

## See Also

- [Microsoft.Quantum.Arithmetic.IncrementPhaseByModularInteger](xref:Microsoft.Quantum.Arithmetic.IncrementPhaseByModularInteger)