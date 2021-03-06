<p align="center">
	<img src="https://github.com/zapatacomputing/google_autoencoder/blob/master/zlogo.png" width="150px"/>
</p>

# Implementation of CUSP using Cirq

## Description
Compressed Unsupervised State Preparation (CUSP) is a method for building more efficient quantum circuits by using a quantum autoencoder. The protocol performs a kind of circuit synthesis that, if training is successful, results in a more compact circuit. Since typically shorter-depth circuits are less prone to noise on a real quantum computer, this tool gives the opportunity to make a more accurate state preparation, resulting in better accuracy for a quantum computation. In this demo, we will use the example of improving a circuit which computes the ground state energies of molecular hydrogen at various bond lengths.


For a formal description of the CUSP protocol, please see: [CUSP Algorithm Overview](https://github.com/zapatacomputing/cusp_cirq_demo/blob/master/cusp_protocol.pdf).


To proceed to the code demo, see: [CUSP Demo](https://github.com/zapatacomputing/cusp_cirq_demo/blob/master/cusp_demo_short.ipynb).

For a short video tutorial, see: [Video Code Walkthrough](https://www.youtube.com/watch?v=79Hd-M_xN3Q)

## Dependencies and Versions Used
- Python 3.5
- [OpenFermion](https://github.com/quantumlib/OpenFermion) 0.6
- [Cirq](https://github.com/quantumlib/Cirq) 

## Authors
[Jonathan Olson](https://github.com/olsonjonny), [Sukin Sim (Hannah)](https://github.com/hsim13372), [Yudong Cao](https://github.com/yudongcao)
