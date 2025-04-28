# Electronic Structure Calculations

Electronic structure calculations form the foundation of computational materials science, enabling the prediction and analysis of a material’s electronic properties. Utilizing density functional theory (DFT) and related methods, these calculations provide insights into wave functions, energy levels, and electron distributions, offering a detailed understanding of metallic, insulating, and semiconducting behaviors.


## Density Functional Theory (DFT)

* In Kohn-Sham Density Functional Theory (DFT), the complex many-electron system is approximated by a fictitious system of non-interacting electrons moving in an effective potential, designed to reproduce the exact ground-state electron density of the real, interacting system.

* Instead of solving the many-body Schrödinger equation directly, DFT leverages functionals of the electron density to approximate the ground-state properties.

* DFT as the most widely used approach.

## Band Structures and Density of States (DOS)

After conducting electronic structure calculations, we can derive a band structure. Band structures illustrate the relationship between electron energy and crystal momentum, offering essential insights into whether a material behaves as a conductor, semiconductor, or insulator. Key aspects include the Fermi level, valence and conduction bands, and the band gap. Additionally, the Density of States (DOS) provides a distribution of electronic states across energy levels, revealing the contributions of various atomic orbitals and spin states to the material's electronic properties.

<div style="text-align: center;">
<img src="./bandstructure.png" alt="BandStruct" style="width: 300px; height: auto;">
</div>
<div style="text-align: center; font-size: 0.9em; color: gray;">
<p>A generic Band Structure</p>
</div>

* Determine if a material is a conductor, semiconductor, or insulator.

* Estimate the band gap (direct or indirect).

* Identify features like band dispersion (effective mass).

* Analyze orbital contributions (e.g., s, p, d character).


Despite its broad success, standard DFT is known to systematically: 

DFT tends to underestimate the band gap.

Strongly correlated materials (e.g., transition metal oxides) are poorly described by standard DFT.

Need for higher-level corrections (e.g., GW approximation, hybrid functionals).
[Back to Home](index.md)