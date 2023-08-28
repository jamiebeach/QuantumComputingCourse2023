- Build a binary two-bit adder using quantum logic gates
- Hint : 
    - A classic two-bit adder uses a combination of a XOR and AND gate.
    - Both bit A and bit B are input into both XOR and AND gates.
    - Output of XOR gate is the Sum and output of AND gate is the carry-out bit
    - Works as follows :

    |**A**|**B**|**Sum**|**Carry-Out**|
    |---|---|---|---|
    |0|0|0|0|
    |0|1|1|0|
    |1|0|1|0|
    |1|1|0|1|
    - Our Quantum circuit would use four logic qubits
    - Qubits 0 and 1 would be inputs A and B
    - Use poli-x gates to set bits 0 and 1 as needed.
    - The sum and carry-out bits would land on qubits 2 and 3, accordingly.
    - The quantum circuit will take the qubits 0 and 1 and perform operations on them to manipulate bits 2 and 3.
