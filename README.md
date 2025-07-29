# Quantum Random Number Generator (Simulated)

This project implements a simulated Quantum Random Number Generator (QRNG) using Qiskit and the Aer simulator backend. The randomness is generated from the probabilistic outcomes of quantum measurements after preparing qubits in a superposition state.

## Description

The generator uses `n` qubits, each placed in a superposition using the Hadamard gate. Upon measurement, each qubit collapses to 0 or 1 with equal probability. By measuring all qubits, we obtain a random bitstring, which is then converted into a decimal number.

The simulation runs for a configurable number of iterations, each producing a different random number.

## Requirements

- Python 3.x
- Qiskit

To install the required dependencies, run:

```bash
pip install qiskit
# quantum-random-number-generator
