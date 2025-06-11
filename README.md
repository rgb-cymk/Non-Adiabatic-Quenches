# Non-Adiabatic-Quenches

## Abstract

Using computational techniques such as Quantum Circuit Models, implemented in the Python programming language using IBM's Qiskit, we simulate the out-of-equilibrium dynamics of the 1D Transverse Field Ising Model (TFIM). Spin correlation propagation was studied using a quantum quench from the ferromagnetic to paramagnetic phase under periodic boundary conditions. It was shown that for specific quantum devices like IBM’s Kyiv, unmitigated noisy experiments using Hamiltonian Trotterization for long real-time evolutions are unfeasible due to current depolarizing errors on one- and two-qubit gates. Despite this, noiseless simulation data allowed us to make a reasonable estimate of the velocity of spin correlations, supported by a near equivalence to a contextual calculation using the analytical solution as developed by Jordan and Wigner (JW).

After a JW, Fourier and Bogoliubov transform of the 1D periodic TFIM hamiltonian, the following maximum velocity of spin correlation velocity is calculated:

$$
v(k = \frac{\pi}{2a}) \approx 0.9 \quad (\text{in units of } \frac{J_a}{\hbar})
$$

Where a is the lattice spacing, and J the coupling constant. 

