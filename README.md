<div align="center">
  <h1>🌌 Quantum Computing Simulator</h1>
  
 ![Python](https://img.shields.io/badge/Made%20with-Python%203.8+-blue.svg)
![Quantum](https://img.shields.io/badge/Quantum-Simulator-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Lines of Code](https://img.shields.io/badge/Lines%20of%20Code-3185-brightgreen)
![Pillow Version](https://img.shields.io/pypi/v/pillow)  
</div>

### 🚀 Features
- Full-featured quantum computer simulator
- Supports up to 10 qubits
- Includes basic gates (X, Y, Z, H, S, T, CNOT)
- Grover's and Shor's algorithms implementation
- Interactive GUI with visualization
- Educational purpose - great for learning QC basics

### 💻 Installation
```bash
git clone https://github.com/Nuxora/Quantum-Simulator-PC-On-Python.git
cd quantum-simulator
pip install -r requirements.txt
```

### 🏃‍♂️ Quick Start
python
from src.simulator import QuantumSimulator

qs = QuantumSimulator(2)  # Create 2-qubit system
qs.apply_gate('H', 0)    # Apply Hadamard to qubit 0
qs.cnot(0, 1)            # Entangle qubits
print(qs.measure(0))      # Measure qubit 0


## 👨‍💻 Development

### 🇬🇧 Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request



## library

Make sure you have these installed before running the project:

1. Basic packages:  
```bash
pip install numpy matplotlib tkinter
