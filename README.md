# Numerically Solving Schrodinger Equation.
Schrodinger Equation governs the evolution of a state, given a quantum system. Given a hamiltonian, the evolution can be described as, 

$$ i \hbar \frac{\partial \ket{\psi(t)}}{\partial t}= \hat{H}\ket{\psi(t)}$$

where $\hbar$ is plancks constant divided by $2\pi$, $\hat{H}$ is Hamiltonian of the quantum system and $\ket{\psi(t)}$ is the state. Here $t$ is time as a parameter.


## Time-Independent Schrodinger Equation

> Reference: N-Zettili Quantum Mechanics, Chapter 4.

The Algorithm solves the schrodinger equation with the boundary conditions, $\psi(x_{min})=\psi(x_{max})=0.$ By solve I mean, finding wave function $\psi_n(x)$ for given energy $E_n$ for the n-th excited state.

To calculate the double derivatives we make use of "Numerov Algorithm".