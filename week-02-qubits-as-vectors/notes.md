# Week 2: Qubits as Vectors

This week builds directly on linear algebra and introduces qubits as mathematical objects.

A qubit is not defined by physics first.
It is defined as a vector in a two-dimensional vector space.

## Basis States

The simplest qubit states are called basis states.

|0⟩ is represented as:
[1, 0]

|1⟩ is represented as:
[0, 1]

These vectors form an orthonormal basis.

## General Qubit State

Any qubit can be written as a linear combination of the basis states:

|ψ⟩ = a|0⟩ + b|1⟩

Where:
• a and b are probability amplitudes
• a² + b² = 1 (normalization rule)

This condition ensures total probability equals 1.

## Superposition (Mathematical View)

Superposition does not mean “both 0 and 1 at the same time”.

It means:
The qubit vector points in a direction that is not aligned with either basis vector.

Measurement projects the vector onto one of the basis states.

## Measurement as Projection

When a qubit is measured:
• The vector collapses onto |0⟩ or |1⟩
• Probabilities depend on the squared amplitudes

Thinking in terms of projection makes measurement intuitive.

## Key Takeaway

A qubit is a vector.
Superposition is vector addition.
Measurement is projection onto basis vectors.

Once this is clear, quantum behavior feels structured, not mysterious.
