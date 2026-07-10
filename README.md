# surface-code
- Ongoing review and follow-up of my previous undergraduate group research project; "Modeling Three-dimensional Surface Codes on Cubic Lattices" found in https://github.com/MoonSumin123/Surface_Code
- This project is to practice "Surface codes: Towards practical large-scale quantum computation."

## 1. Error models for surface codes

### 1.1. Class-Simple

During the surface code cycles, errors arise from multiple sources: single-qubit gates, measurements, initializations, Hadamard gates, and CNOT gates. To simplify the model, we abstract the noises by assuming that all accumulated errors manifest on the data qubits immediately before the measurement cycle. Specifically, bit-flip ($X$) and phase-flip ($Z$) errors are probabilistically applied to the data qubits.

![class-simple_figure](./)

### 1.2. Class-0

TBA: errors per cycle considered

## References
- Fowler, A. G., Mariantoni, M., Martinis, J. M., & Cleland, A. N. (2012). Surface codes: Towards practical large-scale quantum computation. _Physical Review A,_ 86(3). https://doi.org/10.1103/physreva.86.032324
- Higgott, O. (2022). PyMatching: A Python Package for Decoding Quantum Codes with Minimum-Weight Perfect Matching. _ACM Transactions on Quantum Computing,_ 3(3), 1–16. https://doi.org/10.1145/3505637
