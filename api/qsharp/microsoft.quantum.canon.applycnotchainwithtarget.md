---
uid: Microsoft.Quantum.Canon.ApplyCNOTChainWithTarget
title: ApplyCNOTChainWithTarget operation
ms.date: 11/10/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ApplyCNOTChainWithTarget
qsharp.summary: Computes the parity of an array of qubits into a target qubit.
---

# ApplyCNOTChainWithTarget operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Computes the parity of an array of qubits into a target qubit.

```qsharp
operation ApplyCNOTChainWithTarget (qubits : Qubit[], targetQubit : Qubit) : Unit is Adj + Ctl
```


## Description

If the array is initially in the state

## Input

### qubits : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

Array of qubits on which the parity is computed.


### targetQubit : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Final qubit into which the parity of 'qubits' is XORed.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

The following are equivalent: