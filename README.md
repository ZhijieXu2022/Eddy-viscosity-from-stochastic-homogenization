# Eddy viscosity from stochastic homogenization: exact cell solutions, the two-thirds law from the filtered energy budget, the spectral eddy viscosity of a shock, and tests against direct numerical simulation

Xu Z., 2026, *Eddy viscosity from stochastic homogenization: exact cell solutions, the two-thirds law from the filtered energy budget, the spectral eddy viscosity of a shock, and tests against direct numerical simulation*, Zenodo [doi:10.5281/zenodo.24096071](https://doi.org/10.5281/zenodo.24096071).

## Major findings

- For a top-hat filter of width R the stationary filtered energy budget is exactly ν[1 + ν<sub>e</sub>(R)]Ω<sub>R</sub> = ε, with νν<sub>e</sub> defined by the subfilter flux; in one dimension Ω<sub>R</sub> = S<sub>2</sub>(R)/R².
- In one dimension the homogenized cell eddy viscosity is exactly ν<sub>e</sub> = ∫(g − 1) ln g dy ≥ 0 with g = e<sup>ξ</sup>/Z: quadratic in the cell Reynolds number when diffusion dominates and ξ<sub>max</sub> − ∫ξ dy − 1/α when advection dominates.
- The cell reproduces the inertial eddy viscosity of a Burgers shock, u<sub>0</sub>R/(6ν), which is also the long-wave spectral eddy viscosity of the shock for a top-hat filter; the sharp-cutoff spectral eddy viscosity of the shock is obtained at finite viscosity and for any filter, and its cusp comes from nonlocal triads.
- In the inertial range ν<sub>t</sub> = c R S<sub>2</sub><sup>1/2</sup>, and the budget gives S<sub>2</sub> ∝ (εR)<sup>2/3</sup>; random-phase cells give c = 0.0817 and, in a separable three-dimensional estimate, a Kolmogorov constant C<sub>K</sub> ≈ 1.36.
- A priori tests on Burgers DNS and on isotropic turbulence at R<sub>λ</sub> ≈ 420 confirm the budget to about 10% and the shock predictions to within 30%.
- Cells built from DNS velocities reproduce the Gaussian coefficient, but the measured coefficient is c = 0.060; with it the budget gives C<sub>K</sub> ≈ 1.67. The closure misses gradient transfer in the dissipative range and backscatter.

## Contents

- `P26_eddy_viscosity_homogenization.pdf`: the manuscript.
- `csv/`: the plotted data of Figs 1–12, one file per figure (12 files).
- `CITATION.cff`: citation metadata.
- `LICENSE`: licence for the contents.

The isotropic-turbulence data used in the a priori tests are from the Johns Hopkins Turbulence Databases ([doi:10.1080/14685240802376389](https://doi.org/10.1080/14685240802376389)).

The same files are archived on Zenodo: [doi:10.5281/zenodo.24096071](https://doi.org/10.5281/zenodo.24096071).
