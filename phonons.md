# Probing Lattice Dynamics

Phonon calculations probe the vibrational properties of a crystal by computing its normal modes across the Brillouin zone. These calculations reveal dynamic stability, thermal properties, and potential structural phase transitions.

### Harmonic Approximation

Expand the total energy to second order in atomic displacements about equilibrium.


Compute forces resulting from small displacements of atoms (finite differences or density-functional perturbation theory).

Construct the dynamical matrix and solve for eigenvalues (ω²) at each k-point.

Supercell vs. Linear-Response

Supercell (Finite Displacements): Displace atoms in a large periodic supercell and calculate forces.

Linear-Response (DFPT): Directly compute dynamical matrix elements using perturbation theory within the primitive cell.