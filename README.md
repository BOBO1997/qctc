# The Simulator of Quantum Computation with Topological Codes

## Abstract

- A fast simulator for topological quantum computation and topological error correction.
- A transpiler of topological computation model.

## Todo List

### Simulating Algorithm
General Topological Code Simulator

#### Stabilizer Simulator by Gottesman-Knill Theorem
Given a graph, output its 
- stabilizer group
- stabilizer generators (output the generators with indicated pauli operators, X, Y, Z?)
by Gottesman-Knill Theorem
- Probability outputs

#### Fast approximation algorithm
- [Scott Aaronson et al's CHP simulator](https://arxiv.org/abs/quant-ph/0406196), based on the stabilizer tableau representation (used in Stim simulator).

### Visualization tools

### Transpiler
- Given a resource state and a quantum circuit, convert the quantum circuit into the adaptive measurement procedure in the resource state
- Add a feature of measurement order (and number) optimization protocol 

### Implementation

#### GPU friendly implementation

- [rustacuda](https://lib.rs/crates/rustacuda), a CUDA API in Rust

#### APIs

- [PyO3](https://crates.io/crates/pyo3), Rust bindings for Python.

## Similar Tools

1. [The Extended Stabilizer Simulator](https://qiskit.org/documentation/tutorials/simulators/6_extended_stabilizer_tutorial.html) in Qiskit
2. [Qiskit Surface Code Encoder/Decoder](https://github.com/yaleqc/qiskit_surface_codes) by Yale Quantum Computing
3. [Surface Codes and Error Correction](https://github.com/The-Singularity-Research/QISKit-Surface-Codes) by Dr. Amelie Schreiber
4. [Stim](https://github.com/quantumlib/stim) in quantumlib by Google

