# Week 3: Quantum Gates as Matrices

After understanding qubits as vectors, the next step is understanding how qubits change.

Quantum gates perform this change.

Mathematically, quantum gates are matrices.

## Gates as Linear Transformations

If:
• A qubit is a vector
• A gate is a matrix

Then applying a gate means:
Matrix × Vector → New Vector

This is standard linear algebra.

## Properties of Quantum Gates

Quantum gates must follow strict rules:

• They preserve vector length
• Total probability remains 1
• Operations are reversible

This is why quantum gates are unitary matrices.

## Common Gates (Conceptual)

Identity Gate:
• Leaves the state unchanged

Pauli-X Gate:
• Flips |0⟩ to |1⟩ and |1⟩ to |0⟩
• Similar to a classical NOT gate

Hadamard Gate:
• Creates superposition
• Rotates the vector to an equal combination of |0⟩ and |1⟩

## Rotation Intuition

Quantum computation is not about flipping bits.
It is about rotating vectors in a state space.

Different rotations lead to different probability outcomes when measured.

## Key Takeaway

Quantum algorithms are sequences of matrix operations applied to vectors.
The power comes from how these rotations interfere before measurement.

Understanding gates as matrices makes quantum computation feel logical and systematic.
