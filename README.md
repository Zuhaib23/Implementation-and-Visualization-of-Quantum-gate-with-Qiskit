# 🧠 Implementation-and-Visualization-of-Quantum-gate-with-Qiskit

 ## 📦 Project Files Download

Due to file size limitations on GitHub, the full project files (including all quantum gate implementations and visualizations) are available via Google Drive:

🔗 **[Download Full Project from Google Drive](https://drive.google.com/drive/folders/1skja1tQ97iIQlRf1HaE8QwiS5-19UL5y?usp=sharing)**


This repository contains Python implementations and visualizations of **basic quantum logic gates** using [Qiskit](https://qiskit.org/). The goal is to demonstrate how each gate works on qubits and provide circuit diagrams and state vector outputs for better understanding.

## 🧪 Gates Implemented

Below are the quantum gates implemented and visualized in this project:

| #  | Gate Name                      | Description                                                |
|----|-------------------------------|------------------------------------------------------------|
| 1  | Pauli-X Gate (`X`)            | Bit-flip gate, analogous to classical NOT gate             |
| 2  | Pauli-Y Gate (`Y`)            | Bit and phase flip gate                                    |
| 3  | Pauli-Z Gate (`Z`)            | Phase-flip gate                                            |
| 4  | Rz / Rφ Gate (`Rz(θ)`)        | Rotates around the Z-axis by θ radians                    |
| 5  | Hadamard Gate (`H`)           | Creates superposition from basis state                    |
| 6  | Controlled-Z Gate (`CZ`)      | Applies Z gate only when control qubit is |1⟩              |
| 7  | Controlled-Y Gate (`CY`)      | Applies Y gate only when control qubit is |1⟩              |
| 8  | Controlled-X Gate (`CNOT`)    | Flips target qubit if control qubit is |1⟩                |
| 9  | CNOT Equivalence Circuit      | CNOT gate built using H and CZ                             |
| 10 | SWAP Gate                     | Swaps the states of two qubits                             |
| 11 | Toffoli Gate (`CCX`)          | Controlled-controlled-X gate (2 controls, 1 target)        |
| 12 | X Gate using H and Z          | Constructs an X gate using Hadamard and Z gates           |

## 🧰 Requirements

Install the required packages using pip:

```bash
pip install qiskit matplotlib



🖼️ Sample Visualization
Each script will:

Display the quantum circuit using Qiskit’s drawing tools.

Show the statevector or measurement probabilities using a bar chart.

Example output for Pauli-X gate:

python
Copy
Edit
# Circuit
     ┌───┐
q_0: ┤ X ├
     └───┘

# Output Statevector
|1⟩


🧠 Educational Value
This repository is ideal for:

Quantum computing beginners

Students learning about quantum logic gates

Anyone exploring Qiskit for circuit building and simulation

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contributions
Feel free to fork, star, and submit pull requests! Suggestions, bug fixes, and improvements are always welcome.

Made with ❤️ using Qiskit


---

Let me know if you'd like the actual `.ipynb` implementation files for each gate or if you need a `requirements.txt` as well.


---


