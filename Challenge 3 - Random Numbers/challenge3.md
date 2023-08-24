Configure the state of three qubits to produce this outcome distribution :

```
   0.4   │    0.375    0.375
         │    ███      ███    
   0.3   │    ███      ███
         │    ███      ███
   0.2   │    ███      ███
         │    ███      ███     0.125     0.125
   0.1   │    ███      ███     ███       ███
         │    ███      ███     ███       ███
   0.0   │    ███      ███     ███       ███
         ──────────────────────────────────────
            |001>     |011>    |101>    |111>
```

For this exercise, I admittedly had to look ahead a little bit. The hit here is to look at each qubit individually and the probability that it should be in a 1 or 0 state. For example, looking at qubit with index 2, 75% of the time it is a 0 and 25% of the time it is a 1. Similarly, looking at qubit 0, it is always 1. Qubit at index 1 is 50% either 1 or 0. What gates accomplish putting the qubits in these superposition states?