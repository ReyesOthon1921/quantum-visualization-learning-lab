\# Bell State Notes



A Bell State is a special quantum state with two qubits.



It uses:



\- Hadamard Gate

\- CNOT Gate

\- Measurement



\## How It Starts



The circuit starts with two qubits:



|00>



\## Step 1: Hadamard Gate



The Hadamard gate puts the first qubit into superposition.



In our project, this was:



qc.h(0)



\## Step 2: CNOT Gate



The CNOT gate connects the two qubits together.



In our project, this was:



qc.cx(0, 1)



\## What Happens



After Hadamard and CNOT, the qubits become entangled.



That means the two qubits are connected in their measurement results.



\## Measurement



When we measured the Bell State, we mostly saw:



00



and



11



\## What I Learned



Today I learned that a Bell State uses superposition and entanglement.



I also learned that quantum circuits can be tested with Qiskit and saved with GitHub.

