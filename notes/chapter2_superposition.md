\# Superposition Study Notes



\## What Is Superposition?



Superposition means a qubit can be described as a combination of basis states before measurement.



A single qubit can be written as:



|ψ⟩ = a|0⟩ + b|1⟩



The values a and b are amplitudes.



\## Difference From a Classical Bit



A classical bit is either:



0 or 1



A qubit can be represented as a combination of:



|0⟩ and |1⟩



until it is measured.



\## Probability Rule



The amplitudes are not directly observed.



Instead:



|a|² = probability of measuring |0⟩



|b|² = probability of measuring |1⟩



The probabilities must add to 1:



|a|² + |b|² = 1



\## Hadamard Gate Example



The Hadamard gate creates a balanced superposition.



H|0⟩ = (|0⟩ + |1⟩) / √2



This means the qubit has about:



50% chance of measuring 0



50% chance of measuring 1



\## Why Superposition Matters



Superposition allows quantum computers to represent many possible states through amplitudes.



However, measurement only returns one classical result.



The power of quantum computing comes from using gates to shape amplitudes before measurement.



\## Connection to Our Qiskit Project



Our Bell-state circuit started by applying a Hadamard gate:



qc.h(0)



That placed the first qubit into superposition.



Then we applied CNOT:



qc.cx(0, 1)



That connected the second qubit to the first and created entanglement.

