\# Bell State and CNOT Study Notes



\## What Is a CNOT Gate?



CNOT stands for Controlled-NOT.



It operates on two qubits:



\- Control qubit

\- Target qubit



The target qubit flips only when the control qubit is 1.



\## Truth Table



00 → 00



01 → 01



10 → 11



11 → 10



\## Why CNOT Matters



The CNOT gate is one of the primary gates used to create entanglement.



Entanglement allows multiple qubits to become correlated.



\## Bell State Creation



Begin with:



|00⟩



Apply Hadamard to qubit 0:



H|0⟩ = (|0⟩ + |1⟩)/√2



State becomes:



(|00⟩ + |10⟩)/√2



Apply CNOT:



(|00⟩ + |11⟩)/√2



This is a Bell State.



\## Bell State Properties



The two qubits become entangled.



Measuring one qubit immediately determines the outcome of the other.



Possible results:



00



11



The results:



01



10



never appear.



\## Connection to Our Qiskit Project



We built our first Bell State using:



qc.h(0)



qc.cx(0,1)



qc.measure(\[0,1],\[0,1])



The histogram showed mostly:



00



11



This verified successful entanglement.

