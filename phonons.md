# Probing Lattice Dynamics

<div style="text-align: justify;">
<p>Phonon calculations probe the vibrational properties of a crystal by computing its normal modes across the Brillouin zone. These calculations reveal dynamic stability, thermal properties, and potential structural phase transitions.</p>
</div>

<div style="text-align: center; margin: 20px 0;">
  <img src="./enhanced_diatomic_molecule.gif" alt="vibrational Structure" style="max-width: 300px; width: 100%; height: auto;">
</div>
<div style="text-align: center; font-size: 0.9em; color: gray;">
<p> A vibrational mode of a diatomic molecule</p>
</div>

### Evaluating the Stability

To assess a system's stability, one generates phonon dispersion spectra by:
* Expanding the total energy as a second-order Taylor series around atomic equilibrium positions
* Calculating forces produced by small atomic displacements (via finite differences or DFPT)
* Constructing and diagonalizing the dynamical matrix to find eigenvalues (ω²) at each k-point.

Key conclusions from phonon calculations:

* Imaginary modes (appearing as negative ω² values) reveal instabilities indicating potential structural distortions or phase transitions
* Absence of imaginary modes confirms dynamic stability with the structure representing a true minimum on the potential energy surface

As usual, these theoretical calculations also imply some limitations of the method:

* Approximations inherent in DFT (exchange-correlation functional limitations)
* Constraints of the harmonic approximation
* Finite temperature effects not captured in ground-state calculations

[Back to Home](index.md)
