# Probing Lattice Dynamics

Phonon calculations probe the vibrational properties of a crystal by computing its normal modes across the Brillouin zone. These calculations reveal dynamic stability, thermal properties, and potential structural phase transitions.

<div style="text-align: center; margin: 20px 0;">
  <img src="./enhanced_diatomic_molecule.gif" alt="vibrational Structure" style="max-width: 300px; width: 100%; height: auto;">
</div>
<div style="text-align: center; font-size: 0.9em; color: gray;">
<p> A vibrational mode of a diatomic molecule</p>
</div>

### Harmonic Approximation

To assess a system's stability, one generates phonon dispersion spectra by:
* Expanding the total energy as a second-order Taylor series around atomic equilibrium positions
* Calculating forces produced by small atomic displacements (via finite differences or DFPT)
* Constructing and diagonalizing the dynamical matrix to find eigenvalues (ω²) at each k-point
Implementation approaches:
* Supercell methods with explicit atomic displacements
* More efficient linear-response calculations using density-functional perturbation theory within the primitive cell
Key conclusions from phonon calculations:
* Imaginary modes (appearing as negative ω² values) reveal instabilities indicating potential structural distortions or phase transitions
* Absence of imaginary modes confirms dynamic stability with the structure representing a true minimum on the potential energy surface
Limitations of the method:
* Approximations inherent in DFT (exchange-correlation functional limitations)
* Constraints of the harmonic approximation
* Finite temperature effects not captured in ground-state calculations