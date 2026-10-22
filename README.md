# QC: Quantum Circuits with Qiskit

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gusfring3369/QC/blob/claude/quantum-circuit-qiskit-d4b5xw/quantum_circuits.ipynb)

A beginner-friendly Jupyter notebook that builds and simulates quantum circuits with [Qiskit](https://www.qiskit.org/) and the Aer simulator.

| Section | What it shows |
|---|---|
| Superposition | Hadamard gate, statevector, Bloch sphere |
| Bell state | Entangling two qubits with H + CNOT |
| GHZ state | Entangling *n* qubits |
| Teleportation | Bell measurement and classically controlled corrections |
| Grover's search | Finding a marked item among 4 in one query |
| Deutsch–Jozsa | Constant vs. balanced function in one query |
| Real hardware | (Optional) running on IBM quantum computers |

## Run it online

**Google Colab (recommended):** click the badge above, then **Runtime → Run all**. The first cell installs Qiskit.

You can also open it from Colab directly: **File → Open notebook → GitHub**, search for `gusfring3369/QC`, pick the branch, and open `quantum_circuits.ipynb`.

## Run it locally

```bash
pip install -r requirements.txt
jupyter notebook quantum_circuits.ipynb
```
