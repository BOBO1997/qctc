# The Simulator of Quantum Computation with Error Corrections

## Abstract

- A fast simulator for quantum computation and error correction.
- A transpiler of topological computation model.

## Todo List

### Features

#### Stabilizer Simulator by Gottesman-Knill Theorem
Given a graph, output its 
- stabilizer group
- stabilizer generators (output the generators with indicated pauli operators, X, Y, Z?)
by Gottesman-Knill Theorem
- Probability outputs

#### Measurement-based Quantum Computation

- quantum computation on various graph structures
- topologically protected quantum computation

#### Fast Approximation Algorithm
- [Scott Aaronson et al's CHP simulator](https://arxiv.org/abs/quant-ph/0406196), based on the stabilizer tableau representation (used in Stim simulator).

### Visualization Tools

### Transpiler
- Given a resource state and a quantum circuit, convert the quantum circuit into the adaptive measurement procedure in the resource state
- Add a feature of measurement order (and number) optimization protocol 

### Implementation

#### GPU friendly implementation

- [rustacuda](https://lib.rs/crates/rustacuda), a CUDA API in Rust

#### Python Bindings

- [PyO3](https://crates.io/crates/pyo3), Rust bindings for Python.

## Similar Tools

1. [The Extended Stabilizer Simulator](https://qiskit.org/documentation/tutorials/simulators/6_extended_stabilizer_tutorial.html) in Qiskit
2. [Qiskit Surface Code Encoder/Decoder](https://github.com/yaleqc/qiskit_surface_codes) by Yale Quantum Computing
3. [Surface Codes and Error Correction](https://github.com/The-Singularity-Research/QISKit-Surface-Codes) by Dr. Amelie Schreiber
4. [Stim](https://github.com/quantumlib/stim) in quantumlib by Google
5. [Surface Code](https://github.com/GuanQunMu/Surface-Code) by GuanQunMu
6. [QTop](https://github.com/jacobmarks/QTop), a visualization tool for topological code
7. [List of Packages](https://github.com/topics/topological-quantum-computation)

