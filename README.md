### Alejandro Chumacero Navarro

I'm a master's student in Physics (Quantum Computing) at UW–Madison, with a background in applied mathematics. Most of what I care about is on the hardware side of quantum computing: superconducting qubits, readout and calibration, and the classical logic and tooling that surrounds them.

A few things I've been building:

- [SystemVerilog FIFO Verification](https://github.com/Chumita003/SystemVerilog_fifo_verification): a synchronous FIFO with a self-checking testbench, a reference model, and randomized tests. My take on RTL design and the fundamentals of verification.
- [Hamiltonian Circuit Optimization](https://github.com/Chumita003/QuantumHackathon-HamiltonianCircuitOptimization): a Trotterized time-evolution circuit for a molecular spin Hamiltonian, with an honest comparison of two optimizers (pyZX and the Qiskit transpiler), including where one of them quietly made the circuit worse.
- [1D](https://github.com/Chumita003/1D_SchrodingerEigensolver) and [2D](https://github.com/Chumita003/2D_SchrodingerEigensolver) Schrödinger Eigensolvers: finite-difference solvers I derived from scratch and validated against every analytic spectrum I could compare them to. The interesting part was tracking down a boundary defect that was quietly capping convergence at first order, fixing it, and then working out which of the leftover errors were real limits instead of bugs — including a 2D delta potential that turns out to have no continuum limit at all.
- [Qubit Readout Analysis](https://github.com/Chumita003/Phys763.HW3-ReadoutAnalysis) and [Detuning and Retuning](https://github.com/Chumita003/Phys763.HW4b-Detuning-RetuningQubits): hands-on analysis of superconducting-qubit experiments (readout fidelity, T1, randomized benchmarking, Power Rabi) from my graduate lab course.

I like work that ties the physics to the actual math and the actual code, and I try to get the numbers right instead of chasing a headline.

You can reach me on [LinkedIn](https://www.linkedin.com/in/alejandro-chumacero-navarro-17392b310).
