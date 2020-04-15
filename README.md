# Quantum Computing
Introduction to quantum circuits and exploring possibilities of further developments:

<a href="url"><img src="https://github.com/lukecyb8687/quantumComputing/blob/master/carbon.png" align="middle" height="200" width="500" ></a>

# Introduction

In this repository, I will be using ***Qiskit***, which is a open-sourced python wrapped module created by IBM. There would be greater value added if one were to approach this topic with basic knowledge of quantum physics.

This repository would be divided into *n* seperate portions:
                    1. **Introductory Quantum Circuits**
                    2. ...
                    3. ...
                    
 # Architecture
 Below is the architecture of this repository:
                    - 📑 quantumCircuit.ipynb

# Prerequisites
- **numpy** 👉 the basic scientific library of Python with built-in math functions and easy array handling
- **matplotlib** 👉  for graph plotting
- **Qiskit** 👉 Building quantum circuits and simulation of results
- **IBM Account** 👉 To generate your API

# Quantum Circuits
## Gates
Basic gates used in this tutorial (to be added on further):
                    1. **Hadamard**
                    2. **Controlled-NOT (CNOT)**
                    3. **X**
                    4. **Z**
 ## Concepts
 Referring to *quantumCircuit.ipynb*, we would first create your own personal quantum circuit by the following steps:
                    1. Initializing the number of quantum bits (Qubits) and classical bits
                    2. Create superpositioning and entanglement by adding in the necessary gates
                    3. Set up simulation backend using the *Qiskit* simulation package: *Aer*
                    4. Run simulation results and visualize it using a histogram
                    5. Connect your quantum circuit to an actual IBM quantum computer near you
                    6. Queue your job to the selected backend system and run the job
                    7. Visualize actual results and compare it to the simulation
                    
 ## Quantum Teleportation
 We will now do a run down of our quantum circuit and perform quantum teleportation. 
 **The aim** is to send a Qubit state |*psi*> from one Qubit to another.
 
 The procedure can likewise be found in the *quantumCircuit.ipynb*. One should have the background mathematical knowledege of how gates work (in the sense of vectors, matrices  in a complex space) in order to fully appreciate this section.
 
 The circuit that was designed in *quantumCircuit.ipynb* allows us to send a quantum state of |1> from Qubit_0 to Qubit_2, hence the resulting classical bits would always have a 1-bit in the classical register assigned to Qubit_2.
 
 # VII. Acknowledgements
- https://qiskit.org/


# IX. Contributors

- **Yun Bin Choh** - _Student @ CentraleSupélec_ - [lukecyb8687](https://github.com/lukecyb8687)
 
