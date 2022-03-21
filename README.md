# Helmholtz-coil-config_3pair
## 3rd year summer research intern at "Ion Trap Quantum Computing Group", Univ of Oxford (Jun 2019)
### Objective: Implement optimized coil arrangements to achieve uniform at the centre of cryogenic ion trap chamber (in this case, centre coordinate (x, y) = (85, 50)[mm])

For those of you who are unaware of what "Helmholtz configuration" is, check this link: https://en.wikipedia.org/wiki/Helmholtz_coil

![image](https://user-images.githubusercontent.com/82307352/158952302-1df0de7a-6be6-49aa-be06-88fb2bb85f23.png)


In ion trap fields, magnetic B field plays a crucial role, especially with **zeeman qubits**, since it defines the quantization axis. Quantization axis then defines the energy states of the trapped ion, and we are using those quantized energy states as a ground of quantum computations. In this sense, strong, yet uniform magnetic field is prerequisite for achieving stabilized qubit states, which is directly related with its **coherence time** (coherence time naively represents the time scale of the lifetime of quantum information stored in the qubit). This project used Ca40+ ion as a qubit, one of the most prospective zeeman qubits.
If you want to do further reading about trapped calcium as a qubit, I recommend this paper: https://www.quantumoptics.at/images/publications/papers/qip04_schmidtkaler.pdf

As I was a total novice with programming, I brute-forcely implemented achieving arragement of 3 Helmholtz-configuration pairs (total 6 coils) 

Below is the result graph of my code:

![image](https://user-images.githubusercontent.com/82307352/158949061-cff88487-cb85-4e96-a518-842a22f66e38.png)

*Note: Sign of current (+ or -) denotes the direction of the current flow (RHS or LHS)*

*Note: Above image represents the simulated cross-section of coil configurations in ion-trap vacuum chamber*
