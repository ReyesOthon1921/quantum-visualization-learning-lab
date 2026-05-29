\# Hadamard Gate Study Notes



\## What Is the Hadamard Gate?



The Hadamard gate is one of the most important gates in quantum computing.



It creates superposition from a basis state.



\## Action on |0>



H|0⟩ = (|0⟩ + |1⟩) / √2



This creates an equal chance of measuring:



\- 0

\- 1



\## Action on |1>



H|1⟩ = (|0⟩ - |1⟩) / √2



The negative sign matters because it affects interference.



\## Why It Matters



The Hadamard gate allows quantum algorithms to spread amplitude across possible states.



It is used in:



\- superposition demos

\- Bell-state circuits

\- Deutsch's algorithm

\- Grover's algorithm

\- quantum teleportation



\## Connection to Our Project



In our Bell-state notebook, we used:



qc.h(0)



This placed the first qubit into superposition before using CNOT to create entanglement.

