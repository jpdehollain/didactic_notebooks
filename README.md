# Didactic notebooks

Collection of jupyter notebooks consisting of interactive lecture / application notes covering various topics related to quantum experiments.

## RISE Presentations

The notebooks in this folders have been set up with [RISE](https://rise.readthedocs.io/) to use in lectures and presentations.

To view and use the notebooks in presentation mode, install rise with:

`conda install -c conda-forge rise`

## Description of available notebooks

### bbRadiationVsJohnson

Application note describing the differences in the energy spectra between Blackbody radiation and Johnson-Nyquist noise.

### jpaTheory

Describes the theory behind non-linear tank circuits, and how to use them as linear amplifiers and digital discriminators for qubit readout.

### 1-qubitGates (WIP)

QIP definition of the qubit Hamiltonian and single qubit gates. Plot a Bloch sphere showing the effects of applying single-qubit gates to a quantum state. TODO: expand to include 2-qubit gates and some simple circuits.

### 1-qubitEvolution

Define qubit hamiltonian in the laboratory frame. Apply the time-evolution operator (for time-dependent and time-independent Hamiltonians) and plot the state evolution on the Bloch sphere. Qubit Hamiltonian in the rotating frame, how to use pulsed interactions to perform single-qubit gates.

### 2-qubitEvolution

Define 2-qubit Hamiltonian and states from single qubits. Add interaction terms and plot the evolution of qubits under 2-qubit interactions.

### spinEvolution

Similar to the initial part of `1-qubitEvolution` but using the specific example of a spin-1/2 in a static magnetic field.
